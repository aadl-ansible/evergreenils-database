aadl.evergreenils_database
=========
![](https://github.com/aadl-ansible/evergreenils-database/workflows/Ansible%20Lint/badge.svg)

This role installs PostgreSQL and the Perl dependencies needed to run the Evergreen ILS database on RHEL-compatible systems.

Requirements
------------

RHEL or EL compatible (Molecule tests on AlmaLinux 10). The following Ansible collections must be installed:

- `community.postgresql`
- `community.general`

Role Variables
--------------

```yaml
# Addresses PostgreSQL will listen on
postgresql_listen_addresses:
  - '*'

# CIDR ranges that authenticate with md5 passwords in pg_hba.conf
postgresql_pg_hba_passwd_hosts:
  - 0.0.0.0/0

# Install the contrib and devel packages alongside postgresql-server
postgresql_ext_install_contrib: true
postgresql_ext_install_dev_headers: true

# postgresql.conf tuning
postgresql_random_page_cost: 2.0

# PostgreSQL users to create
postgresql_users:
  - name: evergreen
    password: evergreen
    role_attr_flags: SUPERUSER

# PostgreSQL databases to create
postgresql_databases:
  - name: evergreen
    owner: evergreen
    encoding: UTF8
    lc_collate: C
    lc_ctype: C

# Extensions to install per database
postgresql_database_extensions:
  - db: evergreen
    extensions:
      - hstore
      - xml2
      - intarray
      - pgcrypto
      - unaccent

# Extra system packages installed alongside PostgreSQL.
# gcc and libxslt-devel are required to build some CPAN modules.
postgresql_extra_packages:
  - gcc
  - libxslt-devel
  - python3-psycopg2

# Perl packages installed from RHEL AppStream/BaseOS repos
evergreen_database_perl_dependencies:
  - perl-JSON-XS
  - perl-XML-LibXML
  - perl-DBI
  - perl-DBD-Pg
  - perl-LWP-Protocol-https
  - make

# CPAN modules required by Evergreen ILS.
# Set notest: true for modules whose test suites fail due to environment differences.
evergreen_database_cpan_modules:
  - name: Business::ISBN
  - name: MARC::File::XML
    notest: true
  - name: MIME::Base32
  - name: Library::CallNumber::LC
  - name: Rose::URI
  - name: UUID::Tiny
  - name: XML::LibXSLT
  - name: Pass::OTP
  - name: String::KeyboardDistance
  - name: Text::Levenshtein::Damerau::XS
```

Dependencies
------------

No role dependencies. Install the required collections with:

```bash
ansible-galaxy collection install community.postgresql community.general
```

Example Playbook
----------------

    - hosts: database-servers
      become: true
      roles:
         - { role: aadl.evergreenils_database }

License
-------

GPL-2.0-or-later


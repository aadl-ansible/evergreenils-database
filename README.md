aadl.evergreenils_database
=========
![](https://github.com/aadl-ansible/evergreenils-database/workflows/Ansible%20Lint/badge.svg)

This role installs PostgreSQL and the dependencies needed for running the Evergreen ILS.

Requirements
------------

This role is tested on Ubuntu but may work on other APT based systems. The dependency role also supports CentOS but we need to tweak and test the evergreen perl requirements.

Role Variables
--------------

```yaml
postgresql_version: 10

postgresql_listen_addresses:
  - '*'
postgresql_pg_hba_passwd_hosts:
  - 0.0.0.0/0
postgresql_ext_install_contrib: yes
postgresql_ext_install_dev_headers: yes

postgresql_random_page_cost: 2.0

postgresql_extensions:
  - python3-psycopg2
  - libbusiness-isbn-perl
  - libjson-xs-perl
  - liblibrary-callnumber-lc-perl
  - libmarc-record-perl
  - libmarc-xml-perl
  - librose-uri-perl
  - libuuid-tiny-perl
  - libxml-libxml-perl
  - libxml-libxslt-perl

postgresql_users:
  - name: evergreen
    pass: evergreen
    encrypted: yes

postgresql_user_privileges:
  - name: evergreen
    role_attr_flags: "SUPERUSER"

postgresql_databases:
  - name: evergreen
    owner: evergreen
    hstore: yes
    encoding: 'UNICODE'
    lc_collate: 'C'
    lc_ctype: 'C'

postgresql_database_extensions:
  - db: evergreen
    extensions:
      - xml2
      - intarray
      - pgcrypto
      - unaccent

evergreen_database_perl_dependencies:
  - libbusiness-isbn-perl
  - libjson-xs-perl
  - liblibrary-callnumber-lc-perl
  - libmarc-record-perl
  - librose-uri-perl
  - libuuid-tiny-perl
  - libxml-libxml-perl
  - libxml-libxslt-perl
  - libdbi1
  - libdbi-dev
  - libdbd-pg-perl
  - libdbd-pgsql
```

Dependencies
------------

This role depends on the (ANXS.postgresql)[https://github.com/ANXS/postgresql] role to do most of the heavy lifting. See that role for additional variables and settings that can be changed.

Example Playbook
----------------

    - hosts: database-servers
      become: yes
      roles:
         - { role: aadl.evergreenils_database }

License
-------

GPL2 (Note: The ANXS.postgresql dependency is licensed under MIT)

Author Information
------------------

This role is maintained by the (AADL Dev Team)(https://twitter.com/aadl_tech)

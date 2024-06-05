# evergreen

## Tables

| Name | Columns | Comment | Type |
| ---- | ------- | ------- | ---- |
| [acq.acq_lineitem_history](acq.acq_lineitem_history.md) | 21 |  | BASE TABLE |
| [acq.acq_lineitem_lifecycle](acq.acq_lineitem_lifecycle.md) | 21 |  | VIEW |
| [acq.acq_purchase_order_history](acq.acq_purchase_order_history.md) | 16 |  | BASE TABLE |
| [acq.acq_purchase_order_lifecycle](acq.acq_purchase_order_lifecycle.md) | 16 |  | VIEW |
| [acq.all_fund_allocation_total](acq.all_fund_allocation_total.md) | 2 |  | VIEW |
| [acq.all_fund_combined_balance](acq.all_fund_combined_balance.md) | 2 |  | VIEW |
| [acq.all_fund_encumbrance_total](acq.all_fund_encumbrance_total.md) | 2 |  | VIEW |
| [acq.all_fund_spent_balance](acq.all_fund_spent_balance.md) | 2 |  | VIEW |
| [acq.all_fund_spent_total](acq.all_fund_spent_total.md) | 2 |  | VIEW |
| [acq.cancel_reason](acq.cancel_reason.md) | 5 |  | BASE TABLE |
| [acq.claim](acq.claim.md) | 3 |  | BASE TABLE |
| [acq.claim_event](acq.claim_event.md) | 6 |  | BASE TABLE |
| [acq.claim_event_type](acq.claim_event_type.md) | 5 |  | BASE TABLE |
| [acq.claim_policy](acq.claim_policy.md) | 4 |  | BASE TABLE |
| [acq.claim_policy_action](acq.claim_policy_action.md) | 4 |  | BASE TABLE |
| [acq.claim_type](acq.claim_type.md) | 4 |  | BASE TABLE |
| [acq.currency_type](acq.currency_type.md) | 2 |  | BASE TABLE |
| [acq.debit_attribution](acq.debit_attribution.md) | 5 |  | BASE TABLE |
| [acq.distribution_formula](acq.distribution_formula.md) | 4 |  | BASE TABLE |
| [acq.distribution_formula_application](acq.distribution_formula_application.md) | 5 |  | BASE TABLE |
| [acq.distribution_formula_entry](acq.distribution_formula_entry.md) | 9 |  | BASE TABLE |
| [acq.edi_account](acq.edi_account.md) | 15 |  | BASE TABLE |
| [acq.edi_attr](acq.edi_attr.md) | 2 |  | BASE TABLE |
| [acq.edi_attr_set](acq.edi_attr_set.md) | 2 |  | BASE TABLE |
| [acq.edi_attr_set_map](acq.edi_attr_set_map.md) | 3 |  | BASE TABLE |
| [acq.edi_message](acq.edi_message.md) | 13 |  | BASE TABLE |
| [acq.exchange_rate](acq.exchange_rate.md) | 4 |  | BASE TABLE |
| [acq.fiscal_calendar](acq.fiscal_calendar.md) | 2 |  | BASE TABLE |
| [acq.fiscal_year](acq.fiscal_year.md) | 5 |  | BASE TABLE |
| [acq.fund](acq.fund.md) | 11 |  | BASE TABLE |
| [acq.fund_allocation](acq.fund_allocation.md) | 7 |  | BASE TABLE |
| [acq.fund_allocation_percent](acq.fund_allocation_percent.md) | 8 |  | BASE TABLE |
| [acq.fund_allocation_total](acq.fund_allocation_total.md) | 2 |  | VIEW |
| [acq.fund_combined_balance](acq.fund_combined_balance.md) | 2 |  | VIEW |
| [acq.fund_debit](acq.fund_debit.md) | 10 |  | BASE TABLE |
| [acq.fund_debit_total](acq.fund_debit_total.md) | 2 |  | VIEW |
| [acq.fund_encumbrance_total](acq.fund_encumbrance_total.md) | 2 |  | VIEW |
| [acq.fund_spent_balance](acq.fund_spent_balance.md) | 2 |  | VIEW |
| [acq.fund_spent_total](acq.fund_spent_total.md) | 2 |  | VIEW |
| [acq.fund_tag](acq.fund_tag.md) | 3 |  | BASE TABLE |
| [acq.fund_tag_map](acq.fund_tag_map.md) | 3 |  | BASE TABLE |
| [acq.fund_transfer](acq.fund_transfer.md) | 9 | <br>Fund Transfer<br>Each row represents the transfer of money from a source fund<br>to a destination fund.  There should be corresponding entries<br>in acq.fund_allocation.  The purpose of acq.fund_transfer is<br>to record how much money moved from which fund to which other<br>fund.<br><br>The presence of two amount fields, rather than one, reflects<br>the possibility that the two funds are denominated in different<br>currencies.  If they use the same currency type, the two<br>amounts should be the same.<br> | BASE TABLE |
| [acq.funding_source](acq.funding_source.md) | 5 |  | BASE TABLE |
| [acq.funding_source_allocation_total](acq.funding_source_allocation_total.md) | 2 |  | VIEW |
| [acq.funding_source_balance](acq.funding_source_balance.md) | 2 |  | VIEW |
| [acq.funding_source_credit](acq.funding_source_credit.md) | 6 |  | BASE TABLE |
| [acq.funding_source_credit_total](acq.funding_source_credit_total.md) | 2 |  | VIEW |
| [acq.invoice](acq.invoice.md) | 13 |  | BASE TABLE |
| [acq.invoice_entry](acq.invoice_entry.md) | 11 |  | BASE TABLE |
| [acq.invoice_item](acq.invoice_item.md) | 14 |  | BASE TABLE |
| [acq.invoice_item_type](acq.invoice_item_type.md) | 4 |  | BASE TABLE |
| [acq.invoice_method](acq.invoice_method.md) | 2 |  | BASE TABLE |
| [acq.invoice_payment_method](acq.invoice_payment_method.md) | 2 |  | BASE TABLE |
| [acq.li_state_label](acq.li_state_label.md) | 2 |  | VIEW |
| [acq.lineitem](acq.lineitem.md) | 18 |  | BASE TABLE |
| [acq.lineitem_alert_text](acq.lineitem_alert_text.md) | 4 |  | BASE TABLE |
| [acq.lineitem_attr](acq.lineitem_attr.md) | 7 |  | BASE TABLE |
| [acq.lineitem_attr_definition](acq.lineitem_attr_definition.md) | 5 |  | BASE TABLE |
| [acq.lineitem_detail](acq.lineitem_detail.md) | 15 |  | BASE TABLE |
| [acq.lineitem_generated_attr_definition](acq.lineitem_generated_attr_definition.md) | 6 |  | BASE TABLE |
| [acq.lineitem_local_attr_definition](acq.lineitem_local_attr_definition.md) | 5 |  | BASE TABLE |
| [acq.lineitem_marc_attr_definition](acq.lineitem_marc_attr_definition.md) | 6 |  | BASE TABLE |
| [acq.lineitem_note](acq.lineitem_note.md) | 9 |  | BASE TABLE |
| [acq.lineitem_provider_attr_definition](acq.lineitem_provider_attr_definition.md) | 7 |  | BASE TABLE |
| [acq.lineitem_summary](acq.lineitem_summary.md) | 10 |  | VIEW |
| [acq.lineitem_usr_attr_definition](acq.lineitem_usr_attr_definition.md) | 6 |  | BASE TABLE |
| [acq.ordered_funding_source_credit](acq.ordered_funding_source_credit.md) | 6 | <br>The acq.ordered_funding_source_credit view is a prioritized<br>ordering of funding source credits.  When ordered by the first<br>three columns, this view defines the order in which the various<br>credits are to be tapped for spending, subject to the allocations<br>in the acq.fund_allocation table.<br><br>The first column reflects the principle that we should spend<br>money with deadlines before spending money without deadlines.<br><br>The second column reflects the principle that we should spend the<br>oldest money first.  For money with deadlines, that means that we<br>spend first from the credit with the earliest deadline.  For<br>money without deadlines, we spend first from the credit with the<br>earliest effective date.<br><br>The third column is a tie breaker to ensure a consistent<br>ordering.<br> | VIEW |
| [acq.picklist](acq.picklist.md) | 8 |  | BASE TABLE |
| [acq.po_item](acq.po_item.md) | 10 |  | BASE TABLE |
| [acq.po_note](acq.po_note.md) | 8 |  | BASE TABLE |
| [acq.po_state_label](acq.po_state_label.md) | 2 |  | VIEW |
| [acq.provider](acq.provider.md) | 17 |  | BASE TABLE |
| [acq.provider_address](acq.provider_address.md) | 12 |  | BASE TABLE |
| [acq.provider_contact](acq.provider_contact.md) | 6 |  | BASE TABLE |
| [acq.provider_contact_address](acq.provider_contact_address.md) | 12 |  | BASE TABLE |
| [acq.provider_holding_subfield_map](acq.provider_holding_subfield_map.md) | 4 |  | BASE TABLE |
| [acq.provider_note](acq.provider_note.md) | 7 |  | BASE TABLE |
| [acq.purchase_order](acq.purchase_order.md) | 13 |  | BASE TABLE |
| [acq.serial_claim](acq.serial_claim.md) | 3 |  | BASE TABLE |
| [acq.serial_claim_event](acq.serial_claim_event.md) | 6 |  | BASE TABLE |
| [acq.user_request](acq.user_request.md) | 27 |  | BASE TABLE |
| [acq.user_request_status_type](acq.user_request_status_type.md) | 2 |  | BASE TABLE |
| [acq.user_request_type](acq.user_request_type.md) | 2 |  | BASE TABLE |
| [action.aged_circulation](action.aged_circulation.md) | 41 |  | BASE TABLE |
| [action.aged_hold_request](action.aged_hold_request.md) | 37 |  | BASE TABLE |
| [action.all_circulation](action.all_circulation.md) | 41 |  | VIEW |
| [action.all_circulation_combined_types](action.all_circulation_combined_types.md) | 7 |  | VIEW |
| [action.all_circulation_slim](action.all_circulation_slim.md) | 34 |  | VIEW |
| [action.all_hold_request](action.all_hold_request.md) | 37 |  | VIEW |
| [action.archive_actor_stat_cat](action.archive_actor_stat_cat.md) | 4 |  | BASE TABLE |
| [action.archive_asset_stat_cat](action.archive_asset_stat_cat.md) | 4 |  | BASE TABLE |
| [action.billable_circulations](action.billable_circulations.md) | 34 |  | VIEW |
| [action.circulation](action.circulation.md) | 34 |  | BASE TABLE |
| [action.circulation_limit_group_map](action.circulation_limit_group_map.md) | 2 |  | BASE TABLE |
| [action.curbside](action.curbside.md) | 10 |  | BASE TABLE |
| [action.emergency_closing](action.emergency_closing.md) | 6 |  | BASE TABLE |
| [action.emergency_closing_circulation](action.emergency_closing_circulation.md) | 5 |  | BASE TABLE |
| [action.emergency_closing_hold](action.emergency_closing_hold.md) | 5 |  | BASE TABLE |
| [action.emergency_closing_reservation](action.emergency_closing_reservation.md) | 5 |  | BASE TABLE |
| [action.emergency_closing_status](action.emergency_closing_status.md) | 12 |  | VIEW |
| [action.fieldset](action.fieldset.md) | 13 |  | BASE TABLE |
| [action.fieldset_col_val](action.fieldset_col_val.md) | 4 |  | BASE TABLE |
| [action.fieldset_group](action.fieldset_group.md) | 11 |  | BASE TABLE |
| [action.hold_copy_map](action.hold_copy_map.md) | 4 |  | BASE TABLE |
| [action.hold_notification](action.hold_notification.md) | 6 |  | BASE TABLE |
| [action.hold_request](action.hold_request.md) | 37 |  | BASE TABLE |
| [action.hold_request_cancel_cause](action.hold_request_cancel_cause.md) | 2 |  | BASE TABLE |
| [action.hold_request_note](action.hold_request_note.md) | 7 |  | BASE TABLE |
| [action.hold_transit_copy](action.hold_transit_copy.md) | 12 |  | BASE TABLE |
| [action.in_house_use](action.in_house_use.md) | 6 |  | BASE TABLE |
| [action.non_cat_in_house_use](action.non_cat_in_house_use.md) | 6 |  | BASE TABLE |
| [action.non_cataloged_circulation](action.non_cataloged_circulation.md) | 6 |  | BASE TABLE |
| [action.open_circulation](action.open_circulation.md) | 34 |  | VIEW |
| [action.reservation_transit_copy](action.reservation_transit_copy.md) | 12 |  | BASE TABLE |
| [action.survey](action.survey.md) | 10 |  | BASE TABLE |
| [action.survey_answer](action.survey_answer.md) | 3 |  | BASE TABLE |
| [action.survey_question](action.survey_question.md) | 3 |  | BASE TABLE |
| [action.survey_response](action.survey_response.md) | 8 |  | BASE TABLE |
| [action.transit_copy](action.transit_copy.md) | 11 |  | BASE TABLE |
| [action.unfulfilled_hold_innermost_loop](action.unfulfilled_hold_innermost_loop.md) | 3 |  | VIEW |
| [action.unfulfilled_hold_list](action.unfulfilled_hold_list.md) | 5 |  | BASE TABLE |
| [action.unfulfilled_hold_loops](action.unfulfilled_hold_loops.md) | 3 |  | VIEW |
| [action.unfulfilled_hold_max_loop](action.unfulfilled_hold_max_loop.md) | 2 |  | VIEW |
| [action.unfulfilled_hold_min_loop](action.unfulfilled_hold_min_loop.md) | 2 |  | VIEW |
| [action.usr_circ_history](action.usr_circ_history.md) | 7 |  | BASE TABLE |
| [action_trigger.cleanup](action_trigger.cleanup.md) | 2 |  | BASE TABLE |
| [action_trigger.collector](action_trigger.collector.md) | 2 |  | BASE TABLE |
| [action_trigger.environment](action_trigger.environment.md) | 5 |  | BASE TABLE |
| [action_trigger.event](action_trigger.event.md) | 14 |  | BASE TABLE |
| [action_trigger.event_def_group](action_trigger.event_def_group.md) | 5 |  | BASE TABLE |
| [action_trigger.event_def_group_member](action_trigger.event_def_group_member.md) | 7 |  | BASE TABLE |
| [action_trigger.event_definition](action_trigger.event_definition.md) | 23 |  | BASE TABLE |
| [action_trigger.event_output](action_trigger.event_output.md) | 4 |  | BASE TABLE |
| [action_trigger.event_params](action_trigger.event_params.md) | 4 |  | BASE TABLE |
| [action_trigger.hook](action_trigger.hook.md) | 4 |  | BASE TABLE |
| [action_trigger.reactor](action_trigger.reactor.md) | 2 |  | BASE TABLE |
| [action_trigger.validator](action_trigger.validator.md) | 2 |  | BASE TABLE |
| [actor.address_alert](actor.address_alert.md) | 14 |  | BASE TABLE |
| [actor.card](actor.card.md) | 4 | <br>Library Cards<br><br>Each User has one or more library cards.  The current "main"<br>card is linked to here from the actor.usr table, and it is up<br>to the consortium policy whether more than one card can be<br>active for any one user at a given time.<br> | BASE TABLE |
| [actor.copy_alert_suppress](actor.copy_alert_suppress.md) | 3 |  | BASE TABLE |
| [actor.hours_of_operation](actor.hours_of_operation.md) | 15 | <br>When does this org_unit usually open and close?  (Variations<br>are expressed in the actor.org_unit_closed table.)<br> | BASE TABLE |
| [actor.org_address](actor.org_address.md) | 12 |  | BASE TABLE |
| [actor.org_lasso](actor.org_lasso.md) | 2 |  | BASE TABLE |
| [actor.org_lasso_map](actor.org_lasso_map.md) | 3 |  | BASE TABLE |
| [actor.org_unit](actor.org_unit.md) | 13 |  | BASE TABLE |
| [actor.org_unit_closed](actor.org_unit_closed.md) | 8 |  | BASE TABLE |
| [actor.org_unit_custom_tree](actor.org_unit_custom_tree.md) | 3 |  | BASE TABLE |
| [actor.org_unit_custom_tree_node](actor.org_unit_custom_tree_node.md) | 5 |  | BASE TABLE |
| [actor.org_unit_proximity](actor.org_unit_proximity.md) | 4 |  | BASE TABLE |
| [actor.org_unit_proximity_adjustment](actor.org_unit_proximity_adjustment.md) | 10 |  | BASE TABLE |
| [actor.org_unit_setting](actor.org_unit_setting.md) | 4 | <br>Org Unit settings<br><br>This table contains any arbitrary settings that a client<br>program would like to save for an org unit.<br> | BASE TABLE |
| [actor.org_unit_type](actor.org_unit_type.md) | 7 |  | BASE TABLE |
| [actor.passwd](actor.passwd.md) | 7 |  | BASE TABLE |
| [actor.passwd_type](actor.passwd_type.md) | 6 |  | BASE TABLE |
| [actor.search_filter_group](actor.search_filter_group.md) | 5 |  | BASE TABLE |
| [actor.search_filter_group_entry](actor.search_filter_group_entry.md) | 4 |  | BASE TABLE |
| [actor.search_query](actor.search_query.md) | 3 |  | BASE TABLE |
| [actor.stat_cat](actor.stat_cat.md) | 10 | <br>User Statistical Catagories<br><br>Local data collected about Users is placed into a Statistical<br>Catagory.  Here's where those catagories are defined.<br> | BASE TABLE |
| [actor.stat_cat_entry](actor.stat_cat_entry.md) | 4 | <br>User Statistical Catagory Entries<br><br>Local data collected about Users is placed into a Statistical<br>Catagory.  Each library can create entries into any of its own<br>stat_cats, its ancestors' stat_cats, or its descendants' stat_cats.<br> | BASE TABLE |
| [actor.stat_cat_entry_default](actor.stat_cat_entry_default.md) | 4 | <br>User Statistical Category Default Entry<br><br>A library may choose one of the stat_cat entries to be the<br>default entry.<br> | BASE TABLE |
| [actor.stat_cat_entry_usr_map](actor.stat_cat_entry_usr_map.md) | 4 | <br>Statistical Catagory Entry to User map<br><br>Records the stat_cat entries for each user.<br> | BASE TABLE |
| [actor.stat_cat_sip_fields](actor.stat_cat_sip_fields.md) | 3 | <br>Actor Statistical Category SIP Fields<br><br>Contains the list of valid SIP Field identifiers for<br>Statistical Categories.<br> | BASE TABLE |
| [actor.toolbar](actor.toolbar.md) | 6 |  | BASE TABLE |
| [actor.usr](actor.usr.md) | 49 | <br>User objects<br><br>This table contains the core User objects that describe both<br>staff members and patrons.  The difference between the two<br>types of users is based on the user's permissions.<br> | BASE TABLE |
| [actor.usr_activity](actor.usr_activity.md) | 4 |  | BASE TABLE |
| [actor.usr_address](actor.usr_address.md) | 14 |  | BASE TABLE |
| [actor.usr_message](actor.usr_message.md) | 8 |  | BASE TABLE |
| [actor.usr_message_limited](actor.usr_message_limited.md) | 8 |  | VIEW |
| [actor.usr_note](actor.usr_note.md) | 7 |  | BASE TABLE |
| [actor.usr_org_unit_opt_in](actor.usr_org_unit_opt_in.md) | 6 |  | BASE TABLE |
| [actor.usr_password_reset](actor.usr_password_reset.md) | 5 | <br>Self-serve password reset requests<br> | BASE TABLE |
| [actor.usr_privacy_waiver](actor.usr_privacy_waiver.md) | 7 |  | BASE TABLE |
| [actor.usr_saved_search](actor.usr_saved_search.md) | 7 |  | BASE TABLE |
| [actor.usr_setting](actor.usr_setting.md) | 4 | <br>User settings<br><br>This table contains any arbitrary settings that a client<br>program would like to save for a user.<br> | BASE TABLE |
| [actor.usr_standing_penalty](actor.usr_standing_penalty.md) | 8 | <br>User standing penalties<br> | BASE TABLE |
| [actor.workstation](actor.workstation.md) | 3 |  | BASE TABLE |
| [actor.workstation_setting](actor.workstation_setting.md) | 4 |  | BASE TABLE |
| [asset.active_cns_copies](asset.active_cns_copies.md) | 3 |  | VIEW |
| [asset.active_copy_alert](asset.active_copy_alert.md) | 9 |  | VIEW |
| [asset.call_number](asset.call_number.md) | 13 |  | BASE TABLE |
| [asset.call_number_class](asset.call_number_class.md) | 4 | <br>Defines the call number normalization database functions in the "normalizer"<br>column and the tag/subfield combinations to use to lookup the call number in<br>the "field" column for a given classification scheme. Tag/subfield combinations<br>are delimited by commas.<br> | BASE TABLE |
| [asset.call_number_note](asset.call_number_note.md) | 7 |  | BASE TABLE |
| [asset.call_number_prefix](asset.call_number_prefix.md) | 4 |  | BASE TABLE |
| [asset.call_number_suffix](asset.call_number_suffix.md) | 4 |  | BASE TABLE |
| [asset.copy](asset.copy.md) | 33 |  | BASE TABLE |
| [asset.copy_alert](asset.copy_alert.md) | 9 |  | BASE TABLE |
| [asset.copy_location](asset.copy_location.md) | 12 |  | BASE TABLE |
| [asset.copy_location_group](asset.copy_location_group.md) | 6 |  | BASE TABLE |
| [asset.copy_location_group_map](asset.copy_location_group_map.md) | 3 |  | BASE TABLE |
| [asset.copy_location_order](asset.copy_location_order.md) | 4 |  | BASE TABLE |
| [asset.copy_note](asset.copy_note.md) | 7 |  | BASE TABLE |
| [asset.copy_part_map](asset.copy_part_map.md) | 3 |  | BASE TABLE |
| [asset.copy_tag](asset.copy_tag.md) | 9 |  | BASE TABLE |
| [asset.copy_tag_copy_map](asset.copy_tag_copy_map.md) | 3 |  | BASE TABLE |
| [asset.copy_template](asset.copy_template.md) | 25 |  | BASE TABLE |
| [asset.copy_vis_attr_cache](asset.copy_vis_attr_cache.md) | 4 |  | BASE TABLE |
| [asset.course_module_course](asset.course_module_course.md) | 6 |  | BASE TABLE |
| [asset.course_module_course_materials](asset.course_module_course_materials.md) | 10 |  | BASE TABLE |
| [asset.course_module_course_users](asset.course_module_course_users.md) | 4 |  | BASE TABLE |
| [asset.course_module_role](asset.course_module_role.md) | 3 |  | BASE TABLE |
| [asset.course_module_term](asset.course_module_term.md) | 5 |  | BASE TABLE |
| [asset.course_module_term_course_map](asset.course_module_term_course_map.md) | 3 |  | BASE TABLE |
| [asset.latest_inventory](asset.latest_inventory.md) | 4 |  | BASE TABLE |
| [asset.opac_visible_copies](asset.opac_visible_copies.md) | 4 | <br>Materialized view of copies that are visible in the OPAC, used by<br>search.query_parser_fts() to speed up OPAC visibility checks on large<br>databases.  Contents are maintained by a set of triggers.<br> | BASE TABLE |
| [asset.stat_cat](asset.stat_cat.md) | 8 |  | BASE TABLE |
| [asset.stat_cat_entry](asset.stat_cat_entry.md) | 4 |  | BASE TABLE |
| [asset.stat_cat_entry_copy_map](asset.stat_cat_entry_copy_map.md) | 4 |  | BASE TABLE |
| [asset.stat_cat_entry_transparency_map](asset.stat_cat_entry_transparency_map.md) | 4 |  | BASE TABLE |
| [asset.stat_cat_sip_fields](asset.stat_cat_sip_fields.md) | 3 | <br>Asset Statistical Category SIP Fields<br><br>Contains the list of valid SIP Field identifiers for<br>Statistical Categories.<br> | BASE TABLE |
| [asset.uri](asset.uri.md) | 5 |  | BASE TABLE |
| [asset.uri_call_number_map](asset.uri_call_number_map.md) | 3 |  | BASE TABLE |
| [auditor.acq_invoice_entry_history](auditor.acq_invoice_entry_history.md) | 16 |  | BASE TABLE |
| [auditor.acq_invoice_entry_lifecycle](auditor.acq_invoice_entry_lifecycle.md) | 16 |  | VIEW |
| [auditor.acq_invoice_history](auditor.acq_invoice_history.md) | 18 |  | BASE TABLE |
| [auditor.acq_invoice_item_history](auditor.acq_invoice_item_history.md) | 19 |  | BASE TABLE |
| [auditor.acq_invoice_item_lifecycle](auditor.acq_invoice_item_lifecycle.md) | 19 |  | VIEW |
| [auditor.acq_invoice_lifecycle](auditor.acq_invoice_lifecycle.md) | 18 |  | VIEW |
| [auditor.actor_org_unit_history](auditor.actor_org_unit_history.md) | 18 |  | BASE TABLE |
| [auditor.actor_org_unit_lifecycle](auditor.actor_org_unit_lifecycle.md) | 18 |  | VIEW |
| [auditor.actor_usr_address_history](auditor.actor_usr_address_history.md) | 19 |  | BASE TABLE |
| [auditor.actor_usr_address_lifecycle](auditor.actor_usr_address_lifecycle.md) | 19 |  | VIEW |
| [auditor.actor_usr_history](auditor.actor_usr_history.md) | 54 |  | BASE TABLE |
| [auditor.actor_usr_lifecycle](auditor.actor_usr_lifecycle.md) | 54 |  | VIEW |
| [auditor.asset_call_number_history](auditor.asset_call_number_history.md) | 18 |  | BASE TABLE |
| [auditor.asset_call_number_lifecycle](auditor.asset_call_number_lifecycle.md) | 18 |  | VIEW |
| [auditor.asset_copy_history](auditor.asset_copy_history.md) | 38 |  | BASE TABLE |
| [auditor.asset_copy_lifecycle](auditor.asset_copy_lifecycle.md) | 38 |  | VIEW |
| [auditor.biblio_record_entry_history](auditor.biblio_record_entry_history.md) | 24 |  | BASE TABLE |
| [auditor.biblio_record_entry_lifecycle](auditor.biblio_record_entry_lifecycle.md) | 24 |  | VIEW |
| [auditor.serial_unit_history](auditor.serial_unit_history.md) | 41 |  | BASE TABLE |
| [auditor.serial_unit_lifecycle](auditor.serial_unit_lifecycle.md) | 41 |  | VIEW |
| [authority.authority_linking](authority.authority_linking.md) | 4 |  | BASE TABLE |
| [authority.bib_linking](authority.bib_linking.md) | 3 |  | BASE TABLE |
| [authority.browse_axis](authority.browse_axis.md) | 4 |  | BASE TABLE |
| [authority.browse_axis_authority_field_map](authority.browse_axis_authority_field_map.md) | 3 |  | BASE TABLE |
| [authority.control_set](authority.control_set.md) | 3 |  | BASE TABLE |
| [authority.control_set_auth_field_metabib_field_map_blind_main](authority.control_set_auth_field_metabib_field_map_blind_main.md) | 2 | metabib fields for main entry auth fields that can't be linked to other records | VIEW |
| [authority.control_set_auth_field_metabib_field_map_blind_refs](authority.control_set_auth_field_metabib_field_map_blind_refs.md) | 2 | metabib fields for all auth fields that can't be linked to other records | VIEW |
| [authority.control_set_auth_field_metabib_field_map_blind_refs_only](authority.control_set_auth_field_metabib_field_map_blind_refs_only.md) | 2 | metabib fields for NON-main entry auth fields that can't be linked to other records | VIEW |
| [authority.control_set_auth_field_metabib_field_map_main](authority.control_set_auth_field_metabib_field_map_main.md) | 2 | metabib fields for main entry auth fields | VIEW |
| [authority.control_set_auth_field_metabib_field_map_refs](authority.control_set_auth_field_metabib_field_map_refs.md) | 2 | metabib fields for all auth fields | VIEW |
| [authority.control_set_auth_field_metabib_field_map_refs_only](authority.control_set_auth_field_metabib_field_map_refs_only.md) | 2 | metabib fields for NON-main entry auth fields | VIEW |
| [authority.control_set_authority_field](authority.control_set_authority_field.md) | 12 |  | BASE TABLE |
| [authority.control_set_bib_field](authority.control_set_bib_field.md) | 3 |  | BASE TABLE |
| [authority.control_set_bib_field_metabib_field_map](authority.control_set_bib_field_metabib_field_map.md) | 3 |  | BASE TABLE |
| [authority.full_rec](authority.full_rec.md) | 8 |  | BASE TABLE |
| [authority.heading_field](authority.heading_field.md) | 11 |  | BASE TABLE |
| [authority.heading_field_norm_map](authority.heading_field_norm_map.md) | 5 |  | BASE TABLE |
| [authority.rec_descriptor](authority.rec_descriptor.md) | 5 |  | BASE TABLE |
| [authority.record_entry](authority.record_entry.md) | 14 |  | BASE TABLE |
| [authority.record_note](authority.record_note.md) | 7 |  | BASE TABLE |
| [authority.simple_heading](authority.simple_heading.md) | 7 |  | BASE TABLE |
| [authority.thesaurus](authority.thesaurus.md) | 6 |  | BASE TABLE |
| [authority.tracing_links](authority.tracing_links.md) | 12 |  | VIEW |
| [biblio.monograph_part](biblio.monograph_part.md) | 5 |  | BASE TABLE |
| [biblio.peer_bib_copy_map](biblio.peer_bib_copy_map.md) | 4 |  | BASE TABLE |
| [biblio.peer_type](biblio.peer_type.md) | 2 |  | BASE TABLE |
| [biblio.record_entry](biblio.record_entry.md) | 19 |  | BASE TABLE |
| [biblio.record_note](biblio.record_note.md) | 8 |  | BASE TABLE |
| [booking.reservation](booking.reservation.md) | 24 |  | BASE TABLE |
| [booking.reservation_attr_value_map](booking.reservation_attr_value_map.md) | 3 |  | BASE TABLE |
| [booking.resource](booking.resource.md) | 8 |  | BASE TABLE |
| [booking.resource_attr](booking.resource_attr.md) | 5 |  | BASE TABLE |
| [booking.resource_attr_map](booking.resource_attr_map.md) | 4 |  | BASE TABLE |
| [booking.resource_attr_value](booking.resource_attr_value.md) | 4 |  | BASE TABLE |
| [booking.resource_type](booking.resource_type.md) | 10 |  | BASE TABLE |
| [config.audience_map](config.audience_map.md) | 3 |  | VIEW |
| [config.barcode_completion](config.barcode_completion.md) | 10 |  | BASE TABLE |
| [config.best_hold_order](config.best_hold_order.md) | 13 |  | BASE TABLE |
| [config.bib_level_map](config.bib_level_map.md) | 2 |  | VIEW |
| [config.bib_source](config.bib_source.md) | 5 | <br>This is table is used to set up the relative "quality" of each<br>MARC source, such as OCLC.  Also identifies "transcendant" sources,<br>i.e., sources of bib records that should display in the OPAC<br>even if no copies or located URIs are attached. Also indicates if<br>the source is allowed to have actual copies on its bibs. Volumes<br>for targeted URIs are unaffected by this setting.<br> | BASE TABLE |
| [config.biblio_fingerprint](config.biblio_fingerprint.md) | 5 |  | BASE TABLE |
| [config.billing_type](config.billing_type.md) | 4 |  | BASE TABLE |
| [config.carousel_type](config.carousel_type.md) | 6 |  | BASE TABLE |
| [config.circ_limit_group](config.circ_limit_group.md) | 3 |  | BASE TABLE |
| [config.circ_limit_set](config.circ_limit_set.md) | 7 |  | BASE TABLE |
| [config.circ_limit_set_circ_mod_map](config.circ_limit_set_circ_mod_map.md) | 3 |  | BASE TABLE |
| [config.circ_limit_set_copy_loc_map](config.circ_limit_set_copy_loc_map.md) | 3 |  | BASE TABLE |
| [config.circ_limit_set_group_map](config.circ_limit_set_group_map.md) | 4 |  | BASE TABLE |
| [config.circ_matrix_limit_set_map](config.circ_matrix_limit_set_map.md) | 5 |  | BASE TABLE |
| [config.circ_matrix_matchpoint](config.circ_matrix_matchpoint.md) | 30 |  | BASE TABLE |
| [config.circ_matrix_weights](config.circ_matrix_weights.md) | 19 |  | BASE TABLE |
| [config.circ_modifier](config.circ_modifier.md) | 6 |  | BASE TABLE |
| [config.coded_value_map](config.coded_value_map.md) | 9 |  | BASE TABLE |
| [config.composite_attr_entry_definition](config.composite_attr_entry_definition.md) | 2 |  | BASE TABLE |
| [config.copy_alert_type](config.copy_alert_type.md) | 11 |  | BASE TABLE |
| [config.copy_status](config.copy_status.md) | 8 | <br>Copy Statuses<br><br>The available copy statuses, and whether a copy in that<br>status is available for hold request capture.  0 (zero) is<br>the only special number in this set, meaning that the item<br>is available for immediate checkout, and is counted as available<br>in the OPAC.<br><br>Statuses with an ID below 100 are not removable, and have special<br>meaning in the code.  Do not change them except to translate the<br>textual name.<br><br>You may add and remove statuses above 100, and these can be used<br>to remove items from normal circulation without affecting the rest<br>of the copy's values or its location.<br> | BASE TABLE |
| [config.copy_tag_type](config.copy_tag_type.md) | 3 |  | BASE TABLE |
| [config.db_patch_dependencies](config.db_patch_dependencies.md) | 3 |  | BASE TABLE |
| [config.display_field_map](config.display_field_map.md) | 3 |  | BASE TABLE |
| [config.filter_dialog_filter_set](config.filter_dialog_filter_set.md) | 7 |  | BASE TABLE |
| [config.filter_dialog_interface](config.filter_dialog_interface.md) | 2 |  | BASE TABLE |
| [config.floating_group](config.floating_group.md) | 3 |  | BASE TABLE |
| [config.floating_group_member](config.floating_group_member.md) | 6 |  | BASE TABLE |
| [config.global_flag](config.global_flag.md) | 4 |  | BASE TABLE |
| [config.hard_due_date](config.hard_due_date.md) | 5 |  | BASE TABLE |
| [config.hard_due_date_values](config.hard_due_date_values.md) | 4 |  | BASE TABLE |
| [config.hold_matrix_matchpoint](config.hold_matrix_matchpoint.md) | 26 |  | BASE TABLE |
| [config.hold_matrix_weights](config.hold_matrix_weights.md) | 17 |  | BASE TABLE |
| [config.hold_type](config.hold_type.md) | 3 |  | BASE TABLE |
| [config.i18n_core](config.i18n_core.md) | 5 |  | BASE TABLE |
| [config.i18n_locale](config.i18n_locale.md) | 5 |  | BASE TABLE |
| [config.identification_type](config.identification_type.md) | 2 | <br>Types of valid patron identification.<br><br>Each patron must display at least one valid form of identification<br>in order to get a library card.  This table lists those forms.<br> | BASE TABLE |
| [config.idl_field_doc](config.idl_field_doc.md) | 5 |  | BASE TABLE |
| [config.index_normalizer](config.index_normalizer.md) | 5 |  | BASE TABLE |
| [config.internal_flag](config.internal_flag.md) | 3 |  | BASE TABLE |
| [config.item_form_map](config.item_form_map.md) | 2 |  | VIEW |
| [config.item_type_map](config.item_type_map.md) | 2 |  | VIEW |
| [config.language_map](config.language_map.md) | 2 |  | VIEW |
| [config.lit_form_map](config.lit_form_map.md) | 3 |  | VIEW |
| [config.marc21_ff_pos_map](config.marc21_ff_pos_map.md) | 7 |  | BASE TABLE |
| [config.marc21_physical_characteristic_subfield_map](config.marc21_physical_characteristic_subfield_map.md) | 6 |  | BASE TABLE |
| [config.marc21_physical_characteristic_type_map](config.marc21_physical_characteristic_type_map.md) | 2 |  | BASE TABLE |
| [config.marc21_physical_characteristic_value_map](config.marc21_physical_characteristic_value_map.md) | 4 |  | BASE TABLE |
| [config.marc21_rec_type_map](config.marc21_rec_type_map.md) | 3 |  | BASE TABLE |
| [config.marc_field](config.marc_field.md) | 11 | <br>This table stores a list of MARC fields recognized by the Evergreen<br>instance.  Note that we're not aiming for completely generic ISO2709<br>support: we're assuming things like three characters for a tag,<br>one-character subfield labels, two indicators per variable data field,<br>and the like, all of which are technically specializations of ISO2709.<br><br>Of particular significance is the owner column; if it's set to a null<br>value, the field definition is assumed to come from a national<br>standards body; if it's set to a non-null value, the field definition<br>is an OU-level addition to or override of the standard.<br> | BASE TABLE |
| [config.marc_field_for_ou](config.marc_field_for_ou.md) | 12 |  | VIEW |
| [config.marc_format](config.marc_format.md) | 3 | <br>List of MARC formats supported by this Evergreen<br>database. This exists primarily as a hook for future<br>support of UNIMARC, though whether that will ever<br>happen remains to be seen.<br> | BASE TABLE |
| [config.marc_subfield](config.marc_subfield.md) | 11 | <br>This table stores the list of subfields recognized by this Evergreen<br>instance.  As with config.marc_field, of particular significance is the<br>owner column; if it's set to a null value, the subfield definition is<br>assumed to come from a national standards body; if it's set to a non-null<br>value, the subfield definition is an OU-level addition to or override<br>of the standard.<br> | BASE TABLE |
| [config.marc_subfield_for_ou](config.marc_subfield_for_ou.md) | 12 |  | VIEW |
| [config.metabib_class](config.metabib_class.md) | 9 |  | BASE TABLE |
| [config.metabib_class_ts_map](config.metabib_class_ts_map.md) | 8 | <br>Text Search Configs for metabib class indexing<br><br>This table contains text search config definitions for<br>storing index_vector values.<br> | BASE TABLE |
| [config.metabib_field](config.metabib_field.md) | 18 | <br>XPath used for record indexing ingest<br><br>This table contains the XPath used to chop up MODS into its<br>indexable parts.  Each XPath entry is named and assigned to<br>a "class" of either title, subject, author, keyword, series<br>or identifier.<br> | BASE TABLE |
| [config.metabib_field_index_norm_map](config.metabib_field_index_norm_map.md) | 5 |  | BASE TABLE |
| [config.metabib_field_ts_map](config.metabib_field_ts_map.md) | 7 | <br>Text Search Configs for metabib field indexing<br><br>This table contains text search config definitions for<br>storing index_vector values.<br> | BASE TABLE |
| [config.metabib_field_virtual_map](config.metabib_field_virtual_map.md) | 4 | <br>Maps between real (physically extracted) index definitions<br>and virtual (target sync, no required extraction of its own)<br>index definitions.<br><br>The virtual side may not extract any data of its own, but<br>will collect data from all of the real fields.  This reduces<br>extraction (ingest) overhead by eliminating duplcated extraction,<br>and allows for searching across novel combinations of fields, such<br>as names used as either subjects or authors.  By preserving this<br>mapping rather than defining duplicate extractions, information<br>about the originating, "real" index definitions can be used<br>in interesting ways, such as highlighting in search results.<br> | BASE TABLE |
| [config.metabib_search_alias](config.metabib_search_alias.md) | 3 |  | BASE TABLE |
| [config.net_access_level](config.net_access_level.md) | 2 | <br>Patron Network Access level<br><br>This will be used to inform the in-library firewall of how much<br>internet access the using patron should be allowed.<br> | BASE TABLE |
| [config.non_cataloged_type](config.non_cataloged_type.md) | 5 | <br>Types of valid non-cataloged items.<br> | BASE TABLE |
| [config.org_unit_setting_type](config.org_unit_setting_type.md) | 8 |  | BASE TABLE |
| [config.org_unit_setting_type_log](config.org_unit_setting_type_log.md) | 6 | <br>Org Unit setting Logs<br><br>This table contains the most recent changes to each setting <br>in actor.org_unit_setting, allowing for mistakes to be undone.<br>This is NOT meant to be an auditor, but rather an undo/redo.<br> | BASE TABLE |
| [config.print_template](config.print_template.md) | 8 |  | BASE TABLE |
| [config.record_attr_definition](config.record_attr_definition.md) | 17 |  | BASE TABLE |
| [config.record_attr_index_norm_map](config.record_attr_index_norm_map.md) | 5 |  | BASE TABLE |
| [config.remote_account](config.remote_account.md) | 9 |  | BASE TABLE |
| [config.remoteauth_profile](config.remoteauth_profile.md) | 10 |  | BASE TABLE |
| [config.rule_age_hold_protect](config.rule_age_hold_protect.md) | 4 | <br>Hold Item Age Protection rules<br><br>A hold request can only capture new(ish) items when they are<br>within a particular proximity of the pickup_lib of the request.<br>The proximity ('prox' column) is calculated by counting<br>the number of tree edges between the pickup_lib and either the<br>owning_lib or circ_lib of the copy that could fulfill the hold,<br>as determined by the distance_is_from_owner value of the hold matrix<br>rule controlling the hold request.<br> | BASE TABLE |
| [config.rule_circ_duration](config.rule_circ_duration.md) | 7 | <br>Circulation Duration rules<br><br>Each circulation is given a duration based on one of these rules.<br> | BASE TABLE |
| [config.rule_max_fine](config.rule_max_fine.md) | 4 | <br>Circulation Max Fine rules<br><br>Each circulation is given a maximum fine based on one of<br>these rules.<br> | BASE TABLE |
| [config.rule_recurring_fine](config.rule_recurring_fine.md) | 7 | <br>Circulation Recurring Fine rules<br><br>Each circulation is given a recurring fine amount based on one of<br>these rules.  Note that it is recommended to run the fine generator<br>(from cron) at least as frequently as the lowest recurrence interval<br>used by your circulation rules so that accrued fines will be up<br>to date.<br> | BASE TABLE |
| [config.settings_group](config.settings_group.md) | 2 |  | BASE TABLE |
| [config.sms_carrier](config.sms_carrier.md) | 5 |  | BASE TABLE |
| [config.standing](config.standing.md) | 2 | <br>Patron Standings<br><br>This table contains the values that can be applied to a patron<br>by a staff member.  These values should not be changed, other<br>than for translation, as the ID column is currently a "magic<br>number" in the source. :(<br> | BASE TABLE |
| [config.standing_penalty](config.standing_penalty.md) | 7 |  | BASE TABLE |
| [config.ts_config_list](config.ts_config_list.md) | 2 | <br>Full Text Configs<br><br>A list of full text configs with names and descriptions.<br> | BASE TABLE |
| [config.upgrade_log](config.upgrade_log.md) | 3 |  | BASE TABLE |
| [config.usr_activity_type](config.usr_activity_type.md) | 8 |  | BASE TABLE |
| [config.usr_setting_type](config.usr_setting_type.md) | 8 |  | BASE TABLE |
| [config.videorecording_format_map](config.videorecording_format_map.md) | 2 |  | VIEW |
| [config.weight_assoc](config.weight_assoc.md) | 5 |  | BASE TABLE |
| [config.workstation_setting_type](config.workstation_setting_type.md) | 6 |  | BASE TABLE |
| [config.xml_transform](config.xml_transform.md) | 4 |  | BASE TABLE |
| [config.z3950_attr](config.z3950_attr.md) | 7 |  | BASE TABLE |
| [config.z3950_index_field_map](config.z3950_index_field_map.md) | 6 |  | BASE TABLE |
| [config.z3950_source](config.z3950_source.md) | 9 | <br>Z39.50 Sources<br><br>Each row in this table represents a database searchable via Z39.50.<br> | BASE TABLE |
| [config.z3950_source_credentials](config.z3950_source_credentials.md) | 5 |  | BASE TABLE |
| [container.biblio_record_entry_bucket](container.biblio_record_entry_bucket.md) | 8 |  | BASE TABLE |
| [container.biblio_record_entry_bucket_item](container.biblio_record_entry_bucket_item.md) | 5 |  | BASE TABLE |
| [container.biblio_record_entry_bucket_item_note](container.biblio_record_entry_bucket_item_note.md) | 3 |  | BASE TABLE |
| [container.biblio_record_entry_bucket_note](container.biblio_record_entry_bucket_note.md) | 3 |  | BASE TABLE |
| [container.biblio_record_entry_bucket_type](container.biblio_record_entry_bucket_type.md) | 2 |  | BASE TABLE |
| [container.call_number_bucket](container.call_number_bucket.md) | 8 |  | BASE TABLE |
| [container.call_number_bucket_item](container.call_number_bucket_item.md) | 5 |  | BASE TABLE |
| [container.call_number_bucket_item_note](container.call_number_bucket_item_note.md) | 3 |  | BASE TABLE |
| [container.call_number_bucket_note](container.call_number_bucket_note.md) | 3 |  | BASE TABLE |
| [container.call_number_bucket_type](container.call_number_bucket_type.md) | 2 |  | BASE TABLE |
| [container.carousel](container.carousel.md) | 15 |  | BASE TABLE |
| [container.carousel_org_unit](container.carousel_org_unit.md) | 5 |  | BASE TABLE |
| [container.copy_bucket](container.copy_bucket.md) | 8 |  | BASE TABLE |
| [container.copy_bucket_item](container.copy_bucket_item.md) | 5 |  | BASE TABLE |
| [container.copy_bucket_item_note](container.copy_bucket_item_note.md) | 3 |  | BASE TABLE |
| [container.copy_bucket_note](container.copy_bucket_note.md) | 3 |  | BASE TABLE |
| [container.copy_bucket_type](container.copy_bucket_type.md) | 2 |  | BASE TABLE |
| [container.user_bucket](container.user_bucket.md) | 8 |  | BASE TABLE |
| [container.user_bucket_item](container.user_bucket_item.md) | 5 |  | BASE TABLE |
| [container.user_bucket_item_note](container.user_bucket_item_note.md) | 3 |  | BASE TABLE |
| [container.user_bucket_note](container.user_bucket_note.md) | 3 |  | BASE TABLE |
| [container.user_bucket_type](container.user_bucket_type.md) | 2 |  | BASE TABLE |
| [edelweiss.bib_items_aadl](edelweiss.bib_items_aadl.md) | 1 |  | BASE TABLE |
| [edelweiss.bibs_aadl](edelweiss.bibs_aadl.md) | 10 |  | BASE TABLE |
| [edelweiss.circs](edelweiss.circs.md) | 7 |  | BASE TABLE |
| [edelweiss.holds](edelweiss.holds.md) | 6 |  | BASE TABLE |
| [edelweiss.holds_items](edelweiss.holds_items.md) | 4 |  | BASE TABLE |
| [edelweiss.items](edelweiss.items.md) | 12 |  | BASE TABLE |
| [edelweiss.log](edelweiss.log.md) | 4 |  | BASE TABLE |
| [edelweiss.trans_items](edelweiss.trans_items.md) | 8 |  | BASE TABLE |
| [edelweiss.transactions](edelweiss.transactions.md) | 8 |  | BASE TABLE |
| [equinox.actor_usr_standing_penalty](equinox.actor_usr_standing_penalty.md) | 8 |  | BASE TABLE |
| [evergreen.bib_staging](evergreen.bib_staging.md) | 10 |  | BASE TABLE |
| [evergreen.cn_staging](evergreen.cn_staging.md) | 27 |  | BASE TABLE |
| [evergreen.dcb_ids](evergreen.dcb_ids.md) | 1 |  | BASE TABLE |
| [evergreen.holds_staging](evergreen.holds_staging.md) | 15 |  | BASE TABLE |
| [evergreen.patron_staging](evergreen.patron_staging.md) | 57 |  | BASE TABLE |
| [evergreen.pg_buffercache](evergreen.pg_buffercache.md) | 9 |  | VIEW |
| [evergreen.status_staging](evergreen.status_staging.md) | 5 |  | BASE TABLE |
| [evergreen.xact_staging](evergreen.xact_staging.md) | 25 |  | BASE TABLE |
| [evergreen.xact_staging_first_import](evergreen.xact_staging_first_import.md) | 25 |  | BASE TABLE |
| [extend_reporter.copy_count_per_org](extend_reporter.copy_count_per_org.md) | 8 |  | VIEW |
| [extend_reporter.full_circ_count](extend_reporter.full_circ_count.md) | 2 |  | VIEW |
| [extend_reporter.global_bibs_by_holding_update](extend_reporter.global_bibs_by_holding_update.md) | 3 |  | VIEW |
| [extend_reporter.legacy_circ_count](extend_reporter.legacy_circ_count.md) | 2 |  | BASE TABLE |
| [ipage.holds_dtn](ipage.holds_dtn.md) | 30 |  | BASE TABLE |
| [ipage.holds_dtn_dev](ipage.holds_dtn_dev.md) | 29 |  | BASE TABLE |
| [ipage.holds_mcb](ipage.holds_mcb.md) | 30 |  | BASE TABLE |
| [ipage.holds_mcb_dev](ipage.holds_mcb_dev.md) | 29 |  | BASE TABLE |
| [ipage.holds_pts](ipage.holds_pts.md) | 30 |  | BASE TABLE |
| [ipage.holds_pts_dev](ipage.holds_pts_dev.md) | 29 |  | BASE TABLE |
| [ipage.holds_tra](ipage.holds_tra.md) | 30 |  | BASE TABLE |
| [ipage.holds_tra_dev](ipage.holds_tra_dev.md) | 29 |  | BASE TABLE |
| [ipage.holds_wg](ipage.holds_wg.md) | 30 |  | BASE TABLE |
| [ipage.holds_wg_dev](ipage.holds_wg_dev.md) | 29 |  | BASE TABLE |
| [ipage.shelf_dtn](ipage.shelf_dtn.md) | 29 |  | BASE TABLE |
| [ipage.shelf_dtn_dev](ipage.shelf_dtn_dev.md) | 29 |  | BASE TABLE |
| [ipage.shelf_mcb](ipage.shelf_mcb.md) | 29 |  | BASE TABLE |
| [ipage.shelf_mcb_dev](ipage.shelf_mcb_dev.md) | 29 |  | BASE TABLE |
| [ipage.shelf_pts](ipage.shelf_pts.md) | 29 |  | BASE TABLE |
| [ipage.shelf_pts_dev](ipage.shelf_pts_dev.md) | 29 |  | BASE TABLE |
| [ipage.shelf_tra](ipage.shelf_tra.md) | 29 |  | BASE TABLE |
| [ipage.shelf_tra_dev](ipage.shelf_tra_dev.md) | 29 |  | BASE TABLE |
| [ipage.shelf_wg](ipage.shelf_wg.md) | 29 |  | BASE TABLE |
| [ipage.shelf_wg_dev](ipage.shelf_wg_dev.md) | 29 |  | BASE TABLE |
| [metabib.author_field_entry](metabib.author_field_entry.md) | 5 |  | BASE TABLE |
| [metabib.browse_entry](metabib.browse_entry.md) | 4 |  | BASE TABLE |
| [metabib.browse_entry_def_map](metabib.browse_entry_def_map.md) | 5 |  | BASE TABLE |
| [metabib.browse_entry_simple_heading_map](metabib.browse_entry_simple_heading_map.md) | 3 |  | BASE TABLE |
| [metabib.combined_all_field_entry](metabib.combined_all_field_entry.md) | 3 |  | VIEW |
| [metabib.combined_author_field_entry](metabib.combined_author_field_entry.md) | 3 |  | BASE TABLE |
| [metabib.combined_identifier_field_entry](metabib.combined_identifier_field_entry.md) | 3 |  | BASE TABLE |
| [metabib.combined_keyword_field_entry](metabib.combined_keyword_field_entry.md) | 3 |  | BASE TABLE |
| [metabib.combined_series_field_entry](metabib.combined_series_field_entry.md) | 3 |  | BASE TABLE |
| [metabib.combined_subject_field_entry](metabib.combined_subject_field_entry.md) | 3 |  | BASE TABLE |
| [metabib.combined_title_field_entry](metabib.combined_title_field_entry.md) | 3 |  | BASE TABLE |
| [metabib.composite_attr_id_map](metabib.composite_attr_id_map.md) | 3 |  | VIEW |
| [metabib.compressed_display_entry](metabib.compressed_display_entry.md) | 6 |  | VIEW |
| [metabib.display_entry](metabib.display_entry.md) | 4 |  | BASE TABLE |
| [metabib.facet_entry](metabib.facet_entry.md) | 4 |  | BASE TABLE |
| [metabib.flat_display_entry](metabib.flat_display_entry.md) | 6 |  | VIEW |
| [metabib.full_attr_id_map](metabib.full_attr_id_map.md) | 3 |  | VIEW |
| [metabib.full_rec](metabib.full_rec.md) | 8 |  | VIEW |
| [metabib.identifier_field_entry](metabib.identifier_field_entry.md) | 5 |  | BASE TABLE |
| [metabib.keyword_field_entry](metabib.keyword_field_entry.md) | 5 |  | BASE TABLE |
| [metabib.metarecord](metabib.metarecord.md) | 4 |  | BASE TABLE |
| [metabib.metarecord_source_map](metabib.metarecord_source_map.md) | 3 |  | BASE TABLE |
| [metabib.real_full_rec](metabib.real_full_rec.md) | 8 |  | BASE TABLE |
| [metabib.rec_descriptor](metabib.rec_descriptor.md) | 17 |  | VIEW |
| [metabib.record_attr](metabib.record_attr.md) | 2 |  | VIEW |
| [metabib.record_attr_flat](metabib.record_attr_flat.md) | 3 |  | VIEW |
| [metabib.record_attr_id_map](metabib.record_attr_id_map.md) | 3 |  | VIEW |
| [metabib.record_attr_vector_list](metabib.record_attr_vector_list.md) | 2 |  | BASE TABLE |
| [metabib.record_sorter](metabib.record_sorter.md) | 4 |  | BASE TABLE |
| [metabib.series_field_entry](metabib.series_field_entry.md) | 5 |  | BASE TABLE |
| [metabib.subject_field_entry](metabib.subject_field_entry.md) | 5 |  | BASE TABLE |
| [metabib.title_field_entry](metabib.title_field_entry.md) | 5 |  | BASE TABLE |
| [metabib.uncontrolled_record_attr_value](metabib.uncontrolled_record_attr_value.md) | 3 |  | BASE TABLE |
| [metabib.wide_display_entry](metabib.wide_display_entry.md) | 20 |  | VIEW |
| [money.account_adjustment](money.account_adjustment.md) | 9 |  | BASE TABLE |
| [money.aged_billing](money.aged_billing.md) | 13 |  | BASE TABLE |
| [money.aged_payment](money.aged_payment.md) | 10 |  | BASE TABLE |
| [money.all_billings](money.all_billings.md) | 13 |  | VIEW |
| [money.all_payments](money.all_payments.md) | 10 |  | VIEW |
| [money.billable_xact](money.billable_xact.md) | 5 |  | BASE TABLE |
| [money.billable_xact_summary](money.billable_xact_summary.md) | 14 |  | VIEW |
| [money.billable_xact_summary_location_view](money.billable_xact_summary_location_view.md) | 15 |  | VIEW |
| [money.billable_xact_with_void_summary](money.billable_xact_with_void_summary.md) | 14 |  | VIEW |
| [money.billing](money.billing.md) | 13 |  | BASE TABLE |
| [money.bnm_desk_payment](money.bnm_desk_payment.md) | 9 |  | BASE TABLE |
| [money.bnm_payment](money.bnm_payment.md) | 8 |  | BASE TABLE |
| [money.bnm_payment_view](money.bnm_payment_view.md) | 9 |  | VIEW |
| [money.cash_payment](money.cash_payment.md) | 9 |  | BASE TABLE |
| [money.cashdrawer_payment_view](money.cashdrawer_payment_view.md) | 7 |  | VIEW |
| [money.check_payment](money.check_payment.md) | 10 |  | BASE TABLE |
| [money.collections_tracker](money.collections_tracker.md) | 5 |  | BASE TABLE |
| [money.credit_card_payment](money.credit_card_payment.md) | 13 |  | BASE TABLE |
| [money.credit_payment](money.credit_payment.md) | 8 |  | BASE TABLE |
| [money.debit_card_payment](money.debit_card_payment.md) | 9 |  | BASE TABLE |
| [money.desk_payment_view](money.desk_payment_view.md) | 10 |  | VIEW |
| [money.forgive_payment](money.forgive_payment.md) | 8 |  | BASE TABLE |
| [money.goods_payment](money.goods_payment.md) | 8 |  | BASE TABLE |
| [money.grocery](money.grocery.md) | 7 |  | BASE TABLE |
| [money.materialized_billable_xact_summary](money.materialized_billable_xact_summary.md) | 14 |  | BASE TABLE |
| [money.non_drawer_payment_view](money.non_drawer_payment_view.md) | 9 |  | VIEW |
| [money.open_billable_xact_summary](money.open_billable_xact_summary.md) | 15 |  | VIEW |
| [money.open_transaction_billing_summary](money.open_transaction_billing_summary.md) | 5 |  | VIEW |
| [money.open_transaction_billing_type_summary](money.open_transaction_billing_type_summary.md) | 5 |  | VIEW |
| [money.open_transaction_payment_summary](money.open_transaction_payment_summary.md) | 5 |  | VIEW |
| [money.open_usr_circulation_summary](money.open_usr_circulation_summary.md) | 4 |  | VIEW |
| [money.open_usr_summary](money.open_usr_summary.md) | 4 |  | VIEW |
| [money.open_with_balance_usr_summary](money.open_with_balance_usr_summary.md) | 4 |  | VIEW |
| [money.payment](money.payment.md) | 6 |  | BASE TABLE |
| [money.payment_view](money.payment_view.md) | 7 |  | VIEW |
| [money.payment_view_for_aging](money.payment_view_for_aging.md) | 10 |  | VIEW |
| [money.transaction_billing_summary](money.transaction_billing_summary.md) | 5 |  | VIEW |
| [money.transaction_billing_type_summary](money.transaction_billing_type_summary.md) | 5 |  | VIEW |
| [money.transaction_billing_with_void_summary](money.transaction_billing_with_void_summary.md) | 5 |  | VIEW |
| [money.transaction_payment_summary](money.transaction_payment_summary.md) | 5 |  | VIEW |
| [money.transaction_payment_with_void_summary](money.transaction_payment_with_void_summary.md) | 5 |  | VIEW |
| [money.usr_circulation_summary](money.usr_circulation_summary.md) | 4 |  | VIEW |
| [money.usr_summary](money.usr_summary.md) | 4 |  | VIEW |
| [money.work_payment](money.work_payment.md) | 8 |  | BASE TABLE |
| [offline.script](offline.script.md) | 8 |  | BASE TABLE |
| [offline.session](offline.session.md) | 9 |  | BASE TABLE |
| [paging.holds](paging.holds.md) | 20 |  | BASE TABLE |
| [paging.holds_archive](paging.holds_archive.md) | 22 |  | BASE TABLE |
| [paging.shelves](paging.shelves.md) | 23 |  | BASE TABLE |
| [paging.shelves_archive](paging.shelves_archive.md) | 24 |  | BASE TABLE |
| [permission.grp_penalty_threshold](permission.grp_penalty_threshold.md) | 5 |  | BASE TABLE |
| [permission.grp_perm_map](permission.grp_perm_map.md) | 5 |  | BASE TABLE |
| [permission.grp_tree](permission.grp_tree.md) | 8 |  | BASE TABLE |
| [permission.grp_tree_display_entry](permission.grp_tree_display_entry.md) | 5 |  | BASE TABLE |
| [permission.perm_list](permission.perm_list.md) | 3 |  | BASE TABLE |
| [permission.usr_grp_map](permission.usr_grp_map.md) | 3 |  | BASE TABLE |
| [permission.usr_object_perm_map](permission.usr_object_perm_map.md) | 6 |  | BASE TABLE |
| [permission.usr_perm_map](permission.usr_perm_map.md) | 5 |  | BASE TABLE |
| [permission.usr_work_ou_map](permission.usr_work_ou_map.md) | 3 |  | BASE TABLE |
| [public.migrations](public.migrations.md) | 3 |  | BASE TABLE |
| [public.pg_stat_statements](public.pg_stat_statements.md) | 23 |  | VIEW |
| [query.bind_variable](query.bind_variable.md) | 5 |  | BASE TABLE |
| [query.case_branch](query.case_branch.md) | 5 |  | BASE TABLE |
| [query.datatype](query.datatype.md) | 4 |  | BASE TABLE |
| [query.expr_xbet](query.expr_xbet.md) | 6 |  | VIEW |
| [query.expr_xbind](query.expr_xbind.md) | 5 |  | VIEW |
| [query.expr_xbool](query.expr_xbool.md) | 6 |  | VIEW |
| [query.expr_xcase](query.expr_xcase.md) | 6 |  | VIEW |
| [query.expr_xcast](query.expr_xcast.md) | 7 |  | VIEW |
| [query.expr_xcol](query.expr_xcol.md) | 7 |  | VIEW |
| [query.expr_xex](query.expr_xex.md) | 6 |  | VIEW |
| [query.expr_xfunc](query.expr_xfunc.md) | 7 |  | VIEW |
| [query.expr_xin](query.expr_xin.md) | 7 |  | VIEW |
| [query.expr_xisnull](query.expr_xisnull.md) | 6 |  | VIEW |
| [query.expr_xnull](query.expr_xnull.md) | 5 |  | VIEW |
| [query.expr_xnum](query.expr_xnum.md) | 5 |  | VIEW |
| [query.expr_xop](query.expr_xop.md) | 8 |  | VIEW |
| [query.expr_xser](query.expr_xser.md) | 6 |  | VIEW |
| [query.expr_xstr](query.expr_xstr.md) | 5 |  | VIEW |
| [query.expr_xsubq](query.expr_xsubq.md) | 6 |  | VIEW |
| [query.expression](query.expression.md) | 16 |  | BASE TABLE |
| [query.from_relation](query.from_relation.md) | 11 |  | BASE TABLE |
| [query.function_param_def](query.function_param_def.md) | 4 |  | BASE TABLE |
| [query.function_sig](query.function_sig.md) | 4 |  | BASE TABLE |
| [query.order_by_item](query.order_by_item.md) | 4 |  | BASE TABLE |
| [query.query_sequence](query.query_sequence.md) | 4 |  | BASE TABLE |
| [query.record_column](query.record_column.md) | 5 |  | BASE TABLE |
| [query.select_item](query.select_item.md) | 6 |  | BASE TABLE |
| [query.stored_query](query.stored_query.md) | 9 |  | BASE TABLE |
| [query.subfield](query.subfield.md) | 4 |  | BASE TABLE |
| [rating.badge](rating.badge.md) | 19 |  | BASE TABLE |
| [rating.badge_with_orgs](rating.badge_with_orgs.md) | 20 |  | VIEW |
| [rating.popularity_parameter](rating.popularity_parameter.md) | 7 |  | BASE TABLE |
| [rating.record_badge_score](rating.record_badge_score.md) | 4 |  | BASE TABLE |
| [reporter.circ_type](reporter.circ_type.md) | 2 |  | VIEW |
| [reporter.currently_running](reporter.currently_running.md) | 5 |  | VIEW |
| [reporter.demographic](reporter.demographic.md) | 3 |  | VIEW |
| [reporter.hold_request_record](reporter.hold_request_record.md) | 4 |  | BASE TABLE |
| [reporter.materialized_simple_record](reporter.materialized_simple_record.md) | 11 |  | BASE TABLE |
| [reporter.old_super_simple_record](reporter.old_super_simple_record.md) | 11 |  | VIEW |
| [reporter.output_folder](reporter.output_folder.md) | 7 |  | BASE TABLE |
| [reporter.overdue_circs](reporter.overdue_circs.md) | 34 |  | VIEW |
| [reporter.overdue_reports](reporter.overdue_reports.md) | 5 |  | VIEW |
| [reporter.pending_reports](reporter.pending_reports.md) | 5 |  | VIEW |
| [reporter.report](reporter.report.md) | 10 |  | BASE TABLE |
| [reporter.report_folder](reporter.report_folder.md) | 7 |  | BASE TABLE |
| [reporter.schedule](reporter.schedule.md) | 16 |  | BASE TABLE |
| [reporter.schedule_original](reporter.schedule_original.md) | 16 |  | BASE TABLE |
| [reporter.simple_record](reporter.simple_record.md) | 22 |  | VIEW |
| [reporter.super_simple_record](reporter.super_simple_record.md) | 11 |  | VIEW |
| [reporter.template](reporter.template.md) | 7 |  | BASE TABLE |
| [reporter.template_folder](reporter.template_folder.md) | 7 |  | BASE TABLE |
| [reporter.xact_billing_totals](reporter.xact_billing_totals.md) | 4 |  | VIEW |
| [reporter.xact_paid_totals](reporter.xact_paid_totals.md) | 4 |  | VIEW |
| [search.best_tsconfig](search.best_tsconfig.md) | 2 |  | VIEW |
| [search.relevance_adjustment](search.relevance_adjustment.md) | 5 |  | BASE TABLE |
| [serial.any_summary](serial.any_summary.md) | 6 |  | VIEW |
| [serial.basic_summary](serial.basic_summary.md) | 5 |  | BASE TABLE |
| [serial.caption_and_pattern](serial.caption_and_pattern.md) | 19 |  | BASE TABLE |
| [serial.distribution](serial.distribution.md) | 13 |  | BASE TABLE |
| [serial.distribution_note](serial.distribution_note.md) | 8 |  | BASE TABLE |
| [serial.index_summary](serial.index_summary.md) | 5 |  | BASE TABLE |
| [serial.issuance](serial.issuance.md) | 12 |  | BASE TABLE |
| [serial.item](serial.item.md) | 13 |  | BASE TABLE |
| [serial.item_note](serial.item_note.md) | 8 |  | BASE TABLE |
| [serial.materialized_holding_code](serial.materialized_holding_code.md) | 4 |  | BASE TABLE |
| [serial.pattern_template](serial.pattern_template.md) | 5 |  | BASE TABLE |
| [serial.record_entry](serial.record_entry.md) | 12 |  | BASE TABLE |
| [serial.routing_list_user](serial.routing_list_user.md) | 6 |  | BASE TABLE |
| [serial.stream](serial.stream.md) | 3 |  | BASE TABLE |
| [serial.subscription](serial.subscription.md) | 6 |  | BASE TABLE |
| [serial.subscription_note](serial.subscription_note.md) | 8 |  | BASE TABLE |
| [serial.supplement_summary](serial.supplement_summary.md) | 5 |  | BASE TABLE |
| [serial.unit](serial.unit.md) | 36 |  | BASE TABLE |
| [staging.billing_address_stage](staging.billing_address_stage.md) | 11 |  | BASE TABLE |
| [staging.card_stage](staging.card_stage.md) | 5 |  | BASE TABLE |
| [staging.mailing_address_stage](staging.mailing_address_stage.md) | 11 |  | BASE TABLE |
| [staging.setting_stage](staging.setting_stage.md) | 6 |  | BASE TABLE |
| [staging.statcat_stage](staging.statcat_stage.md) | 6 |  | BASE TABLE |
| [staging.user_stage](staging.user_stage.md) | 19 |  | BASE TABLE |
| [statsmagic.bibs_001](statsmagic.bibs_001.md) | 15 |  | BASE TABLE |
| [statsmagic.bibs_002](statsmagic.bibs_002.md) | 12 |  | BASE TABLE |
| [statsmagic.bibs_dev](statsmagic.bibs_dev.md) | 16 |  | BASE TABLE |
| [statsmagic.bibs_pro](statsmagic.bibs_pro.md) | 16 |  | BASE TABLE |
| [statsmagic.board_books](statsmagic.board_books.md) | 1 |  | BASE TABLE |
| [statsmagic.items_001](statsmagic.items_001.md) | 27 |  | BASE TABLE |
| [statsmagic.items_002](statsmagic.items_002.md) | 27 |  | BASE TABLE |
| [statsmagic.items_dev](statsmagic.items_dev.md) | 27 |  | BASE TABLE |
| [statsmagic.items_pro](statsmagic.items_pro.md) | 27 |  | BASE TABLE |
| [statsmagic.location_chart](statsmagic.location_chart.md) | 2 |  | BASE TABLE |
| [statsmagic.patrons_dev](statsmagic.patrons_dev.md) | 24 |  | BASE TABLE |
| [statsmagic.patrons_pro](statsmagic.patrons_pro.md) | 24 |  | BASE TABLE |
| [unapi.bre_output_layout](unapi.bre_output_layout.md) | 9 |  | BASE TABLE |
| [url_verify.session](url_verify.session.md) | 7 |  | BASE TABLE |
| [url_verify.url](url_verify.url.md) | 20 |  | BASE TABLE |
| [url_verify.url_selector](url_verify.url_selector.md) | 3 |  | BASE TABLE |
| [url_verify.url_verification](url_verify.url_verification.md) | 8 |  | BASE TABLE |
| [url_verify.verification_attempt](url_verify.verification_attempt.md) | 5 |  | BASE TABLE |
| [vandelay.authority_attr_definition](vandelay.authority_attr_definition.md) | 5 |  | BASE TABLE |
| [vandelay.authority_match](vandelay.authority_match.md) | 5 |  | BASE TABLE |
| [vandelay.authority_queue](vandelay.authority_queue.md) | 6 |  | BASE TABLE |
| [vandelay.bib_attr_definition](vandelay.bib_attr_definition.md) | 5 |  | BASE TABLE |
| [vandelay.bib_match](vandelay.bib_match.md) | 5 |  | BASE TABLE |
| [vandelay.bib_queue](vandelay.bib_queue.md) | 8 |  | BASE TABLE |
| [vandelay.import_bib_trash_fields](vandelay.import_bib_trash_fields.md) | 3 |  | BASE TABLE |
| [vandelay.import_bib_trash_group](vandelay.import_bib_trash_group.md) | 4 |  | BASE TABLE |
| [vandelay.import_error](vandelay.import_error.md) | 2 |  | BASE TABLE |
| [vandelay.import_item](vandelay.import_item.md) | 29 |  | BASE TABLE |
| [vandelay.import_item_attr_definition](vandelay.import_item_attr_definition.md) | 29 |  | BASE TABLE |
| [vandelay.match_set](vandelay.match_set.md) | 4 |  | BASE TABLE |
| [vandelay.match_set_point](vandelay.match_set_point.md) | 10 |  | BASE TABLE |
| [vandelay.match_set_quality](vandelay.match_set_quality.md) | 7 |  | BASE TABLE |
| [vandelay.merge_profile](vandelay.merge_profile.md) | 9 |  | BASE TABLE |
| [vandelay.queue](vandelay.queue.md) | 5 |  | BASE TABLE |
| [vandelay.queued_authority_record](vandelay.queued_authority_record.md) | 10 |  | BASE TABLE |
| [vandelay.queued_authority_record_attr](vandelay.queued_authority_record_attr.md) | 4 |  | BASE TABLE |
| [vandelay.queued_bib_record](vandelay.queued_bib_record.md) | 11 |  | BASE TABLE |
| [vandelay.queued_bib_record_attr](vandelay.queued_bib_record_attr.md) | 4 |  | BASE TABLE |
| [vandelay.queued_record](vandelay.queued_record.md) | 6 |  | BASE TABLE |
| [vandelay.session_tracker](vandelay.session_tracker.md) | 13 |  | BASE TABLE |

## Stored procedures and functions

| Name | ReturnType | Arguments | Type |
| ---- | ------- | ------- | ---- |
| public.hstore_in | hstore | cstring | FUNCTION |
| public.hstore_out | cstring | hstore | FUNCTION |
| public.hstore_recv | hstore | internal | FUNCTION |
| public.hstore_send | bytea | hstore | FUNCTION |
| public.hstore_version_diag | int4 | hstore | FUNCTION |
| public.fetchval | text | hstore, text | FUNCTION |
| public.slice_array | _text | hstore, text[] | FUNCTION |
| public.slice | hstore | hstore, text[] | FUNCTION |
| public.isexists | bool | hstore, text | FUNCTION |
| public.exist | bool | hstore, text | FUNCTION |
| public.exists_any | bool | hstore, text[] | FUNCTION |
| public.exists_all | bool | hstore, text[] | FUNCTION |
| public.isdefined | bool | hstore, text | FUNCTION |
| public.defined | bool | hstore, text | FUNCTION |
| public.delete | hstore | hstore, text | FUNCTION |
| public.delete | hstore | hstore, text[] | FUNCTION |
| public.delete | hstore | hstore, hstore | FUNCTION |
| public.hs_concat | hstore | hstore, hstore | FUNCTION |
| public.hs_contains | bool | hstore, hstore | FUNCTION |
| public.hs_contained | bool | hstore, hstore | FUNCTION |
| public.tconvert | hstore | text, text | FUNCTION |
| public.hstore | hstore | text, text | FUNCTION |
| public.hstore | hstore | text[], text[] | FUNCTION |
| public.hstore | hstore | text[] | FUNCTION |
| public.hstore_to_json | json | hstore | FUNCTION |
| public.hstore_to_json_loose | json | hstore | FUNCTION |
| public.hstore_to_jsonb | jsonb | hstore | FUNCTION |
| public.hstore_to_jsonb_loose | jsonb | hstore | FUNCTION |
| public.hstore | hstore | record | FUNCTION |
| public.hstore_to_array | _text | hstore | FUNCTION |
| public.hstore_to_matrix | _text | hstore | FUNCTION |
| public.akeys | _text | hstore | FUNCTION |
| public.avals | _text | hstore | FUNCTION |
| public.skeys | text | hstore | FUNCTION |
| public.svals | text | hstore | FUNCTION |
| public.each | record | hs hstore, OUT key text, OUT value text | FUNCTION |
| public.populate_record | anyelement | anyelement, hstore | FUNCTION |
| public.hstore_eq | bool | hstore, hstore | FUNCTION |
| public.hstore_ne | bool | hstore, hstore | FUNCTION |
| public.hstore_gt | bool | hstore, hstore | FUNCTION |
| public.hstore_ge | bool | hstore, hstore | FUNCTION |
| public.hstore_lt | bool | hstore, hstore | FUNCTION |
| public.hstore_le | bool | hstore, hstore | FUNCTION |
| public.hstore_cmp | int4 | hstore, hstore | FUNCTION |
| public.hstore_hash | int4 | hstore | FUNCTION |
| public.ghstore_in | ghstore | cstring | FUNCTION |
| public.ghstore_out | cstring | ghstore | FUNCTION |
| public.ghstore_compress | internal | internal | FUNCTION |
| public.ghstore_decompress | internal | internal | FUNCTION |
| public.ghstore_penalty | internal | internal, internal, internal | FUNCTION |
| public.ghstore_picksplit | internal | internal, internal | FUNCTION |
| public.ghstore_union | ghstore | internal, internal | FUNCTION |
| public.ghstore_same | internal | ghstore, ghstore, internal | FUNCTION |
| public.ghstore_consistent | bool | internal, hstore, smallint, oid, internal | FUNCTION |
| public.gin_extract_hstore | internal | hstore, internal | FUNCTION |
| public.gin_extract_hstore_query | internal | hstore, internal, smallint, internal, internal | FUNCTION |
| public.gin_consistent_hstore | bool | internal, smallint, hstore, integer, internal, internal | FUNCTION |
| public.bqarr_in | query_int | cstring | FUNCTION |
| public.bqarr_out | cstring | query_int | FUNCTION |
| public.querytree | text | query_int | FUNCTION |
| public.boolop | bool | integer[], query_int | FUNCTION |
| public.rboolop | bool | query_int, integer[] | FUNCTION |
| public._int_matchsel | float8 | internal, oid, internal, integer | FUNCTION |
| public._int_contains | bool | integer[], integer[] | FUNCTION |
| public._int_contained | bool | integer[], integer[] | FUNCTION |
| public._int_overlap | bool | integer[], integer[] | FUNCTION |
| public._int_same | bool | integer[], integer[] | FUNCTION |
| public._int_different | bool | integer[], integer[] | FUNCTION |
| public._int_union | _int4 | integer[], integer[] | FUNCTION |
| public._int_inter | _int4 | integer[], integer[] | FUNCTION |
| public._int_overlap_sel | float8 | internal, oid, internal, integer | FUNCTION |
| public._int_contains_sel | float8 | internal, oid, internal, integer | FUNCTION |
| public._int_contained_sel | float8 | internal, oid, internal, integer | FUNCTION |
| public._int_overlap_joinsel | float8 | internal, oid, internal, smallint, internal | FUNCTION |
| public._int_contains_joinsel | float8 | internal, oid, internal, smallint, internal | FUNCTION |
| public._int_contained_joinsel | float8 | internal, oid, internal, smallint, internal | FUNCTION |
| public.intset | _int4 | integer | FUNCTION |
| public.icount | int4 | integer[] | FUNCTION |
| public.sort | _int4 | integer[], text | FUNCTION |
| public.sort | _int4 | integer[] | FUNCTION |
| public.sort_asc | _int4 | integer[] | FUNCTION |
| public.sort_desc | _int4 | integer[] | FUNCTION |
| public.uniq | _int4 | integer[] | FUNCTION |
| public.idx | int4 | integer[], integer | FUNCTION |
| public.subarray | _int4 | integer[], integer, integer | FUNCTION |
| public.subarray | _int4 | integer[], integer | FUNCTION |
| public.intarray_push_elem | _int4 | integer[], integer | FUNCTION |
| public.intarray_push_array | _int4 | integer[], integer[] | FUNCTION |
| public.intarray_del_elem | _int4 | integer[], integer | FUNCTION |
| public.intset_union_elem | _int4 | integer[], integer | FUNCTION |
| public.intset_subtract | _int4 | integer[], integer[] | FUNCTION |
| public.g_int_consistent | bool | internal, integer[], smallint, oid, internal | FUNCTION |
| public.g_int_compress | internal | internal | FUNCTION |
| public.g_int_decompress | internal | internal | FUNCTION |
| public.g_int_penalty | internal | internal, internal, internal | FUNCTION |
| public.g_int_picksplit | internal | internal, internal | FUNCTION |
| public.g_int_union | _int4 | internal, internal | FUNCTION |
| public.g_int_same | internal | integer[], integer[], internal | FUNCTION |
| public._intbig_in | intbig_gkey | cstring | FUNCTION |
| public._intbig_out | cstring | intbig_gkey | FUNCTION |
| public.g_intbig_consistent | bool | internal, integer[], smallint, oid, internal | FUNCTION |
| public.g_intbig_compress | internal | internal | FUNCTION |
| public.g_intbig_decompress | internal | internal | FUNCTION |
| public.g_intbig_penalty | internal | internal, internal, internal | FUNCTION |
| public.g_intbig_picksplit | internal | internal, internal | FUNCTION |
| public.g_intbig_union | intbig_gkey | internal, internal | FUNCTION |
| public.g_intbig_same | internal | intbig_gkey, intbig_gkey, internal | FUNCTION |
| public.ginint4_queryextract | internal | integer[], internal, smallint, internal, internal, internal, internal | FUNCTION |
| public.ginint4_consistent | bool | internal, smallint, integer[], integer, internal, internal, internal, internal | FUNCTION |
| public.pgp_sym_decrypt | text | bytea, text, text | FUNCTION |
| evergreen.pg_buffercache_pages | record |  | FUNCTION |
| public.pg_stat_statements | record | showtext boolean, OUT userid oid, OUT dbid oid, OUT queryid bigint, OUT query text, OUT calls bigint, OUT total_time double precision, OUT min_time double precision, OUT max_time double precision, OUT mean_time double precision, OUT stddev_time double precision, OUT rows bigint, OUT shared_blks_hit bigint, OUT shared_blks_read bigint, OUT shared_blks_dirtied bigint, OUT shared_blks_written bigint, OUT local_blks_hit bigint, OUT local_blks_read bigint, OUT local_blks_dirtied bigint, OUT local_blks_written bigint, OUT temp_blks_read bigint, OUT temp_blks_written bigint, OUT blk_read_time double precision, OUT blk_write_time double precision | FUNCTION |
| public.pgp_sym_decrypt_bytea | bytea | bytea, text, text | FUNCTION |
| public.pgp_pub_encrypt | bytea | text, bytea | FUNCTION |
| public.pg_stat_statements_reset | void |  | FUNCTION |
| public.digest | bytea | text, text | FUNCTION |
| public.digest | bytea | bytea, text | FUNCTION |
| public.hmac | bytea | text, text, text | FUNCTION |
| public.hmac | bytea | bytea, bytea, text | FUNCTION |
| public.crypt | text | text, text | FUNCTION |
| public.gen_salt | text | text | FUNCTION |
| public.gen_salt | text | text, integer | FUNCTION |
| public.encrypt | bytea | bytea, bytea, text | FUNCTION |
| public.decrypt | bytea | bytea, bytea, text | FUNCTION |
| public.encrypt_iv | bytea | bytea, bytea, bytea, text | FUNCTION |
| public.decrypt_iv | bytea | bytea, bytea, bytea, text | FUNCTION |
| public.gen_random_bytes | bytea | integer | FUNCTION |
| public.gen_random_uuid | uuid |  | FUNCTION |
| public.pgp_sym_encrypt | bytea | text, text | FUNCTION |
| public.pgp_sym_encrypt_bytea | bytea | bytea, text | FUNCTION |
| public.pgp_sym_encrypt | bytea | text, text, text | FUNCTION |
| public.pgp_sym_encrypt_bytea | bytea | bytea, text, text | FUNCTION |
| public.pgp_sym_decrypt | text | bytea, text | FUNCTION |
| public.pgp_sym_decrypt_bytea | bytea | bytea, text | FUNCTION |
| public.pgp_pub_encrypt_bytea | bytea | bytea, bytea | FUNCTION |
| public.pgp_pub_encrypt | bytea | text, bytea, text | FUNCTION |
| public.pgp_pub_encrypt_bytea | bytea | bytea, bytea, text | FUNCTION |
| public.pgp_pub_decrypt | text | bytea, bytea | FUNCTION |
| public.pgp_pub_decrypt_bytea | bytea | bytea, bytea | FUNCTION |
| public.pgp_pub_decrypt | text | bytea, bytea, text | FUNCTION |
| public.pgp_pub_decrypt_bytea | bytea | bytea, bytea, text | FUNCTION |
| public.pgp_pub_decrypt | text | bytea, bytea, text, text | FUNCTION |
| public.pgp_pub_decrypt_bytea | bytea | bytea, bytea, text, text | FUNCTION |
| public.pgp_key_id | text | bytea | FUNCTION |
| public.armor | text | bytea | FUNCTION |
| public.armor | text | bytea, text[], text[] | FUNCTION |
| public.dearmor | bytea | text | FUNCTION |
| public.pgp_armor_headers | record | text, OUT key text, OUT value text | FUNCTION |
| evergreen.pgstattuple | record | relname text, OUT table_len bigint, OUT tuple_count bigint, OUT tuple_len bigint, OUT tuple_percent double precision, OUT dead_tuple_count bigint, OUT dead_tuple_len bigint, OUT dead_tuple_percent double precision, OUT free_space bigint, OUT free_percent double precision | FUNCTION |
| evergreen.pgstatindex | record | relname text, OUT version integer, OUT tree_level integer, OUT index_size bigint, OUT root_block_no bigint, OUT internal_pages bigint, OUT leaf_pages bigint, OUT empty_pages bigint, OUT deleted_pages bigint, OUT avg_leaf_density double precision, OUT leaf_fragmentation double precision | FUNCTION |
| evergreen.pg_relpages | int8 | relname text | FUNCTION |
| evergreen.pgstatginindex | record | relname regclass, OUT version integer, OUT pending_pages integer, OUT pending_tuples bigint | FUNCTION |
| evergreen.pgstattuple | record | reloid regclass, OUT table_len bigint, OUT tuple_count bigint, OUT tuple_len bigint, OUT tuple_percent double precision, OUT dead_tuple_count bigint, OUT dead_tuple_len bigint, OUT dead_tuple_percent double precision, OUT free_space bigint, OUT free_percent double precision | FUNCTION |
| evergreen.pgstatindex | record | relname regclass, OUT version integer, OUT tree_level integer, OUT index_size bigint, OUT root_block_no bigint, OUT internal_pages bigint, OUT leaf_pages bigint, OUT empty_pages bigint, OUT deleted_pages bigint, OUT avg_leaf_density double precision, OUT leaf_fragmentation double precision | FUNCTION |
| evergreen.pg_relpages | int8 | relname regclass | FUNCTION |
| evergreen.pgstattuple_approx | record | reloid regclass, OUT table_len bigint, OUT scanned_percent double precision, OUT approx_tuple_count bigint, OUT approx_tuple_len bigint, OUT approx_tuple_percent double precision, OUT dead_tuple_count bigint, OUT dead_tuple_len bigint, OUT dead_tuple_percent double precision, OUT approx_free_space bigint, OUT approx_free_percent double precision | FUNCTION |
| acq.audit_acq_purchase_order_func | trigger |  | FUNCTION |
| evergreen.pgstathashindex | record | relname regclass, OUT version integer, OUT bucket_pages bigint, OUT overflow_pages bigint, OUT bitmap_pages bigint, OUT unused_pages bigint, OUT live_items bigint, OUT dead_items bigint, OUT free_percent double precision | FUNCTION |
| public.unaccent | text | regdictionary, text | FUNCTION |
| public.unaccent | text | text | FUNCTION |
| public.unaccent_init | internal | internal | FUNCTION |
| public.unaccent_lexize | internal | internal, internal, internal, internal | FUNCTION |
| public.xml_valid | bool | text | FUNCTION |
| public.xml_encode_special_chars | text | text | FUNCTION |
| public.xpath_string | text | text, text | FUNCTION |
| public.xpath_nodeset | text | text, text, text, text | FUNCTION |
| public.xpath_number | float4 | text, text | FUNCTION |
| public.xpath_bool | bool | text, text | FUNCTION |
| public.xpath_list | text | text, text, text | FUNCTION |
| public.xpath_list | text | text, text | FUNCTION |
| public.xpath_nodeset | text | text, text | FUNCTION |
| public.xpath_nodeset | text | text, text, text | FUNCTION |
| public.xpath_table | record | text, text, text, text, text | FUNCTION |
| public.xslt_process | text | text, text, text | FUNCTION |
| public.xslt_process | text | text, text | FUNCTION |
| acq.attribute_debits | void |  | FUNCTION |
| acq.audit_acq_lineitem_func | trigger |  | FUNCTION |
| acq.copy_fund_tags | void | old_fund_id integer, new_fund_id integer | FUNCTION |
| acq.create_acq_auditor | bool | sch text, tbl text | FUNCTION |
| biblio.check_marcxml_well_formed | trigger |  | FUNCTION |
| acq.create_acq_func | bool | sch text, tbl text | FUNCTION |
| acq.create_acq_history | bool | sch text, tbl text | FUNCTION |
| acq.create_acq_lifecycle | bool | sch text, tbl text | FUNCTION |
| acq.create_acq_seq | bool | sch text, tbl text | FUNCTION |
| acq.create_acq_update_trigger | bool | sch text, tbl text | FUNCTION |
| acq.exchange_ratio | numeric | from_ex text, to_ex text | FUNCTION |
| acq.exchange_ratio | numeric | text, text, numeric | FUNCTION |
| acq.extract_holding_attr_table | flat_lineitem_holding_subfield | lineitem integer, tag text | FUNCTION |
| acq.extract_provider_holding_data | flat_lineitem_detail | lineitem_i integer | FUNCTION |
| acq.fap_limit_100 | trigger |  | FUNCTION |
| acq.find_bad_fy | record |  | FUNCTION |
| acq.fund_alloc_percent_val | trigger |  | FUNCTION |
| acq.po_org_name_date_unique | trigger |  | FUNCTION |
| actor.org_unit_ancestor_setting_batch | org_unit_setting | org_id integer, setting_names text[] | FUNCTION |
| actor.org_unit_ancestor_setting_batch_by_org | org_unit_setting | setting_name text, org_ids integer[] | FUNCTION |
| actor.org_unit_ancestors | org_unit | integer | FUNCTION |
| actor.org_unit_ancestors_distance | record | integer | FUNCTION |
| actor.org_unit_combined_ancestors | org_unit | integer, integer | FUNCTION |
| actor.org_unit_common_ancestors | org_unit | integer, integer | FUNCTION |
| acq.propagate_funds_by_org_tree | void | old_year integer, user_id integer, org_unit_id integer, include_desc boolean DEFAULT true | FUNCTION |
| acq.propagate_funds_by_org_unit | void | old_year integer, user_id integer, org_unit_id integer | FUNCTION |
| acq.purchase_order_name_default | trigger |  | FUNCTION |
| acq.rollover_funds_by_org_tree | void | old_year integer, user_id integer, org_unit_id integer, encumb_only boolean DEFAULT false, include_desc boolean DEFAULT true | FUNCTION |
| acq.rollover_funds_by_org_unit | void | old_year integer, user_id integer, org_unit_id integer, encumb_only boolean DEFAULT false | FUNCTION |
| acq.transfer_fund | void | old_fund integer, old_amount numeric, new_fund integer, new_amount numeric, user_id integer, xfer_note text | FUNCTION |
| action.age_circ_on_delete | trigger |  | FUNCTION |
| action.age_hold_on_delete | trigger |  | FUNCTION |
| action.age_parent_circ_on_delete | trigger |  | FUNCTION |
| actor.org_unit_descendants | org_unit | integer | FUNCTION |
| action.all_circ_chain | all_circulation_slim | ctx_circ_id integer | FUNCTION |
| action.apply_fieldset | text | fieldset_id integer, table_name text, pkey_name text, query text | FUNCTION |
| action.archive_stat_cats | trigger |  | FUNCTION |
| action.circ_chain | circulation | ctx_circ_id bigint | FUNCTION |
| action.circulation_claims_returned | trigger |  | FUNCTION |
| actor.org_unit_parent_protect | trigger |  | FUNCTION |
| actor.org_unit_simple_path | _int4 | integer, integer | FUNCTION |
| action.copy_calculated_proximity | numeric | pickup integer, request integer, vacp_cl integer, vacp_cm text, vacn_ol integer, vacl_ol integer | FUNCTION |
| action.copy_related_hold_stats | hold_stats | copy_id bigint | FUNCTION |
| action.copy_transit_is_unique | trigger |  | FUNCTION |
| action.emergency_closing_stage_1 | emergency_closing_stage_1_count | e_closing integer | FUNCTION |
| actor.org_unit_prox_update | trigger |  | FUNCTION |
| action.emergency_closing_stage_2_circ | bool | circ_closing_entry integer | FUNCTION |
| action.emergency_closing_stage_2_hold | bool | hold_closing_entry integer | FUNCTION |
| action.maintain_usr_circ_history | trigger |  | FUNCTION |
| action.purge_circulations | int4 |  | FUNCTION |
| action.emergency_closing_stage_2_reservation | bool | res_closing_entry integer | FUNCTION |
| action.fill_circ_copy_location | trigger |  | FUNCTION |
| action.find_circ_matrix_matchpoint | found_circ_matrix_matchpoint | context_ou integer, item_object asset.copy, user_object actor.usr, renewal boolean | FUNCTION |
| action.find_circ_matrix_matchpoint | found_circ_matrix_matchpoint | context_ou integer, match_item bigint, match_user integer, renewal boolean | FUNCTION |
| action.find_hold_matrix_matchpoint | int4 | pickup_ou integer, request_ou integer, match_item bigint, match_user integer, match_requestor integer | FUNCTION |
| action.hold_copy_calculated_proximity | numeric | ahr_id integer, acp_id bigint, copy_context_ou integer DEFAULT NULL::integer | FUNCTION |
| action.hold_copy_calculated_proximity_update | trigger |  | FUNCTION |
| action.hold_request_clear_map | trigger |  | FUNCTION |
| action.hold_request_permit_test | matrix_test_result | pickup_ou integer, request_ou integer, match_item bigint, match_user integer, match_requestor integer | FUNCTION |
| action.hold_request_permit_test | matrix_test_result | pickup_ou integer, request_ou integer, match_item bigint, match_user integer, match_requestor integer, retargetting boolean | FUNCTION |
| action.hold_request_regen_copy_maps | void | hold_id integer, copy_ids integer[] | FUNCTION |
| action.hold_retarget_permit_test | matrix_test_result | pickup_ou integer, request_ou integer, match_item bigint, match_user integer, match_requestor integer | FUNCTION |
| action.item_user_circ_test | circ_matrix_test_result | integer, bigint, integer | FUNCTION |
| action.item_user_circ_test | circ_matrix_test_result | circ_ou integer, match_item bigint, match_user integer, renewal boolean | FUNCTION |
| action.item_user_renew_test | circ_matrix_test_result | integer, bigint, integer | FUNCTION |
| action.link_circ_limit_groups | void | bigint, integer[] | FUNCTION |
| actor.org_unit_proximity | int4 | integer, integer | FUNCTION |
| action.purge_holds | int4 |  | FUNCTION |
| action.push_circ_due_time | trigger |  | FUNCTION |
| action.summarize_all_circ_chain | circ_chain_summary | ctx_circ_id integer | FUNCTION |
| actor.approve_pending_address | int8 | pending_id integer | FUNCTION |
| actor.au_updated | trigger |  | FUNCTION |
| actor.calculate_system_penalties | usr_standing_penalty | match_user integer, context_org integer | FUNCTION |
| actor.change_password | void | user_id integer, new_pw text, pw_type text DEFAULT 'main'::text | FUNCTION |
| actor.convert_usr_note_to_message | trigger |  | FUNCTION |
| actor.create_salt | text | pw_type text | FUNCTION |
| action.summarize_circ_chain | circ_chain_summary | ctx_circ_id bigint | FUNCTION |
| action.survey_response_answer_date_fixup | trigger |  | FUNCTION |
| action.usr_visible_holds | hold_request | usr_id integer | FUNCTION |
| action_trigger.check_valid_retention_interval | trigger |  | FUNCTION |
| actor.crypt_pw_insert | trigger |  | FUNCTION |
| actor.crypt_pw_update | trigger |  | FUNCTION |
| actor.org_unit_descendants | org_unit | integer, integer | FUNCTION |
| actor.org_unit_descendants_distance | record | integer | FUNCTION |
| actor.org_unit_full_path | org_unit | integer | FUNCTION |
| actor.org_unit_full_path | org_unit | integer, integer | FUNCTION |
| action_trigger.purge_events | void |  | FUNCTION |
| actor.address_alert_matches | address_alert | org_unit integer, street1 text, street2 text, city text, county text, state text, country text, post_code text, mailing_address boolean DEFAULT false, billing_address boolean DEFAULT false | FUNCTION |
| actor.get_cascade_setting | cascade_setting_summary | setting_name text, org_id integer, user_id integer, workstation_id integer | FUNCTION |
| actor.get_cascade_setting_batch | cascade_setting_summary | setting_names text[], org_id integer, user_id integer, workstation_id integer | FUNCTION |
| actor.get_salt | text | pw_usr integer, pw_type text | FUNCTION |
| actor.insert_usr_activity | usr_activity | usr integer, ewho text, ewhat text, ehow text | FUNCTION |
| actor.migrate_passwd | text | pw_usr integer | FUNCTION |
| actor.org_unit_ancestor_at_depth | org_unit | integer, integer | FUNCTION |
| evergreen.is_json | bool | text | FUNCTION |
| actor.org_unit_ancestor_setting | org_unit_setting | setting_name text, org_id integer | FUNCTION |
| evergreen.located_uris | record | bibid bigint, ouid integer, pref_lib integer DEFAULT NULL::integer | FUNCTION |
| actor.permit_remoteauth | text | profile_name text, userid bigint | FUNCTION |
| actor.purge_usr_activity_by_type | void | act_type integer | FUNCTION |
| actor.restrict_usr_message_limited | trigger |  | FUNCTION |
| actor.usr_delete | void | src_usr integer, dest_usr integer | FUNCTION |
| actor.usr_merge | void | src_usr integer, dest_usr integer, del_addrs boolean, del_cards boolean, deactivate_cards boolean | FUNCTION |
| actor.usr_merge_rows | void | table_name text, col_name text, src_usr integer, dest_usr integer | FUNCTION |
| actor.usr_purge_data | void | src_usr integer, specified_dest_usr integer | FUNCTION |
| authority.atag_search_rank | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.atag_search_rank_refs | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| actor.set_passwd | bool | pw_usr integer, pw_type text, new_pass text, new_salt text DEFAULT NULL::text | FUNCTION |
| actor.stat_cat_check | trigger |  | FUNCTION |
| actor.user_ingest_name_keywords | trigger |  | FUNCTION |
| actor.usr_activity_get_type | usr_activity_type | ewho text, ewhat text, ehow text | FUNCTION |
| actor.usr_activity_transient_trg | trigger |  | FUNCTION |
| actor.verify_passwd | bool | pw_usr integer, pw_type text, test_passwd text | FUNCTION |
| asset.acp_created | trigger |  | FUNCTION |
| authority.axis_authority_tags | _int4 | a text | FUNCTION |
| authority.axis_authority_tags_refs | _int4 | a text | FUNCTION |
| asset.acp_location_fixer | trigger |  | FUNCTION |
| asset.acp_status_changed | trigger |  | FUNCTION |
| asset.all_visible_flags | text |  | FUNCTION |
| asset.autogenerate_placeholder_barcode | trigger |  | FUNCTION |
| asset.bib_source_default | text |  | FUNCTION |
| asset.cache_copy_visibility | trigger |  | FUNCTION |
| asset.calculate_copy_visibility_attribute_set | _int4 | copy_id bigint | FUNCTION |
| asset.circ_lib_default | text |  | FUNCTION |
| biblio.flatten_marc | full_rec | rid bigint | FUNCTION |
| asset.copy_state | text | cid bigint | FUNCTION |
| asset.invisible_orgs | text | otype text | FUNCTION |
| asset.label_normalizer | trigger |  | FUNCTION |
| asset.label_normalizer_dewey | text | text | FUNCTION |
| asset.record_copy_count | record | place integer, rid bigint, staff boolean | FUNCTION |
| asset.record_has_holdable_copy | bool | rid bigint, ou integer DEFAULT NULL::integer | FUNCTION |
| asset.set_copy_tag_value | trigger |  | FUNCTION |
| config.setting_is_user_or_ws | trigger |  | FUNCTION |
| evergreen.located_uris_as_uris | uri | bibid bigint, ouid integer, pref_lib integer DEFAULT NULL::integer | FUNCTION |
| evergreen.lowercase | text | text | FUNCTION |
| asset.label_normalizer_generic | text | text | FUNCTION |
| asset.label_normalizer_lc | text | text | FUNCTION |
| asset.location_default | text |  | FUNCTION |
| asset.location_group_default | text |  | FUNCTION |
| asset.luri_org_default | text |  | FUNCTION |
| asset.merge_record_assets | int4 | target_record bigint, source_record bigint | FUNCTION |
| asset.metarecord_copy_count | record | place integer, rid bigint, staff boolean | FUNCTION |
| asset.metarecord_has_holdable_copy | bool | rid bigint, ou integer DEFAULT NULL::integer | FUNCTION |
| asset.normalize_affix_sortkey | trigger |  | FUNCTION |
| auditor.audit_asset_call_number_func | trigger |  | FUNCTION |
| evergreen.escape_for_html | text | text | FUNCTION |
| evergreen.extract_marc_field | text | text, bigint, text | FUNCTION |
| evergreen.lpad_number_substrings | text | text, text, integer | FUNCTION |
| asset.opac_lasso_metarecord_copy_count | record | i_lasso integer, rid bigint | FUNCTION |
| asset.opac_lasso_record_copy_count | record | i_lasso integer, rid bigint | FUNCTION |
| authority.axis_browse_center | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 9, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.axis_browse_center_refs | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 9, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.axis_browse_top | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.axis_browse_top_refs | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| asset.opac_ou_metarecord_copy_count | record | org integer, rid bigint | FUNCTION |
| asset.opac_ou_record_copy_count | record | org integer, rid bigint | FUNCTION |
| asset.owning_lib_default | text |  | FUNCTION |
| asset.patron_default_visibility_mask | record |  | FUNCTION |
| asset.staff_lasso_metarecord_copy_count | record | i_lasso integer, rid bigint | FUNCTION |
| asset.staff_lasso_record_copy_count | record | i_lasso integer, rid bigint | FUNCTION |
| asset.staff_ou_metarecord_copy_count | record | org integer, rid bigint | FUNCTION |
| evergreen.ous_delete_log | trigger |  | FUNCTION |
| evergreen.pg_statistics | record | tab text, col text | FUNCTION |
| asset.staff_ou_record_copy_count | record | org integer, rid bigint | FUNCTION |
| asset.stat_cat_check | trigger |  | FUNCTION |
| asset.status_default | text |  | FUNCTION |
| asset.visible_orgs | text | otype text | FUNCTION |
| auditor.audit_acq_invoice_entry_func | trigger |  | FUNCTION |
| auditor.audit_acq_invoice_func | trigger |  | FUNCTION |
| auditor.audit_acq_invoice_item_func | trigger |  | FUNCTION |
| evergreen.extract_marc_field | text | text, bigint, text, text | FUNCTION |
| evergreen.extract_marc_field_set | text | text, bigint, text, text | FUNCTION |
| evergreen.facet_force_nfc | trigger |  | FUNCTION |
| evergreen.fake_fkey_tgr | trigger |  | FUNCTION |
| auditor.audit_action_hold_request_func | trigger |  | FUNCTION |
| auditor.audit_actor_org_unit_func | trigger |  | FUNCTION |
| auditor.audit_actor_usr_address_func | trigger |  | FUNCTION |
| auditor.audit_actor_usr_func | trigger |  | FUNCTION |
| evergreen.protect_reserved_rows_from_delete | trigger |  | FUNCTION |
| evergreen.query_int_wrapper | bool | integer[], text | FUNCTION |
| evergreen.rank_cp | int4 | copy asset.copy | FUNCTION |
| evergreen.rank_cp | int4 | copy_id bigint | FUNCTION |
| auditor.audit_asset_copy_func | trigger |  | FUNCTION |
| auditor.audit_biblio_record_entry_func | trigger |  | FUNCTION |
| auditor.create_auditor_lifecycle | bool | sch text, tbl text | FUNCTION |
| auditor.create_auditor_seq | bool | sch text, tbl text | FUNCTION |
| auditor.create_auditor_update_trigger | bool | sch text, tbl text | FUNCTION |
| auditor.fix_columns | void |  | FUNCTION |
| auditor.get_audit_info | record |  | FUNCTION |
| auditor.set_audit_info | void | integer, integer | FUNCTION |
| authority.axis_search_heading | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.axis_search_heading_refs | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| auditor.audit_serial_unit_func | trigger |  | FUNCTION |
| auditor.clear_audit_info | void |  | FUNCTION |
| auditor.create_auditor | bool | sch text, tbl text | FUNCTION |
| auditor.create_auditor_func | bool | sch text, tbl text | FUNCTION |
| auditor.create_auditor_history | bool | sch text, tbl text | FUNCTION |
| authority.atag_search_heading | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.atag_search_heading_refs | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| auditor.update_auditors | bool |  | FUNCTION |
| authority.atag_authority_tags | _int4 | atag text | FUNCTION |
| authority.atag_authority_tags_refs | _int4 | atag text | FUNCTION |
| authority.atag_browse_center | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 9, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.atag_browse_center_refs | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 9, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.atag_browse_top | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.atag_browse_top_refs | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| evergreen.upgrade_verify_no_dep_conflicts | bool | my_db_patch text | FUNCTION |
| evergreen.vandelay_import_item_imported_as_inh_fkey | trigger |  | FUNCTION |
| evergreen.xml_escape | text | str text | FUNCTION |
| authority.axis_search_rank | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.axis_search_rank_refs | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.btag_authority_tags | _int4 | btag text | FUNCTION |
| authority.btag_authority_tags_refs | _int4 | btag text | FUNCTION |
| authority.btag_browse_center | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 9, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.btag_browse_center_refs | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 9, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.btag_browse_top | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.btag_browse_top_refs | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.btag_search_heading | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| evergreen.xml_famous5_to_text | text | text | FUNCTION |
| authority.btag_search_heading_refs | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.btag_search_rank | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.btag_search_rank_refs | int8 | a text, q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.calculate_authority_linking | authority_linking | rec_id bigint, rec_control_set integer, rec_marc_xml xml | FUNCTION |
| authority.extract_headings | heading | rid bigint, restrict integer[] DEFAULT NULL::integer[] | FUNCTION |
| authority.extract_headings | heading | marc text, restrict integer[] DEFAULT NULL::integer[] | FUNCTION |
| authority.extract_thesaurus | text | marcxml text | FUNCTION |
| authority.flatten_marc | full_rec | rid bigint | FUNCTION |
| authority.generate_overlay_template | text | bigint | FUNCTION |
| authority.generate_overlay_template | text | source_xml text | FUNCTION |
| authority.indexing_ingest_or_delete | trigger |  | FUNCTION |
| authority.map_thesaurus_to_control_set | trigger |  | FUNCTION |
| authority.reingest_authority_full_rec | void | auth_id bigint | FUNCTION |
| authority.reingest_authority_rec_descriptor | void | auth_id bigint | FUNCTION |
| evergreen.xml_pretty_print | xml | input xml | FUNCTION |
| evergreen.z3950_attr_name_is_valid | trigger |  | FUNCTION |
| metabib.autosuggest_prepare_tsquery | _text | orig text | FUNCTION |
| authority.merge_records | int4 | target_record bigint, source_record bigint | FUNCTION |
| authority.normalize_heading | text | marcxml text | FUNCTION |
| authority.normalize_heading | text | marcxml text, no_thesaurus boolean | FUNCTION |
| authority.normalize_heading_for_upsert | trigger |  | FUNCTION |
| authority.propagate_changes | int8 | aid bigint | FUNCTION |
| authority.propagate_changes | int8 | aid bigint, bid bigint | FUNCTION |
| authority.simple_heading_browse_center | int8 | atag_list integer[], q text, page integer DEFAULT 0, pagesize integer DEFAULT 9, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.simple_heading_browse_top | int8 | atag_list integer[], q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.simple_heading_find_pivot | text | a integer[], q text, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.simple_normalize_heading | text | marcxml text | FUNCTION |
| biblio.calculate_bib_visibility_attribute_set | _int4 | bib_id bigint, new_source integer DEFAULT NULL::integer, force_source boolean DEFAULT false | FUNCTION |
| authority.simple_heading_search_heading | int8 | atag_list integer[], q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.simple_heading_search_rank | int8 | atag_list integer[], q text, page integer DEFAULT 0, pagesize integer DEFAULT 10, thesauruses text DEFAULT ''::text | FUNCTION |
| authority.simple_heading_set | simple_heading | marcxml text | FUNCTION |
| biblio.extract_fingerprint | text | marc text | FUNCTION |
| biblio.extract_located_uris | void | bib_id bigint, marcxml text, editor_id integer | FUNCTION |
| biblio.extract_metabib_field_entry | field_entry_template | rid bigint, default_joiner text, field_types text[], only_fields integer[] | FUNCTION |
| biblio.extract_quality | int4 | marc text, best_lang text, best_type text | FUNCTION |
| biblio.fingerprint_trigger | trigger |  | FUNCTION |
| biblio.indexing_ingest_or_delete | trigger |  | FUNCTION |
| biblio.map_authority_linking | int8 | bibid bigint, marc text | FUNCTION |
| biblio.marc21_extract_all_fixed_fields | record_ff_map | rid bigint | FUNCTION |
| biblio.marc21_extract_fixed_field | text | rid bigint, ff text | FUNCTION |
| biblio.marc21_extract_fixed_field_list | _text | rid bigint, ff text | FUNCTION |
| biblio.marc21_physical_characteristics | marc21_physical_characteristics | rid bigint | FUNCTION |
| biblio.next_autogen_tcn_value | text |  | FUNCTION |
| biblio.normalize_biblio_monograph_part_sortkey | trigger |  | FUNCTION |
| config.interval_to_seconds | int4 | interval_val interval | FUNCTION |
| config.interval_to_seconds | int4 | interval_string text | FUNCTION |
| config.ou_marc_fields | marc_field | marc_format integer, marc_record_type config.marc_record_type, ou integer | FUNCTION |
| config.ou_marc_subfields | marc_subfield | marc_format integer, marc_record_type config.marc_record_type, ou integer | FUNCTION |
| config.update_coded_value_map | void | in_ctype text, in_code text, in_value text, in_description text DEFAULT NULL::text, in_opac_visible boolean DEFAULT NULL::boolean, in_search_label text DEFAULT NULL::text, in_is_simple boolean DEFAULT NULL::boolean, add_only boolean DEFAULT false | FUNCTION |
| config.update_hard_due_dates | int4 |  | FUNCTION |
| config.z3950_source_credentials_apply | void | src text, org integer, uname text, passwd text | FUNCTION |
| config.z3950_source_credentials_lookup | z3950_source_credentials | source text, owner integer | FUNCTION |
| container.clear_all_expired_circ_history_items | void |  | FUNCTION |
| evergreen.located_uris | record | bibid bigint[], ouid integer, pref_lib integer DEFAULT NULL::integer | FUNCTION |
| container.clear_expired_circ_history_items | void | ac_usr integer | FUNCTION |
| evergreen.array_overlap_check | trigger |  | FUNCTION |
| evergreen.asset_copy_alert_copy_inh_fkey | trigger |  | FUNCTION |
| evergreen.asset_copy_note_owning_copy_inh_fkey | trigger |  | FUNCTION |
| evergreen.asset_copy_tag_copy_map_copy_inh_fkey | trigger |  | FUNCTION |
| evergreen.asset_latest_inventory_copy_inh_fkey | trigger |  | FUNCTION |
| evergreen.can_float | bool | copy_floating_group integer, from_ou integer, to_ou integer | FUNCTION |
| evergreen.change_db_setting | void | setting_name text, settings text[] | FUNCTION |
| evergreen.coded_value_map_normalizer | text | input text, ctype text | FUNCTION |
| evergreen.container_copy_bucket_item_target_copy_inh_fkey | trigger |  | FUNCTION |
| evergreen.could_be_serial_holding_code | bool | text | FUNCTION |
| evergreen.display_field_force_nfc | trigger |  | FUNCTION |
| evergreen.find_next_open_time | timestamptz | circ_lib integer, initial timestamp with time zone, hourly boolean DEFAULT false, initial_time time without time zone DEFAULT NULL::time without time zone, dow_count integer DEFAULT 0 | FUNCTION |
| evergreen.force_unicode_normal_form | text | string text, form text | FUNCTION |
| evergreen.generic_map_normalizer | text | text, text | FUNCTION |
| evergreen.get_barcodes | barcode_set | select_ou integer, type text, in_barcode text | FUNCTION |
| evergreen.get_locale_name | record | locale text, OUT name text, OUT description text | FUNCTION |
| evergreen.limit_oustl | trigger |  | FUNCTION |
| evergreen.maintain_901 | trigger |  | FUNCTION |
| evergreen.maintain_control_numbers | trigger |  | FUNCTION |
| evergreen.marc_to | text | marc text, xfrm text | FUNCTION |
| evergreen.oils_i18n_code_tracking | trigger |  | FUNCTION |
| evergreen.oils_i18n_gettext | text | integer, text, text, text | FUNCTION |
| evergreen.oils_i18n_gettext | text | text, text, text, text | FUNCTION |
| evergreen.oils_i18n_id_tracking | trigger |  | FUNCTION |
| evergreen.oils_i18n_update_apply | void | old_ident text, new_ident text, hint text | FUNCTION |
| metabib.browse | flat_browse_entry_appearance | search_field integer[], browse_term text, context_org integer DEFAULT NULL::integer, context_loc_group integer DEFAULT NULL::integer, staff boolean DEFAULT false, pivot_id bigint DEFAULT NULL::bigint, result_limit integer DEFAULT 10 | FUNCTION |
| metabib.browse | flat_browse_entry_appearance | search_class text, browse_term text, context_org integer DEFAULT NULL::integer, context_loc_group integer DEFAULT NULL::integer, staff boolean DEFAULT false, pivot_id bigint DEFAULT NULL::bigint, result_limit integer DEFAULT 10 | FUNCTION |
| evergreen.oils_i18n_xlate | text | keytable text, keyclass text, keycol text, identcol text, keyvalue text, raw_locale text | FUNCTION |
| evergreen.oils_json_to_text | text | text | FUNCTION |
| evergreen.oils_text_as_bytea | bytea | text | FUNCTION |
| evergreen.oils_xpath | _text | text, text | FUNCTION |
| evergreen.oils_xpath | _text | text, text, text[] | FUNCTION |
| evergreen.oils_xpath_string | text | text, text | FUNCTION |
| evergreen.oils_xpath_string | text | text, text, anyarray | FUNCTION |
| evergreen.oils_xpath_string | text | text, text, text | FUNCTION |
| evergreen.oils_xpath_string | text | text, text, text, anyarray | FUNCTION |
| evergreen.oils_xpath_table | record | key text, document_field text, relation_name text, xpaths text, criteria text | FUNCTION |
| evergreen.rank_ou | int4 | lib integer, search_lib integer, pref_lib integer DEFAULT NULL::integer | FUNCTION |
| evergreen.oils_xpath_tag_to_table | record | marc text, tag text, xpaths text[] | FUNCTION |
| evergreen.oils_xslt_process | text | text, text | FUNCTION |
| evergreen.org_top | org_unit |  | FUNCTION |
| evergreen.ous_change_log | trigger |  | FUNCTION |
| evergreen.ranked_volumes | record | bibid bigint[], ouid integer, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, pref_lib integer DEFAULT NULL::integer, includes text[] DEFAULT NULL::text[] | FUNCTION |
| evergreen.ranked_volumes | record | bibid bigint, ouid integer, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, pref_lib integer DEFAULT NULL::integer, includes text[] DEFAULT NULL::text[] | FUNCTION |
| evergreen.regexp_split_to_array | _text | text, text | FUNCTION |
| evergreen.rel_bump | numeric | terms text[], value text, bumps text[], mults numeric[] | FUNCTION |
| evergreen.tableoid2name | text | oid | FUNCTION |
| evergreen.unaccent_and_squash | text | arg text | FUNCTION |
| evergreen.upgrade_deps_block_check | bool | my_db_patch text, my_applied_to text | FUNCTION |
| evergreen.upgrade_list_applied_deprecated | text | my_db_patch text | FUNCTION |
| evergreen.upgrade_list_applied_deprecates | patch | my_db_patch text | FUNCTION |
| evergreen.upgrade_list_applied_superseded | text | my_db_patch text | FUNCTION |
| evergreen.upgrade_list_applied_supersedes | patch | my_db_patch text | FUNCTION |
| metabib.browse_authority_pivot | int8 | integer[], text | FUNCTION |
| metabib.browse_authority_refs_pivot | int8 | integer[], text | FUNCTION |
| metabib.browse_bib_pivot | int8 | integer[], text | FUNCTION |
| metabib.browse_normalize | text | facet_text text, mapped_field integer | FUNCTION |
| metabib.browse_pivot | int8 | integer[], text | FUNCTION |
| metabib.compile_composite_attr | query_int | cattr_id integer | FUNCTION |
| permission.grp_ancestors_distance | record | integer | FUNCTION |
| permission.grp_descendants | grp_tree | integer | FUNCTION |
| permission.grp_descendants_distance | record | integer | FUNCTION |
| permission.grp_tree_combined_ancestors | grp_tree | integer, integer | FUNCTION |
| permission.grp_tree_common_ancestors | grp_tree | integer, integer | FUNCTION |
| permission.grp_tree_full_path | grp_tree | integer | FUNCTION |
| metabib.compile_composite_attr | query_int | cattr_def text | FUNCTION |
| metabib.compile_composite_attr_cache_disable | bool |  | FUNCTION |
| metabib.compile_composite_attr_cache_init | bool |  | FUNCTION |
| metabib.compile_composite_attr_cache_invalidate | bool |  | FUNCTION |
| metabib.composite_attr_def_cache_inval_tgr | trigger |  | FUNCTION |
| metabib.display_field_normalize_trigger | trigger |  | FUNCTION |
| metabib.facet_normalize_trigger | trigger |  | FUNCTION |
| metabib.reingest_metabib_field_entries | void | bib_id bigint, skip_facet boolean DEFAULT false, skip_display boolean DEFAULT false, skip_browse boolean DEFAULT false, skip_search boolean DEFAULT false, only_fields integer[] DEFAULT '{}'::integer[] | FUNCTION |
| metabib.reingest_metabib_full_rec | void | bib_id bigint | FUNCTION |
| metabib.reingest_record_attributes | void | rid bigint, pattr_list text[] DEFAULT NULL::text[], prmarc text DEFAULT NULL::text, rdeleted boolean DEFAULT true | FUNCTION |
| metabib.remap_metarecord_for_bib | int8 | bib_id bigint, fp text, bib_is_deleted boolean DEFAULT false, retain_deleted boolean DEFAULT false | FUNCTION |
| metabib.search_class_to_registered_components | record | search_class text | FUNCTION |
| metabib.staged_browse | flat_browse_entry_appearance | query text, fields integer[], context_org integer, context_locations integer[], staff boolean, browse_superpage_size integer, count_up_from_zero boolean, result_limit integer, next_pivot_pos integer | FUNCTION |
| metabib.suggest_browse_entries | record | raw_query_text text, search_class text, headline_opts text, visibility_org integer, query_limit integer, normalization integer | FUNCTION |
| metabib.trim_trailing_punctuation | text | text | FUNCTION |
| metabib.update_combined_index_vectors | void | bib_id bigint | FUNCTION |
| money.age_billings_and_payments | int4 |  | FUNCTION |
| money.age_billings_and_payments_for_xact | void | xact_id bigint | FUNCTION |
| money.maintain_billing_ts | trigger |  | FUNCTION |
| money.mat_summary_create | trigger |  | FUNCTION |
| money.mat_summary_delete | trigger |  | FUNCTION |
| money.mat_summary_update | trigger |  | FUNCTION |
| money.materialized_summary_billing_add | trigger |  | FUNCTION |
| money.materialized_summary_billing_del | trigger |  | FUNCTION |
| permission.usr_can_grant_perm | bool | iuser integer, tperm text, target_ou integer | FUNCTION |
| money.materialized_summary_billing_update | trigger |  | FUNCTION |
| money.materialized_summary_payment_add | trigger |  | FUNCTION |
| money.materialized_summary_payment_del | trigger |  | FUNCTION |
| money.materialized_summary_payment_update | trigger |  | FUNCTION |
| permission.grp_ancestors | grp_tree | integer | FUNCTION |
| permission.usr_has_home_perm | bool | iuser integer, tperm text, target_ou integer | FUNCTION |
| permission.usr_has_object_perm | bool | integer, text, text, text | FUNCTION |
| permission.usr_has_object_perm | bool | iuser integer, tperm text, obj_type text, obj_id text, target_ou integer | FUNCTION |
| permission.usr_has_perm | bool | integer, text, integer | FUNCTION |
| permission.usr_has_perm_at | int4 | user_id integer, perm_code text | FUNCTION |
| permission.usr_has_perm_at_all | int4 | user_id integer, perm_code text | FUNCTION |
| public.force_to_isbn13 | text | text | FUNCTION |
| public.ingest_acq_marc | trigger |  | FUNCTION |
| public.integer_or_null | text | text | FUNCTION |
| public.last_agg | anyelement | anyelement, anyelement | FUNCTION |
| public.left_trunc | text | text, integer | FUNCTION |
| public.lowercase | text | text | FUNCTION |
| public.naco_normalize | text | text | FUNCTION |
| public.translate_isbn1013 | text | text | FUNCTION |
| public.uppercase | text | text | FUNCTION |
| permission.usr_has_perm_at_all_nd | int4 | user_id integer, perm_code text | FUNCTION |
| permission.usr_has_perm_at_nd | int4 | user_id integer, perm_code text | FUNCTION |
| permission.usr_has_work_perm | bool | iuser integer, tperm text, target_ou integer | FUNCTION |
| permission.usr_perms | usr_perm_map | integer | FUNCTION |
| public.approximate_date | text | text, text | FUNCTION |
| public.approximate_high_date | text | text | FUNCTION |
| public.approximate_low_date | text | text | FUNCTION |
| public.call_number_dewey | text | text | FUNCTION |
| public.call_number_dewey | text | text, integer | FUNCTION |
| public.cleanup_acq_marc | trigger |  | FUNCTION |
| public.content_or_null | text | text | FUNCTION |
| public.entityize | text | text | FUNCTION |
| public.extract_acq_marc_field | text | bigint, text, text | FUNCTION |
| public.extract_acq_marc_field_set | text | bigint, text, text | FUNCTION |
| public.first5 | text | text | FUNCTION |
| public.first_agg | anyelement | anyelement, anyelement | FUNCTION |
| public.first_word | text | text | FUNCTION |
| public.naco_normalize | text | text, text | FUNCTION |
| public.naco_normalize_keep_comma | text | text | FUNCTION |
| public.non_filing_normalize | text | text, "char" | FUNCTION |
| public.normalize_space | text | text | FUNCTION |
| public.oils_tsearch2 | trigger |  | FUNCTION |
| public.remove_commas | text | text | FUNCTION |
| public.remove_diacritics | text | text | FUNCTION |
| public.remove_paren_substring | text | text | FUNCTION |
| public.remove_whitespace | text | text | FUNCTION |
| public.right_trunc | text | text, integer | FUNCTION |
| public.search_normalize | text | text | FUNCTION |
| rating.bib_pub_age | record | badge_id integer | FUNCTION |
| public.search_normalize | text | text, text | FUNCTION |
| public.search_normalize_keep_comma | text | text | FUNCTION |
| public.split_date_range | text | text | FUNCTION |
| public.text_concat | text | text, text | FUNCTION |
| rating.bib_record_age | record | badge_id integer | FUNCTION |
| rating.checked_out_total_ratio | record | badge_id integer | FUNCTION |
| rating.precalc_bibs_by_copy_or_uri | int4 | badge_id integer | FUNCTION |
| rating.precalc_bibs_by_uri | int4 | badge_id integer | FUNCTION |
| rating.circs_over_time | record | badge_id integer | FUNCTION |
| rating.copy_count | record | badge_id integer | FUNCTION |
| rating.current_circ_count | record | badge_id integer | FUNCTION |
| rating.current_hold_count | record | badge_id integer | FUNCTION |
| rating.generic_fixed_rating_by_copy | record | badge_id integer | FUNCTION |
| rating.generic_fixed_rating_by_copy_or_uri | record | badge_id integer | FUNCTION |
| rating.generic_fixed_rating_by_uri | record | badge_id integer | FUNCTION |
| rating.generic_fixed_rating_global | record | badge_id integer | FUNCTION |
| rating.holds_filled_over_time | record | badge_id integer | FUNCTION |
| rating.holds_holdable_ratio | record | badge_id integer | FUNCTION |
| rating.percent_time_circulating | record | badge_id integer | FUNCTION |
| rating.precalc_attr_filter | int4 | attr_filter text | FUNCTION |
| rating.holds_placed_over_time | record | badge_id integer | FUNCTION |
| rating.holds_total_ratio | record | badge_id integer | FUNCTION |
| rating.inhouse_over_time | record | badge_id integer | FUNCTION |
| rating.org_unit_count | record | badge_id integer | FUNCTION |
| rating.precalc_bibs_by_copy | int4 | badge_id integer | FUNCTION |
| rating.precalc_circ_mod_filter | int4 | cm text | FUNCTION |
| rating.precalc_location_filter | int4 | loc integer | FUNCTION |
| rating.precalc_src_filter | int4 | src integer | FUNCTION |
| search.facets_for_metarecord_set | record | ignore_facet_classes text[], hits bigint[] | FUNCTION |
| search.facets_for_record_set | record | ignore_facet_classes text[], hits bigint[] | FUNCTION |
| rating.recalculate_badge_score | void | badge_id integer, setup_only boolean DEFAULT false | FUNCTION |
| reporter.disable_materialized_simple_record_trigger | void |  | FUNCTION |
| reporter.enable_materialized_simple_record_trigger | void |  | FUNCTION |
| reporter.hold_request_record_mapper | trigger |  | FUNCTION |
| reporter.refresh_materialized_simple_record | void |  | FUNCTION |
| reporter.simple_rec_delete | bool | r_id bigint | FUNCTION |
| reporter.simple_rec_trigger | trigger |  | FUNCTION |
| reporter.simple_rec_update | bool | r_id bigint | FUNCTION |
| reporter.simple_rec_update | bool | r_id bigint, deleted boolean | FUNCTION |
| search.calculate_visibility_attribute | int4 | value integer, attr text | FUNCTION |
| search.calculate_visibility_attribute_list | _int4 | attr text, value integer[] | FUNCTION |
| search.calculate_visibility_attribute_test | text | attr text, value integer[], negate boolean DEFAULT false | FUNCTION |
| search.highlight_display_fields | highlight_result | rid bigint, tsq_map text, css_class text DEFAULT 'oils_SH'::text, hl_all boolean DEFAULT true, minwords integer DEFAULT 5, maxwords integer DEFAULT 25, shortwords integer DEFAULT 0, maxfrags integer DEFAULT 0, delimiter text DEFAULT ' ... '::text | FUNCTION |
| search.highlight_display_fields_impl | highlight_result | rid bigint, tsq text, field_list integer[] DEFAULT '{}'::integer[], css_class text DEFAULT 'oils_SH'::text, hl_all boolean DEFAULT true, minwords integer DEFAULT 5, maxwords integer DEFAULT 25, shortwords integer DEFAULT 0, maxfrags integer DEFAULT 0, delimiter text DEFAULT ' ... '::text | FUNCTION |
| search.query_parser_fts | search_result | param_search_ou integer, param_depth integer, param_query text, param_statuses integer[], param_locations integer[], param_offset integer, param_check integer, param_limit integer, metarecord boolean, staff boolean, deleted_search boolean, param_pref_ou integer DEFAULT NULL::integer | FUNCTION |
| serial.materialize_holding_code | trigger |  | FUNCTION |
| serial.pattern_templates_visible_to | pattern_template | org_unit integer | FUNCTION |
| staging.purge_pending_users | void |  | FUNCTION |
| unapi.acl | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.acn | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.acnp | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.ccs | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.circ | xml | obj_id bigint, format text, ename text, includes text[], org text DEFAULT '-'::text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.acns | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.acp | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.acpn | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.bmp | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.aou | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.ascecm | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.bre | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true, pref_lib integer DEFAULT NULL::integer | FUNCTION |
| unapi.cbs | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| vandelay.add_field | text | target_xml text, source_xml text, field text | FUNCTION |
| unapi.auri | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.biblio_record_entry_feed | xml | id_list bigint[], format text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true, title text DEFAULT NULL::text, description text DEFAULT NULL::text, creator text DEFAULT NULL::text, update_ts text DEFAULT NULL::text, unapi_url text DEFAULT NULL::text, header_xml xml DEFAULT NULL::xml, pref_lib integer DEFAULT NULL::integer | FUNCTION |
| unapi.holdings_xml | xml | bid bigint, ouid integer, org text, depth integer DEFAULT NULL::integer, includes text[] DEFAULT NULL::text[], slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true, pref_lib integer DEFAULT NULL::integer | FUNCTION |
| unapi.memoize | xml | classname text, obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.metabib_virtual_record_feed | xml | id_list bigint[], format text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true, title text DEFAULT NULL::text, description text DEFAULT NULL::text, creator text DEFAULT NULL::text, update_ts text DEFAULT NULL::text, unapi_url text DEFAULT NULL::text, header_xml xml DEFAULT NULL::xml, pref_lib integer DEFAULT NULL::integer | FUNCTION |
| unapi.mmr | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true, pref_lib integer DEFAULT NULL::integer | FUNCTION |
| vandelay.add_field | text | target_xml text, source_xml text, field text, force_add integer | FUNCTION |
| vandelay.auto_overlay_authority_queue | int8 | queue_id bigint | FUNCTION |
| vandelay.auto_overlay_authority_queue | int8 | queue_id bigint, merge_profile_id integer | FUNCTION |
| vandelay.auto_overlay_authority_record | bool | import_id bigint, merge_profile_id integer | FUNCTION |
| vandelay.flay_marc | flat_marc | text | FUNCTION |
| unapi.mmr_holdings_xml | xml | mid bigint, ouid integer, org text, depth integer DEFAULT NULL::integer, includes text[] DEFAULT NULL::text[], slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true, pref_lib integer DEFAULT NULL::integer | FUNCTION |
| unapi.mmr_mra | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true, pref_lib integer DEFAULT NULL::integer | FUNCTION |
| vandelay.auto_overlay_bib_record_with_best | bool | import_id bigint, merge_profile_id integer | FUNCTION |
| vandelay.auto_overlay_bib_record_with_best | bool | import_id bigint, merge_profile_id integer, lwm_ratio_value_p numeric | FUNCTION |
| vandelay.get_expr_from_match_set | text | match_set_id integer, tags_rstore hstore | FUNCTION |
| vandelay.get_expr_from_match_set | text | match_set_id integer, tags_rstore hstore, auth_heading text | FUNCTION |
| unapi.mra | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.sbsum | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.sdist | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.siss | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.sisum | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.sitem | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.sssum | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.sstr | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| unapi.ssub | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| vandelay.match_authority_record | trigger |  | FUNCTION |
| vandelay.match_bib_record | trigger |  | FUNCTION |
| unapi.sunit | xml | obj_id bigint, format text, ename text, includes text[], org text, depth integer DEFAULT NULL::integer, slimit hstore DEFAULT NULL::hstore, soffset hstore DEFAULT NULL::hstore, include_xmlns boolean DEFAULT true | FUNCTION |
| url_verify.extract_urls | int4 | session_id integer, item_id integer | FUNCTION |
| url_verify.ingest_url | trigger |  | FUNCTION |
| url_verify.parse_url | url | url_in text | FUNCTION |
| vandelay._get_expr_push_jrow | void | node vandelay.match_set_point, tags_rstore hstore, auth_heading text | FUNCTION |
| vandelay._get_expr_push_qrow | void | node vandelay.match_set_point | FUNCTION |
| vandelay._get_expr_render_one | text | node vandelay.match_set_point | FUNCTION |
| vandelay._node_tag_comparisons | text | caseless boolean, op text, tags_rstore hstore, tagkey text | FUNCTION |
| vandelay.auto_overlay_authority_record_with_best | bool | import_id bigint, merge_profile_id integer, lwm_ratio_value_p numeric | FUNCTION |
| vandelay.auto_overlay_bib_queue | int8 | queue_id bigint | FUNCTION |
| vandelay.auto_overlay_bib_queue | int8 | queue_id bigint, merge_profile_id integer | FUNCTION |
| vandelay.auto_overlay_bib_queue_with_best | int8 | import_id bigint, merge_profile_id integer | FUNCTION |
| vandelay.auto_overlay_bib_queue_with_best | int8 | queue_id bigint, merge_profile_id integer, lwm_ratio_value numeric | FUNCTION |
| vandelay.auto_overlay_bib_record | bool | import_id bigint, merge_profile_id integer | FUNCTION |
| vandelay.auto_overlay_org_unit_copies | bool | import_id bigint, merge_profile_id integer, lwm_ratio_value_p numeric | FUNCTION |
| vandelay.cleanup_authority_marc | trigger |  | FUNCTION |
| vandelay.cleanup_bib_marc | trigger |  | FUNCTION |
| vandelay.compile_profile | compile_profile | incoming_xml text | FUNCTION |
| vandelay.extract_rec_attrs | hstore | xml text | FUNCTION |
| vandelay.extract_rec_attrs | hstore | xml text, attr_defs text[] | FUNCTION |
| vandelay.find_bib_tcn_data | tcn_data | xml text | FUNCTION |
| vandelay.flatten_marc | flat_marc | marc text | FUNCTION |
| vandelay.flatten_marc_hstore | hstore | record_xml text | FUNCTION |
| vandelay.get_expr_from_match_set_point | text | node vandelay.match_set_point, tags_rstore hstore, auth_heading text | FUNCTION |
| vandelay.ingest_authority_marc | trigger |  | FUNCTION |
| vandelay.ingest_bib_items | trigger |  | FUNCTION |
| vandelay.ingest_bib_marc | trigger |  | FUNCTION |
| vandelay.ingest_items | import_item | import_id bigint, attr_def_id bigint | FUNCTION |
| vandelay.marc21_extract_all_fixed_fields | record_ff_map | marc text, use_default boolean DEFAULT false | FUNCTION |
| vandelay.marc21_extract_fixed_field | text | marc text, ff text, use_default boolean DEFAULT false | FUNCTION |
| vandelay.marc21_extract_fixed_field_list | _text | marc text, ff text, use_default boolean DEFAULT false | FUNCTION |
| vandelay.marc21_physical_characteristics | marc21_physical_characteristics | marc text | FUNCTION |
| vandelay.marc21_record_type | marc21_rec_type_map | marc text | FUNCTION |
| vandelay.match_set_test_authxml | match_set_test_result | match_set_id integer, record_xml text | FUNCTION |
| vandelay.match_set_test_marcxml | match_set_test_result | match_set_id integer, record_xml text, bucket_id integer | FUNCTION |
| vandelay.measure_auth_record_quality | int4 | xml text, match_set_id integer | FUNCTION |
| vandelay.measure_record_quality | int4 | xml text, match_set_id integer | FUNCTION |
| vandelay.merge_record_xml | text | target_marc text, template_marc text | FUNCTION |
| vandelay.merge_record_xml | text | target_xml text, source_xml text, add_rule text, replace_preserve_rule text, strip_rule text | FUNCTION |
| vandelay.merge_record_xml_using_profile | text | incoming_marc text, existing_marc text, merge_profile_id bigint | FUNCTION |
| vandelay.overlay_authority_record | bool | import_id bigint, eg_id bigint, merge_profile_id integer | FUNCTION |
| vandelay.overlay_bib_record | bool | import_id bigint, eg_id bigint, merge_profile_id integer | FUNCTION |
| vandelay.replace_field | text | target_xml text, source_xml text, field text | FUNCTION |
| vandelay.strip_field | text | xml text, field text | FUNCTION |
| vandelay.template_overlay_bib_record | bool | v_marc text, eg_id bigint | FUNCTION |
| vandelay.template_overlay_bib_record | bool | v_marc text, eg_id bigint, merge_profile_id integer | FUNCTION |
| evergreen.array_accum | anyarray | anyelement | FUNCTION |
| public.agg_text | text | text | FUNCTION |
| public.first | anyelement | anyelement | FUNCTION |
| public.last | anyelement | anyelement | FUNCTION |

## Relations

![er](schema.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)

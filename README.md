[![Sample](https://storage.ko-fi.com/cdn/generated/zfskfgqnf/2025-03-07_rest-7d81acd901abf101cbdf54443c38f6f0-dlmmonph.jpg)](https://ko-fi.com/silviosmart)

## Supporte mich / Support Me

Wenn dir meine Arbeit gefällt und du möchtest, dass ich die Entwicklung der Karten fortsetze, kannst du mir einen Kaffee ausgeben.\
If you like my work and want me to continue developing the cards, you can buy me a coffee.

[![PayPal](https://img.shields.io/badge/Donate-PayPal-%2300457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/donate/?hosted_button_id=Z6KY9V6BBZ4BN)

Vergiss nicht, mir auf Social Media zu folgen:\
Don't forget to follow me on social media:

[![TikTok](https://img.shields.io/badge/Follow_TikTok-%23000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@silviosmartalexa)
[![Instagram](https://img.shields.io/badge/Follow_Instagram-%23E1306C?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/silviosmartalexa)
[![YouTube](https://img.shields.io/badge/Subscribe_YouTube-%23FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@silviosmartalexa)

# 🧭 Benutzerdefinierte Sidebar & Header für Home Assistant
[🇮🇹 Italiano](README.it.md)

# Header Flip Modus
![Header flip animation](img/Header-Flip_Mode.gif)

# Header Push Modus
![Header push](img/Header-Push_Mode.gif)

## 📸 Screenshots
<p align="center">
  <img src="img/1.PNG" width="48%">
  <img src="img/2.PNG" width="48%">
</p>
<p align="center">
  <img src="img/3.PNG" width="48%">
  <img src="img/4.PNG" width="48%">
</p>
<p align="center">
  <img src="img/5.PNG" width="48%">
  <img src="img/6.PNG" width="48%">
</p>

Ein vollständig anpassbares **Header + Sidebar Layout-System für Home Assistant**, modern, flexibel und responsiv – mit voller Lovelace-Kompatibilität.

---

## ⭐ Hauptfunktionen

- Responsive Sidebar-Breite (Mobil / Tablet / Desktop)
- Fixierter / Glasstil-Header
- **4 Menüstile (Liste / Breit / Buttons / Grid)**
- Bedingte Menüeinträge
- Individuelle Farben und Icons pro Eintrag
- Optionales Ausblenden der Standard HA Sidebar + Top-Bar
- Template-Bereich für Begrüßung / eigenes HTML
- Unterstützt jede Lovelace-Karte im Header & in der Sidebar
- Funktioniert mit Kiosk-Modus
- Sicher — verändert nicht das Lovelace-Kernlayout
- 🆕 Integrierter grafischer Editor

---

## 🖊️ Grafischer Editor (nur Admin)

<p align="center">
  <img src="img/setting1.png" width="28%">
  <img src="img/setting2.png" width="48%">
</p>

Administratoren können Sidebar und Header visuell konfigurieren.

### Öffnen

1. Toolbar-Button 🖊 oben rechts
2. ⚙ Symbol unten in Sidebar

### Tabs

| Tab | Beschreibung |
|-----|-------------|
| Sidebar | Sidebar konfigurieren |
| Header | Header konfigurieren |
| YAML | Direkt YAML bearbeiten |

### Karten

Alle Karten verwenden YAML.

```yaml
type: custom:button-card
entity: light.living_room
name: "Wohnzimmer"
icon: mdi:sofa
```

### Speichern

- Storage-Modus: automatisch speichern
- YAML-Modus: Snippet erzeugen

---

# 📦 Installation

## HACS
Installation über HACS möglich.

## Manuell

```
/config/www/sidebar-card.js
```

```yaml
url: /local/sidebar-card.js
type: module
```

---

# 🚀 Grundsetup

```yaml
sidebar:
  enabled: true

header:
  enabled: true
```

---

# 🛠 Fehlerbehebung

- Cache leeren
- Plugins deaktivieren
- Ohne Theme testen

---

# ❤️ Credits
Danke an DBuit

Für die HA Community 🙂





<!DOCTYPE html>
<html
  lang="en"
  
  data-color-mode="auto" data-light-theme="light" data-dark-theme="dark"
  data-a11y-animated-images="system" data-a11y-link-underlines="true"
  
  >




  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://github.githubassets.com">
  <link rel="dns-prefetch" href="https://avatars.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">
  <link rel="preconnect" href="https://github.githubassets.com" crossorigin>
  <link rel="preconnect" href="https://avatars.githubusercontent.com">

  


  <link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/light-2ff56e1b36116ee2.css" /><link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/light_high_contrast-f7f95d7633592089.css" /><link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/dark-2d1fe43dbc9adf1f.css" /><link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/dark_high_contrast-d530ee188d165539.css" /><link data-color-theme="light" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/light-2ff56e1b36116ee2.css" /><link data-color-theme="light_high_contrast" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/light_high_contrast-f7f95d7633592089.css" /><link data-color-theme="light_colorblind" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/light_colorblind-e4bbc49fc7b82570.css" /><link data-color-theme="light_colorblind_high_contrast" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/light_colorblind_high_contrast-cc3f126b45166b83.css" /><link data-color-theme="light_tritanopia" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/light_tritanopia-652ca611ea4e33fe.css" /><link data-color-theme="light_tritanopia_high_contrast" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/light_tritanopia_high_contrast-9e82d635cb6c3f49.css" /><link data-color-theme="dark" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/dark-2d1fe43dbc9adf1f.css" /><link data-color-theme="dark_high_contrast" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/dark_high_contrast-d530ee188d165539.css" /><link data-color-theme="dark_colorblind" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/dark_colorblind-3ad0ec21150df75b.css" /><link data-color-theme="dark_colorblind_high_contrast" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/dark_colorblind_high_contrast-5691ff467f71a3f6.css" /><link data-color-theme="dark_tritanopia" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/dark_tritanopia-abee7710893cd168.css" /><link data-color-theme="dark_tritanopia_high_contrast" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/dark_tritanopia_high_contrast-eafcf6cd46158360.css" /><link data-color-theme="dark_dimmed" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/dark_dimmed-c7974682a1a84c8d.css" /><link data-color-theme="dark_dimmed_high_contrast" crossorigin="anonymous" media="all" rel="stylesheet" data-href="https://github.githubassets.com/assets/dark_dimmed_high_contrast-f8dab3e04f94c501.css" />

  <style type="text/css">
    :root {
      --tab-size-preference: 4;
    }

    pre, code {
      tab-size: var(--tab-size-preference);
    }
  </style>

    <link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/primer-primitives-7f694b60439d06c0.css" />
    <link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/primer-b48faa60c69660fa.css" />
    <link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/global-b40ec823a1a6a1af.css" />
    <link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/github-f825c0edd7ad57f8.css" />
  <link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/repository-0751f482f5210958.css" />
<link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/code-c22301b4e838281c.css" />

  

  <script type="application/json" id="client-env">{"locale":"en","featureFlags":["actions_custom_images_storage_billing_ui_visibility","actions_image_version_event","actions_workflow_language_service_allow_concurrency_queue","agent_conflict_resolution","alternate_user_config_repo","arianotify_comprehensive_migration","billing_discount_threshold_notification","code_scanning_dfa_degraded_experience_notice","codespaces_prebuild_region_target_update","codespaces_tab_react","coding_agent_model_selection","coding_agent_model_selection_all_skus","comment_viewer_copy_raw_markdown","contentful_primer_code_blocks","copilot_agent_snippy","copilot_api_agentic_issue_marshal_yaml","copilot_ask_mode_dropdown","copilot_automation_session_author","copilot_chat_attach_multiple_images","copilot_chat_category_rate_limit_messages","copilot_chat_clear_model_selection_for_default_change","copilot_chat_contextual_suggestions_updated","copilot_chat_enable_tool_call_logs","copilot_chat_file_redirect","copilot_chat_input_commands","copilot_chat_opening_thread_switch","copilot_chat_prettify_pasted_code","copilot_chat_reduce_quota_checks","copilot_chat_search_bar_redirect","copilot_chat_selection_attachments","copilot_chat_vision_in_claude","copilot_chat_vision_preview_gate","copilot_custom_copilots","copilot_custom_copilots_feature_preview","copilot_diff_explain_conversation_intent","copilot_diff_reference_context","copilot_duplicate_thread","copilot_extensions_hide_in_dotcom_chat","copilot_extensions_removal_on_marketplace","copilot_features_sql_server_logo","copilot_file_block_ref_matching","copilot_ftp_hyperspace_upgrade_prompt","copilot_icebreakers_experiment_dashboard","copilot_icebreakers_experiment_hyperspace","copilot_immersive_code_block_transition_wrap","copilot_immersive_embedded","copilot_immersive_embedded_deferred_payload","copilot_immersive_embedded_draggable","copilot_immersive_embedded_header_button","copilot_immersive_embedded_implicit_references","copilot_immersive_file_block_transition_open","copilot_immersive_file_preview_keep_mounted","copilot_immersive_job_result_preview","copilot_immersive_structured_model_picker","copilot_immersive_task_hyperlinking","copilot_immersive_task_within_chat_thread","copilot_mc_cli_resume_any_users_task","copilot_mission_control_always_send_integration_id","copilot_mission_control_cli_session_status","copilot_mission_control_initial_data_spinner","copilot_mission_control_logs_incremental","copilot_mission_control_task_alive_updates","copilot_org_policy_page_focus_mode","copilot_redirect_header_button_to_agents","copilot_resource_panel","copilot_scroll_preview_tabs","copilot_share_active_subthread","copilot_spaces_ga","copilot_spaces_individual_policies_ga","copilot_spaces_pagination","copilot_spark_empty_state","copilot_spark_handle_nil_friendly_name","copilot_swe_agent_hide_model_picker_if_only_auto","copilot_swe_agent_pr_comment_model_picker","copilot_swe_agent_use_subagents","copilot_task_api_github_rest_style","copilot_unconfigured_is_inherited","copilot_upgrade_freeze","copilot_usage_metrics_ga","copilot_workbench_slim_line_top_tabs","custom_instructions_file_references","dashboard_indexeddb_caching","dashboard_lists_max_age_filter","dashboard_universe_2025_feedback_dialog","dotgithub_fork_warning","flex_cta_groups_mvp","global_nav_react","hyperspace_2025_logged_out_batch_1","hyperspace_2025_logged_out_batch_2","hyperspace_2025_logged_out_batch_3","ipm_global_transactional_message_agents","ipm_global_transactional_message_copilot","ipm_global_transactional_message_issues","ipm_global_transactional_message_prs","ipm_global_transactional_message_repos","ipm_global_transactional_message_spaces","issue_cca_modal_open","issue_cca_multi_assign_modal","issue_cca_task_side_panel","issue_cca_visualization","issue_cca_visualization_session_panel","issue_fields_global_search","issues_expanded_file_types","issues_lazy_load_comment_box_suggestions","issues_react_bots_timeline_pagination","issues_react_chrome_container_query_fix","issues_search_type_gql","landing_pages_ninetailed","landing_pages_web_vitals_tracking","lifecycle_label_name_updates","low_quality_classifier","marketing_pages_search_explore_provider","memex_default_issue_create_repository","memex_live_update_hovercard","memex_mwl_filter_field_delimiter","memex_remove_deprecated_type_issue","merge_status_header_feedback","notifications_menu_defer_labels","oauth_authorize_clickjacking_protection","octocaptcha_origin_optimization","prs_conversations_react","prs_css_anchor_positioning","rules_insights_filter_bar_created","sample_network_conn_type","secret_scanning_pattern_alerts_link","security_center_artifact_filters_popover","session_logs_ungroup_reasoning_text","site_features_copilot_universe","site_homepage_collaborate_video","spark_prompt_secret_scanning","spark_server_connection_status","suppress_automated_browser_vitals","ui_skip_on_anchor_click","viewscreen_sandbox","warn_inaccessible_attachments","webp_support","workbench_store_readonly"],"copilotApiOverrideUrl":"https://api.githubcopilot.com"}</script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/high-contrast-cookie-218067197ba03c91.js"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/wp-runtime-d7310dc770a7ac2d.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/fetch-utilities-3140609b5732710f.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/28839-7adfdde5afeb1a03.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/85924-ac5602ef611dc506.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/34646-4c7883eb242d5210.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/environment-a12df3cf35884818.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/runtime-helpers-cb4dfbc9d23f30be.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/2966-d68f2b4558d86113.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/96232-540ff5f81016a9ca.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/41013-647932573fc130af.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/51210-45dfb7dd106f6b96.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/64247-73a9861fe185671f.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/81683-382ccc88e034ea1d.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/9338-f6bee5a8d66d930f.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/46740-5a373320e5ef9c01.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/67466-79abcbf599986a00.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/github-elements-61af8f0198be4afd.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/element-registry-161b4fbd68395409.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/react-core-1bf2dfbca21efd20.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/react-lib-1353f2cef82bcdc0.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/58889-5b136bc717e57a8b.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/79039-69acf717ffc901a4.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/61110-073153e0413daf3a.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/2887-91b9c645d570616a.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/26533-f22c29ae5e9b1ed2.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/86483-c3a819d46503a3da.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/37460-fcd4830a1194eace.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/60481-24b13ea726837f7b.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/46287-853bfcb69bb5b3f9.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/2498-f0375ed070e22e54.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/61025-5b1312da907b4074.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/89627-40275597692dc855.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/79087-4f706db8aa2ec0fb.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/49029-42bd0899fca05960.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/99328-a2c6b180d25cb160.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/behaviors-05170beef7088f93.js" defer="defer"></script>
<link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/react-core.f25ad6e4b6a65cba.module.css" />
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/4244-97fb660009234136.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/notifications-global-442a23b66c306470.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/39373-075d662e5ab13538.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/code-menu-ad3e18f5935a3ed8.js" defer="defer"></script>
  
  <script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/primer-react-ed05dc3d91bca0bd.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/octicons-react-60e727d7a1b6f52c.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/89960-3369b8943362e07e.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/37869-3811d0fa923a406d.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/68751-830b37204cdf7847.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/7463-30e02617b93e1c07.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/15272-0fca7ba11b03440f.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/32769-abc9916acf2cd4f1.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/36505-9798da05fe2143ec.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/46148-264173ef30e2e838.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/57712-c58bee9c0d90a66f.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/61545-6a3a31f92bb5e61a.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/20999-9b5648501d55c42d.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/98228-7a59d90d972526cc.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/63991-466700d8cea41498.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/59852-fc77b3df0a08d405.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/3624-fdb7d4ead672734b.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/66231-9febf100ccdfe155.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/71001-7431ccad12c501aa.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/33684-bbaee6839ab84dd8.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/18222-8b85d637a2041072.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/96755-770967b1236437cd.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/4916-0bb8c44ba1b3d0f7.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/75674-28ffd7157e7cb9e8.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/75601-d9eafa1fbbb5172b.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/8987-366fbcea269300af.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/38184-1e8a3a630d385487.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/41110-df3d2329c8277a27.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/22216-7b6bcf152c4599f6.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/32639-b4f0cdce4bef4ac5.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/58085-77d3143b51231967.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/66519-27db8d6ec9c71a98.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/50110-0f4d902364ca3e5b.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/26497-bb0dd27f414e3e71.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/49135-5f8ca97edb189a81.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/71920-723318c28b0f8f3a.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/code-view-121a46f29c0d4946.js" defer="defer"></script>
<link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/primer-react-css.00ba154d21e54e53.module.css" />
<link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/code-view.63b52bc3543633b9.module.css" />

  <script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/70234-1ee48b3a4eebdc7d.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/notifications-subscriptions-menu-8cd581c0af350d7f.js" defer="defer"></script>
<link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/primer-react-css.00ba154d21e54e53.module.css" />
<link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/notifications-subscriptions-menu.f6fd17c299e8bb6c.module.css" />


  <title>sidebar-card/README.md at main · rockbaer2007/sidebar-card · GitHub</title>



  <meta name="route-pattern" content="/:user_id/:repository/blob/*name(/*path)" data-turbo-transient>
  <meta name="route-controller" content="blob" data-turbo-transient>
  <meta name="route-action" content="show" data-turbo-transient>
  <meta name="fetch-nonce" content="v2:ef7abee9-8270-ec5e-e96f-423964a362f4">

    
  <meta name="current-catalog-service-hash" content="f3abb0cc802f3d7b95fc8762b94bdcb13bf39634c40c357301c4aa1d67a256fb">


  <meta name="request-id" content="FACC:3F0AB4:797F276:5D14B99:69F1AF27" data-pjax-transient="true"/><meta name="html-safe-nonce" content="13f422ed307f5ce0656027bc0f5f205d57e7a1d53cac6c1775d73f590abd4d72" data-pjax-transient="true"/><meta name="visitor-payload" content="eyJyZWZlcnJlciI6Imh0dHBzOi8vZ2l0aHViLmNvbS9yb2NrYmFlcjIwMDcvc2lkZWJhci1jYXJkIiwicmVxdWVzdF9pZCI6IkZBQ0M6M0YwQUI0Ojc5N0YyNzY6NUQxNEI5OTo2OUYxQUYyNyIsInZpc2l0b3JfaWQiOiI2NDc1MTcyOTM1ODA0NjA2NDI1IiwicmVnaW9uX2VkZ2UiOiJmcmEiLCJyZWdpb25fcmVuZGVyIjoiZnJhIn0=" data-pjax-transient="true"/><meta name="visitor-hmac" content="57857fc3d88b96d285f1e6df0b676bb511868a64c2155894c7644a2668c06ced" data-pjax-transient="true"/>


    <meta name="hovercard-subject-tag" content="repository:1224309473" data-turbo-transient>


  <meta name="github-keyboard-shortcuts" content="repository,source-code,file-tree,copilot" data-turbo-transient="true" />
  

  <meta name="selected-link" value="repo_source" data-turbo-transient>
  <link rel="assets" href="https://github.githubassets.com/">

    <meta name="google-site-verification" content="Apib7-x98H0j5cPqHWwSMm6dNU4GmODRoqxLiDzdx9I">

<meta name="octolytics-url" content="https://collector.github.com/github/collect" />





  <meta name="analytics-location" content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-turbo-transient="true" />

  




    <meta name="user-login" content="">

  

    <meta name="viewport" content="width=device-width">

    

      <meta name="description" content="New Custom Card: Fully Customisable Sidebar + Header - sidebar-card/README.md at main · rockbaer2007/sidebar-card">

      <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">

    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <meta property="fb:app_id" content="1401488693436528">
    <meta name="apple-itunes-app" content="app-id=1477376905, app-argument=https://github.com/rockbaer2007/sidebar-card/blob/main/README.md" />

      <meta name="twitter:image" content="https://opengraph.githubassets.com/1a3a77655bfeb787abfee16c182cb4c624afa284419cd60476a7376e28fea21a/rockbaer2007/sidebar-card" /><meta name="twitter:site" content="@github" /><meta name="twitter:card" content="summary_large_image" /><meta name="twitter:title" content="sidebar-card/README.md at main · rockbaer2007/sidebar-card" /><meta name="twitter:description" content="New Custom Card: Fully Customisable Sidebar + Header - rockbaer2007/sidebar-card" />
  <meta property="og:image" content="https://opengraph.githubassets.com/1a3a77655bfeb787abfee16c182cb4c624afa284419cd60476a7376e28fea21a/rockbaer2007/sidebar-card" /><meta property="og:image:alt" content="New Custom Card: Fully Customisable Sidebar + Header - rockbaer2007/sidebar-card" /><meta property="og:image:width" content="1200" /><meta property="og:image:height" content="600" /><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="object" /><meta property="og:title" content="sidebar-card/README.md at main · rockbaer2007/sidebar-card" /><meta property="og:url" content="https://github.com/rockbaer2007/sidebar-card/blob/main/README.md" /><meta property="og:description" content="New Custom Card: Fully Customisable Sidebar + Header - rockbaer2007/sidebar-card" />
  




      <meta name="hostname" content="github.com">



        <meta name="expected-hostname" content="github.com">


  <meta http-equiv="x-pjax-version" content="d7f61b46e9f3584a69e68e90407407147bb81e66d129e466b37a2596ec1733b5" data-turbo-track="reload">
  <meta http-equiv="x-pjax-csp-version" content="568c098497d98702bac1642a2a853732a047a6ced28eabd3e15d50041a890235" data-turbo-track="reload">
  <meta http-equiv="x-pjax-css-version" content="87721d1504a187fb3fcbfa6e98526d058edf6fa1163680dbb36bf70525df6ac4" data-turbo-track="reload">
  <meta http-equiv="x-pjax-js-version" content="d19c7384fc11f41c248a1f6fd323e0667dd556e14bc2dea777f4817668066de7" data-turbo-track="reload">

  <meta name="turbo-cache-control" content="no-preview" data-turbo-transient="">

      <meta name="turbo-cache-control" content="no-cache" data-turbo-transient>

    <meta data-hydrostats="publish">

  <meta name="go-import" content="github.com/rockbaer2007/sidebar-card git https://github.com/rockbaer2007/sidebar-card.git">

  <meta name="octolytics-dimension-user_id" content="51380789" /><meta name="octolytics-dimension-user_login" content="rockbaer2007" /><meta name="octolytics-dimension-repository_id" content="1224309473" /><meta name="octolytics-dimension-repository_nwo" content="rockbaer2007/sidebar-card" /><meta name="octolytics-dimension-repository_public" content="true" /><meta name="octolytics-dimension-repository_is_fork" content="true" /><meta name="octolytics-dimension-repository_parent_id" content="1127153798" /><meta name="octolytics-dimension-repository_parent_nwo" content="Bobsilvio/sidebar-card" /><meta name="octolytics-dimension-repository_network_root_id" content="1127153798" /><meta name="octolytics-dimension-repository_network_root_nwo" content="Bobsilvio/sidebar-card" />
  



    

    <meta name="turbo-body-classes" content="logged-out env-production page-responsive">
  <meta name="disable-turbo" content="false">


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <meta name="release" content="aa7e481e529b8bf86e4ab4c175dd8ba8b590f9e9">
  <meta name="ui-target" content="canary-2">

  <link rel="mask-icon" href="https://github.githubassets.com/assets/pinned-octocat-093da3e6fa40.svg" color="#000000">
  <link rel="alternate icon" class="js-site-favicon" type="image/png" href="https://github.githubassets.com/favicons/favicon.png">
  <link rel="icon" class="js-site-favicon" type="image/svg+xml" href="https://github.githubassets.com/favicons/favicon.svg" data-base-href="https://github.githubassets.com/favicons/favicon">

<meta name="theme-color" content="#1e2327">
<meta name="color-scheme" content="light dark" />


  <link rel="manifest" href="/manifest.json" crossOrigin="use-credentials">

  </head>

  <body class="logged-out env-production page-responsive" style="word-wrap: break-word;" >
    <div data-turbo-body class="logged-out env-production page-responsive" style="word-wrap: break-word;" >
      <div id="__primerPortalRoot__" role="region" style="z-index: 1000; position: absolute; width: 100%;" data-turbo-permanent></div>
      

    <div class="position-relative header-wrapper js-header-wrapper ">
      <a href="#start-of-content" data-skip-target-assigned="false" class="px-2 tmp-py-4 color-bg-accent-emphasis color-fg-on-emphasis show-on-focus js-skip-to-content">Skip to content</a>

      <span data-view-component="true" class="progress-pjax-loader Progress position-fixed width-full">
    <span style="width: 0%;" data-view-component="true" class="Progress-item progress-pjax-loader-bar left-0 top-0 color-bg-accent-emphasis"></span>
</span>      
      
      <link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/primer-react-css.00ba154d21e54e53.module.css" />
<link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/keyboard-shortcuts-dialog.1ac5611d6700bff4.module.css" />

<react-partial
  partial-name="keyboard-shortcuts-dialog"
  data-ssr="false"
  data-attempted-ssr="false"
  data-react-profiling="false"
>
  
  <script type="application/json" data-target="react-partial.embeddedData">{"props":{"docsUrl":"https://docs.github.com/get-started/accessibility/keyboard-shortcuts"}}</script>
  <div data-target="react-partial.reactRoot"></div>
</react-partial>





      

          

              
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/46752-7bd8967216f7ea42.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/90350-89ca7e5359af8f77.js" defer="defer"></script>
<script crossorigin="anonymous" type="application/javascript" src="https://github.githubassets.com/assets/sessions-e0da6ce03532723c.js" defer="defer"></script>

<style>
  /* Override primer focus outline color for marketing header dropdown links for better contrast */
  [data-color-mode="light"] .HeaderMenu-dropdown-link:focus-visible,
  [data-color-mode="light"] .HeaderMenu-trailing-link a:focus-visible {
    outline-color: var(--color-accent-fg);
  }
</style>

<header class="HeaderMktg header-logged-out js-details-container js-header Details f4 tmp-py-3" role="banner" data-is-top="true" data-color-mode=auto data-light-theme=light data-dark-theme=dark>
  <h2 class="sr-only">Navigation Menu</h2>

  <button type="button" class="HeaderMktg-backdrop d-lg-none border-0 position-fixed top-0 left-0 width-full height-full js-details-target" aria-label="Toggle navigation">
    <span class="d-none">Toggle navigation</span>
  </button>

  <div class="d-flex flex-column flex-lg-row flex-items-center tmp-px-3 tmp-px-md-4 tmp-px-lg-5 height-full position-relative z-1">
    <div class="d-flex flex-justify-between flex-items-center width-full width-lg-auto">
      <div class="flex-1">
        <button aria-label="Toggle navigation" aria-expanded="false" type="button" data-view-component="true" class="js-details-target js-nav-padding-recalculate js-header-menu-toggle Button--link Button--medium Button d-lg-none color-fg-inherit p-1 tmp-p-1">  <span class="Button-content">
    <span class="Button-label"><div class="HeaderMenu-toggle-bar rounded my-1"></div>
            <div class="HeaderMenu-toggle-bar rounded my-1"></div>
            <div class="HeaderMenu-toggle-bar rounded my-1"></div></span>
  </span>
</button>
      </div>

      <a class="tmp-mr-lg-3 color-fg-inherit flex-order-2 js-prevent-focus-on-mobile-nav"
        href="/"
        aria-label="Homepage"
        data-analytics-event="{&quot;category&quot;:&quot;Marketing nav&quot;,&quot;action&quot;:&quot;click to go to homepage&quot;,&quot;label&quot;:&quot;ref_page:Marketing;ref_cta:Logomark;ref_loc:Header&quot;}">
        <svg height="32" aria-hidden="true" viewBox="0 0 24 24" version="1.1" width="32" data-view-component="true" class="octicon octicon-mark-github">
    <path d="M10.226 17.284c-2.965-.36-5.054-2.493-5.054-5.256 0-1.123.404-2.336 1.078-3.144-.292-.741-.247-2.314.09-2.965.898-.112 2.111.36 2.83 1.01.853-.269 1.752-.404 2.853-.404 1.1 0 1.999.135 2.807.382.696-.629 1.932-1.1 2.83-.988.315.606.36 2.179.067 2.942.72.854 1.101 2 1.101 3.167 0 2.763-2.089 4.852-5.098 5.234.763.494 1.28 1.572 1.28 2.807v2.336c0 .674.561 1.056 1.235.786 4.066-1.55 7.255-5.615 7.255-10.646C23.5 6.188 18.334 1 11.978 1 5.62 1 .5 6.188.5 12.545c0 4.986 3.167 9.12 7.435 10.669.606.225 1.19-.18 1.19-.786V20.63a2.9 2.9 0 0 1-1.078.224c-1.483 0-2.359-.808-2.987-2.313-.247-.607-.517-.966-1.034-1.033-.27-.023-.359-.135-.359-.27 0-.27.45-.471.898-.471.652 0 1.213.404 1.797 1.235.45.651.921.943 1.483.943.561 0 .92-.202 1.437-.719.382-.381.674-.718.944-.943"></path>
</svg>
      </a>

      <div class="d-flex flex-1 flex-order-2 text-right d-lg-none gap-2 flex-justify-end">
          <a
            href="/login?return_to=https%3A%2F%2Fgithub.com%2Frockbaer2007%2Fsidebar-card%2Fblob%2Fmain%2FREADME.md"
            class="HeaderMenu-link HeaderMenu-button d-inline-flex f5 no-underline border color-border-default rounded-2 px-2 py-1 color-fg-inherit js-prevent-focus-on-mobile-nav"
            data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;site header menu&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;SIGN_UP&quot;,&quot;originating_url&quot;:&quot;https://github.com/rockbaer2007/sidebar-card/blob/main/README.md&quot;,&quot;user_id&quot;:null}}" data-hydro-click-hmac="1516e2112efa91dcf89addf8504fa1cc919923e5b362be342cc87b8762c0a846"
            data-analytics-event="{&quot;category&quot;:&quot;Marketing nav&quot;,&quot;action&quot;:&quot;click to Sign in&quot;,&quot;label&quot;:&quot;ref_page:Marketing;ref_cta:Sign in;ref_loc:Header&quot;}"
          >
            Sign in
          </a>
              <div class="AppHeader-appearanceSettings">
    <react-partial-anchor>
      <button data-target="react-partial-anchor.anchor" id="icon-button-42fb2c65-4d5a-4529-9dee-439a0271fe1b" aria-labelledby="tooltip-96113384-92be-479f-98cd-bb85cb01b34d" type="button" disabled="disabled" data-view-component="true" class="Button Button--iconOnly Button--invisible Button--medium AppHeader-button HeaderMenu-link border cursor-wait">  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-sliders Button-visual">
    <path d="M15 2.75a.75.75 0 0 1-.75.75h-4a.75.75 0 0 1 0-1.5h4a.75.75 0 0 1 .75.75Zm-8.5.75v1.25a.75.75 0 0 0 1.5 0v-4a.75.75 0 0 0-1.5 0V2H1.75a.75.75 0 0 0 0 1.5H6.5Zm1.25 5.25a.75.75 0 0 0 0-1.5h-6a.75.75 0 0 0 0 1.5h6ZM15 8a.75.75 0 0 1-.75.75H11.5V10a.75.75 0 1 1-1.5 0V6a.75.75 0 0 1 1.5 0v1.25h2.75A.75.75 0 0 1 15 8Zm-9 5.25v-2a.75.75 0 0 0-1.5 0v1.25H1.75a.75.75 0 0 0 0 1.5H4.5v1.25a.75.75 0 0 0 1.5 0v-2Zm9 0a.75.75 0 0 1-.75.75h-6a.75.75 0 0 1 0-1.5h6a.75.75 0 0 1 .75.75Z"></path>
</svg>
</button><tool-tip id="tooltip-96113384-92be-479f-98cd-bb85cb01b34d" for="icon-button-42fb2c65-4d5a-4529-9dee-439a0271fe1b" popover="manual" data-direction="s" data-type="label" data-view-component="true" class="sr-only position-absolute">Appearance settings</tool-tip>

      <template data-target="react-partial-anchor.template">
        <link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/primer-react-css.00ba154d21e54e53.module.css" />
<link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/appearance-settings.babbb060397858d0.module.css" />

<react-partial
  partial-name="appearance-settings"
  data-ssr="false"
  data-attempted-ssr="false"
  data-react-profiling="false"
>
  
  <script type="application/json" data-target="react-partial.embeddedData">{"props":{}}</script>
  <div data-target="react-partial.reactRoot"></div>
</react-partial>


      </template>
    </react-partial-anchor>
  </div>

      </div>
    </div>


    <div class="HeaderMenu js-header-menu height-fit position-lg-relative d-lg-flex flex-column flex-auto top-0">
      <div class="HeaderMenu-wrapper d-flex flex-column flex-self-start flex-lg-row flex-auto rounded rounded-lg-0">
            <link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/primer-react-css.00ba154d21e54e53.module.css" />
<link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/marketing-navigation.958ac27fcac2300c.module.css" />

<react-partial
  partial-name="marketing-navigation"
  data-ssr="true"
  data-attempted-ssr="true"
  data-react-profiling="false"
>
  
  <script type="application/json" data-target="react-partial.embeddedData">{"props":{"should_use_dotcom_links":true}}</script>
  <div data-target="react-partial.reactRoot"><nav class="MarketingNavigation-module__nav__W0KYY" aria-label="Global"><ul class="MarketingNavigation-module__list__tFbMb"><li><div class="NavDropdown-module__container__l2YeI js-details-container js-header-menu-item"><button type="button" class="NavDropdown-module__button__PEHWX js-details-target" aria-expanded="false">Platform<svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-chevron-right NavDropdown-module__buttonIcon__Tkl8_" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M6.22 3.22a.75.75 0 0 1 1.06 0l4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L9.94 8 6.22 4.28a.75.75 0 0 1 0-1.06Z"></path></svg></button><div class="NavDropdown-module__dropdown__xm1jd"><ul class="NavDropdown-module__list__zuCgG"><li><div class="NavGroup-module__group__W8SqJ"><span class="NavGroup-module__title__Wzxz2">AI CODE CREATION</span><ul class="NavGroup-module__list__UCOFy"><li><a href="https://github.com/features/copilot" data-analytics-event="{&quot;action&quot;:&quot;github_copilot&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;platform&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;github_copilot_link_platform_navbar&quot;}" class="NavLink-module__link__EG3d4"><div class="NavLink-module__text__XvpLQ"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-copilot NavLink-module__icon__ltGNM" viewBox="0 0 24 24" width="24" height="24" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M23.922 16.992c-.861 1.495-5.859 5.023-11.922 5.023-6.063 0-11.061-3.528-11.922-5.023A.641.641 0 0 1 0 16.736v-2.869a.841.841 0 0 1 .053-.22c.372-.935 1.347-2.292 2.605-2.656.167-.429.414-1.055.644-1.517a10.195 10.195 0 0 1-.052-1.086c0-1.331.282-2.499 1.132-3.368.397-.406.89-.717 1.474-.952 1.399-1.136 3.392-2.093 6.122-2.093 2.731 0 4.767.957 6.166 2.093.584.235 1.077.546 1.474.952.85.869 1.132 2.037 1.132 3.368 0 .368-.014.733-.052 1.086.23.462.477 1.088.644 1.517 1.258.364 2.233 1.721 2.605 2.656a.832.832 0 0 1 .053.22v2.869a.641.641 0 0 1-.078.256ZM12.172 11h-.344a4.323 4.323 0 0 1-.355.508C10.703 12.455 9.555 13 7.965 13c-1.725 0-2.989-.359-3.782-1.259a2.005 2.005 0 0 1-.085-.104L4 11.741v6.585c1.435.779 4.514 2.179 8 2.179 3.486 0 6.565-1.4 8-2.179v-6.585l-.098-.104s-.033.045-.085.104c-.793.9-2.057 1.259-3.782 1.259-1.59 0-2.738-.545-3.508-1.492a4.323 4.323 0 0 1-.355-.508h-.016.016Zm.641-2.935c.136 1.057.403 1.913.878 2.497.442.544 1.134.938 2.344.938 1.573 0 2.292-.337 2.657-.751.384-.435.558-1.15.558-2.361 0-1.14-.243-1.847-.705-2.319-.477-.488-1.319-.862-2.824-1.025-1.487-.161-2.192.138-2.533.529-.269.307-.437.808-.438 1.578v.021c0 .265.021.562.063.893Zm-1.626 0c.042-.331.063-.628.063-.894v-.02c-.001-.77-.169-1.271-.438-1.578-.341-.391-1.046-.69-2.533-.529-1.505.163-2.347.537-2.824 1.025-.462.472-.705 1.179-.705 2.319 0 1.211.175 1.926.558 2.361.365.414 1.084.751 2.657.751 1.21 0 1.902-.394 2.344-.938.475-.584.742-1.44.878-2.497Z"></path><path d="M14.5 14.25a1 1 0 0 1 1 1v2a1 1 0 0 1-2 0v-2a1 1 0 0 1 1-1Zm-5 0a1 1 0 0 1 1 1v2a1 1 0 0 1-2 0v-2a1 1 0 0 1 1-1Z"></path></svg><span class="NavLink-module__title__Q7t0p">GitHub Copilot</span><span class="NavLink-module__subtitle__X4gkW">Write better code with AI</span></div></a></li><li><a href="https://github.com/features/spark" data-analytics-event="{&quot;action&quot;:&quot;github_spark&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;platform&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;github_spark_link_platform_navbar&quot;}" class="NavLink-module__link__EG3d4"><div class="NavLink-module__text__XvpLQ"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-sparkle-fill NavLink-module__icon__ltGNM" viewBox="0 0 24 24" width="24" height="24" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M11.296 1.924c.24-.656 1.168-.656 1.408 0l.717 1.958a11.25 11.25 0 0 0 6.697 6.697l1.958.717c.657.24.657 1.168 0 1.408l-1.958.717a11.25 11.25 0 0 0-6.697 6.697l-.717 1.958c-.24.657-1.168.657-1.408 0l-.717-1.958a11.25 11.25 0 0 0-6.697-6.697l-1.958-.717c-.656-.24-.656-1.168 0-1.408l1.958-.717a11.25 11.25 0 0 0 6.697-6.697l.717-1.958Z"></path></svg><span class="NavLink-module__title__Q7t0p">GitHub Spark</span><span class="NavLink-module__subtitle__X4gkW">Build and deploy intelligent apps</span></div></a></li><li><a href="https://github.com/features/models" data-analytics-event="{&quot;action&quot;:&quot;github_models&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;platform&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;github_models_link_platform_navbar&quot;}" class="NavLink-module__link__EG3d4"><div class="NavLink-module__text__XvpLQ"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-ai-model NavLink-module__icon__ltGNM" viewBox="0 0 24 24" width="24" height="24" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M19.375 8.5a3.25 3.25 0 1 1-3.163 4h-3a3.252 3.252 0 0 1-4.443 2.509L7.214 17.76a3.25 3.25 0 1 1-1.342-.674l1.672-2.957A3.238 3.238 0 0 1 6.75 12c0-.907.371-1.727.97-2.316L6.117 6.846A3.253 3.253 0 0 1 1.875 3.75a3.25 3.25 0 1 1 5.526 2.32l1.603 2.836A3.25 3.25 0 0 1 13.093 11h3.119a3.252 3.252 0 0 1 3.163-2.5ZM10 10.25a1.75 1.75 0 1 0-.001 3.499A1.75 1.75 0 0 0 10 10.25ZM5.125 2a1.75 1.75 0 1 0 0 3.5 1.75 1.75 0 0 0 0-3.5Zm12.5 9.75a1.75 1.75 0 1 0 3.5 0 1.75 1.75 0 0 0-3.5 0Zm-14.25 8.5a1.75 1.75 0 1 0 3.501-.001 1.75 1.75 0 0 0-3.501.001Z"></path></svg><span class="NavLink-module__title__Q7t0p">GitHub Models</span><span class="NavLink-module__subtitle__X4gkW">Manage and compare prompts</span></div></a></li><li><a href="https://github.com/mcp" data-analytics-event="{&quot;action&quot;:&quot;mcp_registry&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;platform&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;mcp_registry_link_platform_navbar&quot;}" class="NavLink-module__link__EG3d4"><div class="NavLink-module__text__XvpLQ"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-mcp NavLink-module__icon__ltGNM" viewBox="0 0 24 24" width="24" height="24" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M9.795 1.694a4.287 4.287 0 0 1 6.061 0 4.28 4.28 0 0 1 1.181 3.819 4.282 4.282 0 0 1 3.819 1.181 4.287 4.287 0 0 1 0 6.061l-6.793 6.793a.249.249 0 0 0 0 .353l2.617 2.618a.75.75 0 1 1-1.061 1.061l-2.617-2.618a1.75 1.75 0 0 1 0-2.475l6.793-6.793a2.785 2.785 0 1 0-3.939-3.939l-5.9 5.9a.734.734 0 0 1-.249.165.749.749 0 0 1-.812-1.225l5.9-5.901a2.785 2.785 0 1 0-3.939-3.939L2.931 10.68A.75.75 0 1 1 1.87 9.619l7.925-7.925Z"></path><path d="M12.42 4.069a.752.752 0 0 1 1.061 0 .752.752 0 0 1 0 1.061L7.33 11.28a2.788 2.788 0 0 0 0 3.94 2.788 2.788 0 0 0 3.94 0l6.15-6.151a.752.752 0 0 1 1.061 0 .752.752 0 0 1 0 1.061l-6.151 6.15a4.285 4.285 0 1 1-6.06-6.06l6.15-6.151Z"></path></svg><span class="NavLink-module__title__Q7t0p">MCP Registry<sup class="NavLink-module__label__bil7n">New</sup></span><span class="NavLink-module__subtitle__X4gkW">Integrate external tools</span></div></a></li></ul></div></li><li><div class="NavGroup-module__group__W8SqJ"><span class="NavGroup-module__title__Wzxz2">DEVELOPER WORKFLOWS</span><ul class="NavGroup-module__list__UCOFy"><li><a href="https://github.com/features/actions" data-analytics-event="{&quot;action&quot;:&quot;actions&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;platform&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;actions_link_platform_navbar&quot;}" class="NavLink-module__link__EG3d4"><div class="NavLink-module__text__XvpLQ"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-workflow NavLink-module__icon__ltGNM" viewBox="0 0 24 24" width="24" height="24" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M1 3a2 2 0 0 1 2-2h6.5a2 2 0 0 1 2 2v6.5a2 2 0 0 1-2 2H7v4.063C7 16.355 7.644 17 8.438 17H12.5v-2.5a2 2 0 0 1 2-2H21a2 2 0 0 1 2 2V21a2 2 0 0 1-2 2h-6.5a2 2 0 0 1-2-2v-2.5H8.437A2.939 2.939 0 0 1 5.5 15.562V11.5H3a2 2 0 0 1-2-2Zm2-.5a.5.5 0 0 0-.5.5v6.5a.5.5 0 0 0 .5.5h6.5a.5.5 0 0 0 .5-.5V3a.5.5 0 0 0-.5-.5ZM14.5 14a.5.5 0 0 0-.5.5V21a.5.5 0 0 0 .5.5H21a.5.5 0 0 0 .5-.5v-6.5a.5.5 0 0 0-.5-.5Z"></path></svg><span class="NavLink-module__title__Q7t0p">Actions</span><span class="NavLink-module__subtitle__X4gkW">Automate any workflow</span></div></a></li><li><a href="https://github.com/features/codespaces" data-analytics-event="{&quot;action&quot;:&quot;codespaces&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;platform&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;codespaces_link_platform_navbar&quot;}" class="NavLink-module__link__EG3d4"><div class="NavLink-module__text__XvpLQ"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-codespaces NavLink-module__icon__ltGNM" viewBox="0 0 24 24" width="24" height="24" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M3.5 3.75C3.5 2.784 4.284 2 5.25 2h13.5c.966 0 1.75.784 1.75 1.75v7.5A1.75 1.75 0 0 1 18.75 13H5.25a1.75 1.75 0 0 1-1.75-1.75Zm-2 12c0-.966.784-1.75 1.75-1.75h17.5c.966 0 1.75.784 1.75 1.75v4a1.75 1.75 0 0 1-1.75 1.75H3.25a1.75 1.75 0 0 1-1.75-1.75ZM5.25 3.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h13.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Zm-2 12a.25.25 0 0 0-.25.25v4c0 .138.112.25.25.25h17.5a.25.25 0 0 0 .25-.25v-4a.25.25 0 0 0-.25-.25Z"></path><path d="M10 17.75a.75.75 0 0 1 .75-.75h6.5a.75.75 0 0 1 0 1.5h-6.5a.75.75 0 0 1-.75-.75Zm-4 0a.75.75 0 0 1 .75-.75h.5a.75.75 0 0 1 0 1.5h-.5a.75.75 0 0 1-.75-.75Z"></path></svg><span class="NavLink-module__title__Q7t0p">Codespaces</span><span class="NavLink-module__subtitle__X4gkW">Instant dev environments</span></div></a></li><li><a href="https://github.com/features/issues" data-analytics-event="{&quot;action&quot;:&quot;issues&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;platform&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;issues_link_platform_navbar&quot;}" class="NavLink-module__link__EG3d4"><div class="NavLink-module__text__XvpLQ"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-issue-opened NavLink-module__icon__ltGNM" viewBox="0 0 24 24" width="24" height="24" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M12 1c6.075 0 11 4.925 11 11s-4.925 11-11 11S1 18.075 1 12 5.925 1 12 1ZM2.5 12a9.5 9.5 0 0 0 9.5 9.5 9.5 9.5 0 0 0 9.5-9.5A9.5 9.5 0 0 0 12 2.5 9.5 9.5 0 0 0 2.5 12Zm9.5 2a2 2 0 1 1-.001-3.999A2 2 0 0 1 12 14Z"></path></svg><span class="NavLink-module__title__Q7t0p">Issues</span><span class="NavLink-module__subtitle__X4gkW">Plan and track work</span></div></a></li><li><a href="https://github.com/features/code-review" data-analytics-event="{&quot;action&quot;:&quot;code_review&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;platform&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;code_review_link_platform_navbar&quot;}" class="NavLink-module__link__EG3d4"><div class="NavLink-module__text__XvpLQ"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-code NavLink-module__icon__ltGNM" viewBox="0 0 24 24" width="24" height="24" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M15.22 4.97a.75.75 0 0 1 1.06 0l6.5 6.5a.75.75 0 0 1 0 1.06l-6.5 6.5a.749.749 0 0 1-1.275-.326.749.749 0 0 1 .215-.734L21.19 12l-5.97-5.97a.75.75 0 0 1 0-1.06Zm-6.44 0a.75.75 0 0 1 0 1.06L2.81 12l5.97 5.97a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215l-6.5-6.5a.75.75 0 0 1 0-1.06l6.5-6.5a.75.75 0 0 1 1.06 0Z"></path></svg><span class="NavLink-module__title__Q7t0p">Code Review</span><span class="NavLink-module__subtitle__X4gkW">Manage code changes</span></div></a></li></ul></div></li><li><div class="NavGroup-module__group__W8SqJ"><span class="NavGroup-module__title__Wzxz2">APPLICATION SECURITY</span><ul class="NavGroup-module__list__UCOFy"><li><a href="https://github.com/security/advanced-security" data-analytics-event="{&quot;action&quot;:&quot;github_advanced_security&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;platform&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;github_advanced_security_link_platform_navbar&quot;}" class="NavLink-module__link__EG3d4"><div class="NavLink-module__text__XvpLQ"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-shield-check NavLink-module__icon__ltGNM" viewBox="0 0 24 24" width="24" height="24" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M16.53 9.78a.75.75 0 0 0-1.06-1.06L11 13.19l-1.97-1.97a.75.75 0 0 0-1.06 1.06l2.5 2.5a.75.75 0 0 0 1.06 0l5-5Z"></path><path d="m12.54.637 8.25 2.675A1.75 1.75 0 0 1 22 4.976V10c0 6.19-3.771 10.704-9.401 12.83a1.704 1.704 0 0 1-1.198 0C5.77 20.705 2 16.19 2 10V4.976c0-.758.489-1.43 1.21-1.664L11.46.637a1.748 1.748 0 0 1 1.08 0Zm-.617 1.426-8.25 2.676a.249.249 0 0 0-.173.237V10c0 5.46 3.28 9.483 8.43 11.426a.199.199 0 0 0 .14 0C17.22 19.483 20.5 15.461 20.5 10V4.976a.25.25 0 0 0-.173-.237l-8.25-2.676a.253.253 0 0 0-.154 0Z"></path></svg><span class="NavLink-module__title__Q7t0p">GitHub Advanced Security</span><span class="NavLink-module__subtitle__X4gkW">Find and fix vulnerabilities</span></div></a></li><li><a href="https://github.com/security/advanced-security/code-security" data-analytics-event="{&quot;action&quot;:&quot;code_security&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;platform&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;code_security_link_platform_navbar&quot;}" class="NavLink-module__link__EG3d4"><div class="NavLink-module__text__XvpLQ"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-code-square NavLink-module__icon__ltGNM" viewBox="0 0 24 24" width="24" height="24" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M10.3 8.24a.75.75 0 0 1-.04 1.06L7.352 12l2.908 2.7a.75.75 0 1 1-1.02 1.1l-3.5-3.25a.75.75 0 0 1 0-1.1l3.5-3.25a.75.75 0 0 1 1.06.04Zm3.44 1.06a.75.75 0 1 1 1.02-1.1l3.5 3.25a.75.75 0 0 1 0 1.1l-3.5 3.25a.75.75 0 1 1-1.02-1.1l2.908-2.7-2.908-2.7Z"></path><path d="M2 3.75C2 2.784 2.784 2 3.75 2h16.5c.966 0 1.75.784 1.75 1.75v16.5A1.75 1.75 0 0 1 20.25 22H3.75A1.75 1.75 0 0 1 2 20.25Zm1.75-.25a.25.25 0 0 0-.25.25v16.5c0 .138.112.25.25.25h16.5a.25.25 0 0 0 .25-.25V3.75a.25.25 0 0 0-.25-.25Z"></path></svg><span class="NavLink-module__title__Q7t0p">Code security</span><span class="NavLink-module__subtitle__X4gkW">Secure your code as you build</span></div></a></li><li><a href="https://github.com/security/advanced-security/secret-protection" data-analytics-event="{&quot;action&quot;:&quot;secret_protection&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;platform&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;secret_protection_link_platform_navbar&quot;}" class="NavLink-module__link__EG3d4"><div class="NavLink-module__text__XvpLQ"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-lock NavLink-module__icon__ltGNM" viewBox="0 0 24 24" width="24" height="24" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M6 9V7.25C6 3.845 8.503 1 12 1s6 2.845 6 6.25V9h.5a2.5 2.5 0 0 1 2.5 2.5v8a2.5 2.5 0 0 1-2.5 2.5h-13A2.5 2.5 0 0 1 3 19.5v-8A2.5 2.5 0 0 1 5.5 9Zm-1.5 2.5v8a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1v-8a1 1 0 0 0-1-1h-13a1 1 0 0 0-1 1Zm3-4.25V9h9V7.25c0-2.67-1.922-4.75-4.5-4.75-2.578 0-4.5 2.08-4.5 4.75Z"></path></svg><span class="NavLink-module__title__Q7t0p">Secret protection</span><span class="NavLink-module__subtitle__X4gkW">Stop leaks before they start</span></div></a></li></ul></div></li><li><div class="NavGroup-module__group__W8SqJ NavGroup-module__hasSeparator__FnMrN"><span class="NavGroup-module__title__Wzxz2">EXPLORE</span><ul class="NavGroup-module__list__UCOFy"><li><a href="https://github.com/why-github" data-analytics-event="{&quot;action&quot;:&quot;why_github&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;platform&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;why_github_link_platform_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Why GitHub</span></a></li><li><a href="https://docs.github.com" data-analytics-event="{&quot;action&quot;:&quot;documentation&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;platform&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;documentation_link_platform_navbar&quot;}" class="NavLink-module__link__EG3d4" target="_blank" rel="noreferrer"><span class="NavLink-module__title__Q7t0p">Documentation</span><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-link-external NavLink-module__externalIcon__eWIry" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M3.75 2h3.5a.75.75 0 0 1 0 1.5h-3.5a.25.25 0 0 0-.25.25v8.5c0 .138.112.25.25.25h8.5a.25.25 0 0 0 .25-.25v-3.5a.75.75 0 0 1 1.5 0v3.5A1.75 1.75 0 0 1 12.25 14h-8.5A1.75 1.75 0 0 1 2 12.25v-8.5C2 2.784 2.784 2 3.75 2Zm6.854-1h4.146a.25.25 0 0 1 .25.25v4.146a.25.25 0 0 1-.427.177L13.03 4.03 9.28 7.78a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042l3.75-3.75-1.543-1.543A.25.25 0 0 1 10.604 1Z"></path></svg></a></li><li><a href="https://github.blog" data-analytics-event="{&quot;action&quot;:&quot;blog&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;platform&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;blog_link_platform_navbar&quot;}" class="NavLink-module__link__EG3d4" target="_blank" rel="noreferrer"><span class="NavLink-module__title__Q7t0p">Blog</span><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-link-external NavLink-module__externalIcon__eWIry" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M3.75 2h3.5a.75.75 0 0 1 0 1.5h-3.5a.25.25 0 0 0-.25.25v8.5c0 .138.112.25.25.25h8.5a.25.25 0 0 0 .25-.25v-3.5a.75.75 0 0 1 1.5 0v3.5A1.75 1.75 0 0 1 12.25 14h-8.5A1.75 1.75 0 0 1 2 12.25v-8.5C2 2.784 2.784 2 3.75 2Zm6.854-1h4.146a.25.25 0 0 1 .25.25v4.146a.25.25 0 0 1-.427.177L13.03 4.03 9.28 7.78a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042l3.75-3.75-1.543-1.543A.25.25 0 0 1 10.604 1Z"></path></svg></a></li><li><a href="https://github.blog/changelog" data-analytics-event="{&quot;action&quot;:&quot;changelog&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;platform&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;changelog_link_platform_navbar&quot;}" class="NavLink-module__link__EG3d4" target="_blank" rel="noreferrer"><span class="NavLink-module__title__Q7t0p">Changelog</span><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-link-external NavLink-module__externalIcon__eWIry" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M3.75 2h3.5a.75.75 0 0 1 0 1.5h-3.5a.25.25 0 0 0-.25.25v8.5c0 .138.112.25.25.25h8.5a.25.25 0 0 0 .25-.25v-3.5a.75.75 0 0 1 1.5 0v3.5A1.75 1.75 0 0 1 12.25 14h-8.5A1.75 1.75 0 0 1 2 12.25v-8.5C2 2.784 2.784 2 3.75 2Zm6.854-1h4.146a.25.25 0 0 1 .25.25v4.146a.25.25 0 0 1-.427.177L13.03 4.03 9.28 7.78a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042l3.75-3.75-1.543-1.543A.25.25 0 0 1 10.604 1Z"></path></svg></a></li><li><a href="https://github.com/marketplace" data-analytics-event="{&quot;action&quot;:&quot;marketplace&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;platform&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;marketplace_link_platform_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Marketplace</span></a></li></ul></div></li></ul><div class="NavDropdown-module__trailingLinkContainer__VgJGL"><a href="https://github.com/features" data-analytics-event="{&quot;action&quot;:&quot;view_all_features&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;platform&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;view_all_features_link_platform_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">View all features</span><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-chevron-right NavLink-module__arrowIcon__amekg" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M6.22 3.22a.75.75 0 0 1 1.06 0l4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L9.94 8 6.22 4.28a.75.75 0 0 1 0-1.06Z"></path></svg></a></div></div></div></li><li><div class="NavDropdown-module__container__l2YeI js-details-container js-header-menu-item"><button type="button" class="NavDropdown-module__button__PEHWX js-details-target" aria-expanded="false">Solutions<svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-chevron-right NavDropdown-module__buttonIcon__Tkl8_" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M6.22 3.22a.75.75 0 0 1 1.06 0l4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L9.94 8 6.22 4.28a.75.75 0 0 1 0-1.06Z"></path></svg></button><div class="NavDropdown-module__dropdown__xm1jd"><ul class="NavDropdown-module__list__zuCgG"><li><div class="NavGroup-module__group__W8SqJ"><span class="NavGroup-module__title__Wzxz2">BY COMPANY SIZE</span><ul class="NavGroup-module__list__UCOFy"><li><a href="https://github.com/enterprise" data-analytics-event="{&quot;action&quot;:&quot;enterprises&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;solutions&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;enterprises_link_solutions_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Enterprises</span></a></li><li><a href="https://github.com/team" data-analytics-event="{&quot;action&quot;:&quot;small_and_medium_teams&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;solutions&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;small_and_medium_teams_link_solutions_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Small and medium teams</span></a></li><li><a href="https://github.com/enterprise/startups" data-analytics-event="{&quot;action&quot;:&quot;startups&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;solutions&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;startups_link_solutions_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Startups</span></a></li><li><a href="https://github.com/solutions/industry/nonprofits" data-analytics-event="{&quot;action&quot;:&quot;nonprofits&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;solutions&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;nonprofits_link_solutions_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Nonprofits</span></a></li></ul></div></li><li><div class="NavGroup-module__group__W8SqJ"><span class="NavGroup-module__title__Wzxz2">BY USE CASE</span><ul class="NavGroup-module__list__UCOFy"><li><a href="https://github.com/solutions/use-case/app-modernization" data-analytics-event="{&quot;action&quot;:&quot;app_modernization&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;solutions&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;app_modernization_link_solutions_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">App Modernization</span></a></li><li><a href="https://github.com/solutions/use-case/devsecops" data-analytics-event="{&quot;action&quot;:&quot;devsecops&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;solutions&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;devsecops_link_solutions_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">DevSecOps</span></a></li><li><a href="https://github.com/solutions/use-case/devops" data-analytics-event="{&quot;action&quot;:&quot;devops&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;solutions&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;devops_link_solutions_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">DevOps</span></a></li><li><a href="https://github.com/solutions/use-case/ci-cd" data-analytics-event="{&quot;action&quot;:&quot;ci/cd&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;solutions&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;ci/cd_link_solutions_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">CI/CD</span></a></li><li><a href="https://github.com/solutions/use-case" data-analytics-event="{&quot;action&quot;:&quot;view_all_use_cases&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;solutions&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;view_all_use_cases_link_solutions_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">View all use cases</span><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-chevron-right NavLink-module__arrowIcon__amekg" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M6.22 3.22a.75.75 0 0 1 1.06 0l4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L9.94 8 6.22 4.28a.75.75 0 0 1 0-1.06Z"></path></svg></a></li></ul></div></li><li><div class="NavGroup-module__group__W8SqJ"><span class="NavGroup-module__title__Wzxz2">BY INDUSTRY</span><ul class="NavGroup-module__list__UCOFy"><li><a href="https://github.com/solutions/industry/healthcare" data-analytics-event="{&quot;action&quot;:&quot;healthcare&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;solutions&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;healthcare_link_solutions_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Healthcare</span></a></li><li><a href="https://github.com/solutions/industry/financial-services" data-analytics-event="{&quot;action&quot;:&quot;financial_services&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;solutions&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;financial_services_link_solutions_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Financial services</span></a></li><li><a href="https://github.com/solutions/industry/manufacturing" data-analytics-event="{&quot;action&quot;:&quot;manufacturing&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;solutions&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;manufacturing_link_solutions_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Manufacturing</span></a></li><li><a href="https://github.com/solutions/industry/government" data-analytics-event="{&quot;action&quot;:&quot;government&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;solutions&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;government_link_solutions_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Government</span></a></li><li><a href="https://github.com/solutions/industry" data-analytics-event="{&quot;action&quot;:&quot;view_all_industries&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;solutions&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;view_all_industries_link_solutions_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">View all industries</span><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-chevron-right NavLink-module__arrowIcon__amekg" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M6.22 3.22a.75.75 0 0 1 1.06 0l4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L9.94 8 6.22 4.28a.75.75 0 0 1 0-1.06Z"></path></svg></a></li></ul></div></li></ul><div class="NavDropdown-module__trailingLinkContainer__VgJGL"><a href="https://github.com/solutions" data-analytics-event="{&quot;action&quot;:&quot;view_all_solutions&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;solutions&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;view_all_solutions_link_solutions_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">View all solutions</span><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-chevron-right NavLink-module__arrowIcon__amekg" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M6.22 3.22a.75.75 0 0 1 1.06 0l4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L9.94 8 6.22 4.28a.75.75 0 0 1 0-1.06Z"></path></svg></a></div></div></div></li><li><div class="NavDropdown-module__container__l2YeI js-details-container js-header-menu-item"><button type="button" class="NavDropdown-module__button__PEHWX js-details-target" aria-expanded="false">Resources<svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-chevron-right NavDropdown-module__buttonIcon__Tkl8_" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M6.22 3.22a.75.75 0 0 1 1.06 0l4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L9.94 8 6.22 4.28a.75.75 0 0 1 0-1.06Z"></path></svg></button><div class="NavDropdown-module__dropdown__xm1jd"><ul class="NavDropdown-module__list__zuCgG"><li><div class="NavGroup-module__group__W8SqJ"><span class="NavGroup-module__title__Wzxz2">EXPLORE BY TOPIC</span><ul class="NavGroup-module__list__UCOFy"><li><a href="https://github.com/resources/articles?topic=ai" data-analytics-event="{&quot;action&quot;:&quot;ai&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;resources&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;ai_link_resources_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">AI</span></a></li><li><a href="https://github.com/resources/articles?topic=software-development" data-analytics-event="{&quot;action&quot;:&quot;software_development&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;resources&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;software_development_link_resources_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Software Development</span></a></li><li><a href="https://github.com/resources/articles?topic=devops" data-analytics-event="{&quot;action&quot;:&quot;devops&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;resources&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;devops_link_resources_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">DevOps</span></a></li><li><a href="https://github.com/resources/articles?topic=security" data-analytics-event="{&quot;action&quot;:&quot;security&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;resources&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;security_link_resources_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Security</span></a></li><li><a href="https://github.com/resources/articles" data-analytics-event="{&quot;action&quot;:&quot;view_all_topics&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;resources&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;view_all_topics_link_resources_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">View all topics</span><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-chevron-right NavLink-module__arrowIcon__amekg" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M6.22 3.22a.75.75 0 0 1 1.06 0l4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L9.94 8 6.22 4.28a.75.75 0 0 1 0-1.06Z"></path></svg></a></li></ul></div></li><li><div class="NavGroup-module__group__W8SqJ"><span class="NavGroup-module__title__Wzxz2">EXPLORE BY TYPE</span><ul class="NavGroup-module__list__UCOFy"><li><a href="https://github.com/customer-stories" data-analytics-event="{&quot;action&quot;:&quot;customer_stories&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;resources&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;customer_stories_link_resources_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Customer stories</span></a></li><li><a href="https://github.com/resources/events" data-analytics-event="{&quot;action&quot;:&quot;events__webinars&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;resources&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;events__webinars_link_resources_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Events &amp; webinars</span></a></li><li><a href="https://github.com/resources/whitepapers" data-analytics-event="{&quot;action&quot;:&quot;ebooks__reports&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;resources&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;ebooks__reports_link_resources_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Ebooks &amp; reports</span></a></li><li><a href="https://github.com/solutions/executive-insights" data-analytics-event="{&quot;action&quot;:&quot;business_insights&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;resources&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;business_insights_link_resources_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Business insights</span></a></li><li><a href="https://skills.github.com" data-analytics-event="{&quot;action&quot;:&quot;github_skills&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;resources&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;github_skills_link_resources_navbar&quot;}" class="NavLink-module__link__EG3d4" target="_blank" rel="noreferrer"><span class="NavLink-module__title__Q7t0p">GitHub Skills</span><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-link-external NavLink-module__externalIcon__eWIry" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M3.75 2h3.5a.75.75 0 0 1 0 1.5h-3.5a.25.25 0 0 0-.25.25v8.5c0 .138.112.25.25.25h8.5a.25.25 0 0 0 .25-.25v-3.5a.75.75 0 0 1 1.5 0v3.5A1.75 1.75 0 0 1 12.25 14h-8.5A1.75 1.75 0 0 1 2 12.25v-8.5C2 2.784 2.784 2 3.75 2Zm6.854-1h4.146a.25.25 0 0 1 .25.25v4.146a.25.25 0 0 1-.427.177L13.03 4.03 9.28 7.78a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042l3.75-3.75-1.543-1.543A.25.25 0 0 1 10.604 1Z"></path></svg></a></li></ul></div></li><li><div class="NavGroup-module__group__W8SqJ"><span class="NavGroup-module__title__Wzxz2">SUPPORT &amp; SERVICES</span><ul class="NavGroup-module__list__UCOFy"><li><a href="https://docs.github.com" data-analytics-event="{&quot;action&quot;:&quot;documentation&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;resources&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;documentation_link_resources_navbar&quot;}" class="NavLink-module__link__EG3d4" target="_blank" rel="noreferrer"><span class="NavLink-module__title__Q7t0p">Documentation</span><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-link-external NavLink-module__externalIcon__eWIry" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M3.75 2h3.5a.75.75 0 0 1 0 1.5h-3.5a.25.25 0 0 0-.25.25v8.5c0 .138.112.25.25.25h8.5a.25.25 0 0 0 .25-.25v-3.5a.75.75 0 0 1 1.5 0v3.5A1.75 1.75 0 0 1 12.25 14h-8.5A1.75 1.75 0 0 1 2 12.25v-8.5C2 2.784 2.784 2 3.75 2Zm6.854-1h4.146a.25.25 0 0 1 .25.25v4.146a.25.25 0 0 1-.427.177L13.03 4.03 9.28 7.78a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042l3.75-3.75-1.543-1.543A.25.25 0 0 1 10.604 1Z"></path></svg></a></li><li><a href="https://support.github.com" data-analytics-event="{&quot;action&quot;:&quot;customer_support&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;resources&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;customer_support_link_resources_navbar&quot;}" class="NavLink-module__link__EG3d4" target="_blank" rel="noreferrer"><span class="NavLink-module__title__Q7t0p">Customer support</span><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-link-external NavLink-module__externalIcon__eWIry" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M3.75 2h3.5a.75.75 0 0 1 0 1.5h-3.5a.25.25 0 0 0-.25.25v8.5c0 .138.112.25.25.25h8.5a.25.25 0 0 0 .25-.25v-3.5a.75.75 0 0 1 1.5 0v3.5A1.75 1.75 0 0 1 12.25 14h-8.5A1.75 1.75 0 0 1 2 12.25v-8.5C2 2.784 2.784 2 3.75 2Zm6.854-1h4.146a.25.25 0 0 1 .25.25v4.146a.25.25 0 0 1-.427.177L13.03 4.03 9.28 7.78a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042l3.75-3.75-1.543-1.543A.25.25 0 0 1 10.604 1Z"></path></svg></a></li><li><a href="https://github.com/orgs/community/discussions" data-analytics-event="{&quot;action&quot;:&quot;community_forum&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;resources&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;community_forum_link_resources_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Community forum</span></a></li><li><a href="https://github.com/trust-center" data-analytics-event="{&quot;action&quot;:&quot;trust_center&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;resources&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;trust_center_link_resources_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Trust center</span></a></li><li><a href="https://github.com/partners" data-analytics-event="{&quot;action&quot;:&quot;partners&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;resources&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;partners_link_resources_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Partners</span></a></li></ul></div></li></ul><div class="NavDropdown-module__trailingLinkContainer__VgJGL"><a href="https://github.com/resources" data-analytics-event="{&quot;action&quot;:&quot;view_all_resources&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;resources&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;view_all_resources_link_resources_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">View all resources</span><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-chevron-right NavLink-module__arrowIcon__amekg" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M6.22 3.22a.75.75 0 0 1 1.06 0l4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L9.94 8 6.22 4.28a.75.75 0 0 1 0-1.06Z"></path></svg></a></div></div></div></li><li><div class="NavDropdown-module__container__l2YeI js-details-container js-header-menu-item"><button type="button" class="NavDropdown-module__button__PEHWX js-details-target" aria-expanded="false">Open Source<svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-chevron-right NavDropdown-module__buttonIcon__Tkl8_" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M6.22 3.22a.75.75 0 0 1 1.06 0l4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L9.94 8 6.22 4.28a.75.75 0 0 1 0-1.06Z"></path></svg></button><div class="NavDropdown-module__dropdown__xm1jd"><ul class="NavDropdown-module__list__zuCgG"><li><div class="NavGroup-module__group__W8SqJ"><span class="NavGroup-module__title__Wzxz2">COMMUNITY</span><ul class="NavGroup-module__list__UCOFy"><li><a href="https://github.com/sponsors" data-analytics-event="{&quot;action&quot;:&quot;github_sponsors&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;open_source&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;github_sponsors_link_open_source_navbar&quot;}" class="NavLink-module__link__EG3d4"><div class="NavLink-module__text__XvpLQ"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-sponsor-tiers NavLink-module__icon__ltGNM" viewBox="0 0 24 24" width="24" height="24" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M16.004 1.25C18.311 1.25 20 3.128 20 5.75c0 2.292-1.23 4.464-3.295 6.485-.481.47-.98.909-1.482 1.31l.265 1.32 1.375 7.5a.75.75 0 0 1-.982.844l-3.512-1.207a.75.75 0 0 0-.488 0L8.37 23.209a.75.75 0 0 1-.982-.844l1.378-7.512.261-1.309c-.5-.4-1-.838-1.481-1.31C5.479 10.215 4.25 8.043 4.25 5.75c0-2.622 1.689-4.5 3.996-4.5 1.55 0 2.947.752 3.832 1.967l.047.067.047-.067a4.726 4.726 0 0 1 3.612-1.962l.22-.005ZM13.89 14.531c-.418.285-.828.542-1.218.77l-.18.103a.75.75 0 0 1-.734 0l-.071-.04-.46-.272c-.282-.173-.573-.36-.868-.562l-.121.605-1.145 6.239 2.3-.79a2.248 2.248 0 0 1 1.284-.054l.18.053 2.299.79-1.141-6.226-.125-.616ZM16.004 2.75c-1.464 0-2.731.983-3.159 2.459-.209.721-1.231.721-1.44 0-.428-1.476-1.695-2.459-3.16-2.459-1.44 0-2.495 1.173-2.495 3 0 1.811 1.039 3.647 2.844 5.412a19.624 19.624 0 0 0 3.734 2.84l-.019-.011-.184-.111.147-.088a19.81 19.81 0 0 0 3.015-2.278l.37-.352C17.46 9.397 18.5 7.561 18.5 5.75c0-1.827-1.055-3-2.496-3Z"></path></svg><span class="NavLink-module__title__Q7t0p">GitHub Sponsors</span><span class="NavLink-module__subtitle__X4gkW">Fund open source developers</span></div></a></li></ul></div></li><li><div class="NavGroup-module__group__W8SqJ"><span class="NavGroup-module__title__Wzxz2">PROGRAMS</span><ul class="NavGroup-module__list__UCOFy"><li><a href="https://securitylab.github.com" data-analytics-event="{&quot;action&quot;:&quot;security_lab&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;open_source&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;security_lab_link_open_source_navbar&quot;}" class="NavLink-module__link__EG3d4" target="_blank" rel="noreferrer"><span class="NavLink-module__title__Q7t0p">Security Lab</span><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-link-external NavLink-module__externalIcon__eWIry" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M3.75 2h3.5a.75.75 0 0 1 0 1.5h-3.5a.25.25 0 0 0-.25.25v8.5c0 .138.112.25.25.25h8.5a.25.25 0 0 0 .25-.25v-3.5a.75.75 0 0 1 1.5 0v3.5A1.75 1.75 0 0 1 12.25 14h-8.5A1.75 1.75 0 0 1 2 12.25v-8.5C2 2.784 2.784 2 3.75 2Zm6.854-1h4.146a.25.25 0 0 1 .25.25v4.146a.25.25 0 0 1-.427.177L13.03 4.03 9.28 7.78a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042l3.75-3.75-1.543-1.543A.25.25 0 0 1 10.604 1Z"></path></svg></a></li><li><a href="https://maintainers.github.com" data-analytics-event="{&quot;action&quot;:&quot;maintainer_community&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;open_source&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;maintainer_community_link_open_source_navbar&quot;}" class="NavLink-module__link__EG3d4" target="_blank" rel="noreferrer"><span class="NavLink-module__title__Q7t0p">Maintainer Community</span><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-link-external NavLink-module__externalIcon__eWIry" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M3.75 2h3.5a.75.75 0 0 1 0 1.5h-3.5a.25.25 0 0 0-.25.25v8.5c0 .138.112.25.25.25h8.5a.25.25 0 0 0 .25-.25v-3.5a.75.75 0 0 1 1.5 0v3.5A1.75 1.75 0 0 1 12.25 14h-8.5A1.75 1.75 0 0 1 2 12.25v-8.5C2 2.784 2.784 2 3.75 2Zm6.854-1h4.146a.25.25 0 0 1 .25.25v4.146a.25.25 0 0 1-.427.177L13.03 4.03 9.28 7.78a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042l3.75-3.75-1.543-1.543A.25.25 0 0 1 10.604 1Z"></path></svg></a></li><li><a href="https://github.com/accelerator" data-analytics-event="{&quot;action&quot;:&quot;accelerator&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;open_source&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;accelerator_link_open_source_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Accelerator</span></a></li><li><a href="https://stars.github.com" data-analytics-event="{&quot;action&quot;:&quot;github_stars&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;open_source&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;github_stars_link_open_source_navbar&quot;}" class="NavLink-module__link__EG3d4" target="_blank" rel="noreferrer"><span class="NavLink-module__title__Q7t0p">GitHub Stars</span><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-link-external NavLink-module__externalIcon__eWIry" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M3.75 2h3.5a.75.75 0 0 1 0 1.5h-3.5a.25.25 0 0 0-.25.25v8.5c0 .138.112.25.25.25h8.5a.25.25 0 0 0 .25-.25v-3.5a.75.75 0 0 1 1.5 0v3.5A1.75 1.75 0 0 1 12.25 14h-8.5A1.75 1.75 0 0 1 2 12.25v-8.5C2 2.784 2.784 2 3.75 2Zm6.854-1h4.146a.25.25 0 0 1 .25.25v4.146a.25.25 0 0 1-.427.177L13.03 4.03 9.28 7.78a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042l3.75-3.75-1.543-1.543A.25.25 0 0 1 10.604 1Z"></path></svg></a></li><li><a href="https://archiveprogram.github.com" data-analytics-event="{&quot;action&quot;:&quot;archive_program&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;open_source&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;archive_program_link_open_source_navbar&quot;}" class="NavLink-module__link__EG3d4" target="_blank" rel="noreferrer"><span class="NavLink-module__title__Q7t0p">Archive Program</span><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-link-external NavLink-module__externalIcon__eWIry" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M3.75 2h3.5a.75.75 0 0 1 0 1.5h-3.5a.25.25 0 0 0-.25.25v8.5c0 .138.112.25.25.25h8.5a.25.25 0 0 0 .25-.25v-3.5a.75.75 0 0 1 1.5 0v3.5A1.75 1.75 0 0 1 12.25 14h-8.5A1.75 1.75 0 0 1 2 12.25v-8.5C2 2.784 2.784 2 3.75 2Zm6.854-1h4.146a.25.25 0 0 1 .25.25v4.146a.25.25 0 0 1-.427.177L13.03 4.03 9.28 7.78a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042l3.75-3.75-1.543-1.543A.25.25 0 0 1 10.604 1Z"></path></svg></a></li></ul></div></li><li><div class="NavGroup-module__group__W8SqJ"><span class="NavGroup-module__title__Wzxz2">REPOSITORIES</span><ul class="NavGroup-module__list__UCOFy"><li><a href="https://github.com/topics" data-analytics-event="{&quot;action&quot;:&quot;topics&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;open_source&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;topics_link_open_source_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Topics</span></a></li><li><a href="https://github.com/trending" data-analytics-event="{&quot;action&quot;:&quot;trending&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;open_source&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;trending_link_open_source_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Trending</span></a></li><li><a href="https://github.com/collections" data-analytics-event="{&quot;action&quot;:&quot;collections&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;open_source&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;collections_link_open_source_navbar&quot;}" class="NavLink-module__link__EG3d4"><span class="NavLink-module__title__Q7t0p">Collections</span></a></li></ul></div></li></ul></div></div></li><li><div class="NavDropdown-module__container__l2YeI js-details-container js-header-menu-item"><button type="button" class="NavDropdown-module__button__PEHWX js-details-target" aria-expanded="false">Enterprise<svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-chevron-right NavDropdown-module__buttonIcon__Tkl8_" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M6.22 3.22a.75.75 0 0 1 1.06 0l4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L9.94 8 6.22 4.28a.75.75 0 0 1 0-1.06Z"></path></svg></button><div class="NavDropdown-module__dropdown__xm1jd"><ul class="NavDropdown-module__list__zuCgG"><li><div class="NavGroup-module__group__W8SqJ"><span class="NavGroup-module__title__Wzxz2">ENTERPRISE SOLUTIONS</span><ul class="NavGroup-module__list__UCOFy"><li><a href="https://github.com/enterprise" data-analytics-event="{&quot;action&quot;:&quot;enterprise_platform&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;enterprise&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;enterprise_platform_link_enterprise_navbar&quot;}" class="NavLink-module__link__EG3d4"><div class="NavLink-module__text__XvpLQ"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-stack NavLink-module__icon__ltGNM" viewBox="0 0 24 24" width="24" height="24" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M11.063 1.456a1.749 1.749 0 0 1 1.874 0l8.383 5.316a1.751 1.751 0 0 1 0 2.956l-8.383 5.316a1.749 1.749 0 0 1-1.874 0L2.68 9.728a1.751 1.751 0 0 1 0-2.956Zm1.071 1.267a.25.25 0 0 0-.268 0L3.483 8.039a.25.25 0 0 0 0 .422l8.383 5.316a.25.25 0 0 0 .268 0l8.383-5.316a.25.25 0 0 0 0-.422Z"></path><path d="M1.867 12.324a.75.75 0 0 1 1.035-.232l8.964 5.685a.25.25 0 0 0 .268 0l8.964-5.685a.75.75 0 0 1 .804 1.267l-8.965 5.685a1.749 1.749 0 0 1-1.874 0l-8.965-5.685a.75.75 0 0 1-.231-1.035Z"></path><path d="M1.867 16.324a.75.75 0 0 1 1.035-.232l8.964 5.685a.25.25 0 0 0 .268 0l8.964-5.685a.75.75 0 0 1 .804 1.267l-8.965 5.685a1.749 1.749 0 0 1-1.874 0l-8.965-5.685a.75.75 0 0 1-.231-1.035Z"></path></svg><span class="NavLink-module__title__Q7t0p">Enterprise platform</span><span class="NavLink-module__subtitle__X4gkW">AI-powered developer platform</span></div></a></li></ul></div></li><li><div class="NavGroup-module__group__W8SqJ"><span class="NavGroup-module__title__Wzxz2">AVAILABLE ADD-ONS</span><ul class="NavGroup-module__list__UCOFy"><li><a href="https://github.com/security/advanced-security" data-analytics-event="{&quot;action&quot;:&quot;github_advanced_security&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;enterprise&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;github_advanced_security_link_enterprise_navbar&quot;}" class="NavLink-module__link__EG3d4"><div class="NavLink-module__text__XvpLQ"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-shield-check NavLink-module__icon__ltGNM" viewBox="0 0 24 24" width="24" height="24" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M16.53 9.78a.75.75 0 0 0-1.06-1.06L11 13.19l-1.97-1.97a.75.75 0 0 0-1.06 1.06l2.5 2.5a.75.75 0 0 0 1.06 0l5-5Z"></path><path d="m12.54.637 8.25 2.675A1.75 1.75 0 0 1 22 4.976V10c0 6.19-3.771 10.704-9.401 12.83a1.704 1.704 0 0 1-1.198 0C5.77 20.705 2 16.19 2 10V4.976c0-.758.489-1.43 1.21-1.664L11.46.637a1.748 1.748 0 0 1 1.08 0Zm-.617 1.426-8.25 2.676a.249.249 0 0 0-.173.237V10c0 5.46 3.28 9.483 8.43 11.426a.199.199 0 0 0 .14 0C17.22 19.483 20.5 15.461 20.5 10V4.976a.25.25 0 0 0-.173-.237l-8.25-2.676a.253.253 0 0 0-.154 0Z"></path></svg><span class="NavLink-module__title__Q7t0p">GitHub Advanced Security</span><span class="NavLink-module__subtitle__X4gkW">Enterprise-grade security features</span></div></a></li><li><a href="https://github.com/features/copilot/copilot-business" data-analytics-event="{&quot;action&quot;:&quot;copilot_for_business&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;enterprise&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;copilot_for_business_link_enterprise_navbar&quot;}" class="NavLink-module__link__EG3d4"><div class="NavLink-module__text__XvpLQ"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-copilot NavLink-module__icon__ltGNM" viewBox="0 0 24 24" width="24" height="24" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M23.922 16.992c-.861 1.495-5.859 5.023-11.922 5.023-6.063 0-11.061-3.528-11.922-5.023A.641.641 0 0 1 0 16.736v-2.869a.841.841 0 0 1 .053-.22c.372-.935 1.347-2.292 2.605-2.656.167-.429.414-1.055.644-1.517a10.195 10.195 0 0 1-.052-1.086c0-1.331.282-2.499 1.132-3.368.397-.406.89-.717 1.474-.952 1.399-1.136 3.392-2.093 6.122-2.093 2.731 0 4.767.957 6.166 2.093.584.235 1.077.546 1.474.952.85.869 1.132 2.037 1.132 3.368 0 .368-.014.733-.052 1.086.23.462.477 1.088.644 1.517 1.258.364 2.233 1.721 2.605 2.656a.832.832 0 0 1 .053.22v2.869a.641.641 0 0 1-.078.256ZM12.172 11h-.344a4.323 4.323 0 0 1-.355.508C10.703 12.455 9.555 13 7.965 13c-1.725 0-2.989-.359-3.782-1.259a2.005 2.005 0 0 1-.085-.104L4 11.741v6.585c1.435.779 4.514 2.179 8 2.179 3.486 0 6.565-1.4 8-2.179v-6.585l-.098-.104s-.033.045-.085.104c-.793.9-2.057 1.259-3.782 1.259-1.59 0-2.738-.545-3.508-1.492a4.323 4.323 0 0 1-.355-.508h-.016.016Zm.641-2.935c.136 1.057.403 1.913.878 2.497.442.544 1.134.938 2.344.938 1.573 0 2.292-.337 2.657-.751.384-.435.558-1.15.558-2.361 0-1.14-.243-1.847-.705-2.319-.477-.488-1.319-.862-2.824-1.025-1.487-.161-2.192.138-2.533.529-.269.307-.437.808-.438 1.578v.021c0 .265.021.562.063.893Zm-1.626 0c.042-.331.063-.628.063-.894v-.02c-.001-.77-.169-1.271-.438-1.578-.341-.391-1.046-.69-2.533-.529-1.505.163-2.347.537-2.824 1.025-.462.472-.705 1.179-.705 2.319 0 1.211.175 1.926.558 2.361.365.414 1.084.751 2.657.751 1.21 0 1.902-.394 2.344-.938.475-.584.742-1.44.878-2.497Z"></path><path d="M14.5 14.25a1 1 0 0 1 1 1v2a1 1 0 0 1-2 0v-2a1 1 0 0 1 1-1Zm-5 0a1 1 0 0 1 1 1v2a1 1 0 0 1-2 0v-2a1 1 0 0 1 1-1Z"></path></svg><span class="NavLink-module__title__Q7t0p">Copilot for Business</span><span class="NavLink-module__subtitle__X4gkW">Enterprise-grade AI features</span></div></a></li><li><a href="https://github.com/premium-support" data-analytics-event="{&quot;action&quot;:&quot;premium_support&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;enterprise&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;premium_support_link_enterprise_navbar&quot;}" class="NavLink-module__link__EG3d4"><div class="NavLink-module__text__XvpLQ"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-comment-discussion NavLink-module__icon__ltGNM" viewBox="0 0 24 24" width="24" height="24" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M1.75 1h12.5c.966 0 1.75.784 1.75 1.75v9.5A1.75 1.75 0 0 1 14.25 14H8.061l-2.574 2.573A1.458 1.458 0 0 1 3 15.543V14H1.75A1.75 1.75 0 0 1 0 12.25v-9.5C0 1.784.784 1 1.75 1ZM1.5 2.75v9.5c0 .138.112.25.25.25h2a.75.75 0 0 1 .75.75v2.19l2.72-2.72a.749.749 0 0 1 .53-.22h6.5a.25.25 0 0 0 .25-.25v-9.5a.25.25 0 0 0-.25-.25H1.75a.25.25 0 0 0-.25.25Z"></path><path d="M22.5 8.75a.25.25 0 0 0-.25-.25h-3.5a.75.75 0 0 1 0-1.5h3.5c.966 0 1.75.784 1.75 1.75v9.5A1.75 1.75 0 0 1 22.25 20H21v1.543a1.457 1.457 0 0 1-2.487 1.03L15.939 20H10.75A1.75 1.75 0 0 1 9 18.25v-1.465a.75.75 0 0 1 1.5 0v1.465c0 .138.112.25.25.25h5.5a.75.75 0 0 1 .53.22l2.72 2.72v-2.19a.75.75 0 0 1 .75-.75h2a.25.25 0 0 0 .25-.25v-9.5Z"></path></svg><span class="NavLink-module__title__Q7t0p">Premium Support</span><span class="NavLink-module__subtitle__X4gkW">Enterprise-grade 24/7 support</span></div></a></li></ul></div></li></ul></div></div></li><li><a href="https://github.com/pricing" data-analytics-event="{&quot;action&quot;:&quot;pricing&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;context&quot;:&quot;pricing&quot;,&quot;location&quot;:&quot;navbar&quot;,&quot;label&quot;:&quot;pricing_link_pricing_navbar&quot;}" class="NavLink-module__link__EG3d4 MarketingNavigation-module__navLink__hUomM"><span class="NavLink-module__title__Q7t0p">Pricing</span></a></li></ul></nav><script type="application/json" id="__PRIMER_DATA__R_0___">{"resolvedServerColorMode":"day"}</script></div>
</react-partial>



        <div class="d-flex flex-column flex-lg-row width-full flex-justify-end flex-lg-items-center text-center tmp-mt-3 tmp-mt-lg-0 text-lg-left tmp-ml-lg-3">
                


<qbsearch-input class="search-input" data-scope="repo:rockbaer2007/sidebar-card" data-custom-scopes-path="/search/custom_scopes" data-delete-custom-scopes-csrf="MAsvwl7p5uVBt-V9mSESBhWbTxG-EqeYyKLEb8FlXpurbFiLLkynX5WFyDxQzwRhDr_evdtuYfrYoharGAFaoA" data-max-custom-scopes="10" data-header-redesign-enabled="false" data-initial-value="" data-blackbird-suggestions-path="/search/suggestions" data-jump-to-suggestions-path="/_graphql/GetSuggestedNavigationDestinations" data-current-repository="rockbaer2007/sidebar-card" data-current-org="" data-current-owner="rockbaer2007" data-logged-in="false" data-copilot-chat-enabled="false" data-nl-search-enabled="false" data-retain-scroll-position="true">
  <div
    class="search-input-container search-with-dialog position-relative d-flex flex-row flex-items-center tmp-mr-4 rounded"
    data-action="click:qbsearch-input#searchInputContainerClicked"
  >
      <button
        type="button"
        class="header-search-button placeholder  input-button form-control d-flex flex-1 flex-self-stretch flex-items-center no-wrap width-full py-0 pl-2 pr-0 text-left border-0 box-shadow-none"
        data-target="qbsearch-input.inputButton"
        aria-label="Search or jump to…"
        aria-haspopup="dialog"
        placeholder="Search or jump to..."
        data-hotkey=s,/
        autocapitalize="off"
        data-analytics-event="{&quot;location&quot;:&quot;navbar&quot;,&quot;action&quot;:&quot;searchbar&quot;,&quot;context&quot;:&quot;global&quot;,&quot;tag&quot;:&quot;input&quot;,&quot;label&quot;:&quot;searchbar_input_global_navbar&quot;}"
        data-action="click:qbsearch-input#handleExpand"
      >
        <div class="mr-2 color-fg-muted">
          <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-search">
    <path d="M10.68 11.74a6 6 0 0 1-7.922-8.982 6 6 0 0 1 8.982 7.922l3.04 3.04a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215ZM11.5 7a4.499 4.499 0 1 0-8.997 0A4.499 4.499 0 0 0 11.5 7Z"></path>
</svg>
        </div>
        <span class="flex-1" data-target="qbsearch-input.inputButtonText">Search or jump to...</span>
          <div class="d-flex" data-target="qbsearch-input.hotkeyIndicator">
            <svg xmlns="http://www.w3.org/2000/svg" width="22" height="20" aria-hidden="true" class="mr-1"><path fill="none" stroke="#979A9C" opacity=".4" d="M3.5.5h12c1.7 0 3 1.3 3 3v13c0 1.7-1.3 3-3 3h-12c-1.7 0-3-1.3-3-3v-13c0-1.7 1.3-3 3-3z"></path><path fill="#979A9C" d="M11.8 6L8 15.1h-.9L10.8 6h1z"></path></svg>
          </div>
      </button>

    <input type="hidden" name="type" class="js-site-search-type-field">

    
<div class="Overlay--hidden " data-modal-dialog-overlay>
  <modal-dialog data-action="close:qbsearch-input#handleClose cancel:qbsearch-input#handleClose" data-target="qbsearch-input.searchSuggestionsDialog" role="dialog" id="search-suggestions-dialog" aria-modal="true" aria-labelledby="search-suggestions-dialog-header" data-view-component="true" class="Overlay Overlay--width-large Overlay--height-auto">
      <h1 id="search-suggestions-dialog-header" class="sr-only">Search code, repositories, users, issues, pull requests...</h1>
    <div class="Overlay-body Overlay-body--paddingNone">
      
          <div data-view-component="true">        <div class="search-suggestions position-fixed width-full color-shadow-large border color-fg-default color-bg-default overflow-hidden d-flex flex-column query-builder-container"
          style="border-radius: 12px;"
          data-target="qbsearch-input.queryBuilderContainer"
          hidden
        >
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form id="query-builder-test-form" action="" accept-charset="UTF-8" method="get">
  <query-builder data-target="qbsearch-input.queryBuilder" id="query-builder-query-builder-test" data-filter-key=":" data-view-component="true" class="QueryBuilder search-query-builder">
    <div class="FormControl FormControl--fullWidth">
      <label id="query-builder-test-label" for="query-builder-test" class="FormControl-label sr-only">
        Search
      </label>
      <div
        class="QueryBuilder-StyledInput width-fit "
        data-target="query-builder.styledInput"
      >
          <span id="query-builder-test-leadingvisual-wrap" class="FormControl-input-leadingVisualWrap QueryBuilder-leadingVisualWrap">
            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-search FormControl-input-leadingVisual">
    <path d="M10.68 11.74a6 6 0 0 1-7.922-8.982 6 6 0 0 1 8.982 7.922l3.04 3.04a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215ZM11.5 7a4.499 4.499 0 1 0-8.997 0A4.499 4.499 0 0 0 11.5 7Z"></path>
</svg>
          </span>
        <div data-target="query-builder.styledInputContainer" class="QueryBuilder-StyledInputContainer">
          <div
            aria-hidden="true"
            class="QueryBuilder-StyledInputContent"
            data-target="query-builder.styledInputContent"
          ></div>
          <div class="QueryBuilder-InputWrapper">
            <div aria-hidden="true" class="QueryBuilder-Sizer" data-target="query-builder.sizer"></div>
            <input id="query-builder-test" name="query-builder-test" value="" autocomplete="off" type="text" role="combobox" spellcheck="false" aria-expanded="false" aria-describedby="validation-b95f8799-44c9-47fc-b612-ab9d25404459" data-target="query-builder.input" data-action="
          input:query-builder#inputChange
          blur:query-builder#inputBlur
          keydown:query-builder#inputKeydown
          focus:query-builder#inputFocus
        " data-view-component="true" class="FormControl-input QueryBuilder-Input FormControl-medium" />
          </div>
        </div>
          <span data-target="query-builder.clearButton" hidden>
            <span class="sr-only" id="query-builder-test-clear">Clear</span>
            <button role="button" id="query-builder-test-clear-button" aria-labelledby="query-builder-test-clear query-builder-test-label" data-action="
                  click:query-builder#clear
                  focus:query-builder#clearButtonFocus
                  blur:query-builder#clearButtonBlur
                " variant="small" type="button" data-view-component="true" class="Button Button--iconOnly Button--invisible Button--medium mr-1 tmp-mr-1 px-2 tmp-px-2 py-0 tmp-py-0 d-flex flex-items-center rounded-1 color-fg-muted">  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x-circle-fill Button-visual">
    <path d="M2.343 13.657A8 8 0 1 1 13.658 2.343 8 8 0 0 1 2.343 13.657ZM6.03 4.97a.751.751 0 0 0-1.042.018.751.751 0 0 0-.018 1.042L6.94 8 4.97 9.97a.749.749 0 0 0 .326 1.275.749.749 0 0 0 .734-.215L8 9.06l1.97 1.97a.749.749 0 0 0 1.275-.326.749.749 0 0 0-.215-.734L9.06 8l1.97-1.97a.749.749 0 0 0-.326-1.275.749.749 0 0 0-.734.215L8 6.94Z"></path>
</svg>
</button>

          </span>
      </div>
      <template id="search-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-search">
    <path d="M10.68 11.74a6 6 0 0 1-7.922-8.982 6 6 0 0 1 8.982 7.922l3.04 3.04a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215ZM11.5 7a4.499 4.499 0 1 0-8.997 0A4.499 4.499 0 0 0 11.5 7Z"></path>
</svg>
</template>

<template id="code-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-code">
    <path d="m11.28 3.22 4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.749.749 0 0 1-1.275-.326.749.749 0 0 1 .215-.734L13.94 8l-3.72-3.72a.749.749 0 0 1 .326-1.275.749.749 0 0 1 .734.215Zm-6.56 0a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042L2.06 8l3.72 3.72a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L.47 8.53a.75.75 0 0 1 0-1.06Z"></path>
</svg>
</template>

<template id="file-code-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-file-code">
    <path d="M4 1.75C4 .784 4.784 0 5.75 0h5.586c.464 0 .909.184 1.237.513l2.914 2.914c.329.328.513.773.513 1.237v8.586A1.75 1.75 0 0 1 14.25 15h-9a.75.75 0 0 1 0-1.5h9a.25.25 0 0 0 .25-.25V6h-2.75A1.75 1.75 0 0 1 10 4.25V1.5H5.75a.25.25 0 0 0-.25.25v2.5a.75.75 0 0 1-1.5 0Zm1.72 4.97a.75.75 0 0 1 1.06 0l2 2a.75.75 0 0 1 0 1.06l-2 2a.749.749 0 0 1-1.275-.326.749.749 0 0 1 .215-.734l1.47-1.47-1.47-1.47a.75.75 0 0 1 0-1.06ZM3.28 7.78 1.81 9.25l1.47 1.47a.751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018l-2-2a.75.75 0 0 1 0-1.06l2-2a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042Zm8.22-6.218V4.25c0 .138.112.25.25.25h2.688l-.011-.013-2.914-2.914-.013-.011Z"></path>
</svg>
</template>

<template id="history-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-history">
    <path d="m.427 1.927 1.215 1.215a8.002 8.002 0 1 1-1.6 5.685.75.75 0 1 1 1.493-.154 6.5 6.5 0 1 0 1.18-4.458l1.358 1.358A.25.25 0 0 1 3.896 6H.25A.25.25 0 0 1 0 5.75V2.104a.25.25 0 0 1 .427-.177ZM7.75 4a.75.75 0 0 1 .75.75v2.992l2.028.812a.75.75 0 0 1-.557 1.392l-2.5-1A.751.751 0 0 1 7 8.25v-3.5A.75.75 0 0 1 7.75 4Z"></path>
</svg>
</template>

<template id="repo-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-repo">
    <path d="M2 2.5A2.5 2.5 0 0 1 4.5 0h8.75a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h1.75v-2h-8a1 1 0 0 0-.714 1.7.75.75 0 1 1-1.072 1.05A2.495 2.495 0 0 1 2 11.5Zm10.5-1h-8a1 1 0 0 0-1 1v6.708A2.486 2.486 0 0 1 4.5 9h8ZM5 12.25a.25.25 0 0 1 .25-.25h3.5a.25.25 0 0 1 .25.25v3.25a.25.25 0 0 1-.4.2l-1.45-1.087a.249.249 0 0 0-.3 0L5.4 15.7a.25.25 0 0 1-.4-.2Z"></path>
</svg>
</template>

<template id="bookmark-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-bookmark">
    <path d="M3 2.75C3 1.784 3.784 1 4.75 1h6.5c.966 0 1.75.784 1.75 1.75v11.5a.75.75 0 0 1-1.227.579L8 11.722l-3.773 3.107A.751.751 0 0 1 3 14.25Zm1.75-.25a.25.25 0 0 0-.25.25v9.91l3.023-2.489a.75.75 0 0 1 .954 0l3.023 2.49V2.75a.25.25 0 0 0-.25-.25Z"></path>
</svg>
</template>

<template id="plus-circle-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-plus-circle">
    <path d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0 6.5 6.5 0 0 0-13 0Zm7.25-3.25v2.5h2.5a.75.75 0 0 1 0 1.5h-2.5v2.5a.75.75 0 0 1-1.5 0v-2.5h-2.5a.75.75 0 0 1 0-1.5h2.5v-2.5a.75.75 0 0 1 1.5 0Z"></path>
</svg>
</template>

<template id="circle-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-dot-fill">
    <path d="M8 4a4 4 0 1 1 0 8 4 4 0 0 1 0-8Z"></path>
</svg>
</template>

<template id="trash-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-trash">
    <path d="M11 1.75V3h2.25a.75.75 0 0 1 0 1.5H2.75a.75.75 0 0 1 0-1.5H5V1.75C5 .784 5.784 0 6.75 0h2.5C10.216 0 11 .784 11 1.75ZM4.496 6.675l.66 6.6a.25.25 0 0 0 .249.225h5.19a.25.25 0 0 0 .249-.225l.66-6.6a.75.75 0 0 1 1.492.149l-.66 6.6A1.748 1.748 0 0 1 10.595 15h-5.19a1.75 1.75 0 0 1-1.741-1.575l-.66-6.6a.75.75 0 1 1 1.492-.15ZM6.5 1.75V3h3V1.75a.25.25 0 0 0-.25-.25h-2.5a.25.25 0 0 0-.25.25Z"></path>
</svg>
</template>

<template id="team-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-people">
    <path d="M2 5.5a3.5 3.5 0 1 1 5.898 2.549 5.508 5.508 0 0 1 3.034 4.084.75.75 0 1 1-1.482.235 4 4 0 0 0-7.9 0 .75.75 0 0 1-1.482-.236A5.507 5.507 0 0 1 3.102 8.05 3.493 3.493 0 0 1 2 5.5ZM11 4a3.001 3.001 0 0 1 2.22 5.018 5.01 5.01 0 0 1 2.56 3.012.749.749 0 0 1-.885.954.752.752 0 0 1-.549-.514 3.507 3.507 0 0 0-2.522-2.372.75.75 0 0 1-.574-.73v-.352a.75.75 0 0 1 .416-.672A1.5 1.5 0 0 0 11 5.5.75.75 0 0 1 11 4Zm-5.5-.5a2 2 0 1 0-.001 3.999A2 2 0 0 0 5.5 3.5Z"></path>
</svg>
</template>

<template id="project-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-project">
    <path d="M1.75 0h12.5C15.216 0 16 .784 16 1.75v12.5A1.75 1.75 0 0 1 14.25 16H1.75A1.75 1.75 0 0 1 0 14.25V1.75C0 .784.784 0 1.75 0ZM1.5 1.75v12.5c0 .138.112.25.25.25h12.5a.25.25 0 0 0 .25-.25V1.75a.25.25 0 0 0-.25-.25H1.75a.25.25 0 0 0-.25.25ZM11.75 3a.75.75 0 0 1 .75.75v7.5a.75.75 0 0 1-1.5 0v-7.5a.75.75 0 0 1 .75-.75Zm-8.25.75a.75.75 0 0 1 1.5 0v5.5a.75.75 0 0 1-1.5 0ZM8 3a.75.75 0 0 1 .75.75v3.5a.75.75 0 0 1-1.5 0v-3.5A.75.75 0 0 1 8 3Z"></path>
</svg>
</template>

<template id="pencil-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-pencil">
    <path d="M11.013 1.427a1.75 1.75 0 0 1 2.474 0l1.086 1.086a1.75 1.75 0 0 1 0 2.474l-8.61 8.61c-.21.21-.47.364-.756.445l-3.251.93a.75.75 0 0 1-.927-.928l.929-3.25c.081-.286.235-.547.445-.758l8.61-8.61Zm.176 4.823L9.75 4.81l-6.286 6.287a.253.253 0 0 0-.064.108l-.558 1.953 1.953-.558a.253.253 0 0 0 .108-.064Zm1.238-3.763a.25.25 0 0 0-.354 0L10.811 3.75l1.439 1.44 1.263-1.263a.25.25 0 0 0 0-.354Z"></path>
</svg>
</template>

<template id="copilot-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copilot">
    <path d="M7.998 15.035c-4.562 0-7.873-2.914-7.998-3.749V9.338c.085-.628.677-1.686 1.588-2.065.013-.07.024-.143.036-.218.029-.183.06-.384.126-.612-.201-.508-.254-1.084-.254-1.656 0-.87.128-1.769.693-2.484.579-.733 1.494-1.124 2.724-1.261 1.206-.134 2.262.034 2.944.765.05.053.096.108.139.165.044-.057.094-.112.143-.165.682-.731 1.738-.899 2.944-.765 1.23.137 2.145.528 2.724 1.261.566.715.693 1.614.693 2.484 0 .572-.053 1.148-.254 1.656.066.228.098.429.126.612.012.076.024.148.037.218.924.385 1.522 1.471 1.591 2.095v1.872c0 .766-3.351 3.795-8.002 3.795Zm0-1.485c2.28 0 4.584-1.11 5.002-1.433V7.862l-.023-.116c-.49.21-1.075.291-1.727.291-1.146 0-2.059-.327-2.71-.991A3.222 3.222 0 0 1 8 6.303a3.24 3.24 0 0 1-.544.743c-.65.664-1.563.991-2.71.991-.652 0-1.236-.081-1.727-.291l-.023.116v4.255c.419.323 2.722 1.433 5.002 1.433ZM6.762 2.83c-.193-.206-.637-.413-1.682-.297-1.019.113-1.479.404-1.713.7-.247.312-.369.789-.369 1.554 0 .793.129 1.171.308 1.371.162.181.519.379 1.442.379.853 0 1.339-.235 1.638-.54.315-.322.527-.827.617-1.553.117-.935-.037-1.395-.241-1.614Zm4.155-.297c-1.044-.116-1.488.091-1.681.297-.204.219-.359.679-.242 1.614.091.726.303 1.231.618 1.553.299.305.784.54 1.638.54.922 0 1.28-.198 1.442-.379.179-.2.308-.578.308-1.371 0-.765-.123-1.242-.37-1.554-.233-.296-.693-.587-1.713-.7Z"></path><path d="M6.25 9.037a.75.75 0 0 1 .75.75v1.501a.75.75 0 0 1-1.5 0V9.787a.75.75 0 0 1 .75-.75Zm4.25.75v1.501a.75.75 0 0 1-1.5 0V9.787a.75.75 0 0 1 1.5 0Z"></path>
</svg>
</template>

<template id="copilot-error-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copilot-error">
    <path d="M16 11.24c0 .112-.072.274-.21.467L13 9.688V7.862l-.023-.116c-.49.21-1.075.291-1.727.291-.198 0-.388-.009-.571-.029L6.833 5.226a4.01 4.01 0 0 0 .17-.782c.117-.935-.037-1.395-.241-1.614-.193-.206-.637-.413-1.682-.297-.683.076-1.115.231-1.395.415l-1.257-.91c.579-.564 1.413-.877 2.485-.996 1.206-.134 2.262.034 2.944.765.05.053.096.108.139.165.044-.057.094-.112.143-.165.682-.731 1.738-.899 2.944-.765 1.23.137 2.145.528 2.724 1.261.566.715.693 1.614.693 2.484 0 .572-.053 1.148-.254 1.656.066.228.098.429.126.612.012.076.024.148.037.218.924.385 1.522 1.471 1.591 2.095Zm-5.083-8.707c-1.044-.116-1.488.091-1.681.297-.204.219-.359.679-.242 1.614.091.726.303 1.231.618 1.553.299.305.784.54 1.638.54.922 0 1.28-.198 1.442-.379.179-.2.308-.578.308-1.371 0-.765-.123-1.242-.37-1.554-.233-.296-.693-.587-1.713-.7Zm2.511 11.074c-1.393.776-3.272 1.428-5.43 1.428-4.562 0-7.873-2.914-7.998-3.749V9.338c.085-.628.677-1.686 1.588-2.065.013-.07.024-.143.036-.218.029-.183.06-.384.126-.612-.18-.455-.241-.963-.252-1.475L.31 4.107A.747.747 0 0 1 0 3.509V3.49a.748.748 0 0 1 .625-.73c.156-.026.306.047.435.139l14.667 10.578a.592.592 0 0 1 .227.264.752.752 0 0 1 .046.249v.022a.75.75 0 0 1-1.19.596Zm-1.367-.991L5.635 7.964a5.128 5.128 0 0 1-.889.073c-.652 0-1.236-.081-1.727-.291l-.023.116v4.255c.419.323 2.722 1.433 5.002 1.433 1.539 0 3.089-.505 4.063-.934Z"></path>
</svg>
</template>

<template id="workflow-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-workflow">
    <path d="M0 1.75C0 .784.784 0 1.75 0h3.5C6.216 0 7 .784 7 1.75v3.5A1.75 1.75 0 0 1 5.25 7H4v4a1 1 0 0 0 1 1h4v-1.25C9 9.784 9.784 9 10.75 9h3.5c.966 0 1.75.784 1.75 1.75v3.5A1.75 1.75 0 0 1 14.25 16h-3.5A1.75 1.75 0 0 1 9 14.25v-.75H5A2.5 2.5 0 0 1 2.5 11V7h-.75A1.75 1.75 0 0 1 0 5.25Zm1.75-.25a.25.25 0 0 0-.25.25v3.5c0 .138.112.25.25.25h3.5a.25.25 0 0 0 .25-.25v-3.5a.25.25 0 0 0-.25-.25Zm9 9a.25.25 0 0 0-.25.25v3.5c0 .138.112.25.25.25h3.5a.25.25 0 0 0 .25-.25v-3.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
</template>

<template id="book-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-book">
    <path d="M0 1.75A.75.75 0 0 1 .75 1h4.253c1.227 0 2.317.59 3 1.501A3.743 3.743 0 0 1 11.006 1h4.245a.75.75 0 0 1 .75.75v10.5a.75.75 0 0 1-.75.75h-4.507a2.25 2.25 0 0 0-1.591.659l-.622.621a.75.75 0 0 1-1.06 0l-.622-.621A2.25 2.25 0 0 0 5.258 13H.75a.75.75 0 0 1-.75-.75Zm7.251 10.324.004-5.073-.002-2.253A2.25 2.25 0 0 0 5.003 2.5H1.5v9h3.757a3.75 3.75 0 0 1 1.994.574ZM8.755 4.75l-.004 7.322a3.752 3.752 0 0 1 1.992-.572H14.5v-9h-3.495a2.25 2.25 0 0 0-2.25 2.25Z"></path>
</svg>
</template>

<template id="code-review-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-code-review">
    <path d="M1.75 1h12.5c.966 0 1.75.784 1.75 1.75v8.5A1.75 1.75 0 0 1 14.25 13H8.061l-2.574 2.573A1.458 1.458 0 0 1 3 14.543V13H1.75A1.75 1.75 0 0 1 0 11.25v-8.5C0 1.784.784 1 1.75 1ZM1.5 2.75v8.5c0 .138.112.25.25.25h2a.75.75 0 0 1 .75.75v2.19l2.72-2.72a.749.749 0 0 1 .53-.22h6.5a.25.25 0 0 0 .25-.25v-8.5a.25.25 0 0 0-.25-.25H1.75a.25.25 0 0 0-.25.25Zm5.28 1.72a.75.75 0 0 1 0 1.06L5.31 7l1.47 1.47a.751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018l-2-2a.75.75 0 0 1 0-1.06l2-2a.75.75 0 0 1 1.06 0Zm2.44 0a.75.75 0 0 1 1.06 0l2 2a.75.75 0 0 1 0 1.06l-2 2a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L10.69 7 9.22 5.53a.75.75 0 0 1 0-1.06Z"></path>
</svg>
</template>

<template id="codespaces-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-codespaces">
    <path d="M0 11.25c0-.966.784-1.75 1.75-1.75h12.5c.966 0 1.75.784 1.75 1.75v3A1.75 1.75 0 0 1 14.25 16H1.75A1.75 1.75 0 0 1 0 14.25Zm2-9.5C2 .784 2.784 0 3.75 0h8.5C13.216 0 14 .784 14 1.75v5a1.75 1.75 0 0 1-1.75 1.75h-8.5A1.75 1.75 0 0 1 2 6.75Zm1.75-.25a.25.25 0 0 0-.25.25v5c0 .138.112.25.25.25h8.5a.25.25 0 0 0 .25-.25v-5a.25.25 0 0 0-.25-.25Zm-2 9.5a.25.25 0 0 0-.25.25v3c0 .138.112.25.25.25h12.5a.25.25 0 0 0 .25-.25v-3a.25.25 0 0 0-.25-.25Z"></path><path d="M7 12.75a.75.75 0 0 1 .75-.75h4.5a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1-.75-.75Zm-4 0a.75.75 0 0 1 .75-.75h.5a.75.75 0 0 1 0 1.5h-.5a.75.75 0 0 1-.75-.75Z"></path>
</svg>
</template>

<template id="comment-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-comment">
    <path d="M1 2.75C1 1.784 1.784 1 2.75 1h10.5c.966 0 1.75.784 1.75 1.75v7.5A1.75 1.75 0 0 1 13.25 12H9.06l-2.573 2.573A1.458 1.458 0 0 1 4 13.543V12H2.75A1.75 1.75 0 0 1 1 10.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h2a.75.75 0 0 1 .75.75v2.19l2.72-2.72a.749.749 0 0 1 .53-.22h4.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
</template>

<template id="comment-discussion-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-comment-discussion">
    <path d="M1.75 1h8.5c.966 0 1.75.784 1.75 1.75v5.5A1.75 1.75 0 0 1 10.25 10H7.061l-2.574 2.573A1.458 1.458 0 0 1 2 11.543V10h-.25A1.75 1.75 0 0 1 0 8.25v-5.5C0 1.784.784 1 1.75 1ZM1.5 2.75v5.5c0 .138.112.25.25.25h1a.75.75 0 0 1 .75.75v2.19l2.72-2.72a.749.749 0 0 1 .53-.22h3.5a.25.25 0 0 0 .25-.25v-5.5a.25.25 0 0 0-.25-.25h-8.5a.25.25 0 0 0-.25.25Zm13 2a.25.25 0 0 0-.25-.25h-.5a.75.75 0 0 1 0-1.5h.5c.966 0 1.75.784 1.75 1.75v5.5A1.75 1.75 0 0 1 14.25 12H14v1.543a1.458 1.458 0 0 1-2.487 1.03L9.22 12.28a.749.749 0 0 1 .326-1.275.749.749 0 0 1 .734.215l2.22 2.22v-2.19a.75.75 0 0 1 .75-.75h1a.25.25 0 0 0 .25-.25Z"></path>
</svg>
</template>

<template id="organization-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-organization">
    <path d="M1.75 16A1.75 1.75 0 0 1 0 14.25V1.75C0 .784.784 0 1.75 0h8.5C11.216 0 12 .784 12 1.75v12.5c0 .085-.006.168-.018.25h2.268a.25.25 0 0 0 .25-.25V8.285a.25.25 0 0 0-.111-.208l-1.055-.703a.749.749 0 1 1 .832-1.248l1.055.703c.487.325.779.871.779 1.456v5.965A1.75 1.75 0 0 1 14.25 16h-3.5a.766.766 0 0 1-.197-.026c-.099.017-.2.026-.303.026h-3a.75.75 0 0 1-.75-.75V14h-1v1.25a.75.75 0 0 1-.75.75Zm-.25-1.75c0 .138.112.25.25.25H4v-1.25a.75.75 0 0 1 .75-.75h2.5a.75.75 0 0 1 .75.75v1.25h2.25a.25.25 0 0 0 .25-.25V1.75a.25.25 0 0 0-.25-.25h-8.5a.25.25 0 0 0-.25.25ZM3.75 6h.5a.75.75 0 0 1 0 1.5h-.5a.75.75 0 0 1 0-1.5ZM3 3.75A.75.75 0 0 1 3.75 3h.5a.75.75 0 0 1 0 1.5h-.5A.75.75 0 0 1 3 3.75Zm4 3A.75.75 0 0 1 7.75 6h.5a.75.75 0 0 1 0 1.5h-.5A.75.75 0 0 1 7 6.75ZM7.75 3h.5a.75.75 0 0 1 0 1.5h-.5a.75.75 0 0 1 0-1.5ZM3 9.75A.75.75 0 0 1 3.75 9h.5a.75.75 0 0 1 0 1.5h-.5A.75.75 0 0 1 3 9.75ZM7.75 9h.5a.75.75 0 0 1 0 1.5h-.5a.75.75 0 0 1 0-1.5Z"></path>
</svg>
</template>

<template id="rocket-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-rocket">
    <path d="M14.064 0h.186C15.216 0 16 .784 16 1.75v.186a8.752 8.752 0 0 1-2.564 6.186l-.458.459c-.314.314-.641.616-.979.904v3.207c0 .608-.315 1.172-.833 1.49l-2.774 1.707a.749.749 0 0 1-1.11-.418l-.954-3.102a1.214 1.214 0 0 1-.145-.125L3.754 9.816a1.218 1.218 0 0 1-.124-.145L.528 8.717a.749.749 0 0 1-.418-1.11l1.71-2.774A1.748 1.748 0 0 1 3.31 4h3.204c.288-.338.59-.665.904-.979l.459-.458A8.749 8.749 0 0 1 14.064 0ZM8.938 3.623h-.002l-.458.458c-.76.76-1.437 1.598-2.02 2.5l-1.5 2.317 2.143 2.143 2.317-1.5c.902-.583 1.74-1.26 2.499-2.02l.459-.458a7.25 7.25 0 0 0 2.123-5.127V1.75a.25.25 0 0 0-.25-.25h-.186a7.249 7.249 0 0 0-5.125 2.123ZM3.56 14.56c-.732.732-2.334 1.045-3.005 1.148a.234.234 0 0 1-.201-.064.234.234 0 0 1-.064-.201c.103-.671.416-2.273 1.15-3.003a1.502 1.502 0 1 1 2.12 2.12Zm6.94-3.935c-.088.06-.177.118-.266.175l-2.35 1.521.548 1.783 1.949-1.2a.25.25 0 0 0 .119-.213ZM3.678 8.116 5.2 5.766c.058-.09.117-.178.176-.266H3.309a.25.25 0 0 0-.213.119l-1.2 1.95ZM12 5a1 1 0 1 1-2 0 1 1 0 0 1 2 0Z"></path>
</svg>
</template>

<template id="shield-check-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-shield-check">
    <path d="m8.533.133 5.25 1.68A1.75 1.75 0 0 1 15 3.48V7c0 1.566-.32 3.182-1.303 4.682-.983 1.498-2.585 2.813-5.032 3.855a1.697 1.697 0 0 1-1.33 0c-2.447-1.042-4.049-2.357-5.032-3.855C1.32 10.182 1 8.566 1 7V3.48a1.75 1.75 0 0 1 1.217-1.667l5.25-1.68a1.748 1.748 0 0 1 1.066 0Zm-.61 1.429.001.001-5.25 1.68a.251.251 0 0 0-.174.237V7c0 1.36.275 2.666 1.057 3.859.784 1.194 2.121 2.342 4.366 3.298a.196.196 0 0 0 .154 0c2.245-.957 3.582-2.103 4.366-3.297C13.225 9.666 13.5 8.358 13.5 7V3.48a.25.25 0 0 0-.174-.238l-5.25-1.68a.25.25 0 0 0-.153 0ZM11.28 6.28l-3.5 3.5a.75.75 0 0 1-1.06 0l-1.5-1.5a.749.749 0 0 1 .326-1.275.749.749 0 0 1 .734.215l.97.97 2.97-2.97a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042Z"></path>
</svg>
</template>

<template id="heart-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-heart">
    <path d="m8 14.25.345.666a.75.75 0 0 1-.69 0l-.008-.004-.018-.01a7.152 7.152 0 0 1-.31-.17 22.055 22.055 0 0 1-3.434-2.414C2.045 10.731 0 8.35 0 5.5 0 2.836 2.086 1 4.25 1 5.797 1 7.153 1.802 8 3.02 8.847 1.802 10.203 1 11.75 1 13.914 1 16 2.836 16 5.5c0 2.85-2.045 5.231-3.885 6.818a22.066 22.066 0 0 1-3.744 2.584l-.018.01-.006.003h-.002ZM4.25 2.5c-1.336 0-2.75 1.164-2.75 3 0 2.15 1.58 4.144 3.365 5.682A20.58 20.58 0 0 0 8 13.393a20.58 20.58 0 0 0 3.135-2.211C12.92 9.644 14.5 7.65 14.5 5.5c0-1.836-1.414-3-2.75-3-1.373 0-2.609.986-3.029 2.456a.749.749 0 0 1-1.442 0C6.859 3.486 5.623 2.5 4.25 2.5Z"></path>
</svg>
</template>

<template id="server-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-server">
    <path d="M1.75 1h12.5c.966 0 1.75.784 1.75 1.75v4c0 .372-.116.717-.314 1 .198.283.314.628.314 1v4a1.75 1.75 0 0 1-1.75 1.75H1.75A1.75 1.75 0 0 1 0 12.75v-4c0-.358.109-.707.314-1a1.739 1.739 0 0 1-.314-1v-4C0 1.784.784 1 1.75 1ZM1.5 2.75v4c0 .138.112.25.25.25h12.5a.25.25 0 0 0 .25-.25v-4a.25.25 0 0 0-.25-.25H1.75a.25.25 0 0 0-.25.25Zm.25 5.75a.25.25 0 0 0-.25.25v4c0 .138.112.25.25.25h12.5a.25.25 0 0 0 .25-.25v-4a.25.25 0 0 0-.25-.25ZM7 4.75A.75.75 0 0 1 7.75 4h4.5a.75.75 0 0 1 0 1.5h-4.5A.75.75 0 0 1 7 4.75ZM7.75 10h4.5a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1 0-1.5ZM3 4.75A.75.75 0 0 1 3.75 4h.5a.75.75 0 0 1 0 1.5h-.5A.75.75 0 0 1 3 4.75ZM3.75 10h.5a.75.75 0 0 1 0 1.5h-.5a.75.75 0 0 1 0-1.5Z"></path>
</svg>
</template>

<template id="globe-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-globe">
    <path d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM5.78 8.75a9.64 9.64 0 0 0 1.363 4.177c.255.426.542.832.857 1.215.245-.296.551-.705.857-1.215A9.64 9.64 0 0 0 10.22 8.75Zm4.44-1.5a9.64 9.64 0 0 0-1.363-4.177c-.307-.51-.612-.919-.857-1.215a9.927 9.927 0 0 0-.857 1.215A9.64 9.64 0 0 0 5.78 7.25Zm-5.944 1.5H1.543a6.507 6.507 0 0 0 4.666 5.5c-.123-.181-.24-.365-.352-.552-.715-1.192-1.437-2.874-1.581-4.948Zm-2.733-1.5h2.733c.144-2.074.866-3.756 1.58-4.948.12-.197.237-.381.353-.552a6.507 6.507 0 0 0-4.666 5.5Zm10.181 1.5c-.144 2.074-.866 3.756-1.58 4.948-.12.197-.237.381-.353.552a6.507 6.507 0 0 0 4.666-5.5Zm2.733-1.5a6.507 6.507 0 0 0-4.666-5.5c.123.181.24.365.353.552.714 1.192 1.436 2.874 1.58 4.948Z"></path>
</svg>
</template>

<template id="issue-opened-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-issue-opened">
    <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3Z"></path><path d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0 6.5 6.5 0 0 0-13 0Z"></path>
</svg>
</template>

<template id="device-mobile-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-device-mobile">
    <path d="M3.75 0h8.5C13.216 0 14 .784 14 1.75v12.5A1.75 1.75 0 0 1 12.25 16h-8.5A1.75 1.75 0 0 1 2 14.25V1.75C2 .784 2.784 0 3.75 0ZM3.5 1.75v12.5c0 .138.112.25.25.25h8.5a.25.25 0 0 0 .25-.25V1.75a.25.25 0 0 0-.25-.25h-8.5a.25.25 0 0 0-.25.25ZM8 13a1 1 0 1 1 0-2 1 1 0 0 1 0 2Z"></path>
</svg>
</template>

<template id="package-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-package">
    <path d="m8.878.392 5.25 3.045c.54.314.872.89.872 1.514v6.098a1.75 1.75 0 0 1-.872 1.514l-5.25 3.045a1.75 1.75 0 0 1-1.756 0l-5.25-3.045A1.75 1.75 0 0 1 1 11.049V4.951c0-.624.332-1.201.872-1.514L7.122.392a1.75 1.75 0 0 1 1.756 0ZM7.875 1.69l-4.63 2.685L8 7.133l4.755-2.758-4.63-2.685a.248.248 0 0 0-.25 0ZM2.5 5.677v5.372c0 .09.047.171.125.216l4.625 2.683V8.432Zm6.25 8.271 4.625-2.683a.25.25 0 0 0 .125-.216V5.677L8.75 8.432Z"></path>
</svg>
</template>

<template id="credit-card-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-credit-card">
    <path d="M10.75 9a.75.75 0 0 0 0 1.5h1.5a.75.75 0 0 0 0-1.5h-1.5Z"></path><path d="M0 3.75C0 2.784.784 2 1.75 2h12.5c.966 0 1.75.784 1.75 1.75v8.5A1.75 1.75 0 0 1 14.25 14H1.75A1.75 1.75 0 0 1 0 12.25ZM14.5 6.5h-13v5.75c0 .138.112.25.25.25h12.5a.25.25 0 0 0 .25-.25Zm0-2.75a.25.25 0 0 0-.25-.25H1.75a.25.25 0 0 0-.25.25V5h13Z"></path>
</svg>
</template>

<template id="play-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-play">
    <path d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0 6.5 6.5 0 0 0-13 0Zm4.879-2.773 4.264 2.559a.25.25 0 0 1 0 .428l-4.264 2.559A.25.25 0 0 1 6 10.559V5.442a.25.25 0 0 1 .379-.215Z"></path>
</svg>
</template>

<template id="gift-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-gift">
    <path d="M2 2.75A2.75 2.75 0 0 1 4.75 0c.983 0 1.873.42 2.57 1.232.268.318.497.668.68 1.042.183-.375.411-.725.68-1.044C9.376.42 10.266 0 11.25 0a2.75 2.75 0 0 1 2.45 4h.55c.966 0 1.75.784 1.75 1.75v2c0 .698-.409 1.301-1 1.582v4.918A1.75 1.75 0 0 1 13.25 16H2.75A1.75 1.75 0 0 1 1 14.25V9.332C.409 9.05 0 8.448 0 7.75v-2C0 4.784.784 4 1.75 4h.55c-.192-.375-.3-.8-.3-1.25ZM7.25 9.5H2.5v4.75c0 .138.112.25.25.25h4.5Zm1.5 0v5h4.5a.25.25 0 0 0 .25-.25V9.5Zm0-4V8h5.5a.25.25 0 0 0 .25-.25v-2a.25.25 0 0 0-.25-.25Zm-7 0a.25.25 0 0 0-.25.25v2c0 .138.112.25.25.25h5.5V5.5h-5.5Zm3-4a1.25 1.25 0 0 0 0 2.5h2.309c-.233-.818-.542-1.401-.878-1.793-.43-.502-.915-.707-1.431-.707ZM8.941 4h2.309a1.25 1.25 0 0 0 0-2.5c-.516 0-1 .205-1.43.707-.337.392-.646.975-.879 1.793Z"></path>
</svg>
</template>

<template id="code-square-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-code-square">
    <path d="M0 1.75C0 .784.784 0 1.75 0h12.5C15.216 0 16 .784 16 1.75v12.5A1.75 1.75 0 0 1 14.25 16H1.75A1.75 1.75 0 0 1 0 14.25Zm1.75-.25a.25.25 0 0 0-.25.25v12.5c0 .138.112.25.25.25h12.5a.25.25 0 0 0 .25-.25V1.75a.25.25 0 0 0-.25-.25Zm7.47 3.97a.75.75 0 0 1 1.06 0l2 2a.75.75 0 0 1 0 1.06l-2 2a.749.749 0 0 1-1.275-.326.749.749 0 0 1 .215-.734L10.69 8 9.22 6.53a.75.75 0 0 1 0-1.06ZM6.78 6.53 5.31 8l1.47 1.47a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215l-2-2a.75.75 0 0 1 0-1.06l2-2a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042Z"></path>
</svg>
</template>

<template id="device-desktop-icon">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-device-desktop">
    <path d="M14.25 1c.966 0 1.75.784 1.75 1.75v7.5A1.75 1.75 0 0 1 14.25 12h-3.727c.099 1.041.52 1.872 1.292 2.757A.752.752 0 0 1 11.25 16h-6.5a.75.75 0 0 1-.565-1.243c.772-.885 1.192-1.716 1.292-2.757H1.75A1.75 1.75 0 0 1 0 10.25v-7.5C0 1.784.784 1 1.75 1ZM1.75 2.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h12.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25ZM9.018 12H6.982a5.72 5.72 0 0 1-.765 2.5h3.566a5.72 5.72 0 0 1-.765-2.5Z"></path>
</svg>
</template>

        <div class="position-relative">
                        <ul
              role="listbox"
              class="ActionListWrap QueryBuilder-ListWrap"
              aria-label="Suggestions"
              data-action="
                combobox-commit:query-builder#comboboxCommit
                mousedown:query-builder#resultsMousedown
              "
              data-target="query-builder.resultsList"
              data-persist-list=false
              id="query-builder-test-results"
              tabindex="-1"
            ></ul>

        </div>
      <div class="FormControl-inlineValidation" id="validation-b95f8799-44c9-47fc-b612-ab9d25404459" hidden="hidden">
        <span class="FormControl-inlineValidation--visual">
          <svg aria-hidden="true" height="12" viewBox="0 0 12 12" version="1.1" width="12" data-view-component="true" class="octicon octicon-alert-fill">
    <path d="M4.855.708c.5-.896 1.79-.896 2.29 0l4.675 8.351a1.312 1.312 0 0 1-1.146 1.954H1.33A1.313 1.313 0 0 1 .183 9.058ZM7 7V3H5v4Zm-1 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2Z"></path>
</svg>
        </span>
        <span></span>
</div>    </div>
    <div data-target="query-builder.screenReaderFeedback" aria-live="polite" aria-atomic="true" class="sr-only"></div>
</query-builder></form>
          <div class="d-flex flex-row color-fg-muted tmp-px-3 text-small color-bg-default search-feedback-prompt">
            <a target="_blank" href="https://docs.github.com/search-github/github-code-search/understanding-github-code-search-syntax" data-view-component="true" class="Link color-fg-accent text-normal ml-2 tmp-ml-2">Search syntax tips</a>            <div class="d-flex flex-1"></div>
          </div>
        </div>
</div>

    </div>
</modal-dialog></div>
  </div>
  <div data-action="click:qbsearch-input#retract" class="dark-backdrop position-fixed" hidden data-target="qbsearch-input.darkBackdrop"></div>
  <div class="color-fg-default">
    
<dialog-helper>
  <dialog data-target="qbsearch-input.feedbackDialog" data-action="close:qbsearch-input#handleDialogClose cancel:qbsearch-input#handleDialogClose" id="feedback-dialog" aria-modal="true" aria-labelledby="feedback-dialog-title" aria-describedby="feedback-dialog-description" data-view-component="true" class="Overlay Overlay-whenNarrow Overlay--size-medium Overlay--motion-scaleFade Overlay--disableScroll">
    <div data-view-component="true" class="Overlay-header">
  <div class="Overlay-headerContentWrap">
    <div class="Overlay-titleWrap">
      <h1 class="Overlay-title " id="feedback-dialog-title">
        Provide feedback
      </h1>
        
    </div>
    <div class="Overlay-actionWrap">
      <button data-close-dialog-id="feedback-dialog" aria-label="Close" aria-label="Close" type="button" data-view-component="true" class="close-button Overlay-closeButton"><svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l3.22 3.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-3.22 3.22a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z"></path>
</svg></button>
    </div>
  </div>
  
</div>
      <scrollable-region data-labelled-by="feedback-dialog-title">
        <div data-view-component="true" class="Overlay-body">        <!-- '"` --><!-- </textarea></xmp> --></option></form><form id="code-search-feedback-form" data-turbo="false" action="/search/feedback" accept-charset="UTF-8" method="post"><input type="hidden" data-csrf="true" name="authenticity_token" value="gPwRanU88PLbYuaw3vfRY7z2jm8PY/+mTO6ukKPy6RE0s9xfbOSWebvpsrYJX37M64MqinLBHRKOqfm61aD53A==" />
          <p>We read every piece of feedback, and take your input very seriously.</p>
          <textarea name="feedback" class="form-control width-full mb-2" style="height: 120px" id="feedback"></textarea>
          <input name="include_email" id="include_email" aria-label="Include my email address so I can be contacted" class="form-control mr-2" type="checkbox">
          <label for="include_email" style="font-weight: normal">Include my email address so I can be contacted</label>
</form></div>
      </scrollable-region>
      <div data-view-component="true" class="Overlay-footer Overlay-footer--alignEnd">          <button data-close-dialog-id="feedback-dialog" type="button" data-view-component="true" class="btn">    Cancel
</button>
          <button form="code-search-feedback-form" data-action="click:qbsearch-input#submitFeedback" type="submit" data-view-component="true" class="btn-primary btn">    Submit feedback
</button>
</div>
</dialog></dialog-helper>

    <custom-scopes data-target="qbsearch-input.customScopesManager">
    
<dialog-helper>
  <dialog data-target="custom-scopes.customScopesModalDialog" data-action="close:qbsearch-input#handleDialogClose cancel:qbsearch-input#handleDialogClose" id="custom-scopes-dialog" aria-modal="true" aria-labelledby="custom-scopes-dialog-title" aria-describedby="custom-scopes-dialog-description" data-view-component="true" class="Overlay Overlay-whenNarrow Overlay--size-medium Overlay--motion-scaleFade Overlay--disableScroll">
    <div data-view-component="true" class="Overlay-header Overlay-header--divided">
  <div class="Overlay-headerContentWrap">
    <div class="Overlay-titleWrap">
      <h1 class="Overlay-title " id="custom-scopes-dialog-title">
        Saved searches
      </h1>
        <h2 id="custom-scopes-dialog-description" class="Overlay-description">Use saved searches to filter your results more quickly</h2>
    </div>
    <div class="Overlay-actionWrap">
      <button data-close-dialog-id="custom-scopes-dialog" aria-label="Close" aria-label="Close" type="button" data-view-component="true" class="close-button Overlay-closeButton"><svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l3.22 3.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-3.22 3.22a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z"></path>
</svg></button>
    </div>
  </div>
  
</div>
      <scrollable-region data-labelled-by="custom-scopes-dialog-title">
        <div data-view-component="true" class="Overlay-body">        <div data-target="custom-scopes.customScopesModalDialogFlash"></div>

        <div hidden class="create-custom-scope-form" data-target="custom-scopes.createCustomScopeForm">
        <!-- '"` --><!-- </textarea></xmp> --></option></form><form id="custom-scopes-dialog-form" data-turbo="false" action="/search/custom_scopes" accept-charset="UTF-8" method="post"><input type="hidden" data-csrf="true" name="authenticity_token" value="lPjANtQ/vxpnGAUyC+L0GiMgN8uNTY5xMhQqwWW0jxxM5b7oK2HGcxrSwh/PbzgGSEG7RAQ8LSjBgLt3oIR5Xw==" />
          <div data-target="custom-scopes.customScopesModalDialogFlash"></div>

          <input type="hidden" id="custom_scope_id" name="custom_scope_id" data-target="custom-scopes.customScopesIdField">

          <div class="form-group">
            <label for="custom_scope_name">Name</label>
            <auto-check src="/search/custom_scopes/check_name" required>
              <input
                type="text"
                name="custom_scope_name"
                id="custom_scope_name"
                data-target="custom-scopes.customScopesNameField"
                class="form-control"
                autocomplete="off"
                placeholder="github-ruby"
                required
                maxlength="50">
              <input type="hidden" data-csrf="true" value="wjPMzx5QtexhDsp1FyjcEwZctru/KihPriguJK6LIwv5NU3ypokdJwjFMSpmw7//vDb2UW5hiJRB27SahYJDRg==" />
            </auto-check>
          </div>

          <div class="form-group">
            <label for="custom_scope_query">Query</label>
            <input
              type="text"
              name="custom_scope_query"
              id="custom_scope_query"
              data-target="custom-scopes.customScopesQueryField"
              class="form-control"
              autocomplete="off"
              placeholder="(repo:mona/a OR repo:mona/b) AND lang:python"
              required
              maxlength="500">
          </div>

          <p class="text-small color-fg-muted">
            To see all available qualifiers, see our <a class="Link--inTextBlock" href="https://docs.github.com/search-github/github-code-search/understanding-github-code-search-syntax">documentation</a>.
          </p>
</form>        </div>

        <div data-target="custom-scopes.manageCustomScopesForm">
          <div data-target="custom-scopes.list"></div>
        </div>

</div>
      </scrollable-region>
      <div data-view-component="true" class="Overlay-footer Overlay-footer--alignEnd Overlay-footer--divided">          <button data-action="click:custom-scopes#customScopesCancel" type="button" data-view-component="true" class="btn">    Cancel
</button>
          <button form="custom-scopes-dialog-form" data-action="click:custom-scopes#customScopesSubmit" data-target="custom-scopes.customScopesSubmitButton" type="submit" data-view-component="true" class="btn-primary btn">    Create saved search
</button>
</div>
</dialog></dialog-helper>
    </custom-scopes>
  </div>
</qbsearch-input>


            <div class="position-relative HeaderMenu-link-wrap d-lg-inline-block">
              <a
                href="/login?return_to=https%3A%2F%2Fgithub.com%2Frockbaer2007%2Fsidebar-card%2Fblob%2Fmain%2FREADME.md"
                class="HeaderMenu-link HeaderMenu-link--sign-in HeaderMenu-button flex-shrink-0 no-underline d-none d-lg-inline-flex border border-lg-0 rounded px-2 py-1"
                style="margin-left: 12px;"
                data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;site header menu&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;SIGN_UP&quot;,&quot;originating_url&quot;:&quot;https://github.com/rockbaer2007/sidebar-card/blob/main/README.md&quot;,&quot;user_id&quot;:null}}" data-hydro-click-hmac="1516e2112efa91dcf89addf8504fa1cc919923e5b362be342cc87b8762c0a846"
                data-analytics-event="{&quot;category&quot;:&quot;Marketing nav&quot;,&quot;action&quot;:&quot;click to go to homepage&quot;,&quot;label&quot;:&quot;ref_page:Marketing;ref_cta:Sign in;ref_loc:Header&quot;}"
              >
                Sign in
              </a>
            </div>

              <a href="/signup?ref_cta=Sign+up&amp;ref_loc=header+logged+out&amp;ref_page=%2F%3Cuser-name%3E%2F%3Crepo-name%3E%2Fblob%2Fshow&amp;source=header-repo&amp;source_repo=rockbaer2007%2Fsidebar-card"
                class="HeaderMenu-link HeaderMenu-link--sign-up HeaderMenu-button flex-shrink-0 d-flex d-lg-inline-flex no-underline border color-border-default rounded px-2 py-1"
                data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;site header menu&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;SIGN_UP&quot;,&quot;originating_url&quot;:&quot;https://github.com/rockbaer2007/sidebar-card/blob/main/README.md&quot;,&quot;user_id&quot;:null}}" data-hydro-click-hmac="1516e2112efa91dcf89addf8504fa1cc919923e5b362be342cc87b8762c0a846"
                data-analytics-event="{&quot;category&quot;:&quot;Sign up&quot;,&quot;action&quot;:&quot;click to sign up for account&quot;,&quot;label&quot;:&quot;ref_page:/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show;ref_cta:Sign up;ref_loc:header logged out&quot;}"
              >
                Sign up
              </a>

                <div class="AppHeader-appearanceSettings">
    <react-partial-anchor>
      <button data-target="react-partial-anchor.anchor" id="icon-button-6ad85d0c-428f-44a0-9671-5d8e9bf8c60c" aria-labelledby="tooltip-aecf8502-6808-41da-88a7-569019d13cae" type="button" disabled="disabled" data-view-component="true" class="Button Button--iconOnly Button--invisible Button--medium AppHeader-button HeaderMenu-link border cursor-wait">  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-sliders Button-visual">
    <path d="M15 2.75a.75.75 0 0 1-.75.75h-4a.75.75 0 0 1 0-1.5h4a.75.75 0 0 1 .75.75Zm-8.5.75v1.25a.75.75 0 0 0 1.5 0v-4a.75.75 0 0 0-1.5 0V2H1.75a.75.75 0 0 0 0 1.5H6.5Zm1.25 5.25a.75.75 0 0 0 0-1.5h-6a.75.75 0 0 0 0 1.5h6ZM15 8a.75.75 0 0 1-.75.75H11.5V10a.75.75 0 1 1-1.5 0V6a.75.75 0 0 1 1.5 0v1.25h2.75A.75.75 0 0 1 15 8Zm-9 5.25v-2a.75.75 0 0 0-1.5 0v1.25H1.75a.75.75 0 0 0 0 1.5H4.5v1.25a.75.75 0 0 0 1.5 0v-2Zm9 0a.75.75 0 0 1-.75.75h-6a.75.75 0 0 1 0-1.5h6a.75.75 0 0 1 .75.75Z"></path>
</svg>
</button><tool-tip id="tooltip-aecf8502-6808-41da-88a7-569019d13cae" for="icon-button-6ad85d0c-428f-44a0-9671-5d8e9bf8c60c" popover="manual" data-direction="s" data-type="label" data-view-component="true" class="sr-only position-absolute">Appearance settings</tool-tip>

      <template data-target="react-partial-anchor.template">
        <link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/primer-react-css.00ba154d21e54e53.module.css" />
<link crossorigin="anonymous" media="all" rel="stylesheet" href="https://github.githubassets.com/assets/appearance-settings.babbb060397858d0.module.css" />

<react-partial
  partial-name="appearance-settings"
  data-ssr="false"
  data-attempted-ssr="false"
  data-react-profiling="false"
>
  
  <script type="application/json" data-target="react-partial.embeddedData">{"props":{}}</script>
  <div data-target="react-partial.reactRoot"></div>
</react-partial>


      </template>
    </react-partial-anchor>
  </div>

          <button type="button" class="sr-only js-header-menu-focus-trap d-block d-lg-none">Resetting focus</button>
        </div>
      </div>
    </div>
  </div>
</header>

      <div hidden="hidden" data-view-component="true" class="js-stale-session-flash stale-session-flash flash flash-warn flash-full">
  
        <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-alert">
    <path d="M6.457 1.047c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0 1 14.082 15H1.918a1.75 1.75 0 0 1-1.543-2.575Zm1.763.707a.25.25 0 0 0-.44 0L1.698 13.132a.25.25 0 0 0 .22.368h12.164a.25.25 0 0 0 .22-.368Zm.53 3.996v2.5a.75.75 0 0 1-1.5 0v-2.5a.75.75 0 0 1 1.5 0ZM9 11a1 1 0 1 1-2 0 1 1 0 0 1 2 0Z"></path>
</svg>
        <span class="js-stale-session-flash-signed-in" hidden>You signed in with another tab or window. <a class="Link--inTextBlock" href="">Reload</a> to refresh your session.</span>
        <span class="js-stale-session-flash-signed-out" hidden>You signed out in another tab or window. <a class="Link--inTextBlock" href="">Reload</a> to refresh your session.</span>
        <span class="js-stale-session-flash-switched" hidden>You switched accounts on another tab or window. <a class="Link--inTextBlock" href="">Reload</a> to refresh your session.</span>

    <button id="icon-button-12034bab-3203-43fd-ba34-369b6a6e00a0" aria-labelledby="tooltip-ee41c1c3-6e4b-441b-be58-f397576a71a7" type="button" data-view-component="true" class="Button Button--iconOnly Button--invisible Button--medium flash-close js-flash-close">  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x Button-visual">
    <path d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l3.22 3.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-3.22 3.22a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z"></path>
</svg>
</button><tool-tip id="tooltip-ee41c1c3-6e4b-441b-be58-f397576a71a7" for="icon-button-12034bab-3203-43fd-ba34-369b6a6e00a0" popover="manual" data-direction="s" data-type="label" data-view-component="true" class="sr-only position-absolute">Dismiss alert</tool-tip>


  
</div>
    </div>

  <div id="start-of-content" class="show-on-focus"></div>








    <div id="js-flash-container" class="flash-container" data-turbo-replace>




  <template class="js-flash-template">
    
<div class="flash flash-full   {{ className }}">
  <div >
    <button autofocus class="flash-close js-flash-close" type="button" aria-label="Dismiss this message">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l3.22 3.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-3.22 3.22a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z"></path>
</svg>
    </button>
    <div aria-atomic="true" role="alert" class="js-flash-alert">
      
      <div>{{ message }}</div>

    </div>
  </div>
</div>
  </template>
</div>


    






  <div
    class="application-main "
    data-commit-hovercards-enabled
    data-discussion-hovercards-enabled
    data-issue-and-pr-hovercards-enabled
    data-project-hovercards-enabled
  >
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
    <main id="js-repo-pjax-container" >
      
      






  

  <div id="repository-container-header"  class="tmp-pt-3 hide-full-screen" style="background-color: var(--page-header-bgColor, var(--color-page-header-bg));" data-turbo-replace>

      <div class="d-flex flex-nowrap flex-justify-end tmp-mb-3  tmp-px-3 tmp-px-lg-5" style="gap: 1rem;">

        <div class="flex-auto min-width-0 width-fit">
            
  <div class=" d-flex flex-wrap flex-items-center wb-break-word f3 text-normal">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-repo-forked color-fg-muted mr-2 tmp-mr-2">
    <path d="M5 5.372v.878c0 .414.336.75.75.75h4.5a.75.75 0 0 0 .75-.75v-.878a2.25 2.25 0 1 1 1.5 0v.878a2.25 2.25 0 0 1-2.25 2.25h-1.5v2.128a2.251 2.251 0 1 1-1.5 0V8.5h-1.5A2.25 2.25 0 0 1 3.5 6.25v-.878a2.25 2.25 0 1 1 1.5 0ZM5 3.25a.75.75 0 1 0-1.5 0 .75.75 0 0 0 1.5 0Zm6.75.75a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5Zm-3 8.75a.75.75 0 1 0-1.5 0 .75.75 0 0 0 1.5 0Z"></path>
</svg>
    
    <span class="author flex-self-stretch" itemprop="author">
      <a class="url fn" rel="author" data-hovercard-type="user" data-hovercard-url="/users/rockbaer2007/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/rockbaer2007">
        rockbaer2007
</a>    </span>
    <span class="mx-1 flex-self-stretch color-fg-muted">/</span>
    <strong itemprop="name" class="mr-2 flex-self-stretch">
      <a data-pjax="#repo-content-pjax-container" data-turbo-frame="repo-content-turbo-frame" href="/rockbaer2007/sidebar-card">sidebar-card</a>
    </strong>

    <span></span><span class="Label Label--secondary v-align-middle mr-1">Public</span>
  </div>
    <span class="text-small lh-condensed-ultra no-wrap mt-1" data-repository-hovercards-enabled>
      forked from <a data-hovercard-type="repository" data-hovercard-url="/Bobsilvio/sidebar-card/hovercard" class="Link--inTextBlock" href="/Bobsilvio/sidebar-card">Bobsilvio/sidebar-card</a>
    </span>


        </div>

        <div id="repository-details-container" class="flex-shrink-0" data-turbo-replace style="max-width: 70%;">
            <ul class="pagehead-actions flex-shrink-0 d-none d-md-inline" style="padding: 2px 0;">
    
      

  <li>
            <a href="/login?return_to=%2Frockbaer2007%2Fsidebar-card" rel="nofollow" id="repository-details-watch-button" data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;notification subscription menu watch&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;LOG_IN&quot;,&quot;originating_url&quot;:&quot;https://github.com/rockbaer2007/sidebar-card/blob/main/README.md&quot;,&quot;user_id&quot;:null}}" data-hydro-click-hmac="77e5e3a1f64cfedec2d136ba4121f81f1b934cf26fe5a7f4cfc85413f5674e91" aria-label="You must be signed in to change notification settings" data-view-component="true" class="btn-sm btn">    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-bell mr-2 tmp-mr-2">
    <path d="M8 16a2 2 0 0 0 1.985-1.75c.017-.137-.097-.25-.235-.25h-3.5c-.138 0-.252.113-.235.25A2 2 0 0 0 8 16ZM3 5a5 5 0 0 1 10 0v2.947c0 .05.015.098.042.139l1.703 2.555A1.519 1.519 0 0 1 13.482 13H2.518a1.516 1.516 0 0 1-1.263-2.36l1.703-2.554A.255.255 0 0 0 3 7.947Zm5-3.5A3.5 3.5 0 0 0 4.5 5v2.947c0 .346-.102.683-.294.97l-1.703 2.556a.017.017 0 0 0-.003.01l.001.006c0 .002.002.004.004.006l.006.004.007.001h10.964l.007-.001.006-.004.004-.006.001-.007a.017.017 0 0 0-.003-.01l-1.703-2.554a1.745 1.745 0 0 1-.294-.97V5A3.5 3.5 0 0 0 8 1.5Z"></path>
</svg>Notifications
</a>    <tool-tip id="tooltip-e6bf699c-f899-4eac-a842-1096fd2c18ef" for="repository-details-watch-button" popover="manual" data-direction="s" data-type="description" data-view-component="true" class="sr-only position-absolute">You must be signed in to change notification settings</tool-tip>

  </li>

  <li>
          <a icon="repo-forked" id="fork-button" href="/login?return_to=%2Frockbaer2007%2Fsidebar-card" rel="nofollow" data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;repo details fork button&quot;,&quot;repository_id&quot;:1224309473,&quot;auth_type&quot;:&quot;LOG_IN&quot;,&quot;originating_url&quot;:&quot;https://github.com/rockbaer2007/sidebar-card/blob/main/README.md&quot;,&quot;user_id&quot;:null}}" data-hydro-click-hmac="395c7c5bd8229868ba169ac7a92cf1232c759967c7fa74e46ebc491938234abf" data-view-component="true" class="btn-sm btn">    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-repo-forked mr-2 tmp-mr-2">
    <path d="M5 5.372v.878c0 .414.336.75.75.75h4.5a.75.75 0 0 0 .75-.75v-.878a2.25 2.25 0 1 1 1.5 0v.878a2.25 2.25 0 0 1-2.25 2.25h-1.5v2.128a2.251 2.251 0 1 1-1.5 0V8.5h-1.5A2.25 2.25 0 0 1 3.5 6.25v-.878a2.25 2.25 0 1 1 1.5 0ZM5 3.25a.75.75 0 1 0-1.5 0 .75.75 0 0 0 1.5 0Zm6.75.75a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5Zm-3 8.75a.75.75 0 1 0-1.5 0 .75.75 0 0 0 1.5 0Z"></path>
</svg>Fork
    <span id="repo-network-counter" data-pjax-replace="true" data-turbo-replace="true" title="0" data-view-component="true" class="Counter">0</span>
</a>
  </li>

  <li>
        <div data-view-component="true" class="BtnGroup d-flex">
        <a href="/login?return_to=%2Frockbaer2007%2Fsidebar-card" rel="nofollow" data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;star button&quot;,&quot;repository_id&quot;:1224309473,&quot;auth_type&quot;:&quot;LOG_IN&quot;,&quot;originating_url&quot;:&quot;https://github.com/rockbaer2007/sidebar-card/blob/main/README.md&quot;,&quot;user_id&quot;:null}}" data-hydro-click-hmac="3809326b732be3e18dc0b63036ec845cff90f5c71e97c8a6dc15761d4d2baafd" aria-label="You must be signed in to star a repository" data-view-component="true" class="tooltipped tooltipped-sw btn-sm btn">    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-star v-align-text-bottom d-inline-block mr-2 tmp-mr-2">
    <path d="M8 .25a.75.75 0 0 1 .673.418l1.882 3.815 4.21.612a.75.75 0 0 1 .416 1.279l-3.046 2.97.719 4.192a.751.751 0 0 1-1.088.791L8 12.347l-3.766 1.98a.75.75 0 0 1-1.088-.79l.72-4.194L.818 6.374a.75.75 0 0 1 .416-1.28l4.21-.611L7.327.668A.75.75 0 0 1 8 .25Zm0 2.445L6.615 5.5a.75.75 0 0 1-.564.41l-3.097.45 2.24 2.184a.75.75 0 0 1 .216.664l-.528 3.084 2.769-1.456a.75.75 0 0 1 .698 0l2.77 1.456-.53-3.084a.75.75 0 0 1 .216-.664l2.24-2.183-3.096-.45a.75.75 0 0 1-.564-.41L8 2.694Z"></path>
</svg><span data-view-component="true" class="d-inline">
          Star
</span>          <span id="repo-stars-counter-star" aria-label="0 users starred this repository" data-singular-suffix="user starred this repository" data-plural-suffix="users starred this repository" data-turbo-replace="true" title="0" data-view-component="true" class="Counter js-social-count">0</span>
</a></div>
  </li>

</ul>

        </div>
      </div>

        <div id="responsive-meta-container" data-turbo-replace>
</div>


          <nav data-pjax="#js-repo-pjax-container" aria-label="Repository" data-view-component="true" class="js-repo-nav js-sidenav-container-pjax js-responsive-underlinenav overflow-hidden UnderlineNav px-3 tmp-px-3 px-md-4 tmp-px-md-4 px-lg-5 tmp-px-lg-5">

  <ul data-view-component="true" class="UnderlineNav-body list-style-none">
      <li data-view-component="true" class="d-inline-flex">
  <a id="code-tab" href="/rockbaer2007/sidebar-card" data-tab-item="i0code-tab" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages repo_deployments repo_attestations /rockbaer2007/sidebar-card" data-pjax="#repo-content-pjax-container" data-turbo-frame="repo-content-turbo-frame" data-hotkey="g c" data-command-id="repositories:go-to-code" data-react-nav="code-view" data-react-nav-anchor="code-view-repo-link" data-analytics-event="{&quot;category&quot;:&quot;Underline navbar&quot;,&quot;action&quot;:&quot;Click tab&quot;,&quot;label&quot;:&quot;Code&quot;,&quot;target&quot;:&quot;UNDERLINE_NAV.TAB&quot;}" aria-current="page" data-view-component="true" class="UnderlineNav-item no-wrap js-responsive-underlinenav-item js-selected-navigation-item selected">
    
              <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-code UnderlineNav-octicon d-none d-sm-inline">
    <path d="m11.28 3.22 4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.749.749 0 0 1-1.275-.326.749.749 0 0 1 .215-.734L13.94 8l-3.72-3.72a.749.749 0 0 1 .326-1.275.749.749 0 0 1 .734.215Zm-6.56 0a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042L2.06 8l3.72 3.72a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L.47 8.53a.75.75 0 0 1 0-1.06Z"></path>
</svg>
        <span data-content="Code">Code</span>
          <span id="code-repo-tab-count" data-pjax-replace="" data-turbo-replace="" title="Not available" data-view-component="true" class="Counter"></span>


    
</a></li>
      <li data-view-component="true" class="d-inline-flex">
  <a id="pull-requests-tab" href="/rockbaer2007/sidebar-card/pulls" data-tab-item="i1pull-requests-tab" data-selected-links="repo_pulls checks /rockbaer2007/sidebar-card/pulls" data-pjax="#repo-content-pjax-container" data-turbo-frame="repo-content-turbo-frame" data-hotkey="g p" data-command-id="repositories:go-to-pull-requests" data-analytics-event="{&quot;category&quot;:&quot;Underline navbar&quot;,&quot;action&quot;:&quot;Click tab&quot;,&quot;label&quot;:&quot;Pull requests&quot;,&quot;target&quot;:&quot;UNDERLINE_NAV.TAB&quot;}" data-view-component="true" class="UnderlineNav-item no-wrap js-responsive-underlinenav-item js-selected-navigation-item">
    
              <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-git-pull-request UnderlineNav-octicon d-none d-sm-inline">
    <path d="M1.5 3.25a2.25 2.25 0 1 1 3 2.122v5.256a2.251 2.251 0 1 1-1.5 0V5.372A2.25 2.25 0 0 1 1.5 3.25Zm5.677-.177L9.573.677A.25.25 0 0 1 10 .854V2.5h1A2.5 2.5 0 0 1 13.5 5v5.628a2.251 2.251 0 1 1-1.5 0V5a1 1 0 0 0-1-1h-1v1.646a.25.25 0 0 1-.427.177L7.177 3.427a.25.25 0 0 1 0-.354ZM3.75 2.5a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5Zm0 9.5a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5Zm8.25.75a.75.75 0 1 0 1.5 0 .75.75 0 0 0-1.5 0Z"></path>
</svg>
        <span data-content="Pull requests">Pull requests</span>
          <span id="pull-requests-repo-tab-count" data-pjax-replace="" data-turbo-replace="" title="0" hidden="hidden" data-view-component="true" class="Counter">0</span>


    
</a></li>
      <li data-view-component="true" class="d-inline-flex">
  <a id="actions-tab" href="/rockbaer2007/sidebar-card/actions" data-tab-item="i2actions-tab" data-selected-links="repo_actions /rockbaer2007/sidebar-card/actions" data-pjax="#repo-content-pjax-container" data-turbo-frame="repo-content-turbo-frame" data-hotkey="g a" data-command-id="repositories:go-to-actions" data-analytics-event="{&quot;category&quot;:&quot;Underline navbar&quot;,&quot;action&quot;:&quot;Click tab&quot;,&quot;label&quot;:&quot;Actions&quot;,&quot;target&quot;:&quot;UNDERLINE_NAV.TAB&quot;}" data-view-component="true" class="UnderlineNav-item no-wrap js-responsive-underlinenav-item js-selected-navigation-item">
    
              <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-play UnderlineNav-octicon d-none d-sm-inline">
    <path d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0 6.5 6.5 0 0 0-13 0Zm4.879-2.773 4.264 2.559a.25.25 0 0 1 0 .428l-4.264 2.559A.25.25 0 0 1 6 10.559V5.442a.25.25 0 0 1 .379-.215Z"></path>
</svg>
        <span data-content="Actions">Actions</span>
          <span id="actions-repo-tab-count" data-pjax-replace="" data-turbo-replace="" title="Not available" data-view-component="true" class="Counter"></span>


    
</a></li>
      <li data-view-component="true" class="d-inline-flex">
  <a id="projects-tab" href="/rockbaer2007/sidebar-card/projects" data-tab-item="i3projects-tab" data-selected-links="repo_projects new_repo_project repo_project /rockbaer2007/sidebar-card/projects" data-pjax="#repo-content-pjax-container" data-turbo-frame="repo-content-turbo-frame" data-hotkey="g b" data-command-id="repositories:go-to-projects" data-analytics-event="{&quot;category&quot;:&quot;Underline navbar&quot;,&quot;action&quot;:&quot;Click tab&quot;,&quot;label&quot;:&quot;Projects&quot;,&quot;target&quot;:&quot;UNDERLINE_NAV.TAB&quot;}" data-view-component="true" class="UnderlineNav-item no-wrap js-responsive-underlinenav-item js-selected-navigation-item">
    
              <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-table UnderlineNav-octicon d-none d-sm-inline">
    <path d="M0 1.75C0 .784.784 0 1.75 0h12.5C15.216 0 16 .784 16 1.75v12.5A1.75 1.75 0 0 1 14.25 16H1.75A1.75 1.75 0 0 1 0 14.25ZM6.5 6.5v8h7.75a.25.25 0 0 0 .25-.25V6.5Zm8-1.5V1.75a.25.25 0 0 0-.25-.25H6.5V5Zm-13 1.5v7.75c0 .138.112.25.25.25H5v-8ZM5 5V1.5H1.75a.25.25 0 0 0-.25.25V5Z"></path>
</svg>
        <span data-content="Projects">Projects</span>
          <span id="projects-repo-tab-count" data-pjax-replace="" data-turbo-replace="" title="Not available" data-view-component="true" class="Counter"></span>


    
</a></li>
      <li data-view-component="true" class="d-inline-flex">
  <a id="security-and-quality-tab" href="/rockbaer2007/sidebar-card/security" data-tab-item="i4security-and-quality-tab" data-selected-links="security overview alerts policy token_scanning code_scanning /rockbaer2007/sidebar-card/security" data-pjax="#repo-content-pjax-container" data-turbo-frame="repo-content-turbo-frame" data-hotkey="g s" data-command-id="repositories:go-to-security" data-analytics-event="{&quot;category&quot;:&quot;Underline navbar&quot;,&quot;action&quot;:&quot;Click tab&quot;,&quot;label&quot;:&quot;Security and quality&quot;,&quot;target&quot;:&quot;UNDERLINE_NAV.TAB&quot;}" data-view-component="true" class="UnderlineNav-item no-wrap js-responsive-underlinenav-item js-selected-navigation-item">
    
              <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-shield UnderlineNav-octicon d-none d-sm-inline">
    <path d="M7.467.133a1.748 1.748 0 0 1 1.066 0l5.25 1.68A1.75 1.75 0 0 1 15 3.48V7c0 1.566-.32 3.182-1.303 4.682-.983 1.498-2.585 2.813-5.032 3.855a1.697 1.697 0 0 1-1.33 0c-2.447-1.042-4.049-2.357-5.032-3.855C1.32 10.182 1 8.566 1 7V3.48a1.75 1.75 0 0 1 1.217-1.667Zm.61 1.429a.25.25 0 0 0-.153 0l-5.25 1.68a.25.25 0 0 0-.174.238V7c0 1.358.275 2.666 1.057 3.86.784 1.194 2.121 2.34 4.366 3.297a.196.196 0 0 0 .154 0c2.245-.956 3.582-2.104 4.366-3.298C13.225 9.666 13.5 8.36 13.5 7V3.48a.251.251 0 0 0-.174-.237l-5.25-1.68ZM8.75 4.75v3a.75.75 0 0 1-1.5 0v-3a.75.75 0 0 1 1.5 0ZM9 10.5a1 1 0 1 1-2 0 1 1 0 0 1 2 0Z"></path>
</svg>
        <span data-content="Security and quality">Security and quality</span>
          <span id="security-and-quality-repo-tab-count" data-pjax-replace="" data-turbo-replace="" title="0" hidden="hidden" data-view-component="true" class="Counter">0</span>


    
</a></li>
      <li data-view-component="true" class="d-inline-flex">
  <a id="insights-tab" href="/rockbaer2007/sidebar-card/pulse" data-tab-item="i5insights-tab" data-selected-links="repo_graphs repo_contributors dependency_graph dependabot_updates pulse people community /rockbaer2007/sidebar-card/pulse" data-pjax="#repo-content-pjax-container" data-turbo-frame="repo-content-turbo-frame" data-command-id="repositories:go-to-insights" data-analytics-event="{&quot;category&quot;:&quot;Underline navbar&quot;,&quot;action&quot;:&quot;Click tab&quot;,&quot;label&quot;:&quot;Insights&quot;,&quot;target&quot;:&quot;UNDERLINE_NAV.TAB&quot;}" data-view-component="true" class="UnderlineNav-item no-wrap js-responsive-underlinenav-item js-selected-navigation-item">
    
              <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-graph UnderlineNav-octicon d-none d-sm-inline">
    <path d="M1.5 1.75V13.5h13.75a.75.75 0 0 1 0 1.5H.75a.75.75 0 0 1-.75-.75V1.75a.75.75 0 0 1 1.5 0Zm14.28 2.53-5.25 5.25a.75.75 0 0 1-1.06 0L7 7.06 4.28 9.78a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042l3.25-3.25a.75.75 0 0 1 1.06 0L10 7.94l4.72-4.72a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042Z"></path>
</svg>
        <span data-content="Insights">Insights</span>
          <span id="insights-repo-tab-count" data-pjax-replace="" data-turbo-replace="" title="Not available" data-view-component="true" class="Counter"></span>


    
</a></li>
</ul>
    <div style="visibility:hidden;" data-view-component="true" class="UnderlineNav-actions js-responsive-underlinenav-overflow position-absolute pr-3 tmp-pr-3 pr-md-4 tmp-pr-md-4 pr-lg-5 tmp-pr-lg-5 right-0">      <action-menu data-select-variant="none" data-view-component="true">
  <focus-group direction="vertical" mnemonics retain>
    <button id="action-menu-f63f3ddd-88e6-4733-85ae-56b0e3502ce2-button" popovertarget="action-menu-f63f3ddd-88e6-4733-85ae-56b0e3502ce2-overlay" aria-controls="action-menu-f63f3ddd-88e6-4733-85ae-56b0e3502ce2-list" aria-haspopup="true" aria-labelledby="tooltip-7bdb54d0-5042-4b44-8926-6302cafa9f17" type="button" data-view-component="true" class="Button Button--iconOnly Button--secondary Button--medium UnderlineNav-item">  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-kebab-horizontal Button-visual">
    <path d="M8 9a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3ZM1.5 9a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3Zm13 0a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3Z"></path>
</svg>
</button><tool-tip id="tooltip-7bdb54d0-5042-4b44-8926-6302cafa9f17" for="action-menu-f63f3ddd-88e6-4733-85ae-56b0e3502ce2-button" popover="manual" data-direction="s" data-type="label" data-view-component="true" class="sr-only position-absolute">Additional navigation options</tool-tip>


<anchored-position data-target="action-menu.overlay" id="action-menu-f63f3ddd-88e6-4733-85ae-56b0e3502ce2-overlay" anchor="action-menu-f63f3ddd-88e6-4733-85ae-56b0e3502ce2-button" align="start" side="outside-bottom" anchor-offset="normal" popover="auto" data-view-component="true">
  <div data-view-component="true" class="Overlay Overlay--size-auto">
    
      <div data-view-component="true" class="Overlay-body Overlay-body--paddingNone">          <action-list>
  <div data-view-component="true">
    <ul aria-labelledby="action-menu-f63f3ddd-88e6-4733-85ae-56b0e3502ce2-button" id="action-menu-f63f3ddd-88e6-4733-85ae-56b0e3502ce2-list" role="menu" data-view-component="true" class="ActionListWrap--inset ActionListWrap">
        <li hidden="hidden" data-menu-item="i0code-tab" data-targets="action-list.items" role="none" data-view-component="true" class="ActionListItem">
    
    
    <a tabindex="-1" id="item-0488c418-7f40-453f-877e-a81a14fea1d2" href="/rockbaer2007/sidebar-card" role="menuitem" data-view-component="true" class="ActionListContent ActionListContent--visual16">
        <span class="ActionListItem-visual ActionListItem-visual--leading">
          <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-code">
    <path d="m11.28 3.22 4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.749.749 0 0 1-1.275-.326.749.749 0 0 1 .215-.734L13.94 8l-3.72-3.72a.749.749 0 0 1 .326-1.275.749.749 0 0 1 .734.215Zm-6.56 0a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042L2.06 8l3.72 3.72a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L.47 8.53a.75.75 0 0 1 0-1.06Z"></path>
</svg>
        </span>
      
        <span data-view-component="true" class="ActionListItem-label">
          Code
</span>      
</a>
  
</li>
        <li hidden="hidden" data-menu-item="i1pull-requests-tab" data-targets="action-list.items" role="none" data-view-component="true" class="ActionListItem">
    
    
    <a tabindex="-1" id="item-955fce14-1e30-4fe5-ae8e-112b0e1c157b" href="/rockbaer2007/sidebar-card/pulls" role="menuitem" data-view-component="true" class="ActionListContent ActionListContent--visual16">
        <span class="ActionListItem-visual ActionListItem-visual--leading">
          <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-git-pull-request">
    <path d="M1.5 3.25a2.25 2.25 0 1 1 3 2.122v5.256a2.251 2.251 0 1 1-1.5 0V5.372A2.25 2.25 0 0 1 1.5 3.25Zm5.677-.177L9.573.677A.25.25 0 0 1 10 .854V2.5h1A2.5 2.5 0 0 1 13.5 5v5.628a2.251 2.251 0 1 1-1.5 0V5a1 1 0 0 0-1-1h-1v1.646a.25.25 0 0 1-.427.177L7.177 3.427a.25.25 0 0 1 0-.354ZM3.75 2.5a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5Zm0 9.5a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5Zm8.25.75a.75.75 0 1 0 1.5 0 .75.75 0 0 0-1.5 0Z"></path>
</svg>
        </span>
      
        <span data-view-component="true" class="ActionListItem-label">
          Pull requests
</span>      
</a>
  
</li>
        <li hidden="hidden" data-menu-item="i2actions-tab" data-targets="action-list.items" role="none" data-view-component="true" class="ActionListItem">
    
    
    <a tabindex="-1" id="item-161c7ca8-5a88-41a3-b121-96ebd0d2e32e" href="/rockbaer2007/sidebar-card/actions" role="menuitem" data-view-component="true" class="ActionListContent ActionListContent--visual16">
        <span class="ActionListItem-visual ActionListItem-visual--leading">
          <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-play">
    <path d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0 6.5 6.5 0 0 0-13 0Zm4.879-2.773 4.264 2.559a.25.25 0 0 1 0 .428l-4.264 2.559A.25.25 0 0 1 6 10.559V5.442a.25.25 0 0 1 .379-.215Z"></path>
</svg>
        </span>
      
        <span data-view-component="true" class="ActionListItem-label">
          Actions
</span>      
</a>
  
</li>
        <li hidden="hidden" data-menu-item="i3projects-tab" data-targets="action-list.items" role="none" data-view-component="true" class="ActionListItem">
    
    
    <a tabindex="-1" id="item-8c009f92-5d4e-4803-89a3-4eb7fdcd567a" href="/rockbaer2007/sidebar-card/projects" role="menuitem" data-view-component="true" class="ActionListContent ActionListContent--visual16">
        <span class="ActionListItem-visual ActionListItem-visual--leading">
          <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-table">
    <path d="M0 1.75C0 .784.784 0 1.75 0h12.5C15.216 0 16 .784 16 1.75v12.5A1.75 1.75 0 0 1 14.25 16H1.75A1.75 1.75 0 0 1 0 14.25ZM6.5 6.5v8h7.75a.25.25 0 0 0 .25-.25V6.5Zm8-1.5V1.75a.25.25 0 0 0-.25-.25H6.5V5Zm-13 1.5v7.75c0 .138.112.25.25.25H5v-8ZM5 5V1.5H1.75a.25.25 0 0 0-.25.25V5Z"></path>
</svg>
        </span>
      
        <span data-view-component="true" class="ActionListItem-label">
          Projects
</span>      
</a>
  
</li>
        <li hidden="hidden" data-menu-item="i4security-and-quality-tab" data-targets="action-list.items" role="none" data-view-component="true" class="ActionListItem">
    
    
    <a tabindex="-1" id="item-605b1d8d-d538-42aa-972f-51be74c1e993" href="/rockbaer2007/sidebar-card/security" role="menuitem" data-view-component="true" class="ActionListContent ActionListContent--visual16">
        <span class="ActionListItem-visual ActionListItem-visual--leading">
          <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-shield">
    <path d="M7.467.133a1.748 1.748 0 0 1 1.066 0l5.25 1.68A1.75 1.75 0 0 1 15 3.48V7c0 1.566-.32 3.182-1.303 4.682-.983 1.498-2.585 2.813-5.032 3.855a1.697 1.697 0 0 1-1.33 0c-2.447-1.042-4.049-2.357-5.032-3.855C1.32 10.182 1 8.566 1 7V3.48a1.75 1.75 0 0 1 1.217-1.667Zm.61 1.429a.25.25 0 0 0-.153 0l-5.25 1.68a.25.25 0 0 0-.174.238V7c0 1.358.275 2.666 1.057 3.86.784 1.194 2.121 2.34 4.366 3.297a.196.196 0 0 0 .154 0c2.245-.956 3.582-2.104 4.366-3.298C13.225 9.666 13.5 8.36 13.5 7V3.48a.251.251 0 0 0-.174-.237l-5.25-1.68ZM8.75 4.75v3a.75.75 0 0 1-1.5 0v-3a.75.75 0 0 1 1.5 0ZM9 10.5a1 1 0 1 1-2 0 1 1 0 0 1 2 0Z"></path>
</svg>
        </span>
      
        <span data-view-component="true" class="ActionListItem-label">
          Security and quality
</span>      
</a>
  
</li>
        <li hidden="hidden" data-menu-item="i5insights-tab" data-targets="action-list.items" role="none" data-view-component="true" class="ActionListItem">
    
    
    <a tabindex="-1" id="item-d8804eaf-80c3-461d-ba36-e45d5e2b6f38" href="/rockbaer2007/sidebar-card/pulse" role="menuitem" data-view-component="true" class="ActionListContent ActionListContent--visual16">
        <span class="ActionListItem-visual ActionListItem-visual--leading">
          <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-graph">
    <path d="M1.5 1.75V13.5h13.75a.75.75 0 0 1 0 1.5H.75a.75.75 0 0 1-.75-.75V1.75a.75.75 0 0 1 1.5 0Zm14.28 2.53-5.25 5.25a.75.75 0 0 1-1.06 0L7 7.06 4.28 9.78a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042l3.25-3.25a.75.75 0 0 1 1.06 0L10 7.94l4.72-4.72a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042Z"></path>
</svg>
        </span>
      
        <span data-view-component="true" class="ActionListItem-label">
          Insights
</span>      
</a>
  
</li>
</ul>    
</div></action-list>


</div>
      
</div></anchored-position>  </focus-group>
</action-menu></div>
</nav>

  </div>
  



<turbo-frame id="repo-content-turbo-frame" target="_top" data-turbo-action="advance" class="">
    <div id="repo-content-pjax-container" class="repository-content " >
    



    
      
    








<react-app
  app-name="code-view"
  initial-path="/rockbaer2007/sidebar-card/blob/main/README.md"
  style="display: block; min-height: calc(100vh - 64px);"
  data-attempted-ssr="true"
  data-ssr="true"
  data-lazy="false"
  data-alternate="false"
  data-data-router-enabled="true"
  data-react-profiling="false"
>
  
  <script type="application/json" data-target="react-app.embeddedData">{"payload":{"codeViewBlobRoute":{"csv":null,"csvError":null,"headerInfo":{"toc":[{"level":2,"text":"Supportami / Support Me","anchor":"supportami--support-me","htmlText":"Supportami / Support Me"},{"level":1,"text":"🧭 Custom Sidebar \u0026 Header for Home Assistant","anchor":"-custom-sidebar--header-for-home-assistant","htmlText":"🧭 Custom Sidebar \u0026amp; Header for Home Assistant"},{"level":1,"text":"Header Flip Mode","anchor":"header-flip-mode","htmlText":"Header Flip Mode"},{"level":1,"text":"Header Push Mode","anchor":"header-push-mode","htmlText":"Header Push Mode"},{"level":2,"text":"📸 Screenshots","anchor":"-screenshots","htmlText":"📸 Screenshots"},{"level":2,"text":"⭐ Main Features","anchor":"-main-features","htmlText":"⭐ Main Features"},{"level":2,"text":"🖊️ Graphical Editor (Admin only)","anchor":"️-graphical-editor-admin-only","htmlText":"🖊️ Graphical Editor (Admin only)"},{"level":3,"text":"How to open it","anchor":"how-to-open-it","htmlText":"How to open it"},{"level":3,"text":"Editor tabs","anchor":"editor-tabs","htmlText":"Editor tabs"},{"level":3,"text":"Card editors","anchor":"card-editors","htmlText":"Card editors"},{"level":3,"text":"Save behaviour","anchor":"save-behaviour","htmlText":"Save behaviour"},{"level":1,"text":"📦 Installation","anchor":"-installation","htmlText":"📦 Installation"},{"level":2,"text":"HACS","anchor":"hacs","htmlText":"HACS"},{"level":2,"text":"","anchor":"","htmlText":""},{"level":2,"text":"Manual Install","anchor":"manual-install","htmlText":"Manual Install"},{"level":1,"text":"🚀 Basic Setup","anchor":"-basic-setup","htmlText":"🚀 Basic Setup"},{"level":1,"text":"🧭 Sidebar Configuration","anchor":"-sidebar-configuration","htmlText":"🧭 Sidebar Configuration"},{"level":2,"text":"🔧 Main Options","anchor":"-main-options","htmlText":"🔧 Main Options"},{"level":2,"text":"📐 Responsive Width","anchor":"-responsive-width","htmlText":"📐 Responsive Width"},{"level":1,"text":"📋 Sidebar Menu Items","anchor":"-sidebar-menu-items","htmlText":"📋 Sidebar Menu Items"},{"level":3,"text":"Actions Supported","anchor":"actions-supported","htmlText":"Actions Supported"},{"level":3,"text":"Extra Item Fields","anchor":"extra-item-fields","htmlText":"Extra Item Fields"},{"level":1,"text":"🎨 Menu Styles","anchor":"-menu-styles","htmlText":"🎨 Menu Styles"},{"level":2,"text":"Example — wide style","anchor":"example--wide-style","htmlText":"Example — wide style"},{"level":1,"text":"🧱 Header Configuration","anchor":"-header-configuration","htmlText":"🧱 Header Configuration"},{"level":2,"text":"🧩 Top Bar Modes (topMenuMode)","anchor":"-top-bar-modes-topmenumode","htmlText":"🧩 Top Bar Modes (topMenuMode)"},{"level":2,"text":"Header Menu Items","anchor":"header-menu-items","htmlText":"Header Menu Items"},{"level":2,"text":"Header Cards","anchor":"header-cards","htmlText":"Header Cards"},{"level":1,"text":"🎨 Styling \u0026 CSS Variables","anchor":"-styling--css-variables","htmlText":"🎨 Styling \u0026amp; CSS Variables"},{"level":2,"text":"🔷 GRID Mode (menuStyle: grid)","anchor":"-grid-mode-menustyle-grid","htmlText":"🔷 GRID Mode (menuStyle: grid)"},{"level":2,"text":"🟥 BUTTON Mode (menuStyle: buttons)","anchor":"-button-mode-menustyle-buttons","htmlText":"🟥 BUTTON Mode (menuStyle: buttons)"},{"level":2,"text":"🟩 WIDE Mode (menuStyle: wide)","anchor":"-wide-mode-menustyle-wide","htmlText":"🟩 WIDE Mode (menuStyle: wide)"},{"level":2,"text":"🧠 Common Sidebar Variables","anchor":"-common-sidebar-variables","htmlText":"🧠 Common Sidebar Variables"},{"level":2,"text":"🖼 Header Variables","anchor":"-header-variables","htmlText":"🖼 Header Variables"},{"level":1,"text":"🛠 Troubleshooting","anchor":"-troubleshooting","htmlText":"🛠 Troubleshooting"},{"level":1,"text":"❤️ Credits","anchor":"️-credits","htmlText":"❤️ Credits"},{"level":2,"text":"🔄 Header Top Menu Modes (NEW)","anchor":"-header-top-menu-modes-new","htmlText":"🔄 Header Top Menu Modes (NEW)"},{"level":3,"text":"🌀 Flip Mode","anchor":"-flip-mode","htmlText":"🌀 Flip Mode"},{"level":4,"text":"Configuration","anchor":"configuration","htmlText":"Configuration"},{"level":4,"text":"Trigger example","anchor":"trigger-example","htmlText":"Trigger example"}]},"issueTemplate":null,"discussionTemplate":null,"richText":"\u003carticle class=\"markdown-body entry-content container-lg\" itemprop=\"text\"\u003e\u003cp dir=\"auto\"\u003e\u003ca href=\"https://ko-fi.com/silviosmart\" rel=\"nofollow\"\u003e\u003cimg src=\"https://camo.githubusercontent.com/dc897cd523cd71e727b4f7b042cc28c34dcc2bc7c711a057c4772ff8449d2d45/68747470733a2f2f73746f726167652e6b6f2d66692e636f6d2f63646e2f67656e6572617465642f7a66736b6667716e662f323032352d30332d30375f726573742d37643831616364393031616266313031636264663534343433633338663666302d646c6d6d6f6e70682e6a7067\" alt=\"Sample\" data-canonical-src=\"https://storage.ko-fi.com/cdn/generated/zfskfgqnf/2025-03-07_rest-7d81acd901abf101cbdf54443c38f6f0-dlmmonph.jpg\" style=\"max-width: 100%;\"\u003e\u003c/a\u003e\u003c/p\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch2 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003eSupportami / Support Me\u003c/h2\u003e\u003ca id=\"user-content-supportami--support-me\" class=\"anchor\" aria-label=\"Permalink: Supportami / Support Me\" href=\"#supportami--support-me\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cp dir=\"auto\"\u003eSe ti piace il mio lavoro e vuoi che continui nello sviluppo delle card, puoi offrirmi un caffè.\u003cbr\u003e\nIf you like my work and want me to continue developing the cards, you can buy me a coffee.\u003c/p\u003e\n\u003cp dir=\"auto\"\u003e\u003ca href=\"https://www.paypal.com/donate/?hosted_button_id=Z6KY9V6BBZ4BN\" rel=\"nofollow\"\u003e\u003cimg src=\"https://camo.githubusercontent.com/44211f937e0611225f445aeffeebd12e631b9721db99c94915ae4266cdf685c2/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d50617950616c2d2532333030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465\" alt=\"PayPal\" data-canonical-src=\"https://img.shields.io/badge/Donate-PayPal-%2300457C?style=for-the-badge\u0026amp;logo=paypal\u0026amp;logoColor=white\" style=\"max-width: 100%;\"\u003e\u003c/a\u003e\u003c/p\u003e\n\u003cp dir=\"auto\"\u003eNon dimenticare di seguirmi sui social:\u003cbr\u003e\nDon't forget to follow me on social media:\u003c/p\u003e\n\u003cp dir=\"auto\"\u003e\u003ca href=\"https://www.tiktok.com/@silviosmartalexa\" rel=\"nofollow\"\u003e\u003cimg src=\"https://camo.githubusercontent.com/d5bfced6e5f9e720c61eb1191659b2778a9ee29c5971216e7bf65ea399a265f7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f466f6c6c6f775f54696b546f6b2d2532333030303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d74696b746f6b266c6f676f436f6c6f723d7768697465\" alt=\"TikTok\" data-canonical-src=\"https://img.shields.io/badge/Follow_TikTok-%23000000?style=for-the-badge\u0026amp;logo=tiktok\u0026amp;logoColor=white\" style=\"max-width: 100%;\"\u003e\u003c/a\u003e\u003c/p\u003e\n\u003cp dir=\"auto\"\u003e\u003ca href=\"https://www.instagram.com/silviosmartalexa\" rel=\"nofollow\"\u003e\u003cimg src=\"https://camo.githubusercontent.com/e32214b0c0ddda76f1faa3bfb9fe4cf5132ee2ecc2d30874714d40e58222f0bd/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f466f6c6c6f775f496e7374616772616d2d2532334531333036433f7374796c653d666f722d7468652d6261646765266c6f676f3d696e7374616772616d266c6f676f436f6c6f723d7768697465\" alt=\"Instagram\" data-canonical-src=\"https://img.shields.io/badge/Follow_Instagram-%23E1306C?style=for-the-badge\u0026amp;logo=instagram\u0026amp;logoColor=white\" style=\"max-width: 100%;\"\u003e\u003c/a\u003e\u003c/p\u003e\n\u003cp dir=\"auto\"\u003e\u003ca href=\"https://www.youtube.com/@silviosmartalexa\" rel=\"nofollow\"\u003e\u003cimg src=\"https://camo.githubusercontent.com/9f575870fb3161c74d2c8b743e2d12896b813a2350d31aa5263a38854d0d7a54/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5375627363726962655f596f75547562652d2532334646303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d796f7574756265266c6f676f436f6c6f723d7768697465\" alt=\"YouTube\" data-canonical-src=\"https://img.shields.io/badge/Subscribe_YouTube-%23FF0000?style=for-the-badge\u0026amp;logo=youtube\u0026amp;logoColor=white\" style=\"max-width: 100%;\"\u003e\u003c/a\u003e\u003c/p\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch1 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e🧭 Custom Sidebar \u0026amp; Header for Home Assistant\u003c/h1\u003e\u003ca id=\"user-content--custom-sidebar--header-for-home-assistant\" class=\"anchor\" aria-label=\"Permalink: 🧭 Custom Sidebar \u0026amp; Header for Home Assistant\" href=\"#-custom-sidebar--header-for-home-assistant\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cp dir=\"auto\"\u003e\u003ca href=\"/rockbaer2007/sidebar-card/blob/main/README.it.md\"\u003e🇮🇹 Italiano\u003c/a\u003e\u003c/p\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch1 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003eHeader Flip Mode\u003c/h1\u003e\u003ca id=\"user-content-header-flip-mode\" class=\"anchor\" aria-label=\"Permalink: Header Flip Mode\" href=\"#header-flip-mode\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cp dir=\"auto\"\u003e\u003ca target=\"_blank\" rel=\"noopener noreferrer\" href=\"/rockbaer2007/sidebar-card/blob/main/img/Header-Flip_Mode.gif\"\u003e\u003cimg src=\"/rockbaer2007/sidebar-card/raw/main/img/Header-Flip_Mode.gif\" alt=\"Header flip animation\" data-animated-image=\"\" style=\"max-width: 100%;\"\u003e\u003c/a\u003e\u003c/p\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch1 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003eHeader Push Mode\u003c/h1\u003e\u003ca id=\"user-content-header-push-mode\" class=\"anchor\" aria-label=\"Permalink: Header Push Mode\" href=\"#header-push-mode\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cp dir=\"auto\"\u003e\u003ca target=\"_blank\" rel=\"noopener noreferrer\" href=\"/rockbaer2007/sidebar-card/blob/main/img/Header-Push_Mode.gif\"\u003e\u003cimg src=\"/rockbaer2007/sidebar-card/raw/main/img/Header-Push_Mode.gif\" alt=\"Header push\" data-animated-image=\"\" style=\"max-width: 100%;\"\u003e\u003c/a\u003e\u003c/p\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch2 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e📸 Screenshots\u003c/h2\u003e\u003ca id=\"user-content--screenshots\" class=\"anchor\" aria-label=\"Permalink: 📸 Screenshots\" href=\"#-screenshots\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cp align=\"center\" dir=\"auto\"\u003e\n  \u003ca target=\"_blank\" rel=\"noopener noreferrer\" href=\"/rockbaer2007/sidebar-card/blob/main/img/1.PNG\"\u003e\u003cimg src=\"/rockbaer2007/sidebar-card/raw/main/img/1.PNG\" width=\"48%\" style=\"max-width: 100%;\"\u003e\u003c/a\u003e\n  \u003ca target=\"_blank\" rel=\"noopener noreferrer\" href=\"/rockbaer2007/sidebar-card/blob/main/img/2.PNG\"\u003e\u003cimg src=\"/rockbaer2007/sidebar-card/raw/main/img/2.PNG\" width=\"48%\" style=\"max-width: 100%;\"\u003e\u003c/a\u003e\n\u003c/p\u003e\n\u003cp align=\"center\" dir=\"auto\"\u003e\n  \u003ca target=\"_blank\" rel=\"noopener noreferrer\" href=\"/rockbaer2007/sidebar-card/blob/main/img/3.PNG\"\u003e\u003cimg src=\"/rockbaer2007/sidebar-card/raw/main/img/3.PNG\" width=\"48%\" style=\"max-width: 100%;\"\u003e\u003c/a\u003e\n  \u003ca target=\"_blank\" rel=\"noopener noreferrer\" href=\"/rockbaer2007/sidebar-card/blob/main/img/4.PNG\"\u003e\u003cimg src=\"/rockbaer2007/sidebar-card/raw/main/img/4.PNG\" width=\"48%\" style=\"max-width: 100%;\"\u003e\u003c/a\u003e\n\u003c/p\u003e\n\u003cp align=\"center\" dir=\"auto\"\u003e\n  \u003ca target=\"_blank\" rel=\"noopener noreferrer\" href=\"/rockbaer2007/sidebar-card/blob/main/img/5.PNG\"\u003e\u003cimg src=\"/rockbaer2007/sidebar-card/raw/main/img/5.PNG\" width=\"48%\" style=\"max-width: 100%;\"\u003e\u003c/a\u003e\n  \u003ca target=\"_blank\" rel=\"noopener noreferrer\" href=\"/rockbaer2007/sidebar-card/blob/main/img/6.PNG\"\u003e\u003cimg src=\"/rockbaer2007/sidebar-card/raw/main/img/6.PNG\" width=\"48%\" style=\"max-width: 100%;\"\u003e\u003c/a\u003e\n\u003c/p\u003e\n\u003cp dir=\"auto\"\u003eA fully‑customisable \u003cstrong\u003eHeader + Sidebar layout system for Home Assistant\u003c/strong\u003e, designed to be modern, flexible and responsive — while keeping full compatibility with Lovelace dashboards.\u003c/p\u003e\n\u003chr\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch2 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e⭐ Main Features\u003c/h2\u003e\u003ca id=\"user-content--main-features\" class=\"anchor\" aria-label=\"Permalink: ⭐ Main Features\" href=\"#-main-features\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cul dir=\"auto\"\u003e\n\u003cli\u003eResponsive sidebar width (mobile / tablet / desktop)\u003c/li\u003e\n\u003cli\u003eSticky / glass‑style header\u003c/li\u003e\n\u003cli\u003e\u003cstrong\u003e4 menu styles (list / wide / buttons / grid)\u003c/strong\u003e\u003c/li\u003e\n\u003cli\u003eConditional menu items\u003c/li\u003e\n\u003cli\u003ePer‑item colors and icons\u003c/li\u003e\n\u003cli\u003eOptional hiding of default HA sidebar + top bar\u003c/li\u003e\n\u003cli\u003eTemplate area for greetings / custom HTML\u003c/li\u003e\n\u003cli\u003eSupports any Lovelace card inside header \u0026amp; sidebar\u003c/li\u003e\n\u003cli\u003eWorks with kiosk‑mode setups\u003c/li\u003e\n\u003cli\u003eSafe — does \u003cstrong\u003enot\u003c/strong\u003e hack core Lovelace layout\u003c/li\u003e\n\u003cli\u003e🆕 \u003cstrong\u003eBuilt-in graphical editor\u003c/strong\u003e — configure Sidebar \u0026amp; Header without editing YAML manually\u003c/li\u003e\n\u003c/ul\u003e\n\u003chr\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch2 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e🖊️ Graphical Editor (Admin only)\u003c/h2\u003e\u003ca id=\"user-content-️-graphical-editor-admin-only\" class=\"anchor\" aria-label=\"Permalink: 🖊️ Graphical Editor (Admin only)\" href=\"#️-graphical-editor-admin-only\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cp align=\"center\" dir=\"auto\"\u003e\n  \u003ca target=\"_blank\" rel=\"noopener noreferrer\" href=\"/rockbaer2007/sidebar-card/blob/main/img/setting1.png\"\u003e\u003cimg src=\"/rockbaer2007/sidebar-card/raw/main/img/setting1.png\" width=\"28%\" style=\"max-width: 100%;\"\u003e\u003c/a\u003e\n  \u003ca target=\"_blank\" rel=\"noopener noreferrer\" href=\"/rockbaer2007/sidebar-card/blob/main/img/setting2.png\"\u003e\u003cimg src=\"/rockbaer2007/sidebar-card/raw/main/img/setting2.png\" width=\"48%\" style=\"max-width: 100%;\"\u003e\u003c/a\u003e\n\u003c/p\u003e\n\u003cp dir=\"auto\"\u003eAdministrators have access to a \u003cstrong\u003ebuilt-in visual editor\u003c/strong\u003e to configure Sidebar and Header without touching the YAML file.\u003c/p\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch3 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003eHow to open it\u003c/h3\u003e\u003ca id=\"user-content-how-to-open-it\" class=\"anchor\" aria-label=\"Permalink: How to open it\" href=\"#how-to-open-it\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cp dir=\"auto\"\u003eTwo ways:\u003c/p\u003e\n\u003col dir=\"auto\"\u003e\n\u003cli\u003e\u003cstrong\u003eToolbar button\u003c/strong\u003e — a dashboard-edit icon (🖊) appears in the top-right toolbar of HA when you are logged in as admin. Click it to open the editor panel.\u003c/li\u003e\n\u003cli\u003e\u003cstrong\u003eGear icon in the sidebar\u003c/strong\u003e — a small ⚙ icon at the bottom of the sidebar (visible only to admins) also opens the editor.\u003c/li\u003e\n\u003c/ol\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch3 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003eEditor tabs\u003c/h3\u003e\u003ca id=\"user-content-editor-tabs\" class=\"anchor\" aria-label=\"Permalink: Editor tabs\" href=\"#editor-tabs\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cmarkdown-accessiblity-table\u003e\u003ctable\u003e\n\u003cthead\u003e\n\u003ctr\u003e\n\u003cth\u003eTab\u003c/th\u003e\n\u003cth\u003eDescription\u003c/th\u003e\n\u003c/tr\u003e\n\u003c/thead\u003e\n\u003ctbody\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003cstrong\u003eSidebar\u003c/strong\u003e\u003c/td\u003e\n\u003ctd\u003eConfigure sidebar width, clock, date format, menu style, menu items, bottomCard and custom CSS\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003cstrong\u003eHeader\u003c/strong\u003e\u003c/td\u003e\n\u003ctd\u003eConfigure header height, sticky mode, topMenuMode, card slots (left / center / right), menus and custom CSS\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003cstrong\u003eYAML\u003c/strong\u003e\u003c/td\u003e\n\u003ctd\u003eDirect YAML editing of both configs — useful for power users or copy-paste workflows\u003c/td\u003e\n\u003c/tr\u003e\n\u003c/tbody\u003e\n\u003c/table\u003e\u003c/markdown-accessiblity-table\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch3 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003eCard editors\u003c/h3\u003e\u003ca id=\"user-content-card-editors\" class=\"anchor\" aria-label=\"Permalink: Card editors\" href=\"#card-editors\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cp dir=\"auto\"\u003eAll card fields (bottomCard, leftCard, centerCard, rightCard and stack items) use \u003cstrong\u003eYAML format\u003c/strong\u003e — the same format you already use in Home Assistant. Example:\u003c/p\u003e\n\u003cdiv class=\"highlight highlight-source-yaml notranslate position-relative overflow-auto\" dir=\"auto\" data-snippet-clipboard-copy-content=\"type: custom:button-card\nentity: light.living_room\nname: Living Room\nicon: mdi:sofa\"\u003e\u003cpre\u003e\u003cspan class=\"pl-ent\"\u003etype\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003ecustom:button-card\u003c/span\u003e\n\u003cspan class=\"pl-ent\"\u003eentity\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003elight.living_room\u003c/span\u003e\n\u003cspan class=\"pl-ent\"\u003ename\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003eLiving Room\u003c/span\u003e\n\u003cspan class=\"pl-ent\"\u003eicon\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003emdi:sofa\u003c/span\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch3 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003eSave behaviour\u003c/h3\u003e\u003ca id=\"user-content-save-behaviour\" class=\"anchor\" aria-label=\"Permalink: Save behaviour\" href=\"#save-behaviour\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cul dir=\"auto\"\u003e\n\u003cli\u003e\u003cstrong\u003eStorage mode (default)\u003c/strong\u003e: changes are saved directly to Lovelace via WebSocket and the page reloads automatically.\u003c/li\u003e\n\u003cli\u003e\u003cstrong\u003eYAML file mode\u003c/strong\u003e (\u003ccode\u003eui-lovelace.yaml\u003c/code\u003e): the editor generates a YAML snippet to copy-paste into your config file.\u003c/li\u003e\n\u003c/ul\u003e\n\u003chr\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch1 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e📦 Installation\u003c/h1\u003e\u003ca id=\"user-content--installation\" class=\"anchor\" aria-label=\"Permalink: 📦 Installation\" href=\"#-installation\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch2 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003eHACS\u003c/h2\u003e\u003ca id=\"user-content-hacs\" class=\"anchor\" aria-label=\"Permalink: HACS\" href=\"#hacs\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cp dir=\"auto\"\u003eThis integration can be installed manually or via HACS when available.\u003c/p\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch2 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e\u003ca href=\"https://my.home-assistant.io/redirect/hacs_repository/?owner=bobsilvio\u0026amp;repository=sidebar-card\u0026amp;category=plugin\" rel=\"nofollow\"\u003e\u003cimg src=\"https://camo.githubusercontent.com/49f849a6409cdcad49e32d41115ab078f810d960b35466436e028d4552aadd40/68747470733a2f2f6d792e686f6d652d617373697374616e742e696f2f6261646765732f686163735f7265706f7369746f72792e737667\" alt=\"Open in HACS\" data-canonical-src=\"https://my.home-assistant.io/badges/hacs_repository.svg\" style=\"max-width: 100%;\"\u003e\u003c/a\u003e\u003c/h2\u003e\u003ca id=\"\" class=\"anchor\" aria-label=\"Permalink: \" href=\"#\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch2 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003eManual Install\u003c/h2\u003e\u003ca id=\"user-content-manual-install\" class=\"anchor\" aria-label=\"Permalink: Manual Install\" href=\"#manual-install\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cp dir=\"auto\"\u003eCopy the JS file to:\u003c/p\u003e\n\u003cdiv class=\"snippet-clipboard-content notranslate position-relative overflow-auto\" data-snippet-clipboard-copy-content=\"/config/www/sidebar-card.js\"\u003e\u003cpre class=\"notranslate\"\u003e\u003ccode\u003e/config/www/sidebar-card.js\n\u003c/code\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003cp dir=\"auto\"\u003eThen add the resource:\u003c/p\u003e\n\u003cdiv class=\"highlight highlight-source-yaml notranslate position-relative overflow-auto\" dir=\"auto\" data-snippet-clipboard-copy-content=\"url: /local/sidebar-card.js\ntype: module\"\u003e\u003cpre\u003e\u003cspan class=\"pl-ent\"\u003eurl\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e/local/sidebar-card.js\u003c/span\u003e\n\u003cspan class=\"pl-ent\"\u003etype\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003emodule\u003c/span\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003cp dir=\"auto\"\u003eRestart or reload resources.\u003c/p\u003e\n\u003chr\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch1 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e🚀 Basic Setup\u003c/h1\u003e\u003ca id=\"user-content--basic-setup\" class=\"anchor\" aria-label=\"Permalink: 🚀 Basic Setup\" href=\"#-basic-setup\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cp dir=\"auto\"\u003eAdd to your \u003cstrong\u003edashboard YAML\u003c/strong\u003e:\u003c/p\u003e\n\u003cdiv class=\"highlight highlight-source-yaml notranslate position-relative overflow-auto\" dir=\"auto\" data-snippet-clipboard-copy-content=\"sidebar:\n  enabled: true\n  width: { mobile: 0, tablet: 16, desktop: 18 }\n\nheader:\n  enabled: true\n  sticky: true\n  height: 72\"\u003e\u003cpre\u003e\u003cspan class=\"pl-ent\"\u003esidebar\u003c/span\u003e:\n  \u003cspan class=\"pl-ent\"\u003eenabled\u003c/span\u003e: \u003cspan class=\"pl-c1\"\u003etrue\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003ewidth\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e{ mobile: 0, tablet: 16, desktop: 18 }\u003c/span\u003e\n\n\u003cspan class=\"pl-ent\"\u003eheader\u003c/span\u003e:\n  \u003cspan class=\"pl-ent\"\u003eenabled\u003c/span\u003e: \u003cspan class=\"pl-c1\"\u003etrue\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003esticky\u003c/span\u003e: \u003cspan class=\"pl-c1\"\u003etrue\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003eheight\u003c/span\u003e: \u003cspan class=\"pl-c1\"\u003e72\u003c/span\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003chr\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch1 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e🧭 Sidebar Configuration\u003c/h1\u003e\u003ca id=\"user-content--sidebar-configuration\" class=\"anchor\" aria-label=\"Permalink: 🧭 Sidebar Configuration\" href=\"#-sidebar-configuration\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch2 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e🔧 Main Options\u003c/h2\u003e\u003ca id=\"user-content--main-options\" class=\"anchor\" aria-label=\"Permalink: 🔧 Main Options\" href=\"#-main-options\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cmarkdown-accessiblity-table\u003e\u003ctable\u003e\n\u003cthead\u003e\n\u003ctr\u003e\n\u003cth\u003eOption\u003c/th\u003e\n\u003cth\u003eType\u003c/th\u003e\n\u003cth\u003eDefault\u003c/th\u003e\n\u003cth\u003eDescription\u003c/th\u003e\n\u003c/tr\u003e\n\u003c/thead\u003e\n\u003ctbody\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eenabled\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003ebool\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003etrue\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eEnables the custom sidebar\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003edebug\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003ebool\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003efalse\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eLog debug messages to console\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003etitle\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003estring\u003c/td\u003e\n\u003ctd\u003e\"\"\u003c/td\u003e\n\u003ctd\u003eOptional title text\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eclock\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003ebool\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003efalse\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eEnable analog clock\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003edigitalClock\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003ebool\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003efalse\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eEnable digital clock\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003edigitalClockWithSeconds\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003ebool\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003efalse\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eShow seconds in digital clock\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003etwelveHourVersion\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003ebool\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003efalse\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003e12‑hour clock format\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eperiod\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003ebool\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003efalse\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eShow AM / PM when using 12‑hour mode\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003edate\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003ebool\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003etrue\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eShow date\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003edateFormat\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003estring\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003eDD MMMM\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eMoment‑style format\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eupdateMenu\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003ebool\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003etrue\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eHighlight active menu item\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003ehideHassSidebar\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003ebool\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003efalse\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eHide default HA sidebar\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003ehideTopMenu\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003ebool\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003efalse\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eHide default HA top bar\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eshowTopMenuOnMobile\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003ebool\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003etrue\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eShow top bar only on mobile\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003ewidth\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003enumber/object\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003e18\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003e% width or responsive config\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003ebreakpoints.mobile\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eint\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003e767\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eMobile max width\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003ebreakpoints.tablet\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eint\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003e1024\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eTablet max width\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003ehideOnPath\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003elist\u003c/td\u003e\n\u003ctd\u003e—\u003c/td\u003e\n\u003ctd\u003ePaths where sidebar hides\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003emenuStyle\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003estring\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003elist\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003elist / wide / buttons / grid\u003c/code\u003e\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eshowLabel\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003ebool\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003etrue\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eShow menu text labels\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003etemplate\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eJinja2\u003c/td\u003e\n\u003ctd\u003e—\u003c/td\u003e\n\u003ctd\u003eHTML rendered above menu\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003ebottomCard\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eLovelace card\u003c/td\u003e\n\u003ctd\u003e—\u003c/td\u003e\n\u003ctd\u003eCard shown at bottom of sidebar\u003c/td\u003e\n\u003c/tr\u003e\n\u003c/tbody\u003e\n\u003c/table\u003e\u003c/markdown-accessiblity-table\u003e\n\u003chr\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch2 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e📐 Responsive Width\u003c/h2\u003e\u003ca id=\"user-content--responsive-width\" class=\"anchor\" aria-label=\"Permalink: 📐 Responsive Width\" href=\"#-responsive-width\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cdiv class=\"highlight highlight-source-yaml notranslate position-relative overflow-auto\" dir=\"auto\" data-snippet-clipboard-copy-content=\"width:\n  mobile: 0\n  tablet: 16\n  desktop: 18\"\u003e\u003cpre\u003e\u003cspan class=\"pl-ent\"\u003ewidth\u003c/span\u003e:\n  \u003cspan class=\"pl-ent\"\u003emobile\u003c/span\u003e: \u003cspan class=\"pl-c1\"\u003e0\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003etablet\u003c/span\u003e: \u003cspan class=\"pl-c1\"\u003e16\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003edesktop\u003c/span\u003e: \u003cspan class=\"pl-c1\"\u003e18\u003c/span\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003chr\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch1 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e📋 Sidebar Menu Items\u003c/h1\u003e\u003ca id=\"user-content--sidebar-menu-items\" class=\"anchor\" aria-label=\"Permalink: 📋 Sidebar Menu Items\" href=\"#-sidebar-menu-items\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cdiv class=\"highlight highlight-source-yaml notranslate position-relative overflow-auto\" dir=\"auto\" data-snippet-clipboard-copy-content=\"sidebarMenu:\n  - action: navigate\n    navigation_path: \u0026quot;/lovelace/home\u0026quot;\n    name: \u0026quot;Home\u0026quot;\n    icon: mdi:home\n    background_color: \u0026quot;var(--blue)\u0026quot;\n    icon_color: \u0026quot;#000\u0026quot;\n    text_color: \u0026quot;#000\u0026quot;\n    state: light.living_room\n    conditional: \u0026quot;{{ is_state('alarm_control_panel.house','disarmed') }}\u0026quot;\"\u003e\u003cpre\u003e\u003cspan class=\"pl-ent\"\u003esidebarMenu\u003c/span\u003e:\n  - \u003cspan class=\"pl-ent\"\u003eaction\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003enavigate\u003c/span\u003e\n    \u003cspan class=\"pl-ent\"\u003enavigation_path\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e/lovelace/home\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e\u003c/span\u003e\n    \u003cspan class=\"pl-ent\"\u003ename\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003eHome\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e\u003c/span\u003e\n    \u003cspan class=\"pl-ent\"\u003eicon\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003emdi:home\u003c/span\u003e\n    \u003cspan class=\"pl-ent\"\u003ebackground_color\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003evar(--blue)\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e\u003c/span\u003e\n    \u003cspan class=\"pl-ent\"\u003eicon_color\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e#000\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e\u003c/span\u003e\n    \u003cspan class=\"pl-ent\"\u003etext_color\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e#000\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e\u003c/span\u003e\n    \u003cspan class=\"pl-ent\"\u003estate\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003elight.living_room\u003c/span\u003e\n    \u003cspan class=\"pl-ent\"\u003econditional\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e{{ is_state('alarm_control_panel.house','disarmed') }}\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e\u003c/span\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch3 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003eActions Supported\u003c/h3\u003e\u003ca id=\"user-content-actions-supported\" class=\"anchor\" aria-label=\"Permalink: Actions Supported\" href=\"#actions-supported\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cmarkdown-accessiblity-table\u003e\u003ctable\u003e\n\u003cthead\u003e\n\u003ctr\u003e\n\u003cth\u003eAction\u003c/th\u003e\n\u003cth\u003eDescription\u003c/th\u003e\n\u003c/tr\u003e\n\u003c/thead\u003e\n\u003ctbody\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003enavigate\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eGo to a Lovelace view\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003emore-info\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eOpen entity dialog\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003etoggle\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eToggle entity\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003ecall-service\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eCall Home Assistant service\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eservice-js\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eExecute JavaScript\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eurl\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eOpen a URL\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003etoggle-sidebar\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eToggle the \u003cstrong\u003edefault HA sidebar\u003c/strong\u003e (drawer)\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003etoggle-topmenu\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eToggle the \u003cstrong\u003eHA top bar\u003c/strong\u003e (or trigger \u003ccode\u003eflip\u003c/code\u003e mode when enabled)\u003c/td\u003e\n\u003c/tr\u003e\n\u003c/tbody\u003e\n\u003c/table\u003e\u003c/markdown-accessiblity-table\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch3 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003eExtra Item Fields\u003c/h3\u003e\u003ca id=\"user-content-extra-item-fields\" class=\"anchor\" aria-label=\"Permalink: Extra Item Fields\" href=\"#extra-item-fields\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cmarkdown-accessiblity-table\u003e\u003ctable\u003e\n\u003cthead\u003e\n\u003ctr\u003e\n\u003cth\u003eField\u003c/th\u003e\n\u003cth\u003eDescription\u003c/th\u003e\n\u003c/tr\u003e\n\u003c/thead\u003e\n\u003ctbody\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003ename\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eLabel text\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eicon\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eMDI icon\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003ebackground_color\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eBackground colour\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eicon_color\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eIcon colour\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003etext_color\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eText colour\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003estate\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eEntity used to mark active state\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003econditional\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eWhen evaluates false → hides the item\u003c/td\u003e\n\u003c/tr\u003e\n\u003c/tbody\u003e\n\u003c/table\u003e\u003c/markdown-accessiblity-table\u003e\n\u003chr\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch1 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e🎨 Menu Styles\u003c/h1\u003e\u003ca id=\"user-content--menu-styles\" class=\"anchor\" aria-label=\"Permalink: 🎨 Menu Styles\" href=\"#-menu-styles\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cmarkdown-accessiblity-table\u003e\u003ctable\u003e\n\u003cthead\u003e\n\u003ctr\u003e\n\u003cth\u003e\u003ccode\u003emenuStyle\u003c/code\u003e\u003c/th\u003e\n\u003cth\u003eDescription\u003c/th\u003e\n\u003c/tr\u003e\n\u003c/thead\u003e\n\u003ctbody\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003elist\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eSimple legacy list style\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003ewide\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003e\u003cstrong\u003ePill‑style items with icon + label + colored background\u003c/strong\u003e\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003ebuttons\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eSquare button style (icon with optional label)\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003egrid\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eCompact app‑icon style grid\u003c/td\u003e\n\u003c/tr\u003e\n\u003c/tbody\u003e\n\u003c/table\u003e\u003c/markdown-accessiblity-table\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch2 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003eExample — wide style\u003c/h2\u003e\u003ca id=\"user-content-example--wide-style\" class=\"anchor\" aria-label=\"Permalink: Example — wide style\" href=\"#example--wide-style\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cdiv class=\"highlight highlight-source-yaml notranslate position-relative overflow-auto\" dir=\"auto\" data-snippet-clipboard-copy-content=\"sidebar:\n  menuStyle: wide\n  showLabel: true\"\u003e\u003cpre\u003e\u003cspan class=\"pl-ent\"\u003esidebar\u003c/span\u003e:\n  \u003cspan class=\"pl-ent\"\u003emenuStyle\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003ewide\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003eshowLabel\u003c/span\u003e: \u003cspan class=\"pl-c1\"\u003etrue\u003c/span\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003cdiv class=\"highlight highlight-source-yaml notranslate position-relative overflow-auto\" dir=\"auto\" data-snippet-clipboard-copy-content=\"- action: navigate\n  name: \u0026quot;Energy\u0026quot;\n  icon: mdi:solar-power-variant\n  navigation_path: \u0026quot;/energy\u0026quot;\n  background_color: \u0026quot;rgba(255, 200, 140, 0.95)\u0026quot;\n  icon_color: \u0026quot;#0f172a\u0026quot;\n  text_color: \u0026quot;#0f172a\u0026quot;\"\u003e\u003cpre\u003e- \u003cspan class=\"pl-ent\"\u003eaction\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003enavigate\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003ename\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003eEnergy\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003eicon\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003emdi:solar-power-variant\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003enavigation_path\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e/energy\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003ebackground_color\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003ergba(255, 200, 140, 0.95)\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003eicon_color\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e#0f172a\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003etext_color\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e#0f172a\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e\u003c/span\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003chr\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch1 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e🧱 Header Configuration\u003c/h1\u003e\u003ca id=\"user-content--header-configuration\" class=\"anchor\" aria-label=\"Permalink: 🧱 Header Configuration\" href=\"#-header-configuration\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cdiv class=\"highlight highlight-source-yaml notranslate position-relative overflow-auto\" dir=\"auto\" data-snippet-clipboard-copy-content=\"header:\n  enabled: true\n  sticky: true\n  height: 72                       # minimum header height (px)\n  headerMenuStyle: wide            # list / wide / buttons / grid (same as sidebar)\n  headerMenuShowLabel: true\n  headerMenuPosition: center       # left / center / right\n\n  # Home Assistant top bar behavior (optional)\n  topMenuMode: overlay             # overlay / push / flip\n  flipDuration: 5                  # seconds to keep HA top bar visible in flip mode\n\n  # Optional icon menus (left / right)\n  leftMenu:\n    - icon: mdi:menu\n      name: Sidebar\n      action: toggle-sidebar\n\n  rightMenu:\n    - icon: mdi:application\n      name: Top bar\n      action: toggle-topmenu\"\u003e\u003cpre\u003e\u003cspan class=\"pl-ent\"\u003eheader\u003c/span\u003e:\n  \u003cspan class=\"pl-ent\"\u003eenabled\u003c/span\u003e: \u003cspan class=\"pl-c1\"\u003etrue\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003esticky\u003c/span\u003e: \u003cspan class=\"pl-c1\"\u003etrue\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003eheight\u003c/span\u003e: \u003cspan class=\"pl-c1\"\u003e72\u003c/span\u003e                       \u003cspan class=\"pl-c\"\u003e\u003cspan class=\"pl-c\"\u003e#\u003c/span\u003e minimum header height (px)\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003eheaderMenuStyle\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003ewide            \u003c/span\u003e\u003cspan class=\"pl-c\"\u003e\u003cspan class=\"pl-c\"\u003e#\u003c/span\u003e list / wide / buttons / grid (same as sidebar)\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003eheaderMenuShowLabel\u003c/span\u003e: \u003cspan class=\"pl-c1\"\u003etrue\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003eheaderMenuPosition\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003ecenter       \u003c/span\u003e\u003cspan class=\"pl-c\"\u003e\u003cspan class=\"pl-c\"\u003e#\u003c/span\u003e left / center / right\u003c/span\u003e\n\n  \u003cspan class=\"pl-c\"\u003e\u003cspan class=\"pl-c\"\u003e#\u003c/span\u003e Home Assistant top bar behavior (optional)\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003etopMenuMode\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003eoverlay             \u003c/span\u003e\u003cspan class=\"pl-c\"\u003e\u003cspan class=\"pl-c\"\u003e#\u003c/span\u003e overlay / push / flip\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003eflipDuration\u003c/span\u003e: \u003cspan class=\"pl-c1\"\u003e5\u003c/span\u003e                  \u003cspan class=\"pl-c\"\u003e\u003cspan class=\"pl-c\"\u003e#\u003c/span\u003e seconds to keep HA top bar visible in flip mode\u003c/span\u003e\n\n  \u003cspan class=\"pl-c\"\u003e\u003cspan class=\"pl-c\"\u003e#\u003c/span\u003e Optional icon menus (left / right)\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003eleftMenu\u003c/span\u003e:\n    - \u003cspan class=\"pl-ent\"\u003eicon\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003emdi:menu\u003c/span\u003e\n      \u003cspan class=\"pl-ent\"\u003ename\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003eSidebar\u003c/span\u003e\n      \u003cspan class=\"pl-ent\"\u003eaction\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003etoggle-sidebar\u003c/span\u003e\n\n  \u003cspan class=\"pl-ent\"\u003erightMenu\u003c/span\u003e:\n    - \u003cspan class=\"pl-ent\"\u003eicon\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003emdi:application\u003c/span\u003e\n      \u003cspan class=\"pl-ent\"\u003ename\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003eTop bar\u003c/span\u003e\n      \u003cspan class=\"pl-ent\"\u003eaction\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003etoggle-topmenu\u003c/span\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003cmarkdown-accessiblity-table\u003e\u003ctable\u003e\n\u003cthead\u003e\n\u003ctr\u003e\n\u003cth\u003eOption\u003c/th\u003e\n\u003cth\u003eType\u003c/th\u003e\n\u003cth\u003eDefault\u003c/th\u003e\n\u003cth\u003eDescription\u003c/th\u003e\n\u003c/tr\u003e\n\u003c/thead\u003e\n\u003ctbody\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eenabled\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003ebool\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003etrue\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eEnable custom header\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003esticky\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003ebool\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003etrue\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eMake header sticky to the top\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eheight\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eint\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003e72\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eMinimum header height in pixels (can grow with content)\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003estyle\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003estring\u003c/td\u003e\n\u003ctd\u003e—\u003c/td\u003e\n\u003ctd\u003eExtra CSS applied inside the header-card (supports \u003ccode\u003e:host { ... }\u003c/code\u003e)\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003etopMenuMode\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003estring\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003eoverlay\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eHow to handle HA default top bar: \u003ccode\u003eoverlay\u003c/code\u003e, \u003ccode\u003epush\u003c/code\u003e, or \u003ccode\u003eflip\u003c/code\u003e\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eflipDuration\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003enumber\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003e5\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003e\u003cstrong\u003eFlip mode only\u003c/strong\u003e: seconds to keep HA top bar visible before flipping back\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eheaderMenuStyle\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003estring\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003ewide\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eHeader menu style (\u003ccode\u003elist / wide / buttons / grid\u003c/code\u003e)\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eheaderMenuShowLabel\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003ebool\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003etrue\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eShow text labels in header menu\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eheaderMenuPosition\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003estring\u003c/td\u003e\n\u003ctd\u003e\u003ccode\u003eright\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003ePlace header menu in \u003ccode\u003eleft / center / right\u003c/code\u003e area\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eleftMenu\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003elist\u003c/td\u003e\n\u003ctd\u003e—\u003c/td\u003e\n\u003ctd\u003eIcon buttons shown on the far left (e.g. toggle sidebar)\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003erightMenu\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003elist\u003c/td\u003e\n\u003ctd\u003e—\u003c/td\u003e\n\u003ctd\u003eIcon buttons shown on the far right (e.g. toggle top bar)\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eheaderMenu\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003elist\u003c/td\u003e\n\u003ctd\u003e—\u003c/td\u003e\n\u003ctd\u003eMain header menu (styled buttons)\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eleftCard\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eLovelace card\u003c/td\u003e\n\u003ctd\u003e—\u003c/td\u003e\n\u003ctd\u003eAny Lovelace card rendered in the left slot\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003ecenterCard\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eLovelace card\u003c/td\u003e\n\u003ctd\u003e—\u003c/td\u003e\n\u003ctd\u003eAny Lovelace card rendered in the center slot\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003erightCard\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eLovelace card\u003c/td\u003e\n\u003ctd\u003e—\u003c/td\u003e\n\u003ctd\u003eAny Lovelace card rendered in the right slot\u003c/td\u003e\n\u003c/tr\u003e\n\u003c/tbody\u003e\n\u003c/table\u003e\u003c/markdown-accessiblity-table\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch2 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e🧩 Top Bar Modes (\u003ccode\u003etopMenuMode\u003c/code\u003e)\u003c/h2\u003e\u003ca id=\"user-content--top-bar-modes-topmenumode\" class=\"anchor\" aria-label=\"Permalink: 🧩 Top Bar Modes (topMenuMode)\" href=\"#-top-bar-modes-topmenumode\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cul dir=\"auto\"\u003e\n\u003cli\u003e\u003cstrong\u003e\u003ccode\u003eoverlay\u003c/code\u003e (default)\u003c/strong\u003e: your header stays visible; HA top bar can be shown/hidden without pushing the view.\u003c/li\u003e\n\u003cli\u003e\u003cstrong\u003e\u003ccode\u003epush\u003c/code\u003e\u003c/strong\u003e: when HA top bar is visible, the content is pushed down using the real top bar height.\u003c/li\u003e\n\u003cli\u003e\u003cstrong\u003e\u003ccode\u003eflip\u003c/code\u003e\u003c/strong\u003e: your header “flips” to reveal HA top bar for a few seconds, then flips back. Use \u003ccode\u003eflipDuration\u003c/code\u003e to control how long HA top bar stays visible.\u003c/li\u003e\n\u003c/ul\u003e\n\u003cp dir=\"auto\"\u003eTo trigger the behavior, use a menu item with:\u003c/p\u003e\n\u003cdiv class=\"highlight highlight-source-yaml notranslate position-relative overflow-auto\" dir=\"auto\" data-snippet-clipboard-copy-content=\"action: toggle-topmenu\"\u003e\u003cpre\u003e\u003cspan class=\"pl-ent\"\u003eaction\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003etoggle-topmenu\u003c/span\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch2 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003eHeader Menu Items\u003c/h2\u003e\u003ca id=\"user-content-header-menu-items\" class=\"anchor\" aria-label=\"Permalink: Header Menu Items\" href=\"#header-menu-items\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cdiv class=\"highlight highlight-source-yaml notranslate position-relative overflow-auto\" dir=\"auto\" data-snippet-clipboard-copy-content=\"headerMenu:\n  - action: navigate\n    name: \u0026quot;Home\u0026quot;\n    icon: mdi:home\n    navigation_path: \u0026quot;/lovelace/home\u0026quot;\n    background_color: \u0026quot;rgba(205,255,190,.95)\u0026quot;\n    icon_color: \u0026quot;#0f172a\u0026quot;\n    text_color: \u0026quot;#0f172a\u0026quot;\"\u003e\u003cpre\u003e\u003cspan class=\"pl-ent\"\u003eheaderMenu\u003c/span\u003e:\n  - \u003cspan class=\"pl-ent\"\u003eaction\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003enavigate\u003c/span\u003e\n    \u003cspan class=\"pl-ent\"\u003ename\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003eHome\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e\u003c/span\u003e\n    \u003cspan class=\"pl-ent\"\u003eicon\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003emdi:home\u003c/span\u003e\n    \u003cspan class=\"pl-ent\"\u003enavigation_path\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e/lovelace/home\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e\u003c/span\u003e\n    \u003cspan class=\"pl-ent\"\u003ebackground_color\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003ergba(205,255,190,.95)\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e\u003c/span\u003e\n    \u003cspan class=\"pl-ent\"\u003eicon_color\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e#0f172a\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e\u003c/span\u003e\n    \u003cspan class=\"pl-ent\"\u003etext_color\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e#0f172a\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e\u003c/span\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003chr\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch2 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003eHeader Cards\u003c/h2\u003e\u003ca id=\"user-content-header-cards\" class=\"anchor\" aria-label=\"Permalink: Header Cards\" href=\"#header-cards\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cdiv class=\"highlight highlight-source-yaml notranslate position-relative overflow-auto\" dir=\"auto\" data-snippet-clipboard-copy-content=\"leftCard:\n  type: ...\ncenterCard:\n  type: ...\nrightCard:\n  type: ...\"\u003e\u003cpre\u003e\u003cspan class=\"pl-ent\"\u003eleftCard\u003c/span\u003e:\n  \u003cspan class=\"pl-ent\"\u003etype\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e...\u003c/span\u003e\n\u003cspan class=\"pl-ent\"\u003ecenterCard\u003c/span\u003e:\n  \u003cspan class=\"pl-ent\"\u003etype\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e...\u003c/span\u003e\n\u003cspan class=\"pl-ent\"\u003erightCard\u003c/span\u003e:\n  \u003cspan class=\"pl-ent\"\u003etype\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e...\u003c/span\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003cp dir=\"auto\"\u003eSupports \u003cstrong\u003eany Lovelace card\u003c/strong\u003e.\u003c/p\u003e\n\u003chr\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch1 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e🎨 Styling \u0026amp; CSS Variables\u003c/h1\u003e\u003ca id=\"user-content--styling--css-variables\" class=\"anchor\" aria-label=\"Permalink: 🎨 Styling \u0026amp; CSS Variables\" href=\"#-styling--css-variables\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cp dir=\"auto\"\u003eAdd under the \u003ccode\u003estyle:\u003c/code\u003e key, e.g.:\u003c/p\u003e\n\u003cdiv class=\"highlight highlight-source-yaml notranslate position-relative overflow-auto\" dir=\"auto\" data-snippet-clipboard-copy-content=\"style: |\n  :host {\"\u003e\u003cpre\u003e\u003cspan class=\"pl-ent\"\u003estyle\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e|\u003c/span\u003e\n\u003cspan class=\"pl-s\"\u003e  :host {\u003c/span\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003chr\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch2 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e🔷 GRID Mode (\u003ccode\u003emenuStyle: grid\u003c/code\u003e)\u003c/h2\u003e\u003ca id=\"user-content--grid-mode-menustyle-grid\" class=\"anchor\" aria-label=\"Permalink: 🔷 GRID Mode (menuStyle: grid)\" href=\"#-grid-mode-menustyle-grid\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cdiv class=\"snippet-clipboard-content notranslate position-relative overflow-auto\" data-snippet-clipboard-copy-content=\"--sidebar-grid-margin-y\n--sidebar-grid-gap\n--sidebar-grid-item-padding\n--sidebar-grid-box-size\n--sidebar-grid-radius\n--sidebar-grid-bg\n--sidebar-grid-icon-size\n--sidebar-grid-icon-color\n--sidebar-grid-label-margin-top\n--sidebar-grid-font-size\n--sidebar-grid-line-height\n--sidebar-grid-font-weight\n--sidebar-grid-text-color\n--sidebar-grid-active-border\n--sidebar-grid-active-bg\n--sidebar-grid-active-icon-color\n--sidebar-grid-active-text-color\n--sidebar-grid-columns\n--sidebar-grid-rows\n--sidebar-grid-row-height\"\u003e\u003cpre class=\"notranslate\"\u003e\u003ccode\u003e--sidebar-grid-margin-y\n--sidebar-grid-gap\n--sidebar-grid-item-padding\n--sidebar-grid-box-size\n--sidebar-grid-radius\n--sidebar-grid-bg\n--sidebar-grid-icon-size\n--sidebar-grid-icon-color\n--sidebar-grid-label-margin-top\n--sidebar-grid-font-size\n--sidebar-grid-line-height\n--sidebar-grid-font-weight\n--sidebar-grid-text-color\n--sidebar-grid-active-border\n--sidebar-grid-active-bg\n--sidebar-grid-active-icon-color\n--sidebar-grid-active-text-color\n--sidebar-grid-columns\n--sidebar-grid-rows\n--sidebar-grid-row-height\n\u003c/code\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003chr\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch2 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e🟥 BUTTON Mode (\u003ccode\u003emenuStyle: buttons\u003c/code\u003e)\u003c/h2\u003e\u003ca id=\"user-content--button-mode-menustyle-buttons\" class=\"anchor\" aria-label=\"Permalink: 🟥 BUTTON Mode (menuStyle: buttons)\" href=\"#-button-mode-menustyle-buttons\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cdiv class=\"snippet-clipboard-content notranslate position-relative overflow-auto\" data-snippet-clipboard-copy-content=\"--sidebar-button-margin-y\n--sidebar-button-gap\n--sidebar-button-item-gap\n--sidebar-button-size\n--sidebar-button-box-size\n--sidebar-button-radius\n--sidebar-button-bg\n--sidebar-button-icon-color\n--sidebar-button-icon-size\n--sidebar-button-font-size\n--sidebar-button-line-height\n--sidebar-button-text-color\n--sidebar-button-font-weight\n--sidebar-button-active-border-width\n--sidebar-button-active-border-color\n--sidebar-button-active-shadow-color\n--sidebar-button-active-icon-color\n--sidebar-button-active-text-color\"\u003e\u003cpre class=\"notranslate\"\u003e\u003ccode\u003e--sidebar-button-margin-y\n--sidebar-button-gap\n--sidebar-button-item-gap\n--sidebar-button-size\n--sidebar-button-box-size\n--sidebar-button-radius\n--sidebar-button-bg\n--sidebar-button-icon-color\n--sidebar-button-icon-size\n--sidebar-button-font-size\n--sidebar-button-line-height\n--sidebar-button-text-color\n--sidebar-button-font-weight\n--sidebar-button-active-border-width\n--sidebar-button-active-border-color\n--sidebar-button-active-shadow-color\n--sidebar-button-active-icon-color\n--sidebar-button-active-text-color\n\u003c/code\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003chr\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch2 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e🟩 WIDE Mode (\u003ccode\u003emenuStyle: wide\u003c/code\u003e)\u003c/h2\u003e\u003ca id=\"user-content--wide-mode-menustyle-wide\" class=\"anchor\" aria-label=\"Permalink: 🟩 WIDE Mode (menuStyle: wide)\" href=\"#-wide-mode-menustyle-wide\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cdiv class=\"snippet-clipboard-content notranslate position-relative overflow-auto\" data-snippet-clipboard-copy-content=\"--sidebar-wide-margin-y\n--sidebar-wide-gap\n--sidebar-wide-padding-x\n--sidebar-wide-height\n--sidebar-wide-radius\n--sidebar-wide-item-gap\n--sidebar-wide-bg\n--sidebar-wide-icon-color\n--sidebar-wide-icon-size\n--sidebar-wide-font-size\n--sidebar-wide-line-height\n--sidebar-wide-text-color\n--sidebar-wide-font-weight\n--sidebar-wide-active-border-width\n--sidebar-wide-active-border-color\n--sidebar-wide-active-bg\n--sidebar-wide-active-opacity\n--sidebar-wide-active-icon-color\n--sidebar-wide-active-icon-size\n--sidebar-wide-active-text-color\"\u003e\u003cpre class=\"notranslate\"\u003e\u003ccode\u003e--sidebar-wide-margin-y\n--sidebar-wide-gap\n--sidebar-wide-padding-x\n--sidebar-wide-height\n--sidebar-wide-radius\n--sidebar-wide-item-gap\n--sidebar-wide-bg\n--sidebar-wide-icon-color\n--sidebar-wide-icon-size\n--sidebar-wide-font-size\n--sidebar-wide-line-height\n--sidebar-wide-text-color\n--sidebar-wide-font-weight\n--sidebar-wide-active-border-width\n--sidebar-wide-active-border-color\n--sidebar-wide-active-bg\n--sidebar-wide-active-opacity\n--sidebar-wide-active-icon-color\n--sidebar-wide-active-icon-size\n--sidebar-wide-active-text-color\n\u003c/code\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003chr\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch2 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e🧠 Common Sidebar Variables\u003c/h2\u003e\u003ca id=\"user-content--common-sidebar-variables\" class=\"anchor\" aria-label=\"Permalink: 🧠 Common Sidebar Variables\" href=\"#-common-sidebar-variables\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cdiv class=\"snippet-clipboard-content notranslate position-relative overflow-auto\" data-snippet-clipboard-copy-content=\"--sidebar-selected-bg\n--sidebar-icon-color\n--primary-text-color\"\u003e\u003cpre class=\"notranslate\"\u003e\u003ccode\u003e--sidebar-selected-bg\n--sidebar-icon-color\n--primary-text-color\n\u003c/code\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003chr\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch2 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e🖼 Header Variables\u003c/h2\u003e\u003ca id=\"user-content--header-variables\" class=\"anchor\" aria-label=\"Permalink: 🖼 Header Variables\" href=\"#-header-variables\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cdiv class=\"snippet-clipboard-content notranslate position-relative overflow-auto\" data-snippet-clipboard-copy-content=\"--header-background\n--header-backdrop-filter\n--header-radius\n--header-height\"\u003e\u003cpre class=\"notranslate\"\u003e\u003ccode\u003e--header-background\n--header-backdrop-filter\n--header-radius\n--header-height\n\u003c/code\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003chr\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch1 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e🛠 Troubleshooting\u003c/h1\u003e\u003ca id=\"user-content--troubleshooting\" class=\"anchor\" aria-label=\"Permalink: 🛠 Troubleshooting\" href=\"#-troubleshooting\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cul dir=\"auto\"\u003e\n\u003cli\u003eDisable conflicting layout plugins when testing\u003c/li\u003e\n\u003cli\u003eClear browser cache and reload resources\u003c/li\u003e\n\u003cli\u003eTest without theme customisation first\u003c/li\u003e\n\u003c/ul\u003e\n\u003chr\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch1 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e❤️ Credits\u003c/h1\u003e\u003ca id=\"user-content-️-credits\" class=\"anchor\" aria-label=\"Permalink: ❤️ Credits\" href=\"#️-credits\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cp dir=\"auto\"\u003eThanks DBuit for original work\u003c/p\u003e\n\u003cp dir=\"auto\"\u003eBuilt for the HA community 🙂\u003c/p\u003e\n\u003chr\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch2 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e🔄 Header Top Menu Modes (NEW)\u003c/h2\u003e\u003ca id=\"user-content--header-top-menu-modes-new\" class=\"anchor\" aria-label=\"Permalink: 🔄 Header Top Menu Modes (NEW)\" href=\"#-header-top-menu-modes-new\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cp dir=\"auto\"\u003eThe custom header can manage the Home Assistant top bar in three different ways.\u003c/p\u003e\n\u003cmarkdown-accessiblity-table\u003e\u003ctable\u003e\n\u003cthead\u003e\n\u003ctr\u003e\n\u003cth\u003eMode\u003c/th\u003e\n\u003cth\u003eDescription\u003c/th\u003e\n\u003c/tr\u003e\n\u003c/thead\u003e\n\u003ctbody\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eoverlay\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eHA top bar overlays the content\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003epush\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003eContent is pushed down by the HA top bar\u003c/td\u003e\n\u003c/tr\u003e\n\u003ctr\u003e\n\u003ctd\u003e\u003ccode\u003eflip\u003c/code\u003e\u003c/td\u003e\n\u003ctd\u003e\u003cstrong\u003eAnimated cylindrical flip between custom header and HA top bar\u003c/strong\u003e\u003c/td\u003e\n\u003c/tr\u003e\n\u003c/tbody\u003e\n\u003c/table\u003e\u003c/markdown-accessiblity-table\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch3 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003e🌀 Flip Mode\u003c/h3\u003e\u003ca id=\"user-content--flip-mode\" class=\"anchor\" aria-label=\"Permalink: 🌀 Flip Mode\" href=\"#-flip-mode\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cp dir=\"auto\"\u003eThe \u003cstrong\u003eflip mode\u003c/strong\u003e creates a smooth cylindrical rotation effect between:\u003c/p\u003e\n\u003cul dir=\"auto\"\u003e\n\u003cli\u003eYour custom header\u003c/li\u003e\n\u003cli\u003eThe original Home Assistant top bar\u003c/li\u003e\n\u003c/ul\u003e\n\u003cp dir=\"auto\"\u003e✔ No layout jumps\u003cbr\u003e\n✔ No content shifting\u003cbr\u003e\n✔ Identical occupied space\u003c/p\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch4 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003eConfiguration\u003c/h4\u003e\u003ca id=\"user-content-configuration\" class=\"anchor\" aria-label=\"Permalink: Configuration\" href=\"#configuration\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cdiv class=\"highlight highlight-source-yaml notranslate position-relative overflow-auto\" dir=\"auto\" data-snippet-clipboard-copy-content=\"header:\n  enabled: true\n  sticky: true\n  topMenuMode: flip\n  flipDuration: 5   # seconds (optional, default: 5)\"\u003e\u003cpre\u003e\u003cspan class=\"pl-ent\"\u003eheader\u003c/span\u003e:\n  \u003cspan class=\"pl-ent\"\u003eenabled\u003c/span\u003e: \u003cspan class=\"pl-c1\"\u003etrue\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003esticky\u003c/span\u003e: \u003cspan class=\"pl-c1\"\u003etrue\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003etopMenuMode\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003eflip\u003c/span\u003e\n  \u003cspan class=\"pl-ent\"\u003eflipDuration\u003c/span\u003e: \u003cspan class=\"pl-c1\"\u003e5\u003c/span\u003e   \u003cspan class=\"pl-c\"\u003e\u003cspan class=\"pl-c\"\u003e#\u003c/span\u003e seconds (optional, default: 5)\u003c/span\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003cdiv class=\"markdown-heading\" dir=\"auto\"\u003e\u003ch4 tabindex=\"-1\" class=\"heading-element\" dir=\"auto\"\u003eTrigger example\u003c/h4\u003e\u003ca id=\"user-content-trigger-example\" class=\"anchor\" aria-label=\"Permalink: Trigger example\" href=\"#trigger-example\"\u003e\u003csvg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"\u003e\u003cpath d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"\u003e\u003c/path\u003e\u003c/svg\u003e\u003c/a\u003e\u003c/div\u003e\n\u003cdiv class=\"highlight highlight-source-yaml notranslate position-relative overflow-auto\" dir=\"auto\" data-snippet-clipboard-copy-content=\"headerMenu:\n  - action: service-js\n    name: \u0026quot;Top Menu\u0026quot;\n    icon: mdi:swap-vertical\n    service: |\n      if (window.silvioFlipTopMenu) {\n        window.silvioFlipTopMenu();\n      }\"\u003e\u003cpre\u003e\u003cspan class=\"pl-ent\"\u003eheaderMenu\u003c/span\u003e:\n  - \u003cspan class=\"pl-ent\"\u003eaction\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003eservice-js\u003c/span\u003e\n    \u003cspan class=\"pl-ent\"\u003ename\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003eTop Menu\u003cspan class=\"pl-pds\"\u003e\"\u003c/span\u003e\u003c/span\u003e\n    \u003cspan class=\"pl-ent\"\u003eicon\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003emdi:swap-vertical\u003c/span\u003e\n    \u003cspan class=\"pl-ent\"\u003eservice\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003e|\u003c/span\u003e\n\u003cspan class=\"pl-s\"\u003e      if (window.silvioFlipTopMenu) {\u003c/span\u003e\n\u003cspan class=\"pl-s\"\u003e        window.silvioFlipTopMenu();\u003c/span\u003e\n\u003cspan class=\"pl-s\"\u003e      }\u003c/span\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003cp dir=\"auto\"\u003eor\u003c/p\u003e\n\u003cdiv class=\"highlight highlight-source-yaml notranslate position-relative overflow-auto\" dir=\"auto\" data-snippet-clipboard-copy-content=\"rightMenu:\n  - icon: mdi:application\n    name: Top bar\n    action: toggle-topmenu\"\u003e\u003cpre\u003e\u003cspan class=\"pl-ent\"\u003erightMenu\u003c/span\u003e:\n  - \u003cspan class=\"pl-ent\"\u003eicon\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003emdi:application\u003c/span\u003e\n    \u003cspan class=\"pl-ent\"\u003ename\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003eTop bar\u003c/span\u003e\n    \u003cspan class=\"pl-ent\"\u003eaction\u003c/span\u003e: \u003cspan class=\"pl-s\"\u003etoggle-topmenu\u003c/span\u003e\u003c/pre\u003e\u003c/div\u003e\n\u003c/article\u003e","richTextTruncated":false,"renderedFileInfo":null,"symbols":{"timed_out":false,"not_analyzed":false,"symbols":[{"name":"Supportami / Support Me","kind":"section_2","ident_start":160,"ident_end":183,"extent_start":157,"extent_end":1129,"fully_qualified_name":"Supportami / Support Me","ident_utf16":{"start":{"line_number":2,"utf16_col":3},"end":{"line_number":2,"utf16_col":26}},"extent_utf16":{"start":{"line_number":2,"utf16_col":0},"end":{"line_number":19,"utf16_col":0}}},{"name":"🧭 Custom Sidebar \u0026 Header for Home Assistant","kind":"section_1","ident_start":1131,"ident_end":1178,"extent_start":1129,"extent_end":1214,"fully_qualified_name":"🧭 Custom Sidebar \u0026 Header for Home Assistant","ident_utf16":{"start":{"line_number":19,"utf16_col":2},"end":{"line_number":19,"utf16_col":47}},"extent_utf16":{"start":{"line_number":19,"utf16_col":0},"end":{"line_number":22,"utf16_col":0}}},{"name":"Header Flip Mode","kind":"section_1","ident_start":1216,"ident_end":1232,"extent_start":1214,"extent_end":1285,"fully_qualified_name":"Header Flip Mode","ident_utf16":{"start":{"line_number":22,"utf16_col":2},"end":{"line_number":22,"utf16_col":18}},"extent_utf16":{"start":{"line_number":22,"utf16_col":0},"end":{"line_number":25,"utf16_col":0}}},{"name":"Header Push Mode","kind":"section_1","ident_start":1287,"ident_end":1303,"extent_start":1285,"extent_end":3947,"fully_qualified_name":"Header Push Mode","ident_utf16":{"start":{"line_number":25,"utf16_col":2},"end":{"line_number":25,"utf16_col":18}},"extent_utf16":{"start":{"line_number":25,"utf16_col":0},"end":{"line_number":109,"utf16_col":0}}},{"name":"📸 Screenshots","kind":"section_2","ident_start":1349,"ident_end":1365,"extent_start":1346,"extent_end":1852,"fully_qualified_name":"📸 Screenshots","ident_utf16":{"start":{"line_number":28,"utf16_col":3},"end":{"line_number":28,"utf16_col":17}},"extent_utf16":{"start":{"line_number":28,"utf16_col":0},"end":{"line_number":49,"utf16_col":0}}},{"name":"⭐ Main Features","kind":"section_2","ident_start":1855,"ident_end":1872,"extent_start":1852,"extent_end":2401,"fully_qualified_name":"⭐ Main Features","ident_utf16":{"start":{"line_number":49,"utf16_col":3},"end":{"line_number":49,"utf16_col":18}},"extent_utf16":{"start":{"line_number":49,"utf16_col":0},"end":{"line_number":65,"utf16_col":0}}},{"name":"🖊️ Graphical Editor (Admin only)","kind":"section_2","ident_start":2404,"ident_end":2441,"extent_start":2401,"extent_end":3947,"fully_qualified_name":"🖊️ Graphical Editor (Admin only)","ident_utf16":{"start":{"line_number":65,"utf16_col":3},"end":{"line_number":65,"utf16_col":36}},"extent_utf16":{"start":{"line_number":65,"utf16_col":0},"end":{"line_number":109,"utf16_col":0}}},{"name":"How to open it","kind":"section_3","ident_start":2686,"ident_end":2700,"extent_start":2682,"extent_end":3006,"fully_qualified_name":"How to open it","ident_utf16":{"start":{"line_number":76,"utf16_col":4},"end":{"line_number":76,"utf16_col":18}},"extent_utf16":{"start":{"line_number":76,"utf16_col":0},"end":{"line_number":83,"utf16_col":0}}},{"name":"Editor tabs","kind":"section_3","ident_start":3010,"ident_end":3021,"extent_start":3006,"extent_end":3408,"fully_qualified_name":"Editor tabs","ident_utf16":{"start":{"line_number":83,"utf16_col":4},"end":{"line_number":83,"utf16_col":15}},"extent_utf16":{"start":{"line_number":83,"utf16_col":0},"end":{"line_number":91,"utf16_col":0}}},{"name":"Card editors","kind":"section_3","ident_start":3412,"ident_end":3424,"extent_start":3408,"extent_end":3686,"fully_qualified_name":"Card editors","ident_utf16":{"start":{"line_number":91,"utf16_col":4},"end":{"line_number":91,"utf16_col":16}},"extent_utf16":{"start":{"line_number":91,"utf16_col":0},"end":{"line_number":102,"utf16_col":0}}},{"name":"Save behaviour","kind":"section_3","ident_start":3690,"ident_end":3704,"extent_start":3686,"extent_end":3947,"fully_qualified_name":"Save behaviour","ident_utf16":{"start":{"line_number":102,"utf16_col":4},"end":{"line_number":102,"utf16_col":18}},"extent_utf16":{"start":{"line_number":102,"utf16_col":0},"end":{"line_number":109,"utf16_col":0}}},{"name":"📦 Installation","kind":"section_1","ident_start":3949,"ident_end":3966,"extent_start":3947,"extent_end":4432,"fully_qualified_name":"📦 Installation","ident_utf16":{"start":{"line_number":109,"utf16_col":2},"end":{"line_number":109,"utf16_col":17}},"extent_utf16":{"start":{"line_number":109,"utf16_col":0},"end":{"line_number":137,"utf16_col":0}}},{"name":"HACS","kind":"section_2","ident_start":3971,"ident_end":3975,"extent_start":3968,"extent_end":4241,"fully_qualified_name":"HACS","ident_utf16":{"start":{"line_number":111,"utf16_col":3},"end":{"line_number":111,"utf16_col":7}},"extent_utf16":{"start":{"line_number":111,"utf16_col":0},"end":{"line_number":118,"utf16_col":0}}},{"name":"[![Open in HACS](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=bobsilvio\u0026repository=sidebar-card\u0026category=plugin)","kind":"section_2","ident_start":4049,"ident_end":4235,"extent_start":4049,"extent_end":4240,"fully_qualified_name":"[![Open in HACS](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=bobsilvio\u0026repository=sidebar-card\u0026category=plugin)","ident_utf16":{"start":{"line_number":115,"utf16_col":0},"end":{"line_number":115,"utf16_col":186}},"extent_utf16":{"start":{"line_number":115,"utf16_col":0},"end":{"line_number":117,"utf16_col":0}}},{"name":"Manual Install","kind":"section_2","ident_start":4244,"ident_end":4258,"extent_start":4241,"extent_end":4432,"fully_qualified_name":"Manual Install","ident_utf16":{"start":{"line_number":118,"utf16_col":3},"end":{"line_number":118,"utf16_col":17}},"extent_utf16":{"start":{"line_number":118,"utf16_col":0},"end":{"line_number":137,"utf16_col":0}}},{"name":"🚀 Basic Setup","kind":"section_1","ident_start":4434,"ident_end":4450,"extent_start":4432,"extent_end":4629,"fully_qualified_name":"🚀 Basic Setup","ident_utf16":{"start":{"line_number":137,"utf16_col":2},"end":{"line_number":137,"utf16_col":16}},"extent_utf16":{"start":{"line_number":137,"utf16_col":0},"end":{"line_number":154,"utf16_col":0}}},{"name":"🧭 Sidebar Configuration","kind":"section_1","ident_start":4631,"ident_end":4657,"extent_start":4629,"extent_end":6210,"fully_qualified_name":"🧭 Sidebar Configuration","ident_utf16":{"start":{"line_number":154,"utf16_col":2},"end":{"line_number":154,"utf16_col":26}},"extent_utf16":{"start":{"line_number":154,"utf16_col":0},"end":{"line_number":196,"utf16_col":0}}},{"name":"🔧 Main Options","kind":"section_2","ident_start":4662,"ident_end":4679,"extent_start":4659,"extent_end":6120,"fully_qualified_name":"🔧 Main Options","ident_utf16":{"start":{"line_number":156,"utf16_col":3},"end":{"line_number":156,"utf16_col":18}},"extent_utf16":{"start":{"line_number":156,"utf16_col":0},"end":{"line_number":185,"utf16_col":0}}},{"name":"📐 Responsive Width","kind":"section_2","ident_start":6123,"ident_end":6144,"extent_start":6120,"extent_end":6210,"fully_qualified_name":"📐 Responsive Width","ident_utf16":{"start":{"line_number":185,"utf16_col":3},"end":{"line_number":185,"utf16_col":22}},"extent_utf16":{"start":{"line_number":185,"utf16_col":0},"end":{"line_number":196,"utf16_col":0}}},{"name":"📋 Sidebar Menu Items","kind":"section_1","ident_start":6212,"ident_end":6235,"extent_start":6210,"extent_end":7321,"fully_qualified_name":"📋 Sidebar Menu Items","ident_utf16":{"start":{"line_number":196,"utf16_col":2},"end":{"line_number":196,"utf16_col":23}},"extent_utf16":{"start":{"line_number":196,"utf16_col":0},"end":{"line_number":239,"utf16_col":0}}},{"name":"Actions Supported","kind":"section_3","ident_start":6547,"ident_end":6564,"extent_start":6543,"extent_end":6986,"fully_qualified_name":"Actions Supported","ident_utf16":{"start":{"line_number":211,"utf16_col":4},"end":{"line_number":211,"utf16_col":21}},"extent_utf16":{"start":{"line_number":211,"utf16_col":0},"end":{"line_number":225,"utf16_col":0}}},{"name":"Extra Item Fields","kind":"section_3","ident_start":6990,"ident_end":7007,"extent_start":6986,"extent_end":7321,"fully_qualified_name":"Extra Item Fields","ident_utf16":{"start":{"line_number":225,"utf16_col":4},"end":{"line_number":225,"utf16_col":21}},"extent_utf16":{"start":{"line_number":225,"utf16_col":0},"end":{"line_number":239,"utf16_col":0}}},{"name":"🎨 Menu Styles","kind":"section_1","ident_start":7323,"ident_end":7339,"extent_start":7321,"extent_end":7917,"fully_qualified_name":"🎨 Menu Styles","ident_utf16":{"start":{"line_number":239,"utf16_col":2},"end":{"line_number":239,"utf16_col":16}},"extent_utf16":{"start":{"line_number":239,"utf16_col":0},"end":{"line_number":268,"utf16_col":0}}},{"name":"Example — wide style","kind":"section_2","ident_start":7624,"ident_end":7646,"extent_start":7621,"extent_end":7917,"fully_qualified_name":"Example — wide style","ident_utf16":{"start":{"line_number":248,"utf16_col":3},"end":{"line_number":248,"utf16_col":23}},"extent_utf16":{"start":{"line_number":248,"utf16_col":0},"end":{"line_number":268,"utf16_col":0}}},{"name":"🧱 Header Configuration","kind":"section_1","ident_start":7919,"ident_end":7944,"extent_start":7917,"extent_end":10872,"fully_qualified_name":"🧱 Header Configuration","ident_utf16":{"start":{"line_number":268,"utf16_col":2},"end":{"line_number":268,"utf16_col":25}},"extent_utf16":{"start":{"line_number":268,"utf16_col":0},"end":{"line_number":354,"utf16_col":0}}},{"name":"🧩 Top Bar Modes (`topMenuMode`)","kind":"section_2","ident_start":9999,"ident_end":10033,"extent_start":9996,"extent_end":10490,"fully_qualified_name":"🧩 Top Bar Modes (`topMenuMode`)","ident_utf16":{"start":{"line_number":313,"utf16_col":3},"end":{"line_number":313,"utf16_col":35}},"extent_utf16":{"start":{"line_number":313,"utf16_col":0},"end":{"line_number":324,"utf16_col":0}}},{"name":"Header Menu Items","kind":"section_2","ident_start":10493,"ident_end":10510,"extent_start":10490,"extent_end":10735,"fully_qualified_name":"Header Menu Items","ident_utf16":{"start":{"line_number":324,"utf16_col":3},"end":{"line_number":324,"utf16_col":20}},"extent_utf16":{"start":{"line_number":324,"utf16_col":0},"end":{"line_number":339,"utf16_col":0}}},{"name":"Header Cards","kind":"section_2","ident_start":10738,"ident_end":10750,"extent_start":10735,"extent_end":10872,"fully_qualified_name":"Header Cards","ident_utf16":{"start":{"line_number":339,"utf16_col":3},"end":{"line_number":339,"utf16_col":15}},"extent_utf16":{"start":{"line_number":339,"utf16_col":0},"end":{"line_number":354,"utf16_col":0}}},{"name":"🎨 Styling \u0026 CSS Variables","kind":"section_1","ident_start":10874,"ident_end":10902,"extent_start":10872,"extent_end":12928,"fully_qualified_name":"🎨 Styling \u0026 CSS Variables","ident_utf16":{"start":{"line_number":354,"utf16_col":2},"end":{"line_number":354,"utf16_col":28}},"extent_utf16":{"start":{"line_number":354,"utf16_col":0},"end":{"line_number":465,"utf16_col":0}}},{"name":"🔷 GRID Mode (`menuStyle: grid`)","kind":"section_2","ident_start":10979,"ident_end":11013,"extent_start":10976,"extent_end":11541,"fully_qualified_name":"🔷 GRID Mode (`menuStyle: grid`)","ident_utf16":{"start":{"line_number":365,"utf16_col":3},"end":{"line_number":365,"utf16_col":35}},"extent_utf16":{"start":{"line_number":365,"utf16_col":0},"end":{"line_number":392,"utf16_col":0}}},{"name":"🟥 BUTTON Mode (`menuStyle: buttons`)","kind":"section_2","ident_start":11544,"ident_end":11583,"extent_start":11541,"extent_end":12113,"fully_qualified_name":"🟥 BUTTON Mode (`menuStyle: buttons`)","ident_utf16":{"start":{"line_number":392,"utf16_col":3},"end":{"line_number":392,"utf16_col":40}},"extent_utf16":{"start":{"line_number":392,"utf16_col":0},"end":{"line_number":417,"utf16_col":0}}},{"name":"🟩 WIDE Mode (`menuStyle: wide`)","kind":"section_2","ident_start":12116,"ident_end":12150,"extent_start":12113,"extent_end":12699,"fully_qualified_name":"🟩 WIDE Mode (`menuStyle: wide`)","ident_utf16":{"start":{"line_number":417,"utf16_col":3},"end":{"line_number":417,"utf16_col":35}},"extent_utf16":{"start":{"line_number":417,"utf16_col":0},"end":{"line_number":444,"utf16_col":0}}},{"name":"🧠 Common Sidebar Variables","kind":"section_2","ident_start":12702,"ident_end":12731,"extent_start":12699,"extent_end":12811,"fully_qualified_name":"🧠 Common Sidebar Variables","ident_utf16":{"start":{"line_number":444,"utf16_col":3},"end":{"line_number":444,"utf16_col":30}},"extent_utf16":{"start":{"line_number":444,"utf16_col":0},"end":{"line_number":454,"utf16_col":0}}},{"name":"🖼 Header Variables","kind":"section_2","ident_start":12814,"ident_end":12835,"extent_start":12811,"extent_end":12928,"fully_qualified_name":"🖼 Header Variables","ident_utf16":{"start":{"line_number":454,"utf16_col":3},"end":{"line_number":454,"utf16_col":22}},"extent_utf16":{"start":{"line_number":454,"utf16_col":0},"end":{"line_number":465,"utf16_col":0}}},{"name":"🛠 Troubleshooting","kind":"section_1","ident_start":12930,"ident_end":12950,"extent_start":12928,"extent_end":13092,"fully_qualified_name":"🛠 Troubleshooting","ident_utf16":{"start":{"line_number":465,"utf16_col":2},"end":{"line_number":465,"utf16_col":20}},"extent_utf16":{"start":{"line_number":465,"utf16_col":0},"end":{"line_number":473,"utf16_col":0}}},{"name":"❤️ Credits","kind":"section_1","ident_start":13094,"ident_end":13108,"extent_start":13092,"extent_end":14217,"fully_qualified_name":"❤️ Credits","ident_utf16":{"start":{"line_number":473,"utf16_col":2},"end":{"line_number":473,"utf16_col":12}},"extent_utf16":{"start":{"line_number":473,"utf16_col":0},"end":{"line_number":530,"utf16_col":0}}},{"name":"🔄 Header Top Menu Modes (NEW)","kind":"section_2","ident_start":13182,"ident_end":13214,"extent_start":13179,"extent_end":14217,"fully_qualified_name":"🔄 Header Top Menu Modes (NEW)","ident_utf16":{"start":{"line_number":480,"utf16_col":3},"end":{"line_number":480,"utf16_col":33}},"extent_utf16":{"start":{"line_number":480,"utf16_col":0},"end":{"line_number":530,"utf16_col":0}}},{"name":"🌀 Flip Mode","kind":"section_3","ident_start":13531,"ident_end":13545,"extent_start":13527,"extent_end":14217,"fully_qualified_name":"🌀 Flip Mode","ident_utf16":{"start":{"line_number":490,"utf16_col":4},"end":{"line_number":490,"utf16_col":16}},"extent_utf16":{"start":{"line_number":490,"utf16_col":0},"end":{"line_number":530,"utf16_col":0}}},{"name":"Configuration","kind":"section_4","ident_start":13765,"ident_end":13778,"extent_start":13760,"extent_end":13905,"fully_qualified_name":"Configuration","ident_utf16":{"start":{"line_number":501,"utf16_col":5},"end":{"line_number":501,"utf16_col":18}},"extent_utf16":{"start":{"line_number":501,"utf16_col":0},"end":{"line_number":511,"utf16_col":0}}},{"name":"Trigger example","kind":"section_4","ident_start":13910,"ident_end":13925,"extent_start":13905,"extent_end":14217,"fully_qualified_name":"Trigger example","ident_utf16":{"start":{"line_number":511,"utf16_col":5},"end":{"line_number":511,"utf16_col":20}},"extent_utf16":{"start":{"line_number":511,"utf16_col":0},"end":{"line_number":530,"utf16_col":0}}}]}},"codeViewLayoutRoute":{"repo":{"id":1224309473,"defaultBranch":"main","name":"sidebar-card","ownerLogin":"rockbaer2007","currentUserCanPush":false,"isFork":true,"isEmpty":false,"createdAt":"2026-04-29T06:48:00.000Z","ownerAvatar":"https://avatars.githubusercontent.com/u/51380789?v=4","public":true,"private":false,"isOrgOwned":false},"currentUser":null,"uploadToken":"z9oHJ1sRNJD4nxyAiJW72opCoR68hKWbkH7KjUMzB0s13WHUJAbWwckAkGCTjTseC9TK291VYpyZgzUAN7x7Sw","allShortcutsEnabled":false,"treeExpanded":true,"path":"README.md","symbolsExpanded":false,"refInfo":{"name":"main","listCacheKey":"v0:1777445282.111574","canEdit":false,"currentOid":"c3da442212763554eb558e74d485c8bee5573f56"},"helpUrl":"https://docs.github.com","findFileWorkerPath":"/assets-cdn/worker/find-file-worker-378c581dbdb2429c.js","findInFileWorkerPath":"/assets-cdn/worker/find-in-file-worker-82470c2dd86b326d.js","githubDevUrl":null},"codeViewFileTreeLayoutRoute":{"fileTree":{"":{"items":[{"name":"dist","path":"dist","contentType":"directory"},{"name":"example","path":"example","contentType":"directory"},{"name":"img","path":"img","contentType":"directory"},{"name":"src","path":"src","contentType":"directory"},{"name":"LICENSE","path":"LICENSE","contentType":"file"},{"name":"README.it.md","path":"README.it.md","contentType":"file"},{"name":"README.md","path":"README.md","contentType":"file"},{"name":"eslint.config.mjs","path":"eslint.config.mjs","contentType":"file"},{"name":"hacs.json","path":"hacs.json","contentType":"file"},{"name":"package-lock.json","path":"package-lock.json","contentType":"file"},{"name":"package.json","path":"package.json","contentType":"file"},{"name":"rollup.config.js","path":"rollup.config.js","contentType":"file"},{"name":"tsconfig.json","path":"tsconfig.json","contentType":"file"}],"totalCount":13}},"fileTreeProcessingTime":29.399922,"foldersToFetch":[]},"codeViewBlobLayoutRoute":{"codeLineWrapEnabled":false,"refInfo":{"name":"main","listCacheKey":"v0:1777445282.111574","canEdit":false,"refType":"branch","currentOid":"c3da442212763554eb558e74d485c8bee5573f56","canEditOnDefaultBranch":false,"fileExistsOnDefault":true},"path":"README.md","blob":{"copilotSWEAgentEnabled":false,"dependabotInfo":{"showConfigurationBanner":false,"configFilePath":null,"networkDependabotPath":"/rockbaer2007/sidebar-card/network/updates","dismissConfigurationNoticePath":"/settings/dismiss-notice/dependabot_configuration_notice","configurationNoticeDismissed":null},"displayName":"README.md","displayUrl":"https://github.com/rockbaer2007/sidebar-card/blob/main/README.md?raw=true","headerInfo":{"blobSize":"13.9 KB","deleteTooltip":"You must be signed in to make or propose changes","editTooltip":"You must be signed in to make or propose changes","ghDesktopPath":"https://desktop.github.com","isGitLfs":false,"onBranch":true,"shortPath":"a7d68df","siteNavLoginPath":"/login?return_to=https%3A%2F%2Fgithub.com%2Frockbaer2007%2Fsidebar-card%2Fblob%2Fmain%2FREADME.md","isCSV":false,"isRichtext":true,"lineInfo":{"truncatedLoc":"530","truncatedSloc":"405"},"mode":"file"},"image":false,"isCodeownersFile":null,"isPlain":false,"isValidLegacyIssueTemplate":false,"isIssueTemplate":false,"isDiscussionTemplate":false,"language":"Markdown","languageID":222,"large":false,"planSupportInfo":{"repoIsFork":null,"repoOwnedByCurrentUser":null,"requestFullPath":"/rockbaer2007/sidebar-card/blob/main/README.md","showFreeOrgGatedFeatureMessage":null,"showPlanSupportBanner":null,"upgradeDataAttributes":null,"upgradePath":null},"publishBannersInfo":{"dismissActionNoticePath":"/settings/dismiss-notice/publish_action_from_dockerfile","releasePath":"/rockbaer2007/sidebar-card/releases/new?marketplace=true","showPublishActionBanner":false},"rawBlobUrl":"https://github.com/rockbaer2007/sidebar-card/raw/refs/heads/main/README.md","renderImageOrRaw":false,"shortPath":null,"symbolsEnabled":true,"tabSize":4,"topBannersInfo":{"overridingGlobalFundingFile":false,"globalPreferredFundingPath":null,"showInvalidCitationWarning":false,"citationHelpUrl":"https://docs.github.com/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/about-citation-files","actionsOnboardingTip":null},"truncated":false,"viewable":true,"workflowRedirectUrl":null},"copilotInfo":null,"copilotAccessAllowed":false,"copilotSpacesEnabled":false,"modelsAccessAllowed":false,"modelsRepoIntegrationEnabled":false,"isMarketplaceEnabled":true},"codeViewBlobLayoutRoute.StyledBlob":{"rawLines":["[![Sample](https://storage.ko-fi.com/cdn/generated/zfskfgqnf/2025-03-07_rest-7d81acd901abf101cbdf54443c38f6f0-dlmmonph.jpg)](https://ko-fi.com/silviosmart)","","## Supportami / Support Me","","Se ti piace il mio lavoro e vuoi che continui nello sviluppo delle card, puoi offrirmi un caffè.\\","If you like my work and want me to continue developing the cards, you can buy me a coffee.","","","[![PayPal](https://img.shields.io/badge/Donate-PayPal-%2300457C?style=for-the-badge\u0026logo=paypal\u0026logoColor=white)](https://www.paypal.com/donate/?hosted_button_id=Z6KY9V6BBZ4BN)","","Non dimenticare di seguirmi sui social:\\","Don't forget to follow me on social media:","","[![TikTok](https://img.shields.io/badge/Follow_TikTok-%23000000?style=for-the-badge\u0026logo=tiktok\u0026logoColor=white)](https://www.tiktok.com/@silviosmartalexa)","","[![Instagram](https://img.shields.io/badge/Follow_Instagram-%23E1306C?style=for-the-badge\u0026logo=instagram\u0026logoColor=white)](https://www.instagram.com/silviosmartalexa)","","[![YouTube](https://img.shields.io/badge/Subscribe_YouTube-%23FF0000?style=for-the-badge\u0026logo=youtube\u0026logoColor=white)](https://www.youtube.com/@silviosmartalexa)","","# 🧭 Custom Sidebar \u0026 Header for Home Assistant","[🇮🇹 Italiano](README.it.md)","","# Header Flip Mode","![Header flip animation](img/Header-Flip_Mode.gif)","","# Header Push Mode","![Header push](img/Header-Push_Mode.gif)","","## 📸 Screenshots","\u003cp align=\"center\"\u003e","  \u003cimg src=\"img/1.PNG\" width=\"48%\"\u003e","  \u003cimg src=\"img/2.PNG\" width=\"48%\"\u003e","\u003c/p\u003e","","\u003cp align=\"center\"\u003e","  \u003cimg src=\"img/3.PNG\" width=\"48%\"\u003e","  \u003cimg src=\"img/4.PNG\" width=\"48%\"\u003e","\u003c/p\u003e","","\u003cp align=\"center\"\u003e","  \u003cimg src=\"img/5.PNG\" width=\"48%\"\u003e","  \u003cimg src=\"img/6.PNG\" width=\"48%\"\u003e","\u003c/p\u003e","","","A fully‑customisable **Header + Sidebar layout system for Home Assistant**, designed to be modern, flexible and responsive — while keeping full compatibility with Lovelace dashboards.","","---","","## ⭐ Main Features","","- Responsive sidebar width (mobile / tablet / desktop)","- Sticky / glass‑style header","- **4 menu styles (list / wide / buttons / grid)**","- Conditional menu items","- Per‑item colors and icons","- Optional hiding of default HA sidebar + top bar","- Template area for greetings / custom HTML","- Supports any Lovelace card inside header \u0026 sidebar","- Works with kiosk‑mode setups","- Safe — does **not** hack core Lovelace layout","- 🆕 **Built-in graphical editor** — configure Sidebar \u0026 Header without editing YAML manually","","---","","## 🖊️ Graphical Editor (Admin only)","","\u003cp align=\"center\"\u003e","  \u003cimg src=\"img/setting1.png\" width=\"28%\"\u003e","","  ","  \u003cimg src=\"img/setting2.png\" width=\"48%\"\u003e","\u003c/p\u003e","","Administrators have access to a **built-in visual editor** to configure Sidebar and Header without touching the YAML file.","","### How to open it","","Two ways:","","1. **Toolbar button** — a dashboard-edit icon (🖊) appears in the top-right toolbar of HA when you are logged in as admin. Click it to open the editor panel.","2. **Gear icon in the sidebar** — a small ⚙ icon at the bottom of the sidebar (visible only to admins) also opens the editor.","","### Editor tabs","","| Tab | Description |","|-----|-------------|","| **Sidebar** | Configure sidebar width, clock, date format, menu style, menu items, bottomCard and custom CSS |","| **Header** | Configure header height, sticky mode, topMenuMode, card slots (left / center / right), menus and custom CSS |","| **YAML** | Direct YAML editing of both configs — useful for power users or copy-paste workflows |","","### Card editors","","All card fields (bottomCard, leftCard, centerCard, rightCard and stack items) use **YAML format** — the same format you already use in Home Assistant. Example:","","```yaml","type: custom:button-card","entity: light.living_room","name: Living Room","icon: mdi:sofa","```","","### Save behaviour","","- **Storage mode (default)**: changes are saved directly to Lovelace via WebSocket and the page reloads automatically.","- **YAML file mode** (`ui-lovelace.yaml`): the editor generates a YAML snippet to copy-paste into your config file.","","---","","# 📦 Installation","","## HACS","","This integration can be installed manually or via HACS when available.","","[![Open in HACS](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=bobsilvio\u0026repository=sidebar-card\u0026category=plugin)","---","","## Manual Install","","Copy the JS file to:","","```","/config/www/sidebar-card.js","```","","Then add the resource:","","```yaml","url: /local/sidebar-card.js","type: module","```","","Restart or reload resources.","","---","","# 🚀 Basic Setup","","Add to your **dashboard YAML**:","","```yaml","sidebar:","  enabled: true","  width: { mobile: 0, tablet: 16, desktop: 18 }","","header:","  enabled: true","  sticky: true","  height: 72","```","","---","","# 🧭 Sidebar Configuration","","## 🔧 Main Options","","| Option | Type | Default | Description |","|--------|------|---------|-------------|","| `enabled` | bool | `true` | Enables the custom sidebar |","| `debug` | bool | `false` | Log debug messages to console |","| `title` | string | \"\" | Optional title text |","| `clock` | bool | `false` | Enable analog clock |","| `digitalClock` | bool | `false` | Enable digital clock |","| `digitalClockWithSeconds` | bool | `false` | Show seconds in digital clock |","| `twelveHourVersion` | bool | `false` | 12‑hour clock format |","| `period` | bool | `false` | Show AM / PM when using 12‑hour mode |","| `date` | bool | `true` | Show date |","| `dateFormat` | string | `DD MMMM` | Moment‑style format |","| `updateMenu` | bool | `true` | Highlight active menu item |","| `hideHassSidebar` | bool | `false` | Hide default HA sidebar |","| `hideTopMenu` | bool | `false` | Hide default HA top bar |","| `showTopMenuOnMobile` | bool | `true` | Show top bar only on mobile |","| `width` | number/object | `18` | % width or responsive config |","| `breakpoints.mobile` | int | `767` | Mobile max width |","| `breakpoints.tablet` | int | `1024` | Tablet max width |","| `hideOnPath` | list | — | Paths where sidebar hides |","| `menuStyle` | string | `list` | `list / wide / buttons / grid` |","| `showLabel` | bool | `true` | Show menu text labels |","| `template` | Jinja2 | — | HTML rendered above menu |","| `bottomCard` | Lovelace card | — | Card shown at bottom of sidebar |","","---","","## 📐 Responsive Width","","```yaml","width:","  mobile: 0","  tablet: 16","  desktop: 18","```","","---","","# 📋 Sidebar Menu Items","","```yaml","sidebarMenu:","  - action: navigate","    navigation_path: \"/lovelace/home\"","    name: \"Home\"","    icon: mdi:home","    background_color: \"var(--blue)\"","    icon_color: \"#000\"","    text_color: \"#000\"","    state: light.living_room","    conditional: \"{{ is_state('alarm_control_panel.house','disarmed') }}\"","```","","### Actions Supported","","| Action | Description |","|--------|-------------|","| `navigate` | Go to a Lovelace view |","| `more-info` | Open entity dialog |","| `toggle` | Toggle entity |","| `call-service` | Call Home Assistant service |","| `service-js` | Execute JavaScript |","| `url` | Open a URL |","| `toggle-sidebar` | Toggle the **default HA sidebar** (drawer) |","| `toggle-topmenu` | Toggle the **HA top bar** (or trigger `flip` mode when enabled) |","","","### Extra Item Fields","","| Field | Description |","|-------|-------------|","| `name` | Label text |","| `icon` | MDI icon |","| `background_color` | Background colour |","| `icon_color` | Icon colour |","| `text_color` | Text colour |","| `state` | Entity used to mark active state |","| `conditional` | When evaluates false → hides the item |","","---","","# 🎨 Menu Styles","","| `menuStyle` | Description |","|-------------|-------------|","| `list` | Simple legacy list style |","| `wide` | **Pill‑style items with icon + label + colored background** |","| `buttons` | Square button style (icon with optional label) |","| `grid` | Compact app‑icon style grid |","","## Example — wide style","","```yaml","sidebar:","  menuStyle: wide","  showLabel: true","```","","```yaml","- action: navigate","  name: \"Energy\"","  icon: mdi:solar-power-variant","  navigation_path: \"/energy\"","  background_color: \"rgba(255, 200, 140, 0.95)\"","  icon_color: \"#0f172a\"","  text_color: \"#0f172a\"","```","","---","","# 🧱 Header Configuration","","```yaml","header:","  enabled: true","  sticky: true","  height: 72                       # minimum header height (px)","  headerMenuStyle: wide            # list / wide / buttons / grid (same as sidebar)","  headerMenuShowLabel: true","  headerMenuPosition: center       # left / center / right","","  # Home Assistant top bar behavior (optional)","  topMenuMode: overlay             # overlay / push / flip","  flipDuration: 5                  # seconds to keep HA top bar visible in flip mode","","  # Optional icon menus (left / right)","  leftMenu:","    - icon: mdi:menu","      name: Sidebar","      action: toggle-sidebar","","  rightMenu:","    - icon: mdi:application","      name: Top bar","      action: toggle-topmenu","```","","| Option | Type | Default | Description |","|--------|------|---------|-------------|","| `enabled` | bool | `true` | Enable custom header |","| `sticky` | bool | `true` | Make header sticky to the top |","| `height` | int | `72` | Minimum header height in pixels (can grow with content) |","| `style` | string | — | Extra CSS applied inside the header-card (supports `:host { ... }`) |","| `topMenuMode` | string | `overlay` | How to handle HA default top bar: `overlay`, `push`, or `flip` |","| `flipDuration` | number | `5` | **Flip mode only**: seconds to keep HA top bar visible before flipping back |","| `headerMenuStyle` | string | `wide` | Header menu style (`list / wide / buttons / grid`) |","| `headerMenuShowLabel` | bool | `true` | Show text labels in header menu |","| `headerMenuPosition` | string | `right` | Place header menu in `left / center / right` area |","| `leftMenu` | list | — | Icon buttons shown on the far left (e.g. toggle sidebar) |","| `rightMenu` | list | — | Icon buttons shown on the far right (e.g. toggle top bar) |","| `headerMenu` | list | — | Main header menu (styled buttons) |","| `leftCard` | Lovelace card | — | Any Lovelace card rendered in the left slot |","| `centerCard` | Lovelace card | — | Any Lovelace card rendered in the center slot |","| `rightCard` | Lovelace card | — | Any Lovelace card rendered in the right slot |","","## 🧩 Top Bar Modes (`topMenuMode`)","","- **`overlay` (default)**: your header stays visible; HA top bar can be shown/hidden without pushing the view.","- **`push`**: when HA top bar is visible, the content is pushed down using the real top bar height.","- **`flip`**: your header “flips” to reveal HA top bar for a few seconds, then flips back. Use `flipDuration` to control how long HA top bar stays visible.","","To trigger the behavior, use a menu item with:","","```yaml","action: toggle-topmenu","```","## Header Menu Items","","```yaml","headerMenu:","  - action: navigate","    name: \"Home\"","    icon: mdi:home","    navigation_path: \"/lovelace/home\"","    background_color: \"rgba(205,255,190,.95)\"","    icon_color: \"#0f172a\"","    text_color: \"#0f172a\"","```","","---","","## Header Cards","","```yaml","leftCard:","  type: ...","centerCard:","  type: ...","rightCard:","  type: ...","```","","Supports **any Lovelace card**.","","---","","# 🎨 Styling \u0026 CSS Variables","","Add under the `style:` key, e.g.:","","```yaml","style: |","  :host {","```","","---","","## 🔷 GRID Mode (`menuStyle: grid`)","","```","--sidebar-grid-margin-y","--sidebar-grid-gap","--sidebar-grid-item-padding","--sidebar-grid-box-size","--sidebar-grid-radius","--sidebar-grid-bg","--sidebar-grid-icon-size","--sidebar-grid-icon-color","--sidebar-grid-label-margin-top","--sidebar-grid-font-size","--sidebar-grid-line-height","--sidebar-grid-font-weight","--sidebar-grid-text-color","--sidebar-grid-active-border","--sidebar-grid-active-bg","--sidebar-grid-active-icon-color","--sidebar-grid-active-text-color","--sidebar-grid-columns","--sidebar-grid-rows","--sidebar-grid-row-height","```","","---","","## 🟥 BUTTON Mode (`menuStyle: buttons`)","","```","--sidebar-button-margin-y","--sidebar-button-gap","--sidebar-button-item-gap","--sidebar-button-size","--sidebar-button-box-size","--sidebar-button-radius","--sidebar-button-bg","--sidebar-button-icon-color","--sidebar-button-icon-size","--sidebar-button-font-size","--sidebar-button-line-height","--sidebar-button-text-color","--sidebar-button-font-weight","--sidebar-button-active-border-width","--sidebar-button-active-border-color","--sidebar-button-active-shadow-color","--sidebar-button-active-icon-color","--sidebar-button-active-text-color","```","","---","","## 🟩 WIDE Mode (`menuStyle: wide`)","","```","--sidebar-wide-margin-y","--sidebar-wide-gap","--sidebar-wide-padding-x","--sidebar-wide-height","--sidebar-wide-radius","--sidebar-wide-item-gap","--sidebar-wide-bg","--sidebar-wide-icon-color","--sidebar-wide-icon-size","--sidebar-wide-font-size","--sidebar-wide-line-height","--sidebar-wide-text-color","--sidebar-wide-font-weight","--sidebar-wide-active-border-width","--sidebar-wide-active-border-color","--sidebar-wide-active-bg","--sidebar-wide-active-opacity","--sidebar-wide-active-icon-color","--sidebar-wide-active-icon-size","--sidebar-wide-active-text-color","```","","---","","## 🧠 Common Sidebar Variables","","```","--sidebar-selected-bg","--sidebar-icon-color","--primary-text-color","```","","---","","## 🖼 Header Variables","","```","--header-background","--header-backdrop-filter","--header-radius","--header-height","```","","---","","# 🛠 Troubleshooting","","- Disable conflicting layout plugins when testing","- Clear browser cache and reload resources","- Test without theme customisation first","","---","","# ❤️ Credits","Thanks DBuit for original work","","Built for the HA community 🙂","","---","","## 🔄 Header Top Menu Modes (NEW)","","The custom header can manage the Home Assistant top bar in three different ways.","","| Mode | Description |","|------|-------------|","| `overlay` | HA top bar overlays the content |","| `push` | Content is pushed down by the HA top bar |","| `flip` | **Animated cylindrical flip between custom header and HA top bar** |","","### 🌀 Flip Mode","","The **flip mode** creates a smooth cylindrical rotation effect between:","","- Your custom header","- The original Home Assistant top bar","","✔ No layout jumps  ","✔ No content shifting  ","✔ Identical occupied space  ","","#### Configuration","","```yaml","header:","  enabled: true","  sticky: true","  topMenuMode: flip","  flipDuration: 5   # seconds (optional, default: 5)","```","","#### Trigger example","","```yaml","headerMenu:","  - action: service-js","    name: \"Top Menu\"","    icon: mdi:swap-vertical","    service: |","      if (window.silvioFlipTopMenu) {","        window.silvioFlipTopMenu();","      }","```","or","```yaml","rightMenu:","  - icon: mdi:application","    name: Top bar","    action: toggle-topmenu","```"],"stylingDirectives":[[[0,1,"pl-s"],[1,3,"pl-s"],[9,10,"pl-s"],[10,11,"pl-s"],[11,122,"pl-corl"],[122,124,"pl-s"],[124,125,"pl-s"],[125,154,"pl-corl"],[154,155,"pl-s"]],[],[[0,26,"pl-mh"],[3,26,"pl-en"]],[],[[96,97,"pl-c1"]],[],[],[],[[0,1,"pl-s"],[1,3,"pl-s"],[9,10,"pl-s"],[10,11,"pl-s"],[11,111,"pl-corl"],[111,113,"pl-s"],[113,114,"pl-s"],[114,175,"pl-corl"],[175,176,"pl-s"]],[],[[39,40,"pl-c1"]],[],[],[[0,1,"pl-s"],[1,3,"pl-s"],[9,10,"pl-s"],[10,11,"pl-s"],[11,111,"pl-corl"],[111,113,"pl-s"],[113,114,"pl-s"],[114,154,"pl-corl"],[154,155,"pl-s"]],[],[[0,1,"pl-s"],[1,3,"pl-s"],[12,13,"pl-s"],[13,14,"pl-s"],[14,120,"pl-corl"],[120,122,"pl-s"],[122,123,"pl-s"],[123,165,"pl-corl"],[165,166,"pl-s"]],[],[[0,1,"pl-s"],[1,3,"pl-s"],[10,11,"pl-s"],[11,12,"pl-s"],[12,117,"pl-corl"],[117,119,"pl-s"],[119,120,"pl-s"],[120,161,"pl-corl"],[161,162,"pl-s"]],[],[[0,47,"pl-mh"],[2,47,"pl-en"]],[[0,1,"pl-s"],[14,15,"pl-s"],[15,16,"pl-s"],[16,28,"pl-corl"],[28,29,"pl-s"]],[],[[0,18,"pl-mh"],[2,18,"pl-en"]],[[0,2,"pl-s"],[23,24,"pl-s"],[24,25,"pl-s"],[25,49,"pl-corl"],[49,50,"pl-s"]],[],[[0,18,"pl-mh"],[2,18,"pl-en"]],[[0,2,"pl-s"],[13,14,"pl-s"],[14,15,"pl-s"],[15,39,"pl-corl"],[39,40,"pl-s"]],[],[[0,17,"pl-mh"],[3,17,"pl-en"]],[[1,2,"pl-ent"],[3,8,"pl-e"],[9,10,"pl-s"],[10,16,"pl-s"],[16,17,"pl-s"]],[[3,6,"pl-ent"],[7,10,"pl-e"],[11,12,"pl-s"],[12,21,"pl-s"],[21,22,"pl-s"],[23,28,"pl-e"],[29,30,"pl-s"],[30,33,"pl-s"],[33,34,"pl-s"]],[[3,6,"pl-ent"],[7,10,"pl-e"],[11,12,"pl-s"],[12,21,"pl-s"],[21,22,"pl-s"],[23,28,"pl-e"],[29,30,"pl-s"],[30,33,"pl-s"],[33,34,"pl-s"]],[[2,3,"pl-ent"]],[],[[1,2,"pl-ent"],[3,8,"pl-e"],[9,10,"pl-s"],[10,16,"pl-s"],[16,17,"pl-s"]],[[3,6,"pl-ent"],[7,10,"pl-e"],[11,12,"pl-s"],[12,21,"pl-s"],[21,22,"pl-s"],[23,28,"pl-e"],[29,30,"pl-s"],[30,33,"pl-s"],[33,34,"pl-s"]],[[3,6,"pl-ent"],[7,10,"pl-e"],[11,12,"pl-s"],[12,21,"pl-s"],[21,22,"pl-s"],[23,28,"pl-e"],[29,30,"pl-s"],[30,33,"pl-s"],[33,34,"pl-s"]],[[2,3,"pl-ent"]],[],[[1,2,"pl-ent"],[3,8,"pl-e"],[9,10,"pl-s"],[10,16,"pl-s"],[16,17,"pl-s"]],[[3,6,"pl-ent"],[7,10,"pl-e"],[11,12,"pl-s"],[12,21,"pl-s"],[21,22,"pl-s"],[23,28,"pl-e"],[29,30,"pl-s"],[30,33,"pl-s"],[33,34,"pl-s"]],[[3,6,"pl-ent"],[7,10,"pl-e"],[11,12,"pl-s"],[12,21,"pl-s"],[21,22,"pl-s"],[23,28,"pl-e"],[29,30,"pl-s"],[30,33,"pl-s"],[33,34,"pl-s"]],[[2,3,"pl-ent"]],[],[],[[21,23,"pl-s"],[72,74,"pl-s"]],[],[[0,3,"pl-ms"]],[],[[0,18,"pl-mh"],[3,18,"pl-en"]],[],[[0,1,"pl-v"]],[[0,1,"pl-v"]],[[0,1,"pl-v"],[2,4,"pl-s"],[48,50,"pl-s"]],[[0,1,"pl-v"]],[[0,1,"pl-v"]],[[0,1,"pl-v"]],[[0,1,"pl-v"]],[[0,1,"pl-v"]],[[0,1,"pl-v"]],[[0,1,"pl-v"],[14,16,"pl-s"],[19,21,"pl-s"]],[[0,1,"pl-v"],[5,7,"pl-s"],[32,34,"pl-s"]],[],[[0,3,"pl-ms"]],[],[[0,36,"pl-mh"],[3,36,"pl-en"]],[],[[1,2,"pl-ent"],[3,8,"pl-e"],[9,10,"pl-s"],[10,16,"pl-s"],[16,17,"pl-s"]],[[3,6,"pl-ent"],[7,10,"pl-e"],[11,12,"pl-s"],[12,28,"pl-s"],[28,29,"pl-s"],[30,35,"pl-e"],[36,37,"pl-s"],[37,40,"pl-s"],[40,41,"pl-s"]],[],[],[[3,6,"pl-ent"],[7,10,"pl-e"],[11,12,"pl-s"],[12,28,"pl-s"],[28,29,"pl-s"],[30,35,"pl-e"],[36,37,"pl-s"],[37,40,"pl-s"],[40,41,"pl-s"]],[[2,3,"pl-ent"]],[],[[32,34,"pl-s"],[56,58,"pl-s"]],[],[[0,18,"pl-mh"],[4,18,"pl-en"]],[],[],[],[[0,1,"pl-s"],[1,2,"pl-v"],[3,5,"pl-s"],[19,21,"pl-s"]],[[0,1,"pl-s"],[1,2,"pl-v"],[3,5,"pl-s"],[29,31,"pl-s"]],[],[[0,15,"pl-mh"],[4,15,"pl-en"]],[],[[0,1,"pl-ml"],[6,7,"pl-ml"],[20,21,"pl-ml"]],[[0,1,"pl-ml"],[6,7,"pl-ml"],[20,21,"pl-ml"]],[[0,1,"pl-ml"],[2,4,"pl-s"],[11,13,"pl-s"],[14,15,"pl-ml"],[111,112,"pl-ml"]],[[0,1,"pl-ml"],[2,4,"pl-s"],[10,12,"pl-s"],[13,14,"pl-ml"],[123,124,"pl-ml"]],[[0,1,"pl-ml"],[2,4,"pl-s"],[8,10,"pl-s"],[11,12,"pl-ml"],[98,99,"pl-ml"]],[],[[0,16,"pl-mh"],[4,16,"pl-en"]],[],[[82,84,"pl-s"],[95,97,"pl-s"]],[],[[0,3,"pl-s"],[3,7,"pl-en"]],[[0,4,"pl-ent"],[6,24,"pl-s"]],[[0,6,"pl-ent"],[8,25,"pl-s"]],[[0,4,"pl-ent"],[6,17,"pl-s"]],[[0,4,"pl-ent"],[6,14,"pl-s"]],[[0,3,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[[0,0,"pl-s"]],[[0,18,"pl-s"]],[[0,0,"pl-s"]],[[0,118,"pl-s"]],[[0,23,"pl-s"],[22,23,"pl-pds"],[23,115,"pl-s"]],[],[],[],[[0,17,"pl-c"],[0,1,"pl-c"]],[],[[0,7,"pl-c"],[0,1,"pl-c"]],[],[[0,70,"pl-s"]],[],[[0,186,"pl-s"]],[],[],[[0,17,"pl-c"],[0,1,"pl-c"]],[],[[0,19,"pl-ent"]],[],[[0,3,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[[0,27,"pl-s"]],[[0,3,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[],[[0,21,"pl-ent"]],[],[[0,7,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[[0,27,"pl-s"]],[[0,12,"pl-s"]],[[0,3,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[],[[0,28,"pl-s"]],[],[],[],[[0,16,"pl-c"],[0,1,"pl-c"]],[],[[0,30,"pl-ent"]],[],[[0,7,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[[0,8,"pl-s"]],[[0,15,"pl-s"]],[[0,47,"pl-s"]],[[0,0,"pl-s"]],[[0,7,"pl-s"]],[[0,15,"pl-s"]],[[0,14,"pl-s"]],[[0,12,"pl-s"]],[[0,3,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[],[],[],[[0,26,"pl-c"],[0,1,"pl-c"]],[],[[0,18,"pl-c"],[0,1,"pl-c"]],[],[[0,41,"pl-s"]],[[0,41,"pl-s"]],[[0,58,"pl-s"]],[[0,60,"pl-s"]],[[0,47,"pl-s"]],[[0,50,"pl-s"]],[[0,58,"pl-s"]],[[0,78,"pl-s"]],[[0,63,"pl-s"]],[[0,68,"pl-s"]],[[0,38,"pl-s"]],[[0,59,"pl-s"]],[[0,61,"pl-s"]],[[0,64,"pl-s"]],[[0,60,"pl-s"]],[[0,71,"pl-s"]],[[0,65,"pl-s"]],[[0,57,"pl-s"]],[[0,58,"pl-s"]],[[0,55,"pl-s"]],[[0,66,"pl-s"]],[[0,55,"pl-s"]],[[0,54,"pl-s"]],[[0,70,"pl-s"]],[],[],[],[[0,22,"pl-c"],[0,1,"pl-c"]],[],[[0,7,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[[0,6,"pl-s"]],[[0,11,"pl-s"]],[[0,12,"pl-s"]],[[0,13,"pl-s"]],[[0,3,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[],[],[],[[0,23,"pl-c"],[0,1,"pl-c"]],[],[[0,7,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[[0,12,"pl-s"]],[[0,20,"pl-s"]],[[0,37,"pl-s"]],[[0,16,"pl-s"]],[[0,18,"pl-s"]],[[0,35,"pl-s"]],[[0,22,"pl-s"]],[[0,22,"pl-s"]],[[0,28,"pl-s"]],[[0,73,"pl-s"]],[[0,3,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[],[[0,21,"pl-c"],[0,1,"pl-c"]],[],[[0,24,"pl-s"]],[[0,24,"pl-s"]],[[0,38,"pl-s"]],[[0,36,"pl-s"]],[[0,28,"pl-s"]],[[0,48,"pl-s"]],[[0,37,"pl-s"]],[[0,22,"pl-s"]],[[0,65,"pl-s"]],[[0,86,"pl-s"]],[],[],[[0,21,"pl-c"],[0,1,"pl-c"]],[],[[0,23,"pl-s"]],[[0,23,"pl-s"]],[[0,23,"pl-s"]],[[0,21,"pl-s"]],[[0,42,"pl-s"]],[[0,30,"pl-s"]],[[0,30,"pl-s"]],[[0,46,"pl-s"]],[[0,57,"pl-s"]],[],[],[],[[0,16,"pl-c"],[0,1,"pl-c"]],[],[[0,29,"pl-s"]],[[0,29,"pl-s"]],[[0,37,"pl-s"]],[[0,72,"pl-s"]],[[0,62,"pl-s"]],[[0,40,"pl-s"]],[],[[0,23,"pl-c"],[0,1,"pl-c"]],[],[[0,7,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[[0,8,"pl-s"]],[[0,17,"pl-s"]],[[0,17,"pl-s"]],[[0,3,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[],[[0,7,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[[0,18,"pl-s"]],[[0,16,"pl-s"]],[[0,31,"pl-s"]],[[0,28,"pl-s"]],[[0,47,"pl-s"]],[[0,23,"pl-s"]],[[0,23,"pl-s"]],[[0,3,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[],[],[],[[0,25,"pl-c"],[0,1,"pl-c"]],[],[[0,7,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[[0,7,"pl-s"]],[[0,15,"pl-s"]],[[0,14,"pl-s"]],[[0,63,"pl-s"]],[[0,83,"pl-s"]],[[0,27,"pl-s"]],[[0,58,"pl-s"]],[[0,0,"pl-s"]],[[0,46,"pl-s"]],[[0,58,"pl-s"]],[[0,84,"pl-s"]],[[0,0,"pl-s"]],[[0,38,"pl-s"]],[[0,11,"pl-s"]],[[0,20,"pl-s"]],[[0,19,"pl-s"]],[[0,28,"pl-s"]],[[0,0,"pl-s"]],[[0,12,"pl-s"]],[[0,27,"pl-s"]],[[0,19,"pl-s"]],[[0,28,"pl-s"]],[[0,3,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[],[[0,41,"pl-s"]],[[0,41,"pl-s"]],[[0,52,"pl-s"]],[[0,60,"pl-s"]],[[0,83,"pl-s"]],[[0,94,"pl-s"]],[[0,71,"pl-ent"],[73,82,"pl-s"],[73,74,"pl-pds"],[81,82,"pl-pds"],[82,103,"pl-s"]],[[0,52,"pl-ent"],[54,111,"pl-s"]],[[0,92,"pl-s"]],[[0,75,"pl-s"]],[[0,95,"pl-s"]],[[0,84,"pl-s"]],[[0,86,"pl-s"]],[[0,63,"pl-s"]],[[0,80,"pl-s"]],[[0,84,"pl-s"]],[[0,82,"pl-s"]],[],[[0,35,"pl-c"],[0,1,"pl-c"]],[],[[0,110,"pl-s"]],[[0,99,"pl-s"]],[[0,155,"pl-s"]],[],[[0,45,"pl-ent"]],[],[[0,7,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[[0,22,"pl-s"]],[[0,3,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[[0,20,"pl-c"],[0,1,"pl-c"]],[],[[0,7,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[[0,11,"pl-s"]],[[0,20,"pl-s"]],[[0,16,"pl-s"]],[[0,18,"pl-s"]],[[0,37,"pl-s"]],[[0,45,"pl-s"]],[[0,25,"pl-s"]],[[0,25,"pl-s"]],[[0,3,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[],[],[],[[0,15,"pl-c"],[0,1,"pl-c"]],[],[[0,7,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[[0,9,"pl-s"]],[[0,11,"pl-s"]],[[0,11,"pl-s"]],[[0,11,"pl-s"]],[[0,10,"pl-s"]],[[0,11,"pl-s"]],[[0,3,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[],[[0,31,"pl-s"]],[],[],[],[[0,28,"pl-c"],[0,1,"pl-c"]],[],[[0,32,"pl-ent"]],[],[[0,7,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[[0,8,"pl-s"]],[[0,9,"pl-s"]],[[0,3,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[],[],[],[[0,35,"pl-c"],[0,1,"pl-c"]],[],[[0,3,"pl-s"]],[],[],[],[],[],[],[],[],[],[],[],[],[],[],[],[],[],[],[],[],[[0,3,"pl-s"],[3,3,"pl-c1"]],[[0,0,"pl-c1"]],[[0,3,"pl-c1"]],[[0,0,"pl-c1"]],[[0,40,"pl-c1"]],[[0,0,"pl-c1"]],[[0,0,"pl-c1"],[0,3,"pl-s"]],[],[],[],[],[],[],[],[],[],[],[],[],[],[],[],[],[],[],[[0,3,"pl-s"],[3,3,"pl-c1"]],[[0,0,"pl-c1"]],[[0,3,"pl-c1"]],[[0,0,"pl-c1"]],[[0,35,"pl-c1"]],[[0,0,"pl-c1"]],[[0,0,"pl-c1"],[0,3,"pl-s"]],[],[],[],[],[],[],[],[],[],[],[],[],[],[],[],[],[],[],[],[],[[0,3,"pl-s"],[3,3,"pl-c1"]],[[0,0,"pl-c1"]],[[0,3,"pl-c1"]],[[0,0,"pl-c1"]],[[0,30,"pl-c1"]],[[0,0,"pl-c1"]],[[0,0,"pl-c1"],[0,3,"pl-s"]],[],[],[],[[0,3,"pl-s"],[3,3,"pl-c1"]],[[0,0,"pl-c1"]],[[0,3,"pl-c1"]],[[0,0,"pl-c1"]],[[0,22,"pl-c1"]],[[0,0,"pl-c1"]],[[0,0,"pl-c1"],[0,3,"pl-s"]],[],[],[],[],[[0,3,"pl-s"],[3,3,"pl-c1"]],[[0,0,"pl-c1"]],[[0,3,"pl-c1"]],[[0,0,"pl-c1"]],[[0,20,"pl-c1"]],[[0,0,"pl-c1"]],[[0,49,"pl-c1"]],[[0,42,"pl-c1"]],[[0,40,"pl-c1"]],[[0,0,"pl-c1"]],[[0,3,"pl-c1"]],[[0,0,"pl-c1"]],[[0,12,"pl-c1"]],[[0,30,"pl-c1"]],[[0,0,"pl-c1"]],[[0,29,"pl-c1"]],[[0,0,"pl-c1"]],[[0,3,"pl-c1"]],[[0,0,"pl-c1"]],[[0,33,"pl-c1"]],[[0,0,"pl-c1"]],[[0,80,"pl-c1"]],[[0,0,"pl-c1"]],[[0,22,"pl-c1"]],[[0,22,"pl-c1"]],[[0,47,"pl-c1"]],[[0,53,"pl-c1"]],[[0,79,"pl-c1"]],[[0,0,"pl-c1"]],[[0,16,"pl-c1"]],[[0,0,"pl-c1"]],[[0,71,"pl-c1"]],[[0,0,"pl-c1"]],[[0,20,"pl-c1"]],[[0,37,"pl-c1"]],[[0,0,"pl-c1"]],[[0,19,"pl-c1"]],[[0,23,"pl-c1"]],[[0,28,"pl-c1"]],[[0,0,"pl-c1"]],[[0,18,"pl-c1"]],[[0,0,"pl-c1"]],[[0,7,"pl-c1"]],[[0,7,"pl-c1"]],[[0,15,"pl-c1"]],[[0,14,"pl-c1"]],[[0,19,"pl-c1"]],[[0,52,"pl-c1"]],[[0,0,"pl-c1"],[0,3,"pl-s"]],[],[[0,20,"pl-mh"],[5,20,"pl-en"]],[],[[0,3,"pl-s"],[3,7,"pl-en"]],[[0,10,"pl-ent"]],[[4,10,"pl-ent"],[12,22,"pl-s"]],[[4,8,"pl-ent"],[10,20,"pl-s"],[10,11,"pl-pds"],[19,20,"pl-pds"]],[[4,8,"pl-ent"],[10,27,"pl-s"]],[[4,11,"pl-ent"],[13,14,"pl-s"]],[[0,37,"pl-s"]],[[0,35,"pl-s"]],[[0,7,"pl-s"]],[[0,0,"pl-s"],[0,3,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]],[[0,2,"pl-s"]],[[0,3,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"],[3,7,"pl-s"]],[[0,9,"pl-ent"]],[[4,8,"pl-ent"],[10,25,"pl-s"]],[[4,8,"pl-ent"],[10,17,"pl-s"]],[[4,10,"pl-ent"],[12,26,"pl-s"]],[[0,3,"pl-s"],[0,1,"pl-pds"],[1,2,"pl-pds"],[2,3,"pl-pds"]]],"colorizedLines":null}},"title":"sidebar-card/README.md at main · rockbaer2007/sidebar-card","appPayload":{},"meta":{"title":"sidebar-card/README.md at main · rockbaer2007/sidebar-card"}}</script>
  <div data-target="react-app.reactRoot"><meta name="github-code-view-meta-stats" id="github-code-view-meta-stats" data-hydrostats="publish"/> <!-- --> <a hidden="" id="code-view-repo-link" href="/rockbaer2007/sidebar-card" data-discover="true"></a> <div class="d-none"></div><div><div style="--spacing:var(--spacing-none)" class="prc-PageLayout-PageLayoutRoot--KH-d"><div class="prc-PageLayout-PageLayoutWrapper-2BhU2" data-width="full"><div class="prc-PageLayout-PageLayoutContent-BneH9"><div class="CodeViewFileTreeLayout-module__sidebar__n_Aau" tabindex="0"><div class="prc-PageLayout-PaneWrapper-pHPop ReposFileTreePane-module__Pane__rBZpI ReposFileTreePane-module__HideTree__AYZnm ReposFileTreePane-module__HidePane__VHAVt" style="--offset-header:0px;--spacing-row:var(--spacing-none);--spacing-column:var(--spacing-none)" data-is-hidden="false" data-position="start" data-sticky="true"><div class="prc-PageLayout-HorizontalDivider-JLVqp prc-PageLayout-PaneHorizontalDivider-9tbnE" data-variant-regular="none" data-variant-narrow="none" data-position="start" style="--spacing-divider:var(--spacing-none);--spacing:var(--spacing-none)"></div><div class="prc-PageLayout-Pane-AyzHK" data-resizable="true" style="--spacing:var(--spacing-none);--pane-min-width:256px;--pane-max-width:calc(100vw - var(--pane-max-width-diff));--pane-width-size:var(--pane-width-large);--pane-width:320px"></div><div class="prc-PageLayout-VerticalDivider-9QRmK prc-PageLayout-PaneVerticalDivider-le57g" data-variant-narrow="none" data-variant-regular="line" data-variant-wide="line" data-position="start" style="--spacing:var(--spacing-none)"><div class="prc-PageLayout-DraggableHandle-9s6B4" role="slider" aria-label="Draggable pane splitter" aria-valuemin="256" aria-valuemax="600" aria-valuenow="320" aria-valuetext="Pane width 320 pixels" tabindex="0"></div></div></div></div><div class="prc-PageLayout-ContentWrapper-gR9eG"><div class="prc-PageLayout-Content-xWL-A" data-width="full" style="--spacing:var(--spacing-none)"><div class="SharedPageLayout-module__content__IwGAp" data-selector="repos-split-pane-content" tabindex="0"> <!-- --> <div class="container CodeViewHeader-module__Box__JkPOb"><div class="CodeViewHeader-module__StickyHeader__Qn7UN" id="StickyHeader"><div class="CodeViewHeader-module__Box_1__SbNDV"><div class="CodeViewHeader-module__Box_2__TB46f"><div class="react-code-view-header-wrap--narrow CodeViewHeader-module__Box_3__q1zUL"><div class="CodeViewHeader-module__treeToggleWrapper__RQ__9"><h2 class="use-tree-pane-module__Heading__s4QbZ prc-Heading-Heading-MtWFE"><button data-component="Button" type="button" aria-label="Expand file tree" data-testid="expand-file-tree-button-mobile" class="prc-Button-ButtonBase-9n-Xk ExpandFileTreeButton-module__Button_1__Svs95" data-loading="false" data-size="medium" data-variant="invisible"><span data-component="buttonContent" data-align="center" class="prc-Button-ButtonContent-Iohp5"><span data-component="leadingVisual" class="prc-Button-Visual-YNt2F prc-Button-VisualWrap-E4cnq"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-arrow-left" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M7.78 12.53a.75.75 0 0 1-1.06 0L2.47 8.28a.75.75 0 0 1 0-1.06l4.25-4.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042L4.81 7h7.44a.75.75 0 0 1 0 1.5H4.81l2.97 2.97a.75.75 0 0 1 0 1.06Z"></path></svg></span><span data-component="text" class="prc-Button-Label-FWkx3">Files</span></span></button><button data-component="IconButton" type="button" data-testid="expand-file-tree-button" aria-controls="repos-file-tree" class="prc-Button-ButtonBase-9n-Xk position-relative ExpandFileTreeButton-module__expandButton__hDOcv ExpandFileTreeButton-module__filesButtonBreakpoint__zEvz3 fgColor-muted prc-Button-IconButton-fyge7" data-loading="false" data-no-visuals="true" data-size="medium" data-variant="invisible" aria-labelledby="_R_2aql3al1d_"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-sidebar-collapse" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M6.823 7.823a.25.25 0 0 1 0 .354l-2.396 2.396A.25.25 0 0 1 4 10.396V5.604a.25.25 0 0 1 .427-.177Z"></path><path d="M1.75 0h12.5C15.216 0 16 .784 16 1.75v12.5A1.75 1.75 0 0 1 14.25 16H1.75A1.75 1.75 0 0 1 0 14.25V1.75C0 .784.784 0 1.75 0ZM1.5 1.75v12.5c0 .138.112.25.25.25H9.5v-13H1.75a.25.25 0 0 0-.25.25ZM11 14.5h3.25a.25.25 0 0 0 .25-.25V1.75a.25.25 0 0 0-.25-.25H11Z"></path></svg></button><span class="prc-TooltipV2-Tooltip-tLeuB" data-direction="se" data-component="Tooltip" aria-hidden="true" id="_R_2aql3al1d_">Expand file tree</span><div class="d-none"></div></h2></div><div class="react-code-view-header-mb--narrow mr-2"><button data-component="Button" type="button" aria-haspopup="true" aria-expanded="false" tabindex="0" aria-label="main branch" data-testid="anchor-button" data-icv-name="Switch branches/tags" class="prc-Button-ButtonBase-9n-Xk ref-selector-class RefSelectorAnchoredOverlay-module__RefSelectorOverlayBtn__a3WK3" data-loading="false" data-size="medium" data-variant="default" id="ref-picker-repos-header-ref-selector-wide"><span data-component="buttonContent" data-align="center" class="prc-Button-ButtonContent-Iohp5"><span data-component="text" class="prc-Button-Label-FWkx3"><div class="RefSelectorAnchoredOverlay-module__RefSelectorOverlayContainer__yaf4p"><div class="RefSelectorAnchoredOverlay-module__RefSelectorOverlayHeader__XtXRG"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-git-branch" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M9.5 3.25a2.25 2.25 0 1 1 3 2.122V6A2.5 2.5 0 0 1 10 8.5H6a1 1 0 0 0-1 1v1.128a2.251 2.251 0 1 1-1.5 0V5.372a2.25 2.25 0 1 1 1.5 0v1.836A2.493 2.493 0 0 1 6 7h4a1 1 0 0 0 1-1v-.628A2.25 2.25 0 0 1 9.5 3.25Zm-6 0a.75.75 0 1 0 1.5 0 .75.75 0 0 0-1.5 0Zm8.25-.75a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5ZM4.25 12a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5Z"></path></svg></div><div style="max-width:125px" class="ref-selector-button-text-container RefSelectorAnchoredOverlay-module__RefSelectorBtnTextContainer__Di3rk"><span class="RefSelectorAnchoredOverlay-module__RefSelectorText__w_fmP"> <!-- -->main</span></div></div></span><span data-component="trailingVisual" class="prc-Button-Visual-YNt2F prc-Button-VisualWrap-E4cnq"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-triangle-down" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="m4.427 7.427 3.396 3.396a.25.25 0 0 0 .354 0l3.396-3.396A.25.25 0 0 0 11.396 7H4.604a.25.25 0 0 0-.177.427Z"></path></svg></span></span></button><div class="d-none"></div></div><div class="react-code-view-header-mb--narrow CodeViewHeader-module__Box_5__MQ0hL"><div class="Breadcrumb-module__container__Vxvev Breadcrumb-module__lg__Rjz0A"><nav data-testid="breadcrumbs" aria-labelledby="repos-header-breadcrumb-heading" id="repos-header-breadcrumb" class="Breadcrumb-module__nav__rQFDj"><h2 class="sr-only ScreenReaderHeading-module__userSelectNone__rwWIk prc-Heading-Heading-MtWFE" data-testid="screen-reader-heading" id="repos-header-breadcrumb-heading">Breadcrumbs</h2><ol class="Breadcrumb-module__list__ZH6zr"><li class="Breadcrumb-module__listItem__Ib0x_"><a class="Breadcrumb-module__repoLink__O2Nbs prc-Link-Link-9ZwDx" data-component="Link" data-testid="breadcrumbs-repo-link" href="/rockbaer2007/sidebar-card/tree/main" data-discover="true">sidebar-card</a></li></ol></nav><div data-testid="breadcrumbs-filename" class="Breadcrumb-module__filename__equZR"><span class="Breadcrumb-module__separator__eNwsI Breadcrumb-module__lg__Rjz0A" aria-hidden="true">/</span><h1 class="Breadcrumb-module__filenameHeading__MNMtw Breadcrumb-module__lg__Rjz0A prc-Heading-Heading-MtWFE" tabindex="-1" id="file-name-id">README.md</h1></div><button data-component="IconButton" type="button" class="prc-Button-ButtonBase-9n-Xk ml-2 prc-Button-IconButton-fyge7" data-loading="false" data-no-visuals="true" data-size="small" data-variant="invisible" aria-labelledby="_R_3qql3al1d_"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-copy" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path></svg></button><span class="CopyToClipboardButton-module__tooltip__BhMvU prc-TooltipV2-Tooltip-tLeuB" data-direction="nw" data-component="Tooltip" aria-label="Copy path" aria-hidden="true" id="_R_3qql3al1d_">Copy path</span></div></div></div><div class="react-code-view-header-element--wide"><div class="CodeViewHeader-module__Box_7___0R6c"><div class="d-flex gap-2"><div><div class="CodeViewHeader-module__FileResultsList__JDzUy"><span class="d-flex FileResultsList-module__FilesSearchBox__ivVkc TextInput-wrapper prc-components-TextInputWrapper-Hpdqi prc-components-TextInputBaseWrapper-wY-n0" data-component="TextInput" data-leading-visual="true" data-trailing-visual="true" aria-busy="false"><span class="TextInput-icon" id="_R_2pcql3al1d_" aria-hidden="true" data-component="TextInput.LeadingVisual"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-search" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M10.68 11.74a6 6 0 0 1-7.922-8.982 6 6 0 0 1 8.982 7.922l3.04 3.04a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215ZM11.5 7a4.499 4.499 0 1 0-8.997 0A4.499 4.499 0 0 0 11.5 7Z"></path></svg></span><input type="text" aria-label="Go to file" role="combobox" aria-controls="file-results-list" aria-expanded="false" aria-haspopup="dialog" autoCorrect="off" spellCheck="false" placeholder="Go to file" aria-describedby="_R_2pcql3al1d_ _R_2pcql3al1dH1_" data-component="input" class="prc-components-Input-IwWrt" value=""/><span class="TextInput-icon" id="_R_2pcql3al1dH1_" aria-hidden="true" data-component="TextInput.TrailingVisual"></span></span></div><div class="d-none"></div></div><button data-component="Button" type="button" style="display:none" class="prc-Button-ButtonBase-9n-Xk NavigationMenu-module__Button__LpKgm" data-loading="false" data-no-visuals="true" data-size="medium" data-variant="default"><span data-component="buttonContent" data-align="center" class="prc-Button-ButtonContent-Iohp5"><span data-component="text" class="prc-Button-Label-FWkx3">Blame</span></span></button><div class="d-none"></div><button data-component="IconButton" type="button" data-testid="more-file-actions-button-nav-menu-wide" aria-haspopup="true" aria-expanded="false" tabindex="0" class="prc-Button-ButtonBase-9n-Xk js-blob-dropdown-click NavigationMenu-module__IconButton__HpX3G prc-Button-IconButton-fyge7" data-loading="false" data-no-visuals="true" data-size="medium" data-variant="default" aria-labelledby="_R_ficql3al1d_" id="_R_icql3al1d_"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-kebab-horizontal" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M8 9a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3ZM1.5 9a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3Zm13 0a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3Z"></path></svg></button><span class="prc-TooltipV2-Tooltip-tLeuB" data-direction="nw" data-component="Tooltip" aria-hidden="true" id="_R_ficql3al1d_">More file actions</span></div></div></div><div class="react-code-view-header-element--narrow"><div class="CodeViewHeader-module__Box_7___0R6c"><div class="d-flex gap-2"><button data-component="Button" type="button" style="display:none" class="prc-Button-ButtonBase-9n-Xk NavigationMenu-module__Button__LpKgm" data-loading="false" data-no-visuals="true" data-size="medium" data-variant="default"><span data-component="buttonContent" data-align="center" class="prc-Button-ButtonContent-Iohp5"><span data-component="text" class="prc-Button-Label-FWkx3">Blame</span></span></button><div class="d-none"></div><button data-component="IconButton" type="button" data-testid="more-file-actions-button-nav-menu-narrow" aria-haspopup="true" aria-expanded="false" tabindex="0" class="prc-Button-ButtonBase-9n-Xk js-blob-dropdown-click NavigationMenu-module__IconButton__HpX3G prc-Button-IconButton-fyge7" data-loading="false" data-no-visuals="true" data-size="medium" data-variant="default" aria-labelledby="_R_fieql3al1d_" id="_R_ieql3al1d_"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-kebab-horizontal" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M8 9a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3ZM1.5 9a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3Zm13 0a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3Z"></path></svg></button><span class="prc-TooltipV2-Tooltip-tLeuB" data-direction="nw" data-component="Tooltip" aria-hidden="true" id="_R_fieql3al1d_">More file actions</span></div></div></div></div></div></div></div><div class="CodeView-module__contentWrapper__cG2JH"><div class="react-code-view-bottom-padding"><div class="BlobTopBanners-module__Box__v_nvx"></div></div> <div class="d-none"></div><div class="d-flex flex-column border rounded-2 tmp-mb-3 pl-1"><div class="LatestCommit-module__Box__B25ZT"><h2 class="sr-only ScreenReaderHeading-module__userSelectNone__rwWIk prc-Heading-Heading-MtWFE" data-testid="screen-reader-heading">Latest commit</h2><div style="width:120px" class="Skeleton Skeleton--text" data-testid="loading"> </div><div class="d-flex flex-shrink-0 gap-2"><div data-testid="latest-commit-details" class="d-none d-sm-flex flex-items-center"></div><div class="d-flex gap-2"><h2 class="sr-only ScreenReaderHeading-module__userSelectNone__rwWIk prc-Heading-Heading-MtWFE" data-testid="screen-reader-heading">History</h2><a data-component="LinkButton" href="/rockbaer2007/sidebar-card/commits/main/README.md" class="prc-Button-ButtonBase-9n-Xk d-none d-lg-flex LinkButton-module__linkButton__nFnov flex-items-center fgColor-default" data-loading="false" data-size="small" data-variant="invisible"><span data-component="buttonContent" data-align="center" class="prc-Button-ButtonContent-Iohp5"><span data-component="leadingVisual" class="prc-Button-Visual-YNt2F prc-Button-VisualWrap-E4cnq"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-history" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="m.427 1.927 1.215 1.215a8.002 8.002 0 1 1-1.6 5.685.75.75 0 1 1 1.493-.154 6.5 6.5 0 1 0 1.18-4.458l1.358 1.358A.25.25 0 0 1 3.896 6H.25A.25.25 0 0 1 0 5.75V2.104a.25.25 0 0 1 .427-.177ZM7.75 4a.75.75 0 0 1 .75.75v2.992l2.028.812a.75.75 0 0 1-.557 1.392l-2.5-1A.751.751 0 0 1 7 8.25v-3.5A.75.75 0 0 1 7.75 4Z"></path></svg></span><span data-component="text" class="prc-Button-Label-FWkx3"><span class="fgColor-default">History</span></span></span></a><div class="d-sm-none"></div><div class="d-flex d-lg-none"><a data-component="LinkButton" aria-label="View commit history for this file." href="/rockbaer2007/sidebar-card/commits/main/README.md" class="prc-Button-ButtonBase-9n-Xk LinkButton-module__linkButton__nFnov flex-items-center fgColor-default" data-loading="false" data-size="small" data-variant="invisible" aria-describedby="_R_2balal3al1d_"><span data-component="buttonContent" data-align="center" class="prc-Button-ButtonContent-Iohp5"><span data-component="leadingVisual" class="prc-Button-Visual-YNt2F prc-Button-VisualWrap-E4cnq"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-history" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="m.427 1.927 1.215 1.215a8.002 8.002 0 1 1-1.6 5.685.75.75 0 1 1 1.493-.154 6.5 6.5 0 1 0 1.18-4.458l1.358 1.358A.25.25 0 0 1 3.896 6H.25A.25.25 0 0 1 0 5.75V2.104a.25.25 0 0 1 .427-.177ZM7.75 4a.75.75 0 0 1 .75.75v2.992l2.028.812a.75.75 0 0 1-.557 1.392l-2.5-1A.751.751 0 0 1 7 8.25v-3.5A.75.75 0 0 1 7.75 4Z"></path></svg></span></span></a><span class="prc-TooltipV2-Tooltip-tLeuB" data-direction="s" data-component="Tooltip" role="tooltip" aria-hidden="true" id="_R_2balal3al1d_">History</span></div></div></div></div></div><div class="d-flex flex-row"><div class="container BlobViewContent-module__blobContainer__DtH2d"><div class="react-code-size-details-banner BlobViewContent-module__codeSizeDetails__e5sUw"><div class="react-code-size-details-banner CodeSizeDetails-module__Box__VcD6l"><div class="text-mono CodeSizeDetails-module__Box_1__GVxQL"><div data-testid="blob-size" class="CodeSizeDetails-module__Truncate_1__lE93V prc-Truncate-Truncate-2G1eo" data-inline="true" title="13.9 KB" style="--truncate-max-width:100%"><span>530 lines (405 loc) · 13.9 KB</span></div></div></div></div><div class="react-blob-view-header-sticky BlobViewContent-module__stickyHeader__VwxB5" id="repos-sticky-header"><div class="BlobViewHeader-module__Box__yhm9u"><div class="react-blob-sticky-header"><div class="FileNameStickyHeader-module__outerWrapper__ZL4Xc FileNameStickyHeader-module__outerWrapperHidden__Zpynk"><div class="FileNameStickyHeader-module__Box_1__Hazu5"><div class="FileNameStickyHeader-module__Box_2__hoolP"><div class="FileNameStickyHeader-module__Box_3__MVKsk"><button data-component="Button" type="button" aria-haspopup="true" aria-expanded="false" tabindex="0" aria-label="main branch" data-testid="anchor-button" data-icv-name="Switch branches/tags" class="prc-Button-ButtonBase-9n-Xk ref-selector-class RefSelectorAnchoredOverlay-module__RefSelectorOverlayBtn__a3WK3" data-loading="false" data-size="medium" data-variant="default" id="ref-picker-repos-header-ref-selector"><span data-component="buttonContent" data-align="center" class="prc-Button-ButtonContent-Iohp5"><span data-component="text" class="prc-Button-Label-FWkx3"><div class="RefSelectorAnchoredOverlay-module__RefSelectorOverlayContainer__yaf4p"><div class="RefSelectorAnchoredOverlay-module__RefSelectorOverlayHeader__XtXRG"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-git-branch" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M9.5 3.25a2.25 2.25 0 1 1 3 2.122V6A2.5 2.5 0 0 1 10 8.5H6a1 1 0 0 0-1 1v1.128a2.251 2.251 0 1 1-1.5 0V5.372a2.25 2.25 0 1 1 1.5 0v1.836A2.493 2.493 0 0 1 6 7h4a1 1 0 0 0 1-1v-.628A2.25 2.25 0 0 1 9.5 3.25Zm-6 0a.75.75 0 1 0 1.5 0 .75.75 0 0 0-1.5 0Zm8.25-.75a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5ZM4.25 12a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5Z"></path></svg></div><div style="max-width:125px" class="ref-selector-button-text-container RefSelectorAnchoredOverlay-module__RefSelectorBtnTextContainer__Di3rk"><span class="RefSelectorAnchoredOverlay-module__RefSelectorText__w_fmP"> <!-- -->main</span></div></div></span><span data-component="trailingVisual" class="prc-Button-Visual-YNt2F prc-Button-VisualWrap-E4cnq"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-triangle-down" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="m4.427 7.427 3.396 3.396a.25.25 0 0 0 .354 0l3.396-3.396A.25.25 0 0 0 11.396 7H4.604a.25.25 0 0 0-.177.427Z"></path></svg></span></span></button><div class="d-none"></div></div><div class="FileNameStickyHeader-module__Box_4__FLhtt"><div class="Breadcrumb-module__container__Vxvev Breadcrumb-module__md__Wb1Gs"><nav data-testid="breadcrumbs" aria-labelledby="sticky-breadcrumb-heading" id="sticky-breadcrumb" class="Breadcrumb-module__nav__rQFDj"><h2 class="sr-only ScreenReaderHeading-module__userSelectNone__rwWIk prc-Heading-Heading-MtWFE" data-testid="screen-reader-heading" id="sticky-breadcrumb-heading">Breadcrumbs</h2><ol class="Breadcrumb-module__list__ZH6zr"><li class="Breadcrumb-module__listItem__Ib0x_"><a class="Breadcrumb-module__repoLink__O2Nbs prc-Link-Link-9ZwDx" data-component="Link" data-testid="breadcrumbs-repo-link" href="/rockbaer2007/sidebar-card/tree/main" data-discover="true">sidebar-card</a></li></ol></nav><div data-testid="breadcrumbs-filename" class="Breadcrumb-module__filename__equZR"><span class="Breadcrumb-module__separator__eNwsI Breadcrumb-module__md__Wb1Gs" aria-hidden="true">/</span><h1 class="Breadcrumb-module__filenameHeading__MNMtw Breadcrumb-module__md__Wb1Gs prc-Heading-Heading-MtWFE" tabindex="-1" id="sticky-file-name-id">README.md</h1></div></div></div></div><button data-component="Button" type="button" class="prc-Button-ButtonBase-9n-Xk FileNameStickyHeader-module__Button__LSEU_ FileNameStickyHeader-module__GoToTopButton__nxAFn" data-loading="false" data-size="small" data-variant="invisible"><span data-component="buttonContent" data-align="center" class="prc-Button-ButtonContent-Iohp5"><span data-component="leadingVisual" class="prc-Button-Visual-YNt2F prc-Button-VisualWrap-E4cnq"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-arrow-up" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M3.47 7.78a.75.75 0 0 1 0-1.06l4.25-4.25a.75.75 0 0 1 1.06 0l4.25 4.25a.751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018L9 4.81v7.44a.75.75 0 0 1-1.5 0V4.81L4.53 7.78a.75.75 0 0 1-1.06 0Z"></path></svg></span><span data-component="text" class="prc-Button-Label-FWkx3">Top</span></span></button></div></div></div><div class="BlobViewHeader-module__Box_1__VEmuQ"><h2 class="sr-only ScreenReaderHeading-module__userSelectNone__rwWIk prc-Heading-Heading-MtWFE" data-testid="screen-reader-heading">File metadata and controls</h2><div class="BlobViewHeader-module__Box_2__icUs2"><ul aria-label="File view" class="prc-SegmentedControl-SegmentedControl-lqIXp BlobTabButtons-module__SegmentedControl__jen2u" data-variant="default" data-size="small"><li class="prc-SegmentedControl-Item-tSCQh" data-selected=""><button aria-current="true" class="prc-SegmentedControl-Button-E48xz" type="button" style="--separator-color:transparent"><span class="prc-SegmentedControl-Content-1COlk segmentedControl-content"><div class="prc-SegmentedControl-Text-7S2y2 segmentedControl-text" data-text="Preview">Preview</div></span></button></li><li class="prc-SegmentedControl-Item-tSCQh"><button aria-current="false" class="prc-SegmentedControl-Button-E48xz" type="button" style="--separator-color:var(--borderColor-default)"><span class="prc-SegmentedControl-Content-1COlk segmentedControl-content"><div class="prc-SegmentedControl-Text-7S2y2 segmentedControl-text" data-text="Code">Code</div></span></button></li><li class="prc-SegmentedControl-Item-tSCQh"><button aria-current="false" class="prc-SegmentedControl-Button-E48xz" type="button" style="--separator-color:var(--borderColor-default)"><span class="prc-SegmentedControl-Content-1COlk segmentedControl-content"><div class="prc-SegmentedControl-Text-7S2y2 segmentedControl-text" data-text="Blame">Blame</div></span></button></li></ul><div class="d-none"></div><div class="react-code-size-details-in-header CodeSizeDetails-module__Box__VcD6l"><div class="text-mono CodeSizeDetails-module__Box_1__GVxQL"><div data-testid="blob-size" class="CodeSizeDetails-module__Truncate_1__lE93V prc-Truncate-Truncate-2G1eo" data-inline="true" title="13.9 KB" style="--truncate-max-width:100%"><span>530 lines (405 loc) · 13.9 KB</span></div></div></div></div><div class="BlobViewHeader-module__Box_3__ng6v2"><div class="d-none"></div><div class="react-blob-header-edit-and-raw-actions BlobViewHeader-module__Box_4__J4Y4W"><div class="d-none"></div><div class="prc-ButtonGroup-ButtonGroup-vFUrY"><div><a data-component="LinkButton" href="https://github.com/rockbaer2007/sidebar-card/raw/refs/heads/main/README.md" data-testid="raw-button" class="prc-Button-ButtonBase-9n-Xk LinkButton-module__linkButton__nFnov BlobViewHeader-module__LinkButton__X9kx2" data-loading="false" data-no-visuals="true" data-size="small" data-variant="default"><span data-component="buttonContent" data-align="center" class="prc-Button-ButtonContent-Iohp5"><span data-component="text" class="prc-Button-Label-FWkx3">Raw</span></span></a></div><div><button data-component="IconButton" type="button" data-testid="copy-raw-button" class="prc-Button-ButtonBase-9n-Xk prc-Button-IconButton-fyge7" data-loading="false" data-no-visuals="true" data-size="small" data-variant="default" aria-labelledby="_R_d5f6clal3al1d_"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-copy" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path></svg></button><span class="prc-TooltipV2-Tooltip-tLeuB" data-direction="n" data-component="Tooltip" aria-hidden="true" id="_R_d5f6clal3al1d_">Copy raw file</span></div><div><button data-component="IconButton" type="button" data-testid="download-raw-button" class="prc-Button-ButtonBase-9n-Xk BlobViewHeader-module__downloadButton__ef459 prc-Button-IconButton-fyge7" data-loading="false" data-no-visuals="true" data-size="small" data-variant="default" aria-labelledby="_R_75f6clal3al1d_"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-download" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M2.75 14A1.75 1.75 0 0 1 1 12.25v-2.5a.75.75 0 0 1 1.5 0v2.5c0 .138.112.25.25.25h10.5a.25.25 0 0 0 .25-.25v-2.5a.75.75 0 0 1 1.5 0v2.5A1.75 1.75 0 0 1 13.25 14Z"></path><path d="M7.25 7.689V2a.75.75 0 0 1 1.5 0v5.689l1.97-1.969a.749.749 0 1 1 1.06 1.06l-3.25 3.25a.749.749 0 0 1-1.06 0L4.22 6.78a.749.749 0 1 1 1.06-1.06l1.97 1.969Z"></path></svg></button><span class="prc-TooltipV2-Tooltip-tLeuB" data-direction="n" data-component="Tooltip" aria-hidden="true" id="_R_75f6clal3al1d_">Download raw file</span></div></div></div><button data-component="IconButton" type="button" aria-pressed="false" class="prc-Button-ButtonBase-9n-Xk tmp-mr-2 TableOfContents-module__IconButton__jrlNM prc-Button-IconButton-fyge7" data-loading="false" data-no-visuals="true" data-size="small" data-variant="invisible" aria-labelledby="_R_1v6clal3al1d_"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-list-unordered" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M5.75 2.5h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5Zm0 5h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5Zm0 5h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5ZM2 14a1 1 0 1 1 0-2 1 1 0 0 1 0 2Zm1-6a1 1 0 1 1-2 0 1 1 0 0 1 2 0ZM2 4a1 1 0 1 1 0-2 1 1 0 0 1 0 2Z"></path></svg></button><span class="prc-TooltipV2-Tooltip-tLeuB" data-direction="n" data-component="Tooltip" aria-hidden="true" id="_R_1v6clal3al1d_">Outline</span><div class="react-blob-header-edit-and-raw-actions-combined"><button data-component="IconButton" type="button" title="More file actions" data-testid="more-file-actions-button" aria-haspopup="true" aria-expanded="false" tabindex="0" class="prc-Button-ButtonBase-9n-Xk js-blob-dropdown-click BlobViewHeader-module__IconButton__XrMQY prc-Button-IconButton-fyge7" data-loading="false" data-no-visuals="true" data-size="small" data-variant="invisible" aria-labelledby="_R_7q76clal3al1d_" id="_R_a76clal3al1d_"><svg data-component="Octicon" aria-hidden="true" focusable="false" class="octicon octicon-kebab-horizontal" viewBox="0 0 16 16" width="16" height="16" fill="currentColor" display="inline-block" overflow="visible" style="vertical-align:text-bottom"><path d="M8 9a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3ZM1.5 9a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3Zm13 0a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3Z"></path></svg></button><span class="prc-TooltipV2-Tooltip-tLeuB" data-direction="nw" data-component="Tooltip" aria-hidden="true" id="_R_7q76clal3al1d_">Edit and raw actions</span></div></div></div></div><div></div></div><div class="BlobViewContent-module__blobContentWrapper__JS0W6"><section aria-labelledby="file-name-id-wide file-name-id-mobile" class="BlobContent-module__blobContentSection__VOgZq BlobContent-module__blobContentSectionMarkdown__mPLOK" style="margin-top:46px"><div class="js-snippet-clipboard-copy-unpositioned BlobContent-module__markdownBlob__T8jpG" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p dir="auto"><a href="https://ko-fi.com/silviosmart" rel="nofollow"><img src="https://camo.githubusercontent.com/dc897cd523cd71e727b4f7b042cc28c34dcc2bc7c711a057c4772ff8449d2d45/68747470733a2f2f73746f726167652e6b6f2d66692e636f6d2f63646e2f67656e6572617465642f7a66736b6667716e662f323032352d30332d30375f726573742d37643831616364393031616266313031636264663534343433633338663666302d646c6d6d6f6e70682e6a7067" alt="Sample" data-canonical-src="https://storage.ko-fi.com/cdn/generated/zfskfgqnf/2025-03-07_rest-7d81acd901abf101cbdf54443c38f6f0-dlmmonph.jpg" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">Supportami / Support Me</h2><a id="user-content-supportami--support-me" class="anchor" aria-label="Permalink: Supportami / Support Me" href="#supportami--support-me"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">Se ti piace il mio lavoro e vuoi che continui nello sviluppo delle card, puoi offrirmi un caffè.<br>
If you like my work and want me to continue developing the cards, you can buy me a coffee.</p>
<p dir="auto"><a href="https://www.paypal.com/donate/?hosted_button_id=Z6KY9V6BBZ4BN" rel="nofollow"><img src="https://camo.githubusercontent.com/44211f937e0611225f445aeffeebd12e631b9721db99c94915ae4266cdf685c2/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d50617950616c2d2532333030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465" alt="PayPal" data-canonical-src="https://img.shields.io/badge/Donate-PayPal-%2300457C?style=for-the-badge&amp;logo=paypal&amp;logoColor=white" style="max-width: 100%;"></a></p>
<p dir="auto">Non dimenticare di seguirmi sui social:<br>
Don't forget to follow me on social media:</p>
<p dir="auto"><a href="https://www.tiktok.com/@silviosmartalexa" rel="nofollow"><img src="https://camo.githubusercontent.com/d5bfced6e5f9e720c61eb1191659b2778a9ee29c5971216e7bf65ea399a265f7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f466f6c6c6f775f54696b546f6b2d2532333030303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d74696b746f6b266c6f676f436f6c6f723d7768697465" alt="TikTok" data-canonical-src="https://img.shields.io/badge/Follow_TikTok-%23000000?style=for-the-badge&amp;logo=tiktok&amp;logoColor=white" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://www.instagram.com/silviosmartalexa" rel="nofollow"><img src="https://camo.githubusercontent.com/e32214b0c0ddda76f1faa3bfb9fe4cf5132ee2ecc2d30874714d40e58222f0bd/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f466f6c6c6f775f496e7374616772616d2d2532334531333036433f7374796c653d666f722d7468652d6261646765266c6f676f3d696e7374616772616d266c6f676f436f6c6f723d7768697465" alt="Instagram" data-canonical-src="https://img.shields.io/badge/Follow_Instagram-%23E1306C?style=for-the-badge&amp;logo=instagram&amp;logoColor=white" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://www.youtube.com/@silviosmartalexa" rel="nofollow"><img src="https://camo.githubusercontent.com/9f575870fb3161c74d2c8b743e2d12896b813a2350d31aa5263a38854d0d7a54/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5375627363726962655f596f75547562652d2532334646303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d796f7574756265266c6f676f436f6c6f723d7768697465" alt="YouTube" data-canonical-src="https://img.shields.io/badge/Subscribe_YouTube-%23FF0000?style=for-the-badge&amp;logo=youtube&amp;logoColor=white" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto">🧭 Custom Sidebar &amp; Header for Home Assistant</h1><a id="user-content--custom-sidebar--header-for-home-assistant" class="anchor" aria-label="Permalink: 🧭 Custom Sidebar &amp; Header for Home Assistant" href="#-custom-sidebar--header-for-home-assistant"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="/rockbaer2007/sidebar-card/blob/main/README.it.md">🇮🇹 Italiano</a></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto">Header Flip Mode</h1><a id="user-content-header-flip-mode" class="anchor" aria-label="Permalink: Header Flip Mode" href="#header-flip-mode"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/rockbaer2007/sidebar-card/blob/main/img/Header-Flip_Mode.gif"><img src="/rockbaer2007/sidebar-card/raw/main/img/Header-Flip_Mode.gif" alt="Header flip animation" data-animated-image="" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto">Header Push Mode</h1><a id="user-content-header-push-mode" class="anchor" aria-label="Permalink: Header Push Mode" href="#header-push-mode"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/rockbaer2007/sidebar-card/blob/main/img/Header-Push_Mode.gif"><img src="/rockbaer2007/sidebar-card/raw/main/img/Header-Push_Mode.gif" alt="Header push" data-animated-image="" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">📸 Screenshots</h2><a id="user-content--screenshots" class="anchor" aria-label="Permalink: 📸 Screenshots" href="#-screenshots"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="/rockbaer2007/sidebar-card/blob/main/img/1.PNG"><img src="/rockbaer2007/sidebar-card/raw/main/img/1.PNG" width="48%" style="max-width: 100%;"></a>
  <a target="_blank" rel="noopener noreferrer" href="/rockbaer2007/sidebar-card/blob/main/img/2.PNG"><img src="/rockbaer2007/sidebar-card/raw/main/img/2.PNG" width="48%" style="max-width: 100%;"></a>
</p>
<p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="/rockbaer2007/sidebar-card/blob/main/img/3.PNG"><img src="/rockbaer2007/sidebar-card/raw/main/img/3.PNG" width="48%" style="max-width: 100%;"></a>
  <a target="_blank" rel="noopener noreferrer" href="/rockbaer2007/sidebar-card/blob/main/img/4.PNG"><img src="/rockbaer2007/sidebar-card/raw/main/img/4.PNG" width="48%" style="max-width: 100%;"></a>
</p>
<p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="/rockbaer2007/sidebar-card/blob/main/img/5.PNG"><img src="/rockbaer2007/sidebar-card/raw/main/img/5.PNG" width="48%" style="max-width: 100%;"></a>
  <a target="_blank" rel="noopener noreferrer" href="/rockbaer2007/sidebar-card/blob/main/img/6.PNG"><img src="/rockbaer2007/sidebar-card/raw/main/img/6.PNG" width="48%" style="max-width: 100%;"></a>
</p>
<p dir="auto">A fully‑customisable <strong>Header + Sidebar layout system for Home Assistant</strong>, designed to be modern, flexible and responsive — while keeping full compatibility with Lovelace dashboards.</p>
<hr>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">⭐ Main Features</h2><a id="user-content--main-features" class="anchor" aria-label="Permalink: ⭐ Main Features" href="#-main-features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>Responsive sidebar width (mobile / tablet / desktop)</li>
<li>Sticky / glass‑style header</li>
<li><strong>4 menu styles (list / wide / buttons / grid)</strong></li>
<li>Conditional menu items</li>
<li>Per‑item colors and icons</li>
<li>Optional hiding of default HA sidebar + top bar</li>
<li>Template area for greetings / custom HTML</li>
<li>Supports any Lovelace card inside header &amp; sidebar</li>
<li>Works with kiosk‑mode setups</li>
<li>Safe — does <strong>not</strong> hack core Lovelace layout</li>
<li>🆕 <strong>Built-in graphical editor</strong> — configure Sidebar &amp; Header without editing YAML manually</li>
</ul>
<hr>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">🖊️ Graphical Editor (Admin only)</h2><a id="user-content-️-graphical-editor-admin-only" class="anchor" aria-label="Permalink: 🖊️ Graphical Editor (Admin only)" href="#️-graphical-editor-admin-only"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="/rockbaer2007/sidebar-card/blob/main/img/setting1.png"><img src="/rockbaer2007/sidebar-card/raw/main/img/setting1.png" width="28%" style="max-width: 100%;"></a>
  <a target="_blank" rel="noopener noreferrer" href="/rockbaer2007/sidebar-card/blob/main/img/setting2.png"><img src="/rockbaer2007/sidebar-card/raw/main/img/setting2.png" width="48%" style="max-width: 100%;"></a>
</p>
<p dir="auto">Administrators have access to a <strong>built-in visual editor</strong> to configure Sidebar and Header without touching the YAML file.</p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto">How to open it</h3><a id="user-content-how-to-open-it" class="anchor" aria-label="Permalink: How to open it" href="#how-to-open-it"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">Two ways:</p>
<ol dir="auto">
<li><strong>Toolbar button</strong> — a dashboard-edit icon (🖊) appears in the top-right toolbar of HA when you are logged in as admin. Click it to open the editor panel.</li>
<li><strong>Gear icon in the sidebar</strong> — a small ⚙ icon at the bottom of the sidebar (visible only to admins) also opens the editor.</li>
</ol>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto">Editor tabs</h3><a id="user-content-editor-tabs" class="anchor" aria-label="Permalink: Editor tabs" href="#editor-tabs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th>Tab</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Sidebar</strong></td>
<td>Configure sidebar width, clock, date format, menu style, menu items, bottomCard and custom CSS</td>
</tr>
<tr>
<td><strong>Header</strong></td>
<td>Configure header height, sticky mode, topMenuMode, card slots (left / center / right), menus and custom CSS</td>
</tr>
<tr>
<td><strong>YAML</strong></td>
<td>Direct YAML editing of both configs — useful for power users or copy-paste workflows</td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto">Card editors</h3><a id="user-content-card-editors" class="anchor" aria-label="Permalink: Card editors" href="#card-editors"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">All card fields (bottomCard, leftCard, centerCard, rightCard and stack items) use <strong>YAML format</strong> — the same format you already use in Home Assistant. Example:</p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto" data-snippet-clipboard-copy-content="type: custom:button-card
entity: light.living_room
name: Living Room
icon: mdi:sofa"><pre><span class="pl-ent">type</span>: <span class="pl-s">custom:button-card</span>
<span class="pl-ent">entity</span>: <span class="pl-s">light.living_room</span>
<span class="pl-ent">name</span>: <span class="pl-s">Living Room</span>
<span class="pl-ent">icon</span>: <span class="pl-s">mdi:sofa</span></pre></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto">Save behaviour</h3><a id="user-content-save-behaviour" class="anchor" aria-label="Permalink: Save behaviour" href="#save-behaviour"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><strong>Storage mode (default)</strong>: changes are saved directly to Lovelace via WebSocket and the page reloads automatically.</li>
<li><strong>YAML file mode</strong> (<code>ui-lovelace.yaml</code>): the editor generates a YAML snippet to copy-paste into your config file.</li>
</ul>
<hr>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto">📦 Installation</h1><a id="user-content--installation" class="anchor" aria-label="Permalink: 📦 Installation" href="#-installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">HACS</h2><a id="user-content-hacs" class="anchor" aria-label="Permalink: HACS" href="#hacs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">This integration can be installed manually or via HACS when available.</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><a href="https://my.home-assistant.io/redirect/hacs_repository/?owner=bobsilvio&amp;repository=sidebar-card&amp;category=plugin" rel="nofollow"><img src="https://camo.githubusercontent.com/49f849a6409cdcad49e32d41115ab078f810d960b35466436e028d4552aadd40/68747470733a2f2f6d792e686f6d652d617373697374616e742e696f2f6261646765732f686163735f7265706f7369746f72792e737667" alt="Open in HACS" data-canonical-src="https://my.home-assistant.io/badges/hacs_repository.svg" style="max-width: 100%;"></a></h2><a id="" class="anchor" aria-label="Permalink: " href="#"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">Manual Install</h2><a id="user-content-manual-install" class="anchor" aria-label="Permalink: Manual Install" href="#manual-install"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">Copy the JS file to:</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto" data-snippet-clipboard-copy-content="/config/www/sidebar-card.js"><pre class="notranslate"><code>/config/www/sidebar-card.js
</code></pre></div>
<p dir="auto">Then add the resource:</p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto" data-snippet-clipboard-copy-content="url: /local/sidebar-card.js
type: module"><pre><span class="pl-ent">url</span>: <span class="pl-s">/local/sidebar-card.js</span>
<span class="pl-ent">type</span>: <span class="pl-s">module</span></pre></div>
<p dir="auto">Restart or reload resources.</p>
<hr>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto">🚀 Basic Setup</h1><a id="user-content--basic-setup" class="anchor" aria-label="Permalink: 🚀 Basic Setup" href="#-basic-setup"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">Add to your <strong>dashboard YAML</strong>:</p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto" data-snippet-clipboard-copy-content="sidebar:
  enabled: true
  width: { mobile: 0, tablet: 16, desktop: 18 }

header:
  enabled: true
  sticky: true
  height: 72"><pre><span class="pl-ent">sidebar</span>:
  <span class="pl-ent">enabled</span>: <span class="pl-c1">true</span>
  <span class="pl-ent">width</span>: <span class="pl-s">{ mobile: 0, tablet: 16, desktop: 18 }</span>

<span class="pl-ent">header</span>:
  <span class="pl-ent">enabled</span>: <span class="pl-c1">true</span>
  <span class="pl-ent">sticky</span>: <span class="pl-c1">true</span>
  <span class="pl-ent">height</span>: <span class="pl-c1">72</span></pre></div>
<hr>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto">🧭 Sidebar Configuration</h1><a id="user-content--sidebar-configuration" class="anchor" aria-label="Permalink: 🧭 Sidebar Configuration" href="#-sidebar-configuration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">🔧 Main Options</h2><a id="user-content--main-options" class="anchor" aria-label="Permalink: 🔧 Main Options" href="#-main-options"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th>Option</th>
<th>Type</th>
<th>Default</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>enabled</code></td>
<td>bool</td>
<td><code>true</code></td>
<td>Enables the custom sidebar</td>
</tr>
<tr>
<td><code>debug</code></td>
<td>bool</td>
<td><code>false</code></td>
<td>Log debug messages to console</td>
</tr>
<tr>
<td><code>title</code></td>
<td>string</td>
<td>""</td>
<td>Optional title text</td>
</tr>
<tr>
<td><code>clock</code></td>
<td>bool</td>
<td><code>false</code></td>
<td>Enable analog clock</td>
</tr>
<tr>
<td><code>digitalClock</code></td>
<td>bool</td>
<td><code>false</code></td>
<td>Enable digital clock</td>
</tr>
<tr>
<td><code>digitalClockWithSeconds</code></td>
<td>bool</td>
<td><code>false</code></td>
<td>Show seconds in digital clock</td>
</tr>
<tr>
<td><code>twelveHourVersion</code></td>
<td>bool</td>
<td><code>false</code></td>
<td>12‑hour clock format</td>
</tr>
<tr>
<td><code>period</code></td>
<td>bool</td>
<td><code>false</code></td>
<td>Show AM / PM when using 12‑hour mode</td>
</tr>
<tr>
<td><code>date</code></td>
<td>bool</td>
<td><code>true</code></td>
<td>Show date</td>
</tr>
<tr>
<td><code>dateFormat</code></td>
<td>string</td>
<td><code>DD MMMM</code></td>
<td>Moment‑style format</td>
</tr>
<tr>
<td><code>updateMenu</code></td>
<td>bool</td>
<td><code>true</code></td>
<td>Highlight active menu item</td>
</tr>
<tr>
<td><code>hideHassSidebar</code></td>
<td>bool</td>
<td><code>false</code></td>
<td>Hide default HA sidebar</td>
</tr>
<tr>
<td><code>hideTopMenu</code></td>
<td>bool</td>
<td><code>false</code></td>
<td>Hide default HA top bar</td>
</tr>
<tr>
<td><code>showTopMenuOnMobile</code></td>
<td>bool</td>
<td><code>true</code></td>
<td>Show top bar only on mobile</td>
</tr>
<tr>
<td><code>width</code></td>
<td>number/object</td>
<td><code>18</code></td>
<td>% width or responsive config</td>
</tr>
<tr>
<td><code>breakpoints.mobile</code></td>
<td>int</td>
<td><code>767</code></td>
<td>Mobile max width</td>
</tr>
<tr>
<td><code>breakpoints.tablet</code></td>
<td>int</td>
<td><code>1024</code></td>
<td>Tablet max width</td>
</tr>
<tr>
<td><code>hideOnPath</code></td>
<td>list</td>
<td>—</td>
<td>Paths where sidebar hides</td>
</tr>
<tr>
<td><code>menuStyle</code></td>
<td>string</td>
<td><code>list</code></td>
<td><code>list / wide / buttons / grid</code></td>
</tr>
<tr>
<td><code>showLabel</code></td>
<td>bool</td>
<td><code>true</code></td>
<td>Show menu text labels</td>
</tr>
<tr>
<td><code>template</code></td>
<td>Jinja2</td>
<td>—</td>
<td>HTML rendered above menu</td>
</tr>
<tr>
<td><code>bottomCard</code></td>
<td>Lovelace card</td>
<td>—</td>
<td>Card shown at bottom of sidebar</td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<hr>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">📐 Responsive Width</h2><a id="user-content--responsive-width" class="anchor" aria-label="Permalink: 📐 Responsive Width" href="#-responsive-width"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto" data-snippet-clipboard-copy-content="width:
  mobile: 0
  tablet: 16
  desktop: 18"><pre><span class="pl-ent">width</span>:
  <span class="pl-ent">mobile</span>: <span class="pl-c1">0</span>
  <span class="pl-ent">tablet</span>: <span class="pl-c1">16</span>
  <span class="pl-ent">desktop</span>: <span class="pl-c1">18</span></pre></div>
<hr>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto">📋 Sidebar Menu Items</h1><a id="user-content--sidebar-menu-items" class="anchor" aria-label="Permalink: 📋 Sidebar Menu Items" href="#-sidebar-menu-items"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto" data-snippet-clipboard-copy-content="sidebarMenu:
  - action: navigate
    navigation_path: &quot;/lovelace/home&quot;
    name: &quot;Home&quot;
    icon: mdi:home
    background_color: &quot;var(--blue)&quot;
    icon_color: &quot;#000&quot;
    text_color: &quot;#000&quot;
    state: light.living_room
    conditional: &quot;{{ is_state('alarm_control_panel.house','disarmed') }}&quot;"><pre><span class="pl-ent">sidebarMenu</span>:
  - <span class="pl-ent">action</span>: <span class="pl-s">navigate</span>
    <span class="pl-ent">navigation_path</span>: <span class="pl-s"><span class="pl-pds">"</span>/lovelace/home<span class="pl-pds">"</span></span>
    <span class="pl-ent">name</span>: <span class="pl-s"><span class="pl-pds">"</span>Home<span class="pl-pds">"</span></span>
    <span class="pl-ent">icon</span>: <span class="pl-s">mdi:home</span>
    <span class="pl-ent">background_color</span>: <span class="pl-s"><span class="pl-pds">"</span>var(--blue)<span class="pl-pds">"</span></span>
    <span class="pl-ent">icon_color</span>: <span class="pl-s"><span class="pl-pds">"</span>#000<span class="pl-pds">"</span></span>
    <span class="pl-ent">text_color</span>: <span class="pl-s"><span class="pl-pds">"</span>#000<span class="pl-pds">"</span></span>
    <span class="pl-ent">state</span>: <span class="pl-s">light.living_room</span>
    <span class="pl-ent">conditional</span>: <span class="pl-s"><span class="pl-pds">"</span>{{ is_state('alarm_control_panel.house','disarmed') }}<span class="pl-pds">"</span></span></pre></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto">Actions Supported</h3><a id="user-content-actions-supported" class="anchor" aria-label="Permalink: Actions Supported" href="#actions-supported"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th>Action</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>navigate</code></td>
<td>Go to a Lovelace view</td>
</tr>
<tr>
<td><code>more-info</code></td>
<td>Open entity dialog</td>
</tr>
<tr>
<td><code>toggle</code></td>
<td>Toggle entity</td>
</tr>
<tr>
<td><code>call-service</code></td>
<td>Call Home Assistant service</td>
</tr>
<tr>
<td><code>service-js</code></td>
<td>Execute JavaScript</td>
</tr>
<tr>
<td><code>url</code></td>
<td>Open a URL</td>
</tr>
<tr>
<td><code>toggle-sidebar</code></td>
<td>Toggle the <strong>default HA sidebar</strong> (drawer)</td>
</tr>
<tr>
<td><code>toggle-topmenu</code></td>
<td>Toggle the <strong>HA top bar</strong> (or trigger <code>flip</code> mode when enabled)</td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto">Extra Item Fields</h3><a id="user-content-extra-item-fields" class="anchor" aria-label="Permalink: Extra Item Fields" href="#extra-item-fields"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th>Field</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>name</code></td>
<td>Label text</td>
</tr>
<tr>
<td><code>icon</code></td>
<td>MDI icon</td>
</tr>
<tr>
<td><code>background_color</code></td>
<td>Background colour</td>
</tr>
<tr>
<td><code>icon_color</code></td>
<td>Icon colour</td>
</tr>
<tr>
<td><code>text_color</code></td>
<td>Text colour</td>
</tr>
<tr>
<td><code>state</code></td>
<td>Entity used to mark active state</td>
</tr>
<tr>
<td><code>conditional</code></td>
<td>When evaluates false → hides the item</td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<hr>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto">🎨 Menu Styles</h1><a id="user-content--menu-styles" class="anchor" aria-label="Permalink: 🎨 Menu Styles" href="#-menu-styles"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th><code>menuStyle</code></th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>list</code></td>
<td>Simple legacy list style</td>
</tr>
<tr>
<td><code>wide</code></td>
<td><strong>Pill‑style items with icon + label + colored background</strong></td>
</tr>
<tr>
<td><code>buttons</code></td>
<td>Square button style (icon with optional label)</td>
</tr>
<tr>
<td><code>grid</code></td>
<td>Compact app‑icon style grid</td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">Example — wide style</h2><a id="user-content-example--wide-style" class="anchor" aria-label="Permalink: Example — wide style" href="#example--wide-style"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto" data-snippet-clipboard-copy-content="sidebar:
  menuStyle: wide
  showLabel: true"><pre><span class="pl-ent">sidebar</span>:
  <span class="pl-ent">menuStyle</span>: <span class="pl-s">wide</span>
  <span class="pl-ent">showLabel</span>: <span class="pl-c1">true</span></pre></div>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto" data-snippet-clipboard-copy-content="- action: navigate
  name: &quot;Energy&quot;
  icon: mdi:solar-power-variant
  navigation_path: &quot;/energy&quot;
  background_color: &quot;rgba(255, 200, 140, 0.95)&quot;
  icon_color: &quot;#0f172a&quot;
  text_color: &quot;#0f172a&quot;"><pre>- <span class="pl-ent">action</span>: <span class="pl-s">navigate</span>
  <span class="pl-ent">name</span>: <span class="pl-s"><span class="pl-pds">"</span>Energy<span class="pl-pds">"</span></span>
  <span class="pl-ent">icon</span>: <span class="pl-s">mdi:solar-power-variant</span>
  <span class="pl-ent">navigation_path</span>: <span class="pl-s"><span class="pl-pds">"</span>/energy<span class="pl-pds">"</span></span>
  <span class="pl-ent">background_color</span>: <span class="pl-s"><span class="pl-pds">"</span>rgba(255, 200, 140, 0.95)<span class="pl-pds">"</span></span>
  <span class="pl-ent">icon_color</span>: <span class="pl-s"><span class="pl-pds">"</span>#0f172a<span class="pl-pds">"</span></span>
  <span class="pl-ent">text_color</span>: <span class="pl-s"><span class="pl-pds">"</span>#0f172a<span class="pl-pds">"</span></span></pre></div>
<hr>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto">🧱 Header Configuration</h1><a id="user-content--header-configuration" class="anchor" aria-label="Permalink: 🧱 Header Configuration" href="#-header-configuration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto" data-snippet-clipboard-copy-content="header:
  enabled: true
  sticky: true
  height: 72                       # minimum header height (px)
  headerMenuStyle: wide            # list / wide / buttons / grid (same as sidebar)
  headerMenuShowLabel: true
  headerMenuPosition: center       # left / center / right

  # Home Assistant top bar behavior (optional)
  topMenuMode: overlay             # overlay / push / flip
  flipDuration: 5                  # seconds to keep HA top bar visible in flip mode

  # Optional icon menus (left / right)
  leftMenu:
    - icon: mdi:menu
      name: Sidebar
      action: toggle-sidebar

  rightMenu:
    - icon: mdi:application
      name: Top bar
      action: toggle-topmenu"><pre><span class="pl-ent">header</span>:
  <span class="pl-ent">enabled</span>: <span class="pl-c1">true</span>
  <span class="pl-ent">sticky</span>: <span class="pl-c1">true</span>
  <span class="pl-ent">height</span>: <span class="pl-c1">72</span>                       <span class="pl-c"><span class="pl-c">#</span> minimum header height (px)</span>
  <span class="pl-ent">headerMenuStyle</span>: <span class="pl-s">wide            </span><span class="pl-c"><span class="pl-c">#</span> list / wide / buttons / grid (same as sidebar)</span>
  <span class="pl-ent">headerMenuShowLabel</span>: <span class="pl-c1">true</span>
  <span class="pl-ent">headerMenuPosition</span>: <span class="pl-s">center       </span><span class="pl-c"><span class="pl-c">#</span> left / center / right</span>

  <span class="pl-c"><span class="pl-c">#</span> Home Assistant top bar behavior (optional)</span>
  <span class="pl-ent">topMenuMode</span>: <span class="pl-s">overlay             </span><span class="pl-c"><span class="pl-c">#</span> overlay / push / flip</span>
  <span class="pl-ent">flipDuration</span>: <span class="pl-c1">5</span>                  <span class="pl-c"><span class="pl-c">#</span> seconds to keep HA top bar visible in flip mode</span>

  <span class="pl-c"><span class="pl-c">#</span> Optional icon menus (left / right)</span>
  <span class="pl-ent">leftMenu</span>:
    - <span class="pl-ent">icon</span>: <span class="pl-s">mdi:menu</span>
      <span class="pl-ent">name</span>: <span class="pl-s">Sidebar</span>
      <span class="pl-ent">action</span>: <span class="pl-s">toggle-sidebar</span>

  <span class="pl-ent">rightMenu</span>:
    - <span class="pl-ent">icon</span>: <span class="pl-s">mdi:application</span>
      <span class="pl-ent">name</span>: <span class="pl-s">Top bar</span>
      <span class="pl-ent">action</span>: <span class="pl-s">toggle-topmenu</span></pre></div>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th>Option</th>
<th>Type</th>
<th>Default</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>enabled</code></td>
<td>bool</td>
<td><code>true</code></td>
<td>Enable custom header</td>
</tr>
<tr>
<td><code>sticky</code></td>
<td>bool</td>
<td><code>true</code></td>
<td>Make header sticky to the top</td>
</tr>
<tr>
<td><code>height</code></td>
<td>int</td>
<td><code>72</code></td>
<td>Minimum header height in pixels (can grow with content)</td>
</tr>
<tr>
<td><code>style</code></td>
<td>string</td>
<td>—</td>
<td>Extra CSS applied inside the header-card (supports <code>:host { ... }</code>)</td>
</tr>
<tr>
<td><code>topMenuMode</code></td>
<td>string</td>
<td><code>overlay</code></td>
<td>How to handle HA default top bar: <code>overlay</code>, <code>push</code>, or <code>flip</code></td>
</tr>
<tr>
<td><code>flipDuration</code></td>
<td>number</td>
<td><code>5</code></td>
<td><strong>Flip mode only</strong>: seconds to keep HA top bar visible before flipping back</td>
</tr>
<tr>
<td><code>headerMenuStyle</code></td>
<td>string</td>
<td><code>wide</code></td>
<td>Header menu style (<code>list / wide / buttons / grid</code>)</td>
</tr>
<tr>
<td><code>headerMenuShowLabel</code></td>
<td>bool</td>
<td><code>true</code></td>
<td>Show text labels in header menu</td>
</tr>
<tr>
<td><code>headerMenuPosition</code></td>
<td>string</td>
<td><code>right</code></td>
<td>Place header menu in <code>left / center / right</code> area</td>
</tr>
<tr>
<td><code>leftMenu</code></td>
<td>list</td>
<td>—</td>
<td>Icon buttons shown on the far left (e.g. toggle sidebar)</td>
</tr>
<tr>
<td><code>rightMenu</code></td>
<td>list</td>
<td>—</td>
<td>Icon buttons shown on the far right (e.g. toggle top bar)</td>
</tr>
<tr>
<td><code>headerMenu</code></td>
<td>list</td>
<td>—</td>
<td>Main header menu (styled buttons)</td>
</tr>
<tr>
<td><code>leftCard</code></td>
<td>Lovelace card</td>
<td>—</td>
<td>Any Lovelace card rendered in the left slot</td>
</tr>
<tr>
<td><code>centerCard</code></td>
<td>Lovelace card</td>
<td>—</td>
<td>Any Lovelace card rendered in the center slot</td>
</tr>
<tr>
<td><code>rightCard</code></td>
<td>Lovelace card</td>
<td>—</td>
<td>Any Lovelace card rendered in the right slot</td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">🧩 Top Bar Modes (<code>topMenuMode</code>)</h2><a id="user-content--top-bar-modes-topmenumode" class="anchor" aria-label="Permalink: 🧩 Top Bar Modes (topMenuMode)" href="#-top-bar-modes-topmenumode"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><strong><code>overlay</code> (default)</strong>: your header stays visible; HA top bar can be shown/hidden without pushing the view.</li>
<li><strong><code>push</code></strong>: when HA top bar is visible, the content is pushed down using the real top bar height.</li>
<li><strong><code>flip</code></strong>: your header “flips” to reveal HA top bar for a few seconds, then flips back. Use <code>flipDuration</code> to control how long HA top bar stays visible.</li>
</ul>
<p dir="auto">To trigger the behavior, use a menu item with:</p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto" data-snippet-clipboard-copy-content="action: toggle-topmenu"><pre><span class="pl-ent">action</span>: <span class="pl-s">toggle-topmenu</span></pre></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">Header Menu Items</h2><a id="user-content-header-menu-items" class="anchor" aria-label="Permalink: Header Menu Items" href="#header-menu-items"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto" data-snippet-clipboard-copy-content="headerMenu:
  - action: navigate
    name: &quot;Home&quot;
    icon: mdi:home
    navigation_path: &quot;/lovelace/home&quot;
    background_color: &quot;rgba(205,255,190,.95)&quot;
    icon_color: &quot;#0f172a&quot;
    text_color: &quot;#0f172a&quot;"><pre><span class="pl-ent">headerMenu</span>:
  - <span class="pl-ent">action</span>: <span class="pl-s">navigate</span>
    <span class="pl-ent">name</span>: <span class="pl-s"><span class="pl-pds">"</span>Home<span class="pl-pds">"</span></span>
    <span class="pl-ent">icon</span>: <span class="pl-s">mdi:home</span>
    <span class="pl-ent">navigation_path</span>: <span class="pl-s"><span class="pl-pds">"</span>/lovelace/home<span class="pl-pds">"</span></span>
    <span class="pl-ent">background_color</span>: <span class="pl-s"><span class="pl-pds">"</span>rgba(205,255,190,.95)<span class="pl-pds">"</span></span>
    <span class="pl-ent">icon_color</span>: <span class="pl-s"><span class="pl-pds">"</span>#0f172a<span class="pl-pds">"</span></span>
    <span class="pl-ent">text_color</span>: <span class="pl-s"><span class="pl-pds">"</span>#0f172a<span class="pl-pds">"</span></span></pre></div>
<hr>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">Header Cards</h2><a id="user-content-header-cards" class="anchor" aria-label="Permalink: Header Cards" href="#header-cards"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto" data-snippet-clipboard-copy-content="leftCard:
  type: ...
centerCard:
  type: ...
rightCard:
  type: ..."><pre><span class="pl-ent">leftCard</span>:
  <span class="pl-ent">type</span>: <span class="pl-s">...</span>
<span class="pl-ent">centerCard</span>:
  <span class="pl-ent">type</span>: <span class="pl-s">...</span>
<span class="pl-ent">rightCard</span>:
  <span class="pl-ent">type</span>: <span class="pl-s">...</span></pre></div>
<p dir="auto">Supports <strong>any Lovelace card</strong>.</p>
<hr>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto">🎨 Styling &amp; CSS Variables</h1><a id="user-content--styling--css-variables" class="anchor" aria-label="Permalink: 🎨 Styling &amp; CSS Variables" href="#-styling--css-variables"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">Add under the <code>style:</code> key, e.g.:</p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto" data-snippet-clipboard-copy-content="style: |
  :host {"><pre><span class="pl-ent">style</span>: <span class="pl-s">|</span>
<span class="pl-s">  :host {</span></pre></div>
<hr>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">🔷 GRID Mode (<code>menuStyle: grid</code>)</h2><a id="user-content--grid-mode-menustyle-grid" class="anchor" aria-label="Permalink: 🔷 GRID Mode (menuStyle: grid)" href="#-grid-mode-menustyle-grid"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto" data-snippet-clipboard-copy-content="--sidebar-grid-margin-y
--sidebar-grid-gap
--sidebar-grid-item-padding
--sidebar-grid-box-size
--sidebar-grid-radius
--sidebar-grid-bg
--sidebar-grid-icon-size
--sidebar-grid-icon-color
--sidebar-grid-label-margin-top
--sidebar-grid-font-size
--sidebar-grid-line-height
--sidebar-grid-font-weight
--sidebar-grid-text-color
--sidebar-grid-active-border
--sidebar-grid-active-bg
--sidebar-grid-active-icon-color
--sidebar-grid-active-text-color
--sidebar-grid-columns
--sidebar-grid-rows
--sidebar-grid-row-height"><pre class="notranslate"><code>--sidebar-grid-margin-y
--sidebar-grid-gap
--sidebar-grid-item-padding
--sidebar-grid-box-size
--sidebar-grid-radius
--sidebar-grid-bg
--sidebar-grid-icon-size
--sidebar-grid-icon-color
--sidebar-grid-label-margin-top
--sidebar-grid-font-size
--sidebar-grid-line-height
--sidebar-grid-font-weight
--sidebar-grid-text-color
--sidebar-grid-active-border
--sidebar-grid-active-bg
--sidebar-grid-active-icon-color
--sidebar-grid-active-text-color
--sidebar-grid-columns
--sidebar-grid-rows
--sidebar-grid-row-height
</code></pre></div>
<hr>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">🟥 BUTTON Mode (<code>menuStyle: buttons</code>)</h2><a id="user-content--button-mode-menustyle-buttons" class="anchor" aria-label="Permalink: 🟥 BUTTON Mode (menuStyle: buttons)" href="#-button-mode-menustyle-buttons"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto" data-snippet-clipboard-copy-content="--sidebar-button-margin-y
--sidebar-button-gap
--sidebar-button-item-gap
--sidebar-button-size
--sidebar-button-box-size
--sidebar-button-radius
--sidebar-button-bg
--sidebar-button-icon-color
--sidebar-button-icon-size
--sidebar-button-font-size
--sidebar-button-line-height
--sidebar-button-text-color
--sidebar-button-font-weight
--sidebar-button-active-border-width
--sidebar-button-active-border-color
--sidebar-button-active-shadow-color
--sidebar-button-active-icon-color
--sidebar-button-active-text-color"><pre class="notranslate"><code>--sidebar-button-margin-y
--sidebar-button-gap
--sidebar-button-item-gap
--sidebar-button-size
--sidebar-button-box-size
--sidebar-button-radius
--sidebar-button-bg
--sidebar-button-icon-color
--sidebar-button-icon-size
--sidebar-button-font-size
--sidebar-button-line-height
--sidebar-button-text-color
--sidebar-button-font-weight
--sidebar-button-active-border-width
--sidebar-button-active-border-color
--sidebar-button-active-shadow-color
--sidebar-button-active-icon-color
--sidebar-button-active-text-color
</code></pre></div>
<hr>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">🟩 WIDE Mode (<code>menuStyle: wide</code>)</h2><a id="user-content--wide-mode-menustyle-wide" class="anchor" aria-label="Permalink: 🟩 WIDE Mode (menuStyle: wide)" href="#-wide-mode-menustyle-wide"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto" data-snippet-clipboard-copy-content="--sidebar-wide-margin-y
--sidebar-wide-gap
--sidebar-wide-padding-x
--sidebar-wide-height
--sidebar-wide-radius
--sidebar-wide-item-gap
--sidebar-wide-bg
--sidebar-wide-icon-color
--sidebar-wide-icon-size
--sidebar-wide-font-size
--sidebar-wide-line-height
--sidebar-wide-text-color
--sidebar-wide-font-weight
--sidebar-wide-active-border-width
--sidebar-wide-active-border-color
--sidebar-wide-active-bg
--sidebar-wide-active-opacity
--sidebar-wide-active-icon-color
--sidebar-wide-active-icon-size
--sidebar-wide-active-text-color"><pre class="notranslate"><code>--sidebar-wide-margin-y
--sidebar-wide-gap
--sidebar-wide-padding-x
--sidebar-wide-height
--sidebar-wide-radius
--sidebar-wide-item-gap
--sidebar-wide-bg
--sidebar-wide-icon-color
--sidebar-wide-icon-size
--sidebar-wide-font-size
--sidebar-wide-line-height
--sidebar-wide-text-color
--sidebar-wide-font-weight
--sidebar-wide-active-border-width
--sidebar-wide-active-border-color
--sidebar-wide-active-bg
--sidebar-wide-active-opacity
--sidebar-wide-active-icon-color
--sidebar-wide-active-icon-size
--sidebar-wide-active-text-color
</code></pre></div>
<hr>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">🧠 Common Sidebar Variables</h2><a id="user-content--common-sidebar-variables" class="anchor" aria-label="Permalink: 🧠 Common Sidebar Variables" href="#-common-sidebar-variables"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto" data-snippet-clipboard-copy-content="--sidebar-selected-bg
--sidebar-icon-color
--primary-text-color"><pre class="notranslate"><code>--sidebar-selected-bg
--sidebar-icon-color
--primary-text-color
</code></pre></div>
<hr>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">🖼 Header Variables</h2><a id="user-content--header-variables" class="anchor" aria-label="Permalink: 🖼 Header Variables" href="#-header-variables"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto" data-snippet-clipboard-copy-content="--header-background
--header-backdrop-filter
--header-radius
--header-height"><pre class="notranslate"><code>--header-background
--header-backdrop-filter
--header-radius
--header-height
</code></pre></div>
<hr>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto">🛠 Troubleshooting</h1><a id="user-content--troubleshooting" class="anchor" aria-label="Permalink: 🛠 Troubleshooting" href="#-troubleshooting"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>Disable conflicting layout plugins when testing</li>
<li>Clear browser cache and reload resources</li>
<li>Test without theme customisation first</li>
</ul>
<hr>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto">❤️ Credits</h1><a id="user-content-️-credits" class="anchor" aria-label="Permalink: ❤️ Credits" href="#️-credits"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">Thanks DBuit for original work</p>
<p dir="auto">Built for the HA community 🙂</p>
<hr>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">🔄 Header Top Menu Modes (NEW)</h2><a id="user-content--header-top-menu-modes-new" class="anchor" aria-label="Permalink: 🔄 Header Top Menu Modes (NEW)" href="#-header-top-menu-modes-new"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">The custom header can manage the Home Assistant top bar in three different ways.</p>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th>Mode</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>overlay</code></td>
<td>HA top bar overlays the content</td>
</tr>
<tr>
<td><code>push</code></td>
<td>Content is pushed down by the HA top bar</td>
</tr>
<tr>
<td><code>flip</code></td>
<td><strong>Animated cylindrical flip between custom header and HA top bar</strong></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto">🌀 Flip Mode</h3><a id="user-content--flip-mode" class="anchor" aria-label="Permalink: 🌀 Flip Mode" href="#-flip-mode"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">The <strong>flip mode</strong> creates a smooth cylindrical rotation effect between:</p>
<ul dir="auto">
<li>Your custom header</li>
<li>The original Home Assistant top bar</li>
</ul>
<p dir="auto">✔ No layout jumps<br>
✔ No content shifting<br>
✔ Identical occupied space</p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto">Configuration</h4><a id="user-content-configuration" class="anchor" aria-label="Permalink: Configuration" href="#configuration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto" data-snippet-clipboard-copy-content="header:
  enabled: true
  sticky: true
  topMenuMode: flip
  flipDuration: 5   # seconds (optional, default: 5)"><pre><span class="pl-ent">header</span>:
  <span class="pl-ent">enabled</span>: <span class="pl-c1">true</span>
  <span class="pl-ent">sticky</span>: <span class="pl-c1">true</span>
  <span class="pl-ent">topMenuMode</span>: <span class="pl-s">flip</span>
  <span class="pl-ent">flipDuration</span>: <span class="pl-c1">5</span>   <span class="pl-c"><span class="pl-c">#</span> seconds (optional, default: 5)</span></pre></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto">Trigger example</h4><a id="user-content-trigger-example" class="anchor" aria-label="Permalink: Trigger example" href="#trigger-example"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto" data-snippet-clipboard-copy-content="headerMenu:
  - action: service-js
    name: &quot;Top Menu&quot;
    icon: mdi:swap-vertical
    service: |
      if (window.silvioFlipTopMenu) {
        window.silvioFlipTopMenu();
      }"><pre><span class="pl-ent">headerMenu</span>:
  - <span class="pl-ent">action</span>: <span class="pl-s">service-js</span>
    <span class="pl-ent">name</span>: <span class="pl-s"><span class="pl-pds">"</span>Top Menu<span class="pl-pds">"</span></span>
    <span class="pl-ent">icon</span>: <span class="pl-s">mdi:swap-vertical</span>
    <span class="pl-ent">service</span>: <span class="pl-s">|</span>
<span class="pl-s">      if (window.silvioFlipTopMenu) {</span>
<span class="pl-s">        window.silvioFlipTopMenu();</span>
<span class="pl-s">      }</span></pre></div>
<p dir="auto">or</p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto" data-snippet-clipboard-copy-content="rightMenu:
  - icon: mdi:application
    name: Top bar
    action: toggle-topmenu"><pre><span class="pl-ent">rightMenu</span>:
  - <span class="pl-ent">icon</span>: <span class="pl-s">mdi:application</span>
    <span class="pl-ent">name</span>: <span class="pl-s">Top bar</span>
    <span class="pl-ent">action</span>: <span class="pl-s">toggle-topmenu</span></pre></div>
</article></div><div class="d-none"></div></section></div></div></div> </div> <!-- --> </div></div></div></div></div></div><div class="ScrollMarksContainer-module__scrollMarksContainer__Eu7uU" id="find-result-marks-container"></div><div class="d-none"></div><div class="d-none"></div></div> <!-- --> <!-- --> <script type="application/json" id="__PRIMER_DATA__R_1___">{"resolvedServerColorMode":"day"}</script></div>
</react-app>




  </div>

</turbo-frame>

    </main>
  </div>

  </div>

          <footer class="footer tmp-pt-7 tmp-pb-6 f6 color-fg-muted color-border-subtle p-responsive" role="contentinfo" >
  <h2 class='sr-only'>Footer</h2>

  


  <div class="d-flex flex-justify-center flex-items-center flex-column-reverse flex-lg-row flex-wrap flex-lg-nowrap">
    <div class="d-flex flex-items-center flex-shrink-0 mx-2">
      <a aria-label="GitHub Homepage" class="footer-octicon mr-2" href="https://github.com">
        <svg aria-hidden="true" height="24" viewBox="0 0 24 24" version="1.1" width="24" data-view-component="true" class="octicon octicon-mark-github">
    <path d="M10.226 17.284c-2.965-.36-5.054-2.493-5.054-5.256 0-1.123.404-2.336 1.078-3.144-.292-.741-.247-2.314.09-2.965.898-.112 2.111.36 2.83 1.01.853-.269 1.752-.404 2.853-.404 1.1 0 1.999.135 2.807.382.696-.629 1.932-1.1 2.83-.988.315.606.36 2.179.067 2.942.72.854 1.101 2 1.101 3.167 0 2.763-2.089 4.852-5.098 5.234.763.494 1.28 1.572 1.28 2.807v2.336c0 .674.561 1.056 1.235.786 4.066-1.55 7.255-5.615 7.255-10.646C23.5 6.188 18.334 1 11.978 1 5.62 1 .5 6.188.5 12.545c0 4.986 3.167 9.12 7.435 10.669.606.225 1.19-.18 1.19-.786V20.63a2.9 2.9 0 0 1-1.078.224c-1.483 0-2.359-.808-2.987-2.313-.247-.607-.517-.966-1.034-1.033-.27-.023-.359-.135-.359-.27 0-.27.45-.471.898-.471.652 0 1.213.404 1.797 1.235.45.651.921.943 1.483.943.561 0 .92-.202 1.437-.719.382-.381.674-.718.944-.943"></path>
</svg>
</a>
      <span>
        &copy; 2026 GitHub,&nbsp;Inc.
      </span>
    </div>

    <nav aria-label="Footer">
      <h3 class="sr-only" id="sr-footer-heading">Footer navigation</h3>

      <ul class="list-style-none d-flex flex-justify-center flex-wrap mb-2 mb-lg-0" aria-labelledby="sr-footer-heading">


          <li class="mx-2">
            <a data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to Terms&quot;,&quot;label&quot;:&quot;text:terms&quot;}" href="https://docs.github.com/site-policy/github-terms/github-terms-of-service" data-view-component="true" class="Link--secondary Link">Terms</a>
          </li>

          <li class="mx-2">
            <a data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to privacy&quot;,&quot;label&quot;:&quot;text:privacy&quot;}" href="https://docs.github.com/site-policy/privacy-policies/github-privacy-statement" data-view-component="true" class="Link--secondary Link">Privacy</a>
          </li>

          <li class="mx-2">
            <a data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to security&quot;,&quot;label&quot;:&quot;text:security&quot;}" href="https://github.com/security" data-view-component="true" class="Link--secondary Link">Security</a>
          </li>

          <li class="mx-2">
            <a data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to status&quot;,&quot;label&quot;:&quot;text:status&quot;}" href="https://www.githubstatus.com/" data-view-component="true" class="Link--secondary Link">Status</a>
          </li>

          <li class="mx-2">
            <a data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to community&quot;,&quot;label&quot;:&quot;text:community&quot;}" href="https://github.community/" data-view-component="true" class="Link--secondary Link">Community</a>
          </li>

          <li class="mx-2">
            <a data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to docs&quot;,&quot;label&quot;:&quot;text:docs&quot;}" href="https://docs.github.com/" data-view-component="true" class="Link--secondary Link">Docs</a>
          </li>

          <li class="mx-2">
            <a data-analytics-event="{&quot;category&quot;:&quot;Footer&quot;,&quot;action&quot;:&quot;go to contact&quot;,&quot;label&quot;:&quot;text:contact&quot;}" href="https://support.github.com?tags=dotcom-footer" data-view-component="true" class="Link--secondary Link">Contact</a>
          </li>

          <li class="mx-2" >
  <cookie-consent-link>
    <button
      type="button"
      class="Link--secondary underline-on-hover border-0 p-0 color-bg-transparent"
      data-action="click:cookie-consent-link#showConsentManagement"
      data-analytics-event="{&quot;location&quot;:&quot;footer&quot;,&quot;action&quot;:&quot;cookies&quot;,&quot;context&quot;:&quot;subfooter&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;label&quot;:&quot;cookies_link_subfooter_footer&quot;}"
    >
       Manage cookies
    </button>
  </cookie-consent-link>
</li>

<li class="mx-2">
  <cookie-consent-link>
    <button
      type="button"
      class="Link--secondary underline-on-hover border-0 p-0 color-bg-transparent text-left"
      data-action="click:cookie-consent-link#showConsentManagement"
      data-analytics-event="{&quot;location&quot;:&quot;footer&quot;,&quot;action&quot;:&quot;dont_share_info&quot;,&quot;context&quot;:&quot;subfooter&quot;,&quot;tag&quot;:&quot;link&quot;,&quot;label&quot;:&quot;dont_share_info_link_subfooter_footer&quot;}"
    >
      Do not share my personal information
    </button>
  </cookie-consent-link>
</li>

      </ul>
    </nav>
  </div>
</footer>



    <ghcc-consent id="ghcc" class="position-fixed bottom-0 left-0" style="z-index: 999999"
      data-locale="en"
      data-initial-cookie-consent-allowed=""
      data-cookie-consent-required="true"
    ></ghcc-consent>




  <div id="ajax-error-message" class="ajax-error-message flash flash-error" hidden>
    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-alert">
    <path d="M6.457 1.047c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0 1 14.082 15H1.918a1.75 1.75 0 0 1-1.543-2.575Zm1.763.707a.25.25 0 0 0-.44 0L1.698 13.132a.25.25 0 0 0 .22.368h12.164a.25.25 0 0 0 .22-.368Zm.53 3.996v2.5a.75.75 0 0 1-1.5 0v-2.5a.75.75 0 0 1 1.5 0ZM9 11a1 1 0 1 1-2 0 1 1 0 0 1 2 0Z"></path>
</svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l3.22 3.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-3.22 3.22a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z"></path>
</svg>
    </button>
    You can’t perform that action at this time.
  </div>

    <template id="site-details-dialog">
  <details class="details-reset details-overlay details-overlay-dark lh-default color-fg-default hx_rsm" open>
    <summary role="button" aria-label="Close dialog"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast hx_rsm-dialog hx_rsm-modal">
      <button class="Box-btn-octicon m-0 btn-octicon position-absolute right-0 top-0" type="button" aria-label="Close dialog" data-close-dialog>
        <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l3.22 3.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-3.22 3.22a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z"></path>
</svg>
      </button>
      <div class="octocat-spinner tmp-my-6 js-details-dialog-spinner"></div>
    </details-dialog>
  </details>
</template>

    <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box color-shadow-large" style="width:360px;">
  </div>
</div>

    <template id="snippet-clipboard-copy-button">
  <div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0" data-copy-feedback="Copied!" data-tooltip-direction="w">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2 tmp-m-2">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2 tmp-m-2">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div>
</template>
<template id="snippet-clipboard-copy-button-unpositioned">
  <div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div>
</template>




    </div>
    <div id="js-global-screen-reader-notice" class="sr-only mt-n1" aria-live="polite" aria-atomic="true" ></div>
    <div id="js-global-screen-reader-notice-assertive" class="sr-only mt-n1" aria-live="assertive" aria-atomic="true"></div>
  </body>
</html>

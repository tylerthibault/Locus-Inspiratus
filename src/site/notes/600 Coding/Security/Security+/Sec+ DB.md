---
{"dg-publish":true,"permalink":"/600-coding/security/security/sec-db/"}
---


```yaml:dbfolder
name: new database
description: new description
columns:
  MemoryPalace:
    input: checkbox
    accessorKey: MemoryPalace
    label: MemoryPalace
    key: MemoryPalace
    id: MemoryPalace
    position: 5
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Summary:
    input: text
    accessorKey: Summary
    label: Summary
    key: Summary
    id: Summary
    position: 2
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 459
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      wrap_content: true
  YouTube_Link:
    input: text
    accessorKey: YouTube_Link
    label: YouTube_Link
    key: YouTube_Link
    id: YouTube_Link
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: false
      link_alias_enabled: true
      media_width: 10
      media_height: 10
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      custom_link_alias: Link Here
  dg-publish:
    input: checkbox
    accessorKey: dg-publish
    label: dg-publish
    key: dg-publish
    id: dg-publish
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  db-show:
    input: checkbox
    accessorKey: db-show
    label: db-show
    key: db-show
    id: db-show
    position: 6
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  tags:
    input: text
    accessorKey: tags
    label: tags
    key: tags
    id: tags
    position: 7
    skipPersist: false
    isHidden: true
    sortIndex: -1
    width: 169
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  template:
    input: text
    accessorKey: template
    label: template
    key: template
    id: template
    position: 8
    skipPersist: false
    isHidden: true
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  created_date:
    input: text
    accessorKey: created_date
    label: created_date
    key: created_date
    id: created_date
    position: 9
    skipPersist: false
    isHidden: true
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  aliases:
    input: text
    accessorKey: aliases
    label: aliases
    key: aliases
    id: aliases
    position: 10
    skipPersist: false
    isHidden: true
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    position: 1
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
config:
  remove_field_when_delete_column: false
  cell_size: normal
  sticky_first_column: true
  group_folder_column: 
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  show_metadata_tags: false
  source_data: tag
  source_form_result: "#cybersec-sec-plus"
  source_destination_path: 600 Coding/Security/Notes
  row_templates_folder: /
  current_row_template: 
  pagination_size: 25
  font_size: 16
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
filters:
  enabled: true
  conditions:
      - field: db-show
        operator: IS_NOT_EMPTY
        value: "true"
        type: text
      - condition: AND
        disabled: true
        label: "Unfinished Memory Palace "
        color: "hsl(256, 95%, 90%)"
        filters:
        - field: MemoryPalace
          operator: IS_EMPTY
          value: ""
          type: checkbox
```
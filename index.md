
## Default Variables

### finder_arrange_by

Desktop arrange by

#### Default value

```yaml
finder_arrange_by: grid
```

### finder_column_options_arranged_by

Arranged by column option

#### Default value

```yaml
finder_column_options_arranged_by: dnam
```

### finder_column_options_column_width

Column width column option

#### Default value

```yaml
finder_column_options_column_width: 250
```

### finder_column_options_font_size

Font size column option

#### Default value

```yaml
finder_column_options_font_size: 12
```

### finder_column_options_preview_disclosure_state

Preview disclosure state column option

#### Default value

```yaml
finder_column_options_preview_disclosure_state: true
```

### finder_column_options_shared_arrange_by

Shared arrange by column option

#### Default value

```yaml
finder_column_options_shared_arrange_by: kipl
```

### finder_column_options_show_folder_arrow

Show folder arrow column option

#### Default value

```yaml
finder_column_options_show_folder_arrow: true
```

### finder_column_options_show_icons

Show icons column option

#### Default value

```yaml
finder_column_options_show_icons: true
```

### finder_column_options_show_preview

Show preview column option

#### Default value

```yaml
finder_column_options_show_preview: true
```

### finder_column_options_show_thumbnails

Show thumbnails column option

#### Default value

```yaml
finder_column_options_show_thumbnails: true
```

### finder_default_icon_size

Default icon size

#### Default value

```yaml
finder_default_icon_size: 2
```

### finder_default_search_scope

Default search scope

#### Default value

```yaml
finder_default_search_scope: SCcf
```

### finder_dont_write_network_stores

Don't write network stores

#### Default value

```yaml
finder_dont_write_network_stores: true
```

### finder_dont_write_urb_stores

Don't write USB stores

#### Default value

```yaml
finder_dont_write_urb_stores: true
```

### finder_emptry_trash_securely

Empty trash securely

#### Default value

```yaml
finder_emptry_trash_securely: false
```

### finder_enable_extension_change_warning

Extension change warning

#### Default value

```yaml
finder_enable_extension_change_warning: false
```

### finder_enable_text_selection

Enable text selection

#### Default value

```yaml
finder_enable_text_selection: true
```

### finder_expand_print_panel

Expanded print panel

#### Default value

```yaml
finder_expand_print_panel: true
```

### finder_expand_save_panel

Expanded save panel

#### Default value

```yaml
finder_expand_save_panel: true
```

### finder_favorites

Favorites available in finder

#### Default value

```yaml
finder_favorites:
  - name: Home
    path: file:///Users/{{ finder_user }}
  - name: Applications
    path: file:///Applications
  - name: Desktop
    path: file:///Users/{{ finder_user }}/Desktop
  - name: Downloads
    path: file:///Users/{{ finder_user }}/Downloads
```

#### Example usage

```yaml
finder_favorites:
  - name: Home
    path: "file:///Users/{{ finder_user }}"
  - name: Applications
    path: "file:///Applications"
  - name: Desktop
    path: "file:///Users/{{ finder_user }}/Desktop"
```

### finder_folders_first

Sort folders first

#### Default value

```yaml
finder_folders_first: true
```

### finder_grid_spacing

Desktop grid spacing

#### Default value

```yaml
finder_grid_spacing: 100.0
```

### finder_icon_size

Desktop icon size

#### Default value

```yaml
finder_icon_size: 64.0
```

### finder_new_window_target

New window target

#### Default value

```yaml
finder_new_window_target: PfHm
```

### finder_path_bar_at_home

Pathbar home root

#### Default value

```yaml
finder_path_bar_at_home: true
```

### finder_path_in_title

Posix path title

#### Default value

```yaml
finder_path_in_title: true
```

### finder_preferred_group_by

Preferred group by

#### Default value

```yaml
finder_preferred_group_by: Name
```

### finder_preferred_view_style

Preferred view style

#### Default value

```yaml
finder_preferred_view_style: clmv
```

### finder_restore_window_state

Restore window state

#### Default value

```yaml
finder_restore_window_state: true
```

### finder_show_all_extensions

Show all extensions

#### Default value

```yaml
finder_show_all_extensions: true
```

### finder_show_external_drives_on_desktop

Show external drives

#### Default value

```yaml
finder_show_external_drives_on_desktop: false
```

### finder_show_hard_drives_on_desktop

Show internal drives

#### Default value

```yaml
finder_show_hard_drives_on_desktop: false
```

### finder_show_hidden_files

Show all files

#### Default value

```yaml
finder_show_hidden_files: false
```

### finder_show_item_info

Show item info

#### Default value

```yaml
finder_show_item_info: true
```

### finder_show_mounted_servers_on_desktop

Show mounted servers

#### Default value

```yaml
finder_show_mounted_servers_on_desktop: false
```

### finder_show_path_bar

Show path bar

#### Default value

```yaml
finder_show_path_bar: true
```

### finder_show_removable_media_on_desktop

Show removable media

#### Default value

```yaml
finder_show_removable_media_on_desktop: false
```

### finder_show_status_bar

Show status bar

#### Default value

```yaml
finder_show_status_bar: true
```

### finder_show_tab_view

Show tab view

#### Default value

```yaml
finder_show_tab_view: true
```

### finder_springing_delay

Springing delay

#### Default value

```yaml
finder_springing_delay: 0
```

### finder_springing_enabled

Springing enabled

#### Default value

```yaml
finder_springing_enabled: true
```

### finder_user

User to run user-specific commands

#### Default value

```yaml
finder_user | default(homebrew_user) | default(ansible_user_id)
```

### finder_warn_on_empty_trash

Warn on empty trash

#### Default value

```yaml
finder_warn_on_empty_trash: false
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger

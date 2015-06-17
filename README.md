# sublime

My current Sublime Text 3 configuration.

## Settings

```json
{
  "theme": "itg.flat.dark.sublime-theme",
  "color_scheme": "Packages/Theme - itg.flat/itg.dark.tmTheme",

  "font_size": 12,
  "line_padding_top": 2,
  "line_padding_bottom": 2,
  "font_options": [
    "gray_antialias"
  ],
	
  "tab_size": 2,
  "translate_tabs_to_spaces": true,
  "trailing_spaces_trim_on_save": true,
  "ensure_newline_at_eof_on_save": true,
  
  "rulers": [
    120
  ],
  "drag_text": false,
  "enable_tab_scrolling": false,

  "hot_exit": false,
  "remember_open_files": false,
  "create_window_at_startup": false,
  "preview_on_click": false,

  "word_separators": "./\\()\"':,.;<>~!@-#$%^&*|+=[]{}`~?",

  "folder_exclude_patterns": [
    ".git",
    ".sass-cache",
    "node_modules"
  ],

  "ignored_packages": [
    "Vintage"
  ],
}
```

## Packages

* Color Highlighter
* Package Control
* Sass
* SideBarEnhancements
* Theme - itg.flat
* Trailing Spaces

# sublime

My current Sublime Text 3 configuration.

## Settings

Install the required packages, then copy/paste this into `Preferences -> Settings - User`.

```json
{
  "theme": "Material-Theme-Lighter.sublime-theme",
  "color_scheme": "Packages/Material Theme/schemes/Material-Theme-Lighter.tmTheme",
  "material_theme_contrast_mode": true,

  "font_face": "Roboto Mono",
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
    "CSS",
    "Vintage"
  ],
}
```

## Packages

* Color Highlighter
* Package Control
* Sass
* CSS3
* SideBarEnhancements
* Material Theme
* Trailing Spaces

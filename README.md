# Sublime Text 3 Setup

My curated list of Sublime Text plugins I use on a daily-basis. The number one plugin I could not live without is [Package Control](https://github.com/wbond/sublime_package_control) - it is by far the best package manager if you use Sublime Text.

### My Package Control `installed_packages` list

This list is available at `Preferences > Package Settings > Package Control > Settings – User`

```js
{
  "installed_packages":
  [
    "AutoFileName",
    "BracketHighlighter",
    "CSS Snippets",
    "EditorConfig",
    "Emmet",
    "Emmet Css Snippets",
    "Gist",
    "Gutter Color",
    "HTML-CSS-JS Prettify",
    "HTML5",
    "HTMLAttributes",
    "Idiomatic-CSS-Comments-Snippets",
    "Markdown Preview",
    "MarkdownEditing",
    "Package Control",
    "Pretty JSON",
    "Sass",
    "SASS Snippets",
    "SassBeautify",
    "SideBarEnhancements",
    "StringEncode",
    "Terminal",
    "Theme - Soda"
  ]
}
```

Here is my settings as well:

```js
{
  "bold_folder_labels": true,
  "color_scheme": "Packages/User/Vice.tmTheme",
  "command": "use_it",
  "file_exclude_patterns":
  [
    "._*",
    ".DS_Store",
    ".git*",
    "*.pyc",
    "*.rdb",
    "sftp*",
    ".dropbox",
    "Icon*",
    ".sublime-*"
  ],
  "fold_buttons": true,
  "folder_exclude_patterns":
  [
    "wp-admin",
    "wp-includes",
    ".git",
    "env",
    "tmp",
    ".codekit-*"
  ],
  "font_size": 14,
  "highlight_modified_tabs": true,
  "ignored_packages":
  [
    "Vintage",
    "Markdown"
  ],
  "indent_guide_options":
  [
    "draw_normal",
    "draw_active"
  ],
  "keys":
  [
    "ctrl+alt+f"
  ],
  "line_padding_bottom": 1,
  "line_padding_top": 1,
  "match_brackets": true,
  "match_brackets_angle": true,
  "match_brackets_braces": true,
  "match_brackets_content": true,
  "match_brackets_square": true,
  "soda_folder_icons": true,
  "tab_size": 2,
  "theme": "Soda Dark 3.sublime-theme",
  "font_face": "Source Code Pro",
  "font_options":
  [
    "subpixel_antialias"
  ],
  "show_full_path": true,
  "highlight_line": true,
  "highlight_modified_tabs": true,
  "trim_trailing_white_space_on_save": true,
  "word_wrap": true
}
```
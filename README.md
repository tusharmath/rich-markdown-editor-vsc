# Rich Markdown Editor

Edit markdown files with a rich editor in the style of Dropbox Paper/Notion etc.

![Demo](demo.gif)

Perfect for writing docs, authoring blog posts, and editing markdown website content.

## Features

- Preview and edit in a single view
- Format with markdown syntax or slash commands
- Syntax highlighting for code blocks
- Easily add tables, checkboxes, dividers, quotes, links etc

This extension replaces the default code editor for markdown files with a rich version, allowing you to "edit" in preview mode.

## Customization

You can customize the editor's appearance through VS Code settings:

| Setting | Description | Default |
| --- | --- | --- |
| `rich-markdown-editor.fontSize` | Font size for the editor | `16px` |
| `rich-markdown-editor.fontFamily` | Font family for rendering markdown | System default font stack |

Example settings in `settings.json`:

```json
"rich-markdown-editor.fontSize": "18px",
"rich-markdown-editor.fontFamily": "Dank Mono, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
```

## Credits

This extension uses the [rich-markdown-editor](https://github.com/outline/rich-markdown-editor) project generously open sourced by [Outline](https://www.getoutline.com/)
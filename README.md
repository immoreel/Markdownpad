# MarkdownPad

A lightweight, browser-based Markdown editor in a single HTML file.  
[Try it out!](https://immoreel.github.io/Markdownpad/markdownpad.html)

## Features

### Editor
- Real-time preview with split-screen layout
- Syntax highlighting for code blocks
- Resizable editor/preview panes
- Synchronized scrolling
- Word, character, and line count
- Reading time estimation

### Toolbar
- Bold, italic, strikethrough formatting
- Headings (H1, H2, H3)
- Lists (bullet, numbered, checklist)
- Links, images, code blocks, quotes, tables
- Find & Replace
- Undo/Redo
- Fullscreen mode
- Print

### Document Management
- Save/load documents to localStorage
- Import .md files (drag & drop or file picker)
- Export to .md or .html
- Autosave with debouncing

### Keyboard Shortcuts
| Action | Shortcut |
|--------|----------|
| Save | Ctrl+S |
| Bold | Ctrl+B |
| Italic | Ctrl+I |
| Link | Ctrl+K |
| Find & Replace | Ctrl+F |
| Undo | Ctrl+Z |
| Redo | Ctrl+Y / Ctrl+Shift+Z |
| Fullscreen | F11 |
| Exit dialogs | Esc |

## Install

Simply open `markdownpad.html` in your browser. No server required.

Documents are saved in your browser's localStorage.

## Dependencies

Loaded via CDN (requires internet connection):
- [Showdown.js](https://github.com/showdownjs/showdown) v2.1.0 - Markdown to HTML converter
- [Highlight.js](https://highlightjs.org/) v11.11.1 - Syntax highlighting
- [Font Awesome](https://fontawesome.com/) v6.5.1 - Icons

## Version History

### v2.0 (2025)
- Complete rewrite with modern JavaScript (ES6+)
- Added toolbar with formatting buttons
- Added keyboard shortcuts
- Added Find & Replace
- Added import/export (MD and HTML)
- Added drag & drop for files and images
- Added resizable panes
- Added sync scroll
- Added word/character/line count
- Added undo/redo history
- Added fullscreen mode
- Added toast notifications
- Added cheatsheet popup
- Improved autosave (debounced, only on change)
- Improved responsive design for mobile
- Improved print styles
- Updated dependencies to latest versions
- Removed local dependency files (now via CDN)

### v1.0
- Initial release
- Basic Markdown editing and preview
- LocalStorage persistence

# JSON Editor

A single-file, dependency-free web app to view, search, and edit JSON.

**Live demo: https://ytmknd.github.io/JSONEditor/**

## Features

- **Tree view** – indented, collapsible, with inline editing
  - Click a value to edit it (booleans toggle on click)
  - Double-click a key to rename it
  - Add / delete items and change types (string, number, boolean, null, object, array) from the row actions
- **Text view** – edit raw JSON with line/column error reporting
- **Formatting** – indent with 2 spaces, 4 spaces, or tabs; minify; optionally sort keys
- **Search** – keys and/or values, case-sensitive option, regular expressions, highlighted matches with automatic expansion
- **Undo / redo**
- **Files** – open via button or drag & drop, save, copy to clipboard

## Keyboard shortcuts

| Shortcut | Action |
| --- | --- |
| `Ctrl+F` | Focus search |
| `Enter` / `Shift+Enter` / `F3` | Next / previous match |
| `Ctrl+Z` / `Ctrl+Y` | Undo / redo |
| `Ctrl+S` | Save |

## Usage

Open the [live demo](https://ytmknd.github.io/JSONEditor/), or clone the repository and open `index.html` in a browser. No build step or server is needed; everything runs locally in your browser and no data is uploaded.

```sh
git clone https://github.com/ytmknd/JSONEditor.git
cd JSONEditor
# open index.html
```

## License

[MIT](LICENSE)

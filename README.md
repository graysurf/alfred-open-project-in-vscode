# Open Project in VSCode · Alfred Workflow

Fuzzy-find and open any Git project from one or more base directories in Visual Studio Code, sorted by recent usage.

## 🚀 Features

- Recursively scan `$HOME/Project` or other custom paths (supporting multiple).
- Show last Git commit + last opened timestamp.
- Sorted by most recently accessed project.
- Works offline, no plugin managers required.

## 🔧 Configuration

Set these via Alfred's ⚙️ "Configure..." interface:

| Variable       | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| `PROJECT_DIRS` | Comma-separated paths to scan. Supports `$HOME`, `~`, etc.                  |
| `USAGE_FILE`   | Path to the usage log (default: `$HOME/.alfred_project_usage.log`)          |
| `VSCODE_PATH`  | Full path or command to launch your editor (default: `code`)                |

## ⬇️ Download

**[👉 Click to download .alfredworkflow](https://github.com/graysurf/alfred-open-project-in-vscode/releases/download/v1.1.0/open-project-in-vscode.alfredworkflow)**

## 📸 Screenshots

![preview](assets/preview.png)

---

> Visual Studio Code icon © Microsoft, used here for integration clarity.

---

## 🪪 License

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

This project is licensed under the [CC0 1.0 Universal (Public Domain Dedication)](LICENSE).  
You are free to use, modify, distribute, and integrate it without any restrictions or attribution.

# Minimalist Mermaid Builder

A lightweight flowchart builder that generates [Mermaid](https://mermaid-js.github.io/) syntax. Drag shapes onto the canvas, connect them, group nodes and export the diagram.

## Opening the App

Open `index.html` directly in a modern web browser (Chrome, Firefox, Edge, etc.). No build step or server is required – just double click the file or use `file://` in your browser.

## Key Shortcuts

- **C** – Toggle connection mode
- **G** – Toggle group mode
- **H** – Show/hide help panel
- **Ctrl+E** – Export Mermaid code to a `.mmd` file
- **Ctrl+Z/Y** – Undo/redo actions
- **Delete/Escape** – Remove selected nodes or cancel the current action

Quick actions include double‑clicking a node to rename it and shift/right‑clicking nodes to connect them directly.

## Features

- Drag‑and‑drop shapes (process, decision, terminal, subprocess, database)
- Zoom with the mouse wheel and pan with **Ctrl+drag**
- Toggle grid display, undo/redo history and clear the canvas
- Sidebar for node details and generated Mermaid code
- Export the diagram or copy the code to the clipboard
- Keyboard-accessible buttons with visible focus outlines

## Compatibility & Dependencies

The builder uses only vanilla HTML/CSS/JavaScript with no external dependencies. It should work in any modern desktop browser. Clipboard access and file downloads may require user interaction depending on browser security settings.

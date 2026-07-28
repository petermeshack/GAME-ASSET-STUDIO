# Game Asset Studio (Executable Version)

## Overview

**Game Asset Studio** is a standalone desktop application for creating and managing 2D game assets, tilemaps, spritesheets, animations, and TypeScript exports for custom game engines.

This executable version requires **no Python installation**. Simply extract the files and run the application.

---

# Features

## 🗺️ Level Designer

* Create tile-based maps.
* Resize map width, height, and tile size.
* Paint and erase tiles.
* Toggle grid visibility.
* Lock tiles to prevent editing.
* Exclude tiles from the painting palette.
* Edit existing tiles.

---

## 🎨 Pixel Tile Editor

Design pixel-art tiles directly inside the application.

Tools include:

* Pencil
* Eraser
* Bucket Fill
* Magic Wand
* Eyedropper
* Line Tool
* Undo
* Color Picker
* Canvas Resize

Save drawings directly as reusable tiles.

---

## 🖼️ Spritesheet Slicer

Import an existing spritesheet and extract tiles.

Supports:

* Adjustable Grid Width & Height
* Grid Offset
* Crop Offset
* Zoom
* Multi-selection
* Resizable selections
* Tile extraction directly into the Pixel Editor

---

## 🎬 Animated Tile Creator

Create animated tiles using:

* Sprite frame animations
* Color sequence animations

Configure:

* Animation speed
* Frame order
* Preview playback

---

## 🚫 Tile Exclusion Manager

Hide selected tiles from the Level Designer without deleting them from the project.

Useful for:

* Internal assets
* Development tiles
* Special effects
* Reserved tiles

---

## 🎮 Live Emulator

Preview your map and animated tiles without exporting.

---

## 📦 TypeScript Export

Generate TypeScript files ready for use inside compatible game engines.

---

# Project Files

Projects are saved as:

```
project_name.json
```

These files contain:

* Level settings
* Tile definitions
* Animation data
* Map layout
* Excluded tiles

---

# Folder Structure

After using the editor, your project may look like:

```
Game Asset Studio/
│
├── GameAssetStudio.exe
├── assets/
│     tile_grass.png
│     tile_wall.png
│     tile_water.png
│
├── MyProject.json
│
└── exports/
      level.ts
      assets.ts
```

---

# Supported Formats

### Import

* PNG
* JPG
* WEBP

### Save

* JSON Project

### Export

* TypeScript (.ts)

---

# Getting Started

1. Launch **GameAssetStudio.exe**.
2. Create a new project or open an existing one.
3. Create or import tiles.
4. Build your level.
5. Create animations if needed.
6. Preview in the Live Emulator.
7. Export TypeScript files.

---

# Tile IDs

Each tile requires a unique ID.

Examples:

```
g1
w1
t2
lava1
grass2
```

Every tile ID must be unique within the project.

---

# Keyboard Shortcuts

| Shortcut         | Action          |
| ---------------- | --------------- |
| Ctrl + N         | New Project     |
| Ctrl + O         | Open Project    |
| Ctrl + S         | Save Project    |
| Ctrl + Shift + S | Save Project As |

---

# Notes

* Imported assets are copied into the local **assets** folder.
* Generated PNG tiles are automatically managed by the application.
* Unused generated tile images may be removed when closing the application.
* Saving frequently is recommended while working.

---

# System Requirements

Minimum:

* Windows 10 or later (64-bit recommended)
* 4 GB RAM
* 200 MB free disk space

Recommended:

* Windows 11
* 8 GB RAM
* 1920×1080 display or higher

---

# Troubleshooting

### The application will not start

Ensure all files included with the executable remain in the same folder.

---

### Images do not appear

Verify that imported assets have not been moved or deleted after import.

---

### Export files are missing

Ensure the export process completed successfully and that the destination folder is writable.

---

### Project cannot be opened

Confirm the project JSON file has not been manually edited into an invalid format.

---

# Tips

* Keep all project files inside a dedicated project folder.
* Use meaningful tile names.
* Save projects regularly.
* Organize imported assets before beginning large maps.

---

# Version

Game Asset Studio

Executable Edition

---

Enjoy building your worlds!

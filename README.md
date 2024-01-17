# Skru
## What is Skru?
Skru is an open-source and web-based alternative to Usenti, a bitmap editor for paletted images last edited in 2007 (👴🏻) and only compiled for Windows (🤮). This repository is specific to the Skru frontend. For the backend, see [Skrudriver](https://github.com/skrusenti/skrudriver).
## User-facing Features
- Quick Figma-like UI to edit sprites, bitmaps, and palettes.
- Custom support for GBA Mode 3 and 4 bitmaps and Mode 0 sprites and tiles.
- Cross-session and cross-user sharing of bitmaps and palettes.
- Export to a paletted C array without download, just copy to clipboard.
- Support for export to source (`.c`), header (`.h`), or both.
## Technical Features
- Server-side rendering of static elements like toolbars and popups.
- GPU-accelerated rendering of the bitmap canvas.
- Custom parsing and transpiling of bitmaps to C arrays.

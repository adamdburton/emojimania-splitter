# EmojiMania Splitter

Splits an EmojiMania sprite sheet into individual **PNG** and **SVG** icons (including optional scaling), directly in the browser.

## Features

- Batch export to a ZIP containing `png/` and `svg/`
- Live grid overlay (with **Show Overlay** toggle)
- **Preview Zoom** (scales the preview only; exports unchanged)
- Custom **Group Names** (comma-separated) used in exported filenames
- Single icon selection + export (with arrow-key navigation)
- Optional **Solid Icon Color** override for monochrome icons

Live: https://adamdburton.github.io/emojimania-splitter/

![Preview](preview.png)

## Use

1. Open [index.html](index.html) in a browser.
2. Upload your EmojiMania sprite sheet.
3. Adjust the grid settings until the overlay lines up with the icons (use **Show Overlay** to toggle the grid on/off).
4. Use **Preview Zoom** to make alignment easier (preview only).
5. Click **Split & Download ZIP**.

The ZIP contains:
- `png/` (scaled using **Export Scale**)
- `svg/` (pixel-rect SVGs, scaled using **Export Scale**)

## Single Icon Export

- Click an icon in the preview to select it.
- Use the arrow keys (**← ↑ → ↓**) to move the selection.
- (Optional) Edit **Output Name**.
- (Optional) Adjust **Single Export Scale** (applies to single-icon exports only).
- (Optional) Set **Solid Icon Color** (only applies when an icon’s non-transparent pixels are all the same color).
- Export that one icon as **PNG** or **SVG**.
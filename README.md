# Patchworks 🧵

> *stitch your month together*

A personal monthly goal tracker styled as a patchwork quilt. Set up to 24 goals each month, mark them off as you go, and watch your quilt come to life — each completed goal becomes a uniquely patterned fabric patch.

**Live:** [windyzn.github.io/patchworks](https://windyzn.github.io/patchworks)

---

## Features

- **Monthly bingo board** — 5×5 grid with a FREE centre square
- **Goal entry** — fill in up to 24 goals per month; leave blanks to fill in later via Edit Goals
- **Random shuffle** — goals are scrambled into random board positions on creation
- **Fabric patches** — completing a goal transforms its tile into a CSS fabric pattern (gingham, stripe, polka dot, crosshatch, diamond, wide stripe) in a random palette colour
- **Progress bar** — pink progress bar shows completion % at a glance
- **Monthly stats** — Stats tab tracks % complete for every month, calculated against filled goals only
- **Edit Goals** — update any goal text on an existing board
- **Persistent storage** — all data saved to browser localStorage; no account or backend required
- **Bingo detection** — completed rows, columns, and diagonals trigger a celebration animation

---

## Usage

### Adding a new month
1. Click **+ New Month**
2. Select the month
3. Enter your goals (tip: start each with an emoji — e.g. `🏃 Run 5k`)
4. Click **Stitch it together** — goals are shuffled and your board is created

### Marking goals complete
Click any tile to toggle it as done. It will transform into a fabric patch. Click again to undo.

### Editing goals
Click **Edit Goals** on any board to update goal text directly on the tiles. Click **Save** when done.

### Viewing stats
Switch to the **Stats** tab to see completion % for all past months.

---

## Tech

- Single-file HTML — no framework, no build step
- Pure CSS fabric patterns (no images)
- `localStorage` for persistence (browser-only, no sync across devices)
- Deployed via GitHub Pages — auto-deploys on push to `main`

---

## Local development

```bash
# Just open the file directly — no server needed
open index.html
```

To deploy: commit and push to `main`. GitHub Pages picks it up automatically within ~30 seconds.

> **Note:** localStorage is origin-scoped. Data saved at `windyzn.github.io/patchworks` won't be visible when opening the file locally via `file://`, and vice versa.

---

## Palette

| Name | Hex |
|------|-----|
| Navy | `#2b3a8f` |
| Pink | `#e87fa0` |
| Gold | `#e8b84b` |
| Lavender | `#b8a8e8` |
| Teal | `#5ec4b8` |
| Orange | `#e8622a` |
| Cream | `#fdf8f0` |
# Planter Box Gate — 3D Build Guide

An interactive 3D step-by-step build guide for a **120cm tall planter-box gate**, designed to keep a toddler safe while adding garden planters to your outdoor space.

**Built entirely with AI assistance** — every line of 3D code, the shopping list, and the build instructions were generated through conversation with Claude.

## What's Inside

| File | Description |
|------|-------------|
| [`index.html`](index.html) | **Step-by-step 3D build guide** — watch the gate get assembled piece by piece with detailed instructions for each step |
| [`viewer.html`](viewer.html) | **Interactive 3D viewer** — explore the finished design with exploded views, labels, and hover-for-details |

Both files are **single-file HTML** — no build step, no dependencies to install, no server needed. Just open in a browser.

## The Build Guide (`index.html`)

The star of the show. A fully interactive 3D experience that walks you through 11 construction steps:

1. **Foundation Slabs** — level concrete base
2. **Corner Posts** — 8 posts from 45x95mm reglar
3. **Horizontal Rails** — 3 levels of bracing + angle brackets
4. **Shelf Boards** — internal platform with drainage
5. **Cladding** — 16x100mm boards on all sides
6. **Liner & Ballast** — waterproof liner + concrete weight
7. **Ground Anchors** — spikes and wire for stability
8. **Gate Frame** — stiles, rails, and the critical Z-brace
9. **Gate Pickets** — 14 boards with toddler-safe gaps
10. **Hang Gate & Hardware** — hinges, latch, slide bolt
11. **Soil & Plants** — fill and enjoy!

Each step shows:
- **3D animation** of parts being placed
- **Materials list** with exact quantities and dimensions
- **Tools needed** for the step
- **Numbered instructions** you can follow in your workshop
- **Pro tips** from the design process

### Controls
- **Arrow keys** or **click Next/Back** to navigate steps
- **Drag** to rotate the 3D view
- **Scroll** to zoom
- **Hover** parts for dimensions
- **Ghost mode** shows a faint preview of the final build
- **Auto-Play** watches the whole thing build itself

## The Design

Dimensions based on a real shopping list from Danish hardware stores (Bauhaus, Silvan, Jem & Fix):

- **2 planter boxes**: 115x40cm footprint, 120cm tall
- **1 gate**: ~120cm wide, hinged between the planters
- **14 pickets** with <60mm gaps (toddler head-safe)
- **Thumb latch** at adult height + **slide bolt** at the bottom
- **~50kg per planter** (concrete ballast + soil) for stability
- **Ground anchors** with steel wire for extra security
- All lumber is **pressure-treated** (trykimprægneret) for outdoor use

Total cost: ~2,200 DKK (~300 EUR) depending on store.

## Why AI + 3D?

This project demonstrates that **AI can generate useful, interactive 3D visualizations** for real-world build projects. Everything here was created through conversation:

1. **Design the build** — dimensions, materials, structural requirements
2. **Generate the 3D model** — Three.js code with accurate geometry
3. **Create the step-by-step guide** — construction sequence, animations, instructions
4. **Source the materials** — shopping list with real product links and prices

This approach works because:

- **Three.js is text** — AI can write 3D code as easily as any other JavaScript
- **Single-file HTML** — no toolchain complexity, just open and view
- **Interactive by default** — drag, zoom, hover, animate — far more useful than static diagrams
- **Iterative refinement** — change dimensions, add steps, fix details through conversation
- **Domain knowledge** — AI can combine 3D coding with construction knowledge, material specs, and safety standards

### What this means for builders

Instead of squinting at 2D drawings or watching 30-minute YouTube videos, you can:

- **Rotate freely** to see any angle
- **Step through construction** at your own pace
- **Hover for dimensions** on any part
- **See the exploded view** to understand how parts connect

The 3D guide lives alongside the materials — you can check it on your phone in the hardware store or in the workshop while building.

### The tech

Both files use:
- [Three.js](https://threejs.org/) (r128) loaded from CDN
- Zero dependencies, zero build tools
- Pure vanilla JavaScript
- All geometry created programmatically (no 3D modeling software needed)

## Usage

```bash
# Just open in a browser
open index.html

# Or serve locally
python3 -m http.server 8000
# → http://localhost:8000
```

## License

MIT — do whatever you want with it. If you build the gate, send a photo.

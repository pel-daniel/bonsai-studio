# Bonsai Studio

Procedurally generated 3D bonsai trees, built with Three.js. No build step — open the HTML file in a browser.

## Run

Open `bonsai-generator.html` directly in any modern browser.

## Controls

- **Drag** — orbit camera
- **Scroll / pinch** — zoom
- **Species** — Maple (textured leaves) or Pine (needle bundles)
- **Style** — Formal Upright, Slanting, Cascade, Windswept, Broom
- **Complexity** — branching depth
- **Foliage** — leaf/needle density
- **Wildness** — growth randomness
- **新 button** — grow a new tree

## Tech

Single HTML file. Three.js (r128) via CDN, no other dependencies. Trees, bark, leaves, and pot are all generated procedurally at runtime — nothing is loaded from disk.

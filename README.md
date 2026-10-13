# OpenCanvas · Free Painting Studio

An original, dependency-free drawing application inspired by familiar digital painting workflows. Not affiliated with or based on proprietary Procreate code.

## Run
Open `index.html` in a modern browser (Safari, Chrome, Edge, Firefox). No account or install required. For hosting, put `index.html` on any static HTTPS server, including GitHub Pages.

## Features
- Layered HTML Canvas painting, opacity/visibility, layer reordering, duplication and renaming
- Brush, eraser, picker, pan and four simple brush styles
- Pointer events for Apple Pencil/stylus pressure, mouse, touch, and coalesced events
- Two-finger pan/pinch zoom
- Undo/redo snapshots (up to 18 steps)
- PNG export and `.opencanvas` JSON project save/load
- Zero external JavaScript dependencies, no telemetry

## Limitations
This is an MVP, not a Procreate clone. The native Procreate brush engine, proprietary brushes, `.procreate` documents, animations, blend modes, selection/masks, and PSD exports are not implemented. Project snapshots may consume substantial RAM on large canvases. Apple Pencil behavior depends on browser/device support.

## Code/license
Original code contributed under the MIT License. Do not use Procreate logos, name, screenshots, or proprietary materials as app assets.

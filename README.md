# Cozy 3D Room — Three.js Demo

A cozy lo-fi bedroom scene built entirely in-code with [Three.js](https://threejs.org/). No external models or textures — every object is constructed from primitives, procedural geometry, and custom materials.

**[Live demo →](https://adrianhensler.github.io/three-js-room-demo/)**

## Features

- Fully furnished room: bed, desk, bookshelf, lamp, ceiling fan, window with night sky
- Interactive objects: toggle the desk lamp and ceiling fan on/off
- WASD + Q/E first-person movement inside the room
- Drag-to-orbit camera, scroll-to-zoom
- Warm atmospheric lighting — point lights, ambient occlusion-like shadows
- ACESFilmic tonemapping for a cinematic look
- Single HTML file, no build step, no assets

## Interactive Elements

| Object | Action |
|---|---|
| Desk lamp | Click to toggle on/off |
| Ceiling fan | Click to toggle on/off |

## Controls

| Input | Action |
|---|---|
| Drag | Orbit camera |
| Scroll | Zoom |
| W / A / S / D | Move forward / left / back / right |
| Q / E | Move down / up |
| Shift | Move faster |

## Stack

- [Three.js r128](https://threejs.org/) — rendering, geometry, materials, lights
- `OrbitControls` — drag + zoom
- Pure vanilla JS/HTML, single file, no build step

## The prompt

> Make a cozy 3D room demo using Three.js. Single file, no assets. Include interactive objects, movement, and warm atmospheric lighting.

Generated and refined with [Claude Code](https://claude.ai/claude-code).

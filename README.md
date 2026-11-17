# WebGPU Procedural Planet Renderer

ORRERY — Procedural WebGPU Planet Lab v1.0.6, a self-contained interactive planet renderer.

## Run locally

Serve this folder with a local HTTP server, for example:

```sh
python -m http.server 8000
```

Open http://localhost:8000 in a WebGPU-capable browser with hardware acceleration enabled. WebGPU requires localhost or HTTPS.

## Features

- Six planet presets with procedural, seeded surfaces
- Sea level, terrain, clouds, atmosphere, illumination, and rotation controls
- Ray-sphere rendering and an experimental displaced-mesh backend
- Rendering diagnostics, quality settings, and PNG snapshots

## Controls

Drag to orbit, scroll to zoom, Space to pause, R for a new seed, H to hide the interface, and D for diagnostics.

The application is contained in `index.html`; no build step or external assets are required.

# The Socion as Attractor Landscape

Static, GitHub Pages-compatible interactive visualization of the Socion as a grammar-constrained attractor landscape.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload the contents of this folder to the repository root.
3. In **Settings → Pages**, deploy from the `main` branch and root (`/`).

No build step is required. `index.html` loads the bundled Three.js runtime from `assets/three.min.js`. The optional web font falls back to system fonts when unavailable.

## Local preview

Opening `index.html` directly works in modern browsers. For the closest GitHub Pages behavior, serve the folder locally with any static file server.

## Controls

- Drag to rotate; Shift-drag or right-drag to pan; scroll or pinch to zoom.
- Click the field to create a local outward perturbation and terrain-following shockwave.
- Each type basin begins with four visible moving particles. They orbit the stationary type anchor, leave short trails, and may return or spill into another basin after a pulse.
- **Pulse the swarm** or the Space bar emits a coherent field-wide impulse; clicking the terrain produces a localized impulse from the selected epicenter.
- Use the Dynamics controls to tune attractor strength, variability, baseline drift, stress, and DCNH accent.
- **Image** and **Config** always open a preview first. Downloads occur only through the confirmation buttons in those previews.

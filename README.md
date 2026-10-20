# Tabla periódica 3D

Interactive periodic table built with [three.js](https://threejs.org/) (r128).

- All 118 elements, laid out with `CSS3DRenderer`; four shapes: table, sphere, helix and grid.
- Filter by family from the legend and search by name, symbol or atomic number.
- Click an element to open a WebGL view of its atom: a nucleus with its protons and neutrons, plus electron shells (Bohr model) with orbiting electrons.
- Data sheet: atomic number, mass, protons, neutrons (from the most common or most stable isotope), electrons per shell and electron configuration (Madelung rule plus the known exceptions).

## Run

Open `index.html` in a browser. Three.js loads from jsDelivr, so there is no build step.

`app.html` is the same page without the `<html>`/`<head>` skeleton (the version published as a Claude artifact). `index.html` is generated from it; edit `app.html` and rebuild `index.html`.

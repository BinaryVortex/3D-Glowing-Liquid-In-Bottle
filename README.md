# 3D Glowing Liquid In Bottle

A small, animated 3D glowing liquid effect inside a bottle built with plain HTML, CSS and JavaScript.

![Screenshot](./Screenshot%202024-06-08%20123553.png)

## Demo
Open `index.html` in a modern browser (Chrome, Firefox, Edge, Safari) to see the animation.

## Features
- Smooth 3D-looking bottle animation.
- Glowing liquid with hue/shadow effects.
- Pure HTML/CSS with a tiny JavaScript helper (no frameworks).
- Easy to customize color, size and animation timing.

## Files
- `index.html` — markup for the bottle and scene.
- `style.css` — all visual styling and animations.
- `script.js` — small slider/interaction script (this project is primarily visual; JS can be removed if not needed).
- `Screenshot 2024-06-08 123553.png` — demo screenshot used in this README.

## How to use
1. Clone the repo:

   git clone https://github.com/BinaryVortex/3D-Glowing-Liquid-In-Bottle.git
2. Open the project folder and double-click `index.html` (or serve it using a static server).

That's it — the animation runs without a build step.

## Customization
- Change the liquid color: edit the `.liquid` rule in `style.css` (background and drop-shadow color).
- Adjust animation speed: change the `animation`/`@keyframes` timing in `style.css` for `.bowl`, `.liquid`, and `.shadow`.
- Resize the bottle: change the `.bowl` width/height.

## Notes
- The current screenshot file name contains spaces (as committed). GitHub renders the image correctly, but if you prefer a cleaner filename, rename it (e.g. `screenshot.png`) and update the reference in this README.
- `script.js` in this repo contains a slider implementation. The visual demo does not require it; keep or remove it depending on your needs.

## Credits
Created by BinaryVortex.

Enjoy!
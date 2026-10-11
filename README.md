# BLUSH // IRON

A colorful **first-person mech shooter** by Braylon. Pink armor, chrome cannons, lavender skies, and a little chaos.

**[Play in your browser →](https://braylon89.github.io/blush-iron/)**

Step inside a pink mech and clear five waves of rogue machines. Choose upgrades between waves, collect floating armor patches, and bring down the Iron Warden.

## Controls

| Action | Desktop |
| --- | --- |
| Move / strafe | W A S D |
| Look | Mouse (click Deploy to capture it) |
| Fire | Hold left click |
| Boost | Space |
| Missile salvo | Q |
| Aim assist | F or the switch |
| Pause / release mouse | Escape |

Keyboard alternative: Up/Down moves, Left/Right turns, I/K looks up/down, and Enter fires. If mouse capture is unavailable, drag the arena to look.

On touch screens, drag the arena to look, use the direction buttons to move, and hold FIRE. Boost and missiles have buttons too. Aim assist only helps with machines near your crosshair.

Sound is optional. Your best score stays on this device. No account, downloads, or paid assets needed.

## Run locally

Serve this folder with any static server, for example:

```sh
python3 -m http.server 8766 --bind 127.0.0.1
```

Open `http://127.0.0.1:8766`. A WebGL-capable browser is required. GitHub Pages serves the same files directly with no build step.

- `engine.mjs` — movement, enemies, cover, weapons, waves, and upgrades
- `view.mjs` — 3D arena, chrome materials, robots, and cockpit cannons
- `game.mjs` — first-person controls, menus, audio, and HUD
- `index.html` / `style.css` — the pastel arcade interface

The locally bundled `three.module.js` and `three.core.js` are Three.js 0.186.1, used under the MIT license. See [THREE-LICENSE.txt](THREE-LICENSE.txt). Everything in the scene is drawn in code.

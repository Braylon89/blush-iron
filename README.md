# BLUSH // IRON

A pink and chrome mech arena shooter. Built by Braylon. Pilot a heavy combat frame, scrap rogue machines, and defeat the Iron Warden across five waves.

## Play

- **WASD / arrow keys:** move
- **Mouse:** aim, hold left click to fire
- **Space:** boost (briefly protects you from damage)
- **Q:** homing missile salvo
- **F:** toggle aim assist
- **Escape:** pause / resume

On a phone, hold a direction and the **Fire** button. Touch firing automatically aims at the closest enemy. Boost and Salvo have their own buttons.

Weapon heat builds as you fire. Let it cool, use cover to block incoming rounds, and collect green armor patches. Between waves, choose more damage, an armor repair, or better cooling. Sound is optional and starts off. Your best score stays in your browser.

## Run locally

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000`. No install or build step is needed. These files work with GitHub Pages.

## Make it yours

- `engine.mjs`: movement, weapons, enemies, collisions, and waves
- `game.mjs`: mech art, arena rendering, audio, and controls
- `style.css`: cockpit and interface
- `index.html`: page and starting mission

Artwork is drawn in Canvas. Sound effects are synthesized in the browser. No external assets, accounts, or API keys.

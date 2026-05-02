# Gravity Well

A single-file HTML5 Canvas arcade space shooter.

You orbit a black hole and auto-fire at incoming asteroids. Move around the orbit ring with the mouse or `A` / `D` to dodge. Survive escalating waves, chain combos, and rack up score.

## Play

Open `index.html` in any modern browser, or play it live via GitHub Pages once enabled (Settings → Pages → Deploy from `main` branch / root).

## Controls

| Action | Key |
| --- | --- |
| Move around orbit | Mouse, `A` / `D`, or touch |
| Start / restart | `Space`, `Enter`, click, or tap |
| Pause | `Esc` or `P` |

## Features

- Leading auto-aim that predicts asteroid position at bullet arrival
- Combo scoring with timed decay
- Particle explosions, shockwave rings, screen shake
- Procedural accretion-disk animation around the well
- WebAudio retro SFX
- Per-wave invincibility grace period
- High score persisted to `localStorage`

No build step, no dependencies — just a single `index.html`.

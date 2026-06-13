# 3D — a Gamf genre

Published at <https://gamf.github.io/3d/>.

- `games.json` — the list of games in this genre (the hub reads this).
- `games/<slug>/` — one self-contained folder per game.
- `index.html` — this genre's own landing page.

3D games use Three.js loaded from a CDN via an import map (no build step). Copy
`../templates/template-3d-three/` to start. See `../docs/ADD-GAME.md`.

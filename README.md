# indie-game-play

Web builds of Hang's games, published from the private repo codlearner/indie-game for playtesting in a browser
(https://codlearner.github.io/indie-game-play/). Generated files only.

The root `index.html` is a game picker. Each game's build sits in the folder with the same name as its folder in
indie-game, written there by `tools/publish_web.sh GAME`; a new game also gets a card in `index.html` and a cover in
`covers/` (a 640x360 JPEG from a screenshot).

| Game | Path | Built from codlearner/indie-game |
| --- | --- | --- |
| 重力立方 | `cubefps/` | d895a8a (photo-scanned textures, robots aligned with their hitboxes; `?demo=swarm` opens the cube-swarm look test) |
| 羽毛球 | `badminton/` | 799b725 (players with skeletons and swing animation) |
| 零零后 (paused) | `lifesim/` | same build as before, moved from the root unchanged |

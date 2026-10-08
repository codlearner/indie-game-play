# indie-game-play

Web builds of Hang's games, published from the private repo codlearner/indie-game for playtesting in a browser
(https://codlearner.github.io/indie-game-play/). Generated files only.

The root `index.html` is a game picker. Each game's build sits in the folder with the same name as its folder in
indie-game, written there by `tools/publish_web.sh GAME`; a new game also gets a card in `index.html` and a cover in
`covers/` (a 640x360 JPEG from a screenshot).

| Game | Path | Built from codlearner/indie-game |
| --- | --- | --- |
| 水位线 | `waterline/` | 0c97fbf (prototypes 1A, the one-year loop played in the picture of the home or as text, and 1B, one building in real time; a start screen picks one) |
| 重力立方 | `cubefps/` | 9223626 (complete small version: title, settings, one mission of six jammer towers and a three-phase core boss, death and checkpoint, results with rank and best record, generated music and sounds; the city, Meshy props, robots and drones from before; `?demo=swarm` opens the cube-swarm look test) |
| 羽毛球 | `badminton/` | 799b725 (players with skeletons and swing animation) |
| 零零后 (paused) | `lifesim/` | same build as before, moved from the root unchanged |

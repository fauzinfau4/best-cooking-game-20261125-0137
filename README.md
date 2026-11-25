[![make.fun · best-cooking-game-20261125-0137](https://make.fun/badge/best-cooking-game-20261125-0137.svg)](https://make.fun/bounty/best-cooking-game-20261125-0137?utm_source=github&utm_medium=readme&utm_campaign=best-cooking-game-20261125-0137)
[![rank](https://make.fun/badge/best-cooking-game-20261125-0137/fauzinfau4/best-cooking-game-20261125-0137/rank.svg)](https://make.fun/bounty/best-cooking-game-20261125-0137/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=best-cooking-game-20261125-0137)
[![reward](https://make.fun/badge/best-cooking-game-20261125-0137/fauzinfau4/best-cooking-game-20261125-0137/reward.svg)](https://make.fun/bounty/best-cooking-game-20261125-0137?utm_source=github&utm_medium=readme&utm_campaign=best-cooking-game-20261125-0137)

# Senja Kitchen Rush

A one-shift night-market cooking game about keeping a tiny evening stall moving when several tickets arrive at once. Follow each recipe from the pantry through chopping and the hot pan, then plate the exact ingredients and carry the dish to the serve window before its ticket runs out. The pan is ready after four seconds and burns after nine. Three missed or incorrect orders close the stall. Later tickets arrive faster, and each minute brings a twenty-second rush.

## Play

- Move with **WASD** or the **arrow keys**.
- Press **E** or **Space** to use the station you face. Hold it at the chopping board to chop.
- Press **1–5** to jump to pantry, chopping board, stove, plating counter, and serve window.
- Click a station to walk there; click again when close to use it. Click an ingredient bowl to pick it up. Click the pan or plate to act on it.
- **P** or **Escape** pauses. **M** mutes synthesized sounds. **Enter** starts or restarts.

Recipes: Sunset Rice (rice, egg, scallion), Moon Broth (noodles, chicken, greens), Ember Satay (chicken, peanut, lime).

## Run locally

Serve the `game/` folder with any static HTTP server. In the repo, `node serve.ts` serves it at `http://127.0.0.1:8080`. The game uses only its own JavaScript and canvas drawing; it makes no network requests and loads no external assets.

## Screenshot scenes

`shots.json` lists four deterministic scenes staged from the game's own state and renderer with `?shot=start|play|serve|over&seed=17`. To make the required images, serve `game/` locally, open each listed query in a desktop browser, and save a browser screenshot without editing it. The play scene shows a live ticket rush, active prep, a ready pan and a plate at the window.

<sub>Entered on [make.fun](https://make.fun/?ref=7tgjyx9m&utm_source=github&utm_medium=readme&utm_campaign=best-cooking-game-20261125-0137) · AI agents build software for cash rewards</sub>

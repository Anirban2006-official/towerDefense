# Aegis Dominion

Aegis Dominion is a browser-based tower defense game rendered on an HTML canvas. Choose a battlefield, build and upgrade defenses, and survive all 20 enemy waves.

## Features

- Three maps: Verdant Valley, Sunbaked Canyon, and Obsidian Core
- Four upgradeable tower types:
  - **Ballista** — rapid single-target attacks
  - **Bombard** — explosive splash damage
  - **Glacier Spire** — damages and slows enemies
  - **Tesla Arc** — chains lightning between enemies
- Five enemy types, including flyers and the Goliath boss
- 20 waves, with boss encounters on waves 10 and 20
- Adjustable game speed, pause, and audio controls
- Best wave saved separately for each map in your browser
- Mouse and touch input support

## Play

No dependencies, build tools, or installation are required. Open [`index.html`](./index.html) in a modern web browser.

Alternatively, serve the project locally from its directory:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000)
or visit this website: [https://towerdefense-orpin.vercel.app/](https://towerdefense-orpin.vercel.app/)

## How to play

1. Select a map and start the mission.
2. Choose a tower from the sidebar, then click or tap an open tile to place it.
3. Start each wave from the sidebar. Earn gold from defeated enemies and wave bonuses.
4. Select a placed tower to upgrade or sell it. Upgrades cost gold; selling returns 70% of the tower's investment.
5. Keep enemies from reaching the end of the path. Survive all 20 waves to win.

### Controls

| Action | Control |
| --- | --- |
| Select a map, tower, or tile; use buttons | Click or tap |
| Select a tower type | Keys `1`–`4` for Ballista, Bombard, Glacier Spire, and Tesla Arc |
| Pause or resume | `Space` or the on-screen button |
| Change game speed | On-screen `1x`, `2x`, and `3x` buttons |
| Toggle sound | On-screen Audio button |

## Built with

- HTML5 Canvas
- CSS
- Vanilla JavaScript
- Web Audio API for synthesized sound effects

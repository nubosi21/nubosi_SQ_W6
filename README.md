# Week 6 Example 2 — Free Roam Top-Down with Boss Battle

## What This Example Demonstrates

>
## Setup and Interaction Instructions

To run the sketch locally, open `index.html` in Google Chrome using Live Server.

**Controls:**
- Move: WASD
- Shoot: Spacebar (shoots in the direction you last moved)
- B: Skip to boss fight (testing only)
- Restart: R (after win or game over)

Explore the world, survive enemy waves as you move north, then enter the glowing boss zone to fight the giant orange blob. Watch the minimap to track enemies off screen.

**Adding Your Own Sounds**
1. Add your sound files to `assets/sounds/`
2. In `preload()`, uncomment the `loadSound()` lines and update the file paths
3. Uncomment the `play()` or `loop()` calls in the relevant functions — there are hooks for the boss music transition too

**Editing the Waves and Boss**
Open `data/enemies.json` to change when waves spawn, how many enemies appear, their speed, and the boss stats. Each wave has a `spawnAt` world Y value — lower values trigger later since the player starts at the bottom of the world.

**Opening the Chrome Console**
- **Windows:** Press `F12` or `Ctrl + Shift + J`, then click the **Console** tab
- **Mac:** Press `Cmd + Option + J`

## Assets
File                                Source
assets/images/player.png    Inspector Character — PNGTree
assets/images/bgimage.webp  Pixel Border Crossing Background — StockCake
assets/sounds/music.mp3 Game Music Loop 7 — Pixabay
assets/sounds/hit.mp3   Hit Sound Effect — Pixabay
assets/sounds/stamp.wav Stamp Sound Effect — Pixabay

## References
[1] PNGTree. n.d. Forensic Scientist Vector. Retrieved June 17, 2026 from
https://pngtree.com/freepng/forensic-scientist-vector_11066957.html

[2] StockCake. n.d. Pixelated Border Crossing. Retrieved June 17, 2026 from
https://stockcake.com/i/pixelated-border-crossing_3184890_1612432

[3] XtremeFreddy. 2023. Game Music Loop 7. Pixabay. Retrieved June 17, 2026 from
https://pixabay.com/sound-effects/musical-game-music-loop-7-145285/

[4] Pixabay. 2024. Hit Sound Effect. Retrieved June 17, 2026 from
https://pixabay.com/sound-effects/film-special-effects-hit-sound-effect-240898/

[5] NXRT (Freesound). 2022. Laser Pistol Shooting. Pixabay. Retrieved June 17, 2026 from
https://pixabay.com/sound-effects/film-special-effects-laser-pistol-shooting-95497/


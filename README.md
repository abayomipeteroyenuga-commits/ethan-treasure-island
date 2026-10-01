# Ethan Treasure Island — Complete Campaign Edition v2
A standalone 2D browser adventure by Ethan Digital Academy.

## Start playing
Extract the ZIP and open index.html. No installation, build step, API key or internet connection is required. All visuals and sounds are generated within the game.

## The campaign
Explore 12 named islands, from Palmhaven Shore to Crown of the Ocean. Each has its own deterministic layout, increasing enemy strength and environmental colors or decorations. Collect all three ancient keys, activate the numbered beacons in the displayed order, defeat the guardian, then walk to the chest. Completing an island unlocks the next one; finishing island 12 completes the campaign. Replay unlocked islands for coins and faster completion records.

Enemies include melee pursuers and ranged attackers. Guardians fire three projectiles at a time. Use your sword, dash through danger and drink healing potions. Each island starts with two potions.

## Controls
- Move: WASD or arrow keys
- Sword: Space
- Dash: Shift (2.5-second cooldown)
- Heal: E (restores up to three hearts)
- Pause: Escape or Pause
- Mobile: directional pad, sword, arrow dash and plus healing buttons

## Menus and progress
Islands: select any unlocked island.
Shop: spend expedition coins on vitality, boots or blade upgrades, up to three levels each. Vitality adds maximum hearts, boots increase speed and blade increases sword damage. Purchases are saved immediately. Start or retry an island after upgrading for a fresh expedition.
Help: story, controls, achievement status and best completion times.
Sound: optional synthesized effects, off by default.

Completed islands, coins, upgrades, sound preference and best times are stored in this browser. In-progress expeditions restart after closing the page. Browser data clearing removes saved progress. If storage is blocked, play remains available without persistence. No account or server is required.

## Publish
Upload index.html, style.css and game.js together to any static host. For GitHub Pages, place the files in the repository root and enable Pages. For Vercel, import the repository as an Other/static project with no build command. This archive contains the source for hosting; it has not been deployed to a public URL.

## Verification
JavaScript syntax checks and automated simulation checks passed for all twelve island key pickups, ordered beacon puzzles, guardian treasure gates, campaign completion, save data, healing, projectile defeat, retry and pause/resume. Canvas artwork was rendered and visually inspected. Full browser automation could not run in this environment because the browser download failed; physical-device touch behavior is not verified.

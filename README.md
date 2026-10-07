# Clawzy

Grab it. Cash out. A claw machine with a live market.

A single-page game (no build step): HTML, CSS and JavaScript all live in `index.html`.

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` and visit http://localhost:8000

## What's in it
- Arcade-cabinet claw machine: drag the glass or the joystick, press DROP
- Live market: prizes pump and dump and vanish on a timer, rugs cost you coins
- 96 original characters in five rarities, 5 claw upgrades, levels with new twists, 19 achievements
- Connect wallet (Phantom, Solflare, Backpack): reads the address only, no transactions

## Notes
- Free to play. The coins in the game are in-game points only, not a token, and nothing is stored on-chain.
- Progress saves in the browser (per wallet address and as guest).
- The weekly leaderboard, reward banner, wallet registration and owner panel use the shared database that the Claude-hosted page provides. On GitHub Pages or Vercel those parts show fallback messages, and the game itself works normally.
- A weekly reward, if you post one, would be paid by hand by the team. Giveaways have rules in many places, so check where you operate.

## Structure
- `index.html`: the whole game
- `assets/`: icon, profile pictures and X banner

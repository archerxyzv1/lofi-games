<p align="center">
  <img src="assets/lofi-face-a1b88584.webp" alt="Lofi the Yeti" width="120">
</p>

<h1 align="center">Lofi Games</h1>

<p align="center">
  Four free mini-games starring Lofi the Yeti, made for Lofi and the Lofi community.<br>
  Playable right now in your browser. No download. No wallet. Just play.
</p>

<p align="center">
  <a href="https://winterplay.online/lofigame/"><img src="https://img.shields.io/badge/Play%20now-winterplay.online%2Flofigame-16A34A" alt="Play now"></a>
  <a href="https://x.com/lofigamexyz"><img src="https://img.shields.io/badge/X-%40lofigamexyz-black" alt="Lofi Games on X"></a>
  <a href="https://www.youtube.com/@lofigamexyz"><img src="https://img.shields.io/badge/YouTube-Lofi%20Games-red" alt="Lofi Games on YouTube"></a>
</p>

---

## About

Lofi Games is a free browser game hub starring Lofi the Yeti. Four original mini-games, ten levels each, with XP, achievements, daily challenges and a leaderboard. Scores and achievements sync across devices when you sign in.

Made for Lofi the Yeti and the Lofi community — games built for them by us, not Lofi's own official game.

## The games

| Game | What it is | Folder |
| --- | --- | --- |
| **Lofi Dash** | Endless runner through the snow. Jump, dash, survive. | `dash/` |
| **Frozen Crossing** | Cross the frozen river on drifting ice and rideable boats. | `crossing/` |
| **Lofi Rush** | Three-lane mountain runner. Dodge, jump, slide, rush. | `rush/` |
| **Lofi Climb** | Bounce upward, platform to platform, all the way to the moon. | `climb/` |

## Features

- **10 levels per game** — longer climbs and runs as you progress
- **XP and achievements** — 5 achievements per game, 20 in total
- **Daily challenges** — 3 new challenges every day (reset 22:00 Asia/Dhaka)
- **Leaderboard** — top 25 players by XP
- **Stickerbook** — collect achievement stickers, download decorative stickers and phone wallpapers
- **Cross-device sync** — sign in with Google or email and your scores follow you (Firebase Auth + Firestore)
- **SUI wallet sign-in** — coming soon

## Tech stack

- **Vanilla HTML, CSS and JavaScript** — no build step, no framework
- **Firebase Auth** — Google and email sign-in
- **Cloud Firestore** — profiles, best scores, achievements, challenges, leaderboard
- **Canvas 2D** — all four games render on canvas
- **Static hosting** — deploy the files as they are

## Project structure

```
.
├── index.html          # Hub: games, achievements, challenges, leaderboard, settings
├── dash/               # Lofi Dash
├── crossing/           # Frozen Crossing
├── rush/               # Lofi Rush
├── climb/              # Lofi Climb
└── assets/             # Logos, banners, stickers, wallpapers, sprites
```

## Run locally

Serve this folder with any static server. For example:

```bash
npx serve .
```

Then open http://localhost:3000. Sign-in works against the live Firebase project; guest play needs no account.

## Deploying

The live site runs at https://winterplay.online/lofigame/.

This repo holds the Lofi Games project code on its own. The pages reference the `/lofigame/` subpath (game links, shared assets, favicon), so a standalone deployment at a domain root needs those paths rewritten to `/` first. Google sign-in uses the self-hosted Firebase auth handler on `winterplay.online`, so a new domain also needs to be added to the Firebase project's authorized domains.

## Built by

Built by **Archer** — [@0xArcherxyz](https://x.com/0xArcherxyz)

## Links

- **Play:** https://winterplay.online/lofigame/
- **Lofi on X:** https://x.com/lofitheyeti
- **Lofi Games on X:** https://x.com/lofigamexyz
- **Lofi Games on YouTube:** https://www.youtube.com/@lofigamexyz
- **Lofi's site:** https://hackathon.lofitheyeti.com

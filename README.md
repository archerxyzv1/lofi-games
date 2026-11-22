# Lofi Games

Four free mini-games starring Lofi the Yeti, made for Lofi and the Lofi community. Playable right now in your browser. No download. No wallet. Just play.

**Live site:** https://winterplay.online/lofigame/

## The games

- **Lofi Dash** — endless runner through the snow (`dash/`)
- **Frozen Crossing** — cross the frozen river (`crossing/`)
- **Lofi Rush** — three-lane mountain runner (`rush/`)
- **Lofi Climb** — bounce to the moon (`climb/`)

Each game has 10 levels, XP, 5 achievements, and its own best score.

## Features

- 10 levels per game, XP and achievements (20 total)
- Daily challenges (3 per day, reset 22:00 Asia/Dhaka)
- Leaderboard (top 25 by XP)
- Stickerbook of achievements, downloadable stickers and phone wallpapers
- Sign in with Google or email — scores and achievements sync across devices (Firebase Auth + Firestore)
- SUI wallet sign-in coming soon

## Tech

Vanilla HTML/CSS/JS, no build step. Firebase (Auth + Firestore) for sign-in and cloud saves. Deploy as static files; the live site runs at winterplay.online/lofigame/.

## Run locally

Serve this folder with any static server, for example:

```bash
npx serve .
```

## Project

Made for Lofi the Yeti and the Lofi community — games built for them by us, not Lofi's own official game.

- Lofi on X: https://x.com/lofitheyeti
- Lofi Games on X: https://x.com/lofigamexyz
- Lofi Games on YouTube: https://www.youtube.com/@lofigamexyz

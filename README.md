# ☕ Brew Companion

A personal pour-over coffee guide — single-file, mobile-first web app. Live at [brew.kdc.sh](https://brew.kdc.sh).

Built for a beginner dialing in pour-over with a Timemore C3 ESP hand grinder and a generic glass cone dripper, plus traditional Filipino kapeng barako (boiled, Batangas style).

## Features

- **Bean picker** — per-bean grind setting (grinder rotations), water temp, ratio, and brew time, fully editable in-app
- **Ratio calculator** — gram-based or spoon-approximation mode for the pre-scale era
- **Guided pour timer** — bloom → circular pours → drawdown, with per-phase water targets, sound/vibration cues, and screen wake-lock
- **Kapeng barako mode** — separate boiled-brew sequence (1:12, sugar in the pot)
- **Taste troubleshooter** — bitter → coarser/cooler/shorter; sour/weak → finer/hotter/longer
- **Brew log** — date, bean, grind, ratio, temp, rating, notes; stored in localStorage

## Running

It's one file. Open `index.html` in a browser, or serve it:

```sh
python3 -m http.server 8000
```

No build step, no dependencies, no backend. All data (beans, settings, brew logs) lives in the browser's localStorage.

## Deploying

Hosted on Cloudflare Pages:

```sh
npx wrangler pages deploy <staging-dir> --project-name brew-companion --branch main
```

Stage `index.html` into a clean directory first — the deploy uploads everything in the directory it's given.

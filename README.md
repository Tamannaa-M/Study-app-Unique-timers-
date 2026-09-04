# Melt & Burn

A cozy focus timer where you study alongside melting ice, burning candles, or a mystery flight. Sessions track real focus time separately from object progress, support hidden timers, and save history and productivity widgets in the browser.

## Features

- Five distinct ice and candle tiers with animated visual progress
- Mystery flights with destination tickets, changing cabin views, ETA, takeoff and landing
- Optional hidden timer with a final-minute reveal
- Multiple study spaces, ambience controls, notes, tasks, music embeds and history
- Responsive desktop and mobile layouts
- Local browser storage; no account or backend required

## Run locally

Open `index.html` directly, or serve this folder with any static file server.

For the short-duration test mode, open:

```text
http://localhost:8000/?debug=1
```

## Deploy with GitHub Pages

1. Create a new GitHub repository named `melt-and-burn`.
2. Upload everything in this folder to the repository root.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then click **Save**.
6. GitHub will publish the site at `https://YOUR-USERNAME.github.io/melt-and-burn/`.

The project is entirely static and requires no build command.

## Project structure

```text
melt-and-burn/
├── index.html
├── assets/
│   └── flight-weather-sprite.png
├── favicon.svg
├── README.md
└── .gitignore
```


# Window Seat

Road trip games for the UK and Europe. It installs on a phone's home screen and works offline in the car.

## What's in this folder

| File | What it does |
| --- | --- |
| `index.html` | The whole app |
| `manifest.webmanifest` | Lets phones install it as an app, with its name, colours and icons |
| `sw.js` | Keeps a copy on the phone so it works with no signal |
| `icons/` | Home-screen icons |

## Put it online with GitHub Pages (free)

1. Create a new public repository on GitHub, for example `window-seat`.
2. Upload everything in this folder to the root of the repository.
3. In the repository, open **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
4. After a minute or two the app is live at `https://<your-github-name>.github.io/window-seat/`.

## Install it on each phone

- **iPhone:** open the link in Safari, tap Share, then **Add to Home Screen**.
- **Android:** open the link in Chrome, tap the ⋮ menu, then **Install app** or **Add to Home screen**.

Open it once with signal before the trip so it saves a copy for offline use.

## Good to know

- The installed app has the ready-made journeys (London to Paris, London to Cornwall), the driving rules for 19 countries, the checklist, the games and bingo.
- Planning a journey for your own route uses Claude, so that only works in the Claude version: https://claude.ai/artifact/GUBGKjVPT9u9ndEZnJ6Sqg
- Scores and ticks are saved on each phone separately.
- After you change `index.html`, bump `VERSION` in `sw.js` (for example `ws-v2`) so phones pick up the new copy.

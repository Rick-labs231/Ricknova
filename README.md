# Ricknova website

Static site: just `index.html` + `img/`. No build step.

## Fill in your links
Open `index.html`, scroll to the bottom and edit the `LINKS` block:
```js
telegramBot: "https://t.me/Ricknova_Trading_Bot",
whatsapp:    "https://whatsapp.com/channel/0029Vb9XteN6GcGJCijbtO29",
contact:     "https://wa.me/2348154411519",
brushx:      "https://rick-labs231.github.io/brushx/",
brushxApk:   "https://github.com/Rick-labs231/brushx/releases/latest/download/brushx-debug.apk",
github:      "https://github.com/Rick-labs231"
```
Empty links show "coming soon" instead of breaking.

## Host free on GitHub Pages
1. github.com → New repository named exactly `Rick-labs231.github.io` (public).
2. Upload the contents of this folder (index.html, favicon.png, img/) to the repo root.
3. Settings → Pages → Source: Deploy from a branch → `main` / root → Save.
4. Live in a minute or two at `https://rick-labs231.github.io/`.
Quicker alternative: drag this folder onto app.netlify.com/drop.

## Notes
- The bot "chat" box is an illustration with placeholder prices, labelled as such.
- Stats shown: 130+ trades completed, 35% win rate, with a plain-English explanation and a risk warning. Update the numbers in the "bot-stats" section as the log grows (the `data-count` values and text).

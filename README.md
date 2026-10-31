# Santim Shop · ሳንቲም ሱቅ

Static storefront for coin top-ups, priced in Ethiopian birr. Hosted on GitHub Pages.

## Files
- `index.html` the whole site (Amharic by default, English toggle)
- `config.json` prices, pack sizes, payment accounts and Telegram username
- `.nojekyll` tells GitHub Pages to serve files as they are

## Change prices (works from a phone)
1. Open `config.json` in this repo on github.com.
2. Tap the pencil icon (Edit).
3. Change the numbers, for example `"price": 1400`. Keep the commas and quotes.
4. Tap **Commit changes**. The live site updates in about a minute.

## Before going live
Replace in `config.json`: `telegram`, and every payment `account` and `holder`.

## Turn on hosting
Repo **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main, folder: / (root)**.

Santim Shop is an independent store and is not affiliated with TikTok or ByteDance.

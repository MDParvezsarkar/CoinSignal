COIN SIGNAL - FULL PROJECT (upload everything in this folder to your GitHub repo)

FILES
  index.html   The whole website in ONE file (English / Bangla button at top left). No other file is needed for the website.
  smc.js, alerts.mjs, coins.json, state.json, .github/workflows/alerts.yml   Only for the optional Telegram alerts (GitHub Actions)

WEBSITE
  Market tab: top coins ranked by chance of rising in the next 1h / 12h / 24h, with BUY ZONE, SELL ZONE 1 / 2,
  STOP-LOSS, how much to invest, stable coin monitor. Zones come from real Binance history.
  My Coins tab: add each buy, live profit per buy, average, sell target, stop-loss, partial sell, alerts.
  Your old positions are imported automatically from the previous version.

IF DATA SHOWS LOADING
  The page tries 4 Binance hosts at once and shows the exact error. Press "Check connection" to see which host works.
  After uploading, press Ctrl+Shift+R (hard refresh) once, GitHub Pages caches files.

HOW TO UPDATE
  1. Delete the old files in your GitHub repo.
  2. Add file > Upload files. Drag in ALL files and folders (also the hidden .github folder).
  3. Settings > Pages > Deploy from branch: main (root). Wait 1-2 minutes.

Signals are analysis, not financial advice or a guarantee of profit.

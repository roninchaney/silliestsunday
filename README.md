# Kalshi Sports Predictor

A live sports prediction tool for Kalshi event trading. Hosted on GitHub Pages.

## Setup

1. Clone or download this repo
2. Open `index.html` and replace `YOUR_ODDS_API_KEY` with your key from [the-odds-api.com](https://the-odds-api.com)
3. Push to GitHub and enable GitHub Pages (Settings → Pages → Deploy from main branch)
4. Done — the site auto-updates with live game data every time it loads

## How it works

- Fetches live NBA and NFL schedules from The Odds API on page load
- Pulls real Kalshi market prices for each game automatically
- Runs a 7-signal win probability model (home advantage, seeding, series momentum, rating edge, recent form, rivalry factor, injuries)
- Calculates expected value and edge vs the live Kalshi price
- Manual or live ESPN injury entry

## API

- [The Odds API](https://the-odds-api.com) — free tier, 500 requests/month
- ESPN unofficial API — no key required, used for injury data

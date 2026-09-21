# SEC Simulator V1

A custom mobile-first stock-market competition interface based on the supplied ASDAN SEC reference screens and recordings. It uses plain HTML, CSS and JavaScript — no Streamlit and no dashboard template framework.

## V1 pages

- Exchange, watchlist and stock detail
- Buy / sell order panel with a configurable transaction fee
- Portfolio holdings and profit/loss
- Market News and Company Related News
- Overview, Top 3 ROI, asset curve and position volume
- Administrator dashboard, game timer, stocks, news, players and settings
- 3 rounds × 20 days by default; 40-second trading and 20-second closed sessions

## Prototype login

- Game code: `SEC2026`
- Administrator password: `SEC2026`

The player login only asks for a game code and team name, so it is fast to use at an event.

## Data note

This first public build is the requested UI prototype. It stores data in the current browser with `localStorage`. A shared database/realtime backend is the next implementation stage for a true multi-device competition.

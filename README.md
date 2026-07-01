# Formula One Pit Wall · F1 2026

An editorial-style Formula 1 dashboard built as a single HTML file.
Combines live race data with a custom pit stop strategy optimiser —
designed for F1 fans who want standings, strategy, and paddock intel
in one place.

## What it does

- **Live standings** — drivers and constructors updated after every race
- **Season calendar** — all 22 rounds, past results, upcoming race highlighted
- **Race countdown** — ticks to lights out every second
- **Pit Stop Strategy Optimiser** — dynamic programming + Monte Carlo
  simulation to calculate optimal pit windows, undercut/overcut alerts,
  and strategy confidence scores for all 22 drivers
- **Paddock Intel** — last race story, engine news, debut and calendar updates
- **Personalised title** — shows the logged-in user's name (e.g. "Dhruv's Pit Wall")

## Tech

- Vanilla HTML · CSS · JavaScript — zero dependencies, zero backend
- OpenF1 API — live race and session data
- Supabase — Google OAuth authentication
- Deployed via GitHub + Vercel

## Run it locally

Just open `index.html` in any browser. No install, no build step.

## Deploy your own

Fork this repo → connect to Vercel → done in 60 seconds.

## Built by

Chetan Padhiar · First-year B.Tech · Amity University Bengaluru  
[linkedin.com/in/chetan-padhiar-575b22374](https://linkedin.com/in/chetan-padhiar-575b22374)

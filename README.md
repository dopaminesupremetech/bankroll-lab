# Bankroll Lab

A free, browser-based sports betting bankroll simulator. No account or sportsbook connection is required.

## Features
- Compare flat staking, fixed-percentage staking, loss-increase/win-reset, and custom stake progression.
- Run Monte Carlo simulations with average, median, 5th/95th percentile ending bankroll, simulated profit frequency, drawdown stats, and stop-rule frequency.
- Set a maximum stake, drawdown stop, available-bankroll cap, win rate, net payout, run length, and optional seed.
- Review a bet-by-bet ledger, compare strategies on the same sample outcomes, and export the ledger to CSV.

## Run locally
Open `index.html` in any modern browser. The tool runs client-side and sends no betting data to a server.

## Publish with GitHub Pages
This repository includes a GitHub Actions workflow that deploys the static site to GitHub Pages whenever changes are pushed to `main`. In the repository, open **Settings → Pages** and choose **GitHub Actions** as the build and deployment source if it is not selected automatically.

## Disclaimer
This is an educational, hypothetical simulator. It does not predict future outcomes or guarantee profit, and it does not connect to sportsbooks or betting accounts.

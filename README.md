# Stormray Stats ⚡

Real-time basketball stat tracking for Shorewood High School varsity games.

## What It Does

Multi-device stat tracking designed for game day. Two JV players keep stats on separate iPads while the coach views a live dashboard on a third.

**Three roles:**
- **Offense** — Shot chart with make/miss tracking, free throws, assists, turnovers
- **Defense** — Rebounds, steals, blocks, fouls, hustle plays
- **Coach** — Read-only live box score, shot chart, and hustle feed

All stats sync instantly across devices via Firebase Realtime Database.

## Features

- Tap-to-record shot chart with automatic 2pt/3pt detection (NFHS 3-point line)
- Stormray Hustle Plays — track charges, deflections, loose balls, and more
- Per-quarter opponent scoring
- Live box score accessible from any role
- Post-game report with stat leaders, team highlights, and hustle plays
- Export to image (PNG) or spreadsheet (XLSX)
- Season stats with totals and per-game averages
- Season leaderboard across 12 categories
- Embeddable leaderboard widget for your school website
- Works offline — queues writes and syncs when reconnected

## Files

- `index.html` — Main app (single-file React + Firebase)
- `leaderboard.html` — Standalone season leaderboard page
- `embed.html` — Lightweight leaderboard for embedding via iframe
- `logo.png` — Shorewood logo

## Setup

The app is deployed via GitHub Pages and uses Firebase Realtime Database (free Spark plan). No build step — everything runs client-side.

## Live Site

[decentschott.github.io/stormray-stats](https://decentschott.github.io/stormray-stats)

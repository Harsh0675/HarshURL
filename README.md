# HarshURL Pro

A modern URL shortener built with Node.js, Express and SQLite.

## Features
- Random or custom short aliases
- Click tracking
- Expiration dates
- Disable links
- Responsive dashboard with dark/light mode
- SQLite persistence

## Run locally
```bash
npm install
npm start
```
Open `http://localhost:3000`.

## Environment
- `PORT` — server port
- `BASE_URL` — public short-link base URL
- `DB_PATH` — SQLite database path (use a persistent disk in production)

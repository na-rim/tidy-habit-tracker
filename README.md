# tidy-habit-tracker

A responsive habit tracker for daily tidying, with a crayon fruit basket.

- Challenge: 2026-10-24 through 2026-11-22 (30 days)
- Tap any free fruit to record today; tap a recorded fruit to change its record.
- Records stay in this browser using localStorage; no API keys or backend are required.

## Run

```sh
npm ci
npm run dev
```

## Build and verify

```sh
npm run build
node --test tests/habit.test.mjs
npm run test:sites
```

Vercel: Framework Vite, Root Directory repository root, Build Command `npm run build`, Output Directory `dist/client`. The checked-in `vercel.json` declares these settings. Navigation uses URL hashes.

Records on the earlier Sites preview do not transfer between origins to the new Vercel URL.

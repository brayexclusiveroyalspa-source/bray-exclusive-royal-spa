# BrAy Exclusive Royal Spa — GitHub Setup

This folder contains the portable React + Vite source code for the BrAy Exclusive Royal Spa website.

## Run locally

```bash
pnpm install
pnpm dev
```

Open the local URL shown by Vite. The website uses client-side WhatsApp links, browser geolocation, and local image assets under `client/public/assets`.

## Build

```bash
pnpm run check
pnpm run build
```

## Deploy

For Vercel, Netlify, or another Node/Vite host, use `pnpm install` as the install command and `pnpm build` as the build command. The output is generated under `dist/public`.

For GitHub Pages, configure a workflow or Pages build that runs `pnpm install` and `pnpm build`, then publishes `dist/public`. Because the app is a single-page landing page, no server API or database is required.

## WhatsApp

The booking form opens WhatsApp admin at `0857 3958 1203` with a prefilled message containing the selected language, treatment, add-ons, promo, location, and a `WEB-...` reservation code.

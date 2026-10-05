# Drain Cleaning Santa Barbara CA

Professional drain cleaning, clogged drain repair, and hydro jetting website built with Astro and deployed on Cloudflare Pages / Workers.

**Live site:** https://draincleaningsantabarbaraca.com

## Features

- Fully responsive, mobile-friendly design
- Service pages: Drain Cleaning, Clogged Drain Repair, Hydro Jetting, Camera Inspection, Emergency Service
- Service Areas page with embedded Google Map
- Contact page with form and map pinpointing 6 W Figueroa St #213, Santa Barbara, CA 93101
- SEO-ready (sitemap, robots.txt, meta tags, canonical URLs)
- Cloudflare adapter for Pages / Workers deployment
- Teal color scheme optimized for plumbing/drain services

## Commands

| Command | Action |
| --- | --- |
| `npm install` | Install dependencies |
| `npm run dev` | Start local dev server |
| `npm run build` | Build production site to `./dist/` |
| `npm run deploy` | Deploy to Cloudflare |
| `npm run preview` | Preview production build locally |

## Deploy to Cloudflare Pages

1. Connect the repository to Cloudflare Pages (or use Wrangler).
2. **Build command:** `npm run build`
3. **Deploy command / build output:** `npm run deploy` (or set output directory to `dist` in Pages dashboard).
4. Framework preset: Astro (or None).

Alternatively with Wrangler:

```bash
npm run build
npm run deploy
```

## Customize

- Update phone, email, and address in `src/consts.ts`
- Replace Formspree form ID in `src/pages/contact.astro` with your own endpoint
- Colors and styling are in `src/styles/global.css`

## Location

6 W Figueroa St #213  
Santa Barbara, CA 93101  
USA

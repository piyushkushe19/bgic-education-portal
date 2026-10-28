# BGIC Institute

Marketing site for **BGIC Institute** (Mahavir Enclave, New Delhi): coaching & tuition up to Class 12 (CBSE & NIOS), computer courses, IGNOU BCA/MCA, spoken English, and law coaching.

## Why images work on Vercel

The original site loaded photos over plain `http://…bgicinstitute.com`. On an HTTPS host (Vercel), browsers block those as **mixed content**, so images vanished.

All assets now live under `public/img/` and are served from the same origin (`/img/...`), so they load on HTTPS deploys.

## Run locally

```bash
npm install
npm run dev
```

Open [http://127.0.0.1:43123](http://127.0.0.1:43123).

```bash
npm run build    # production build → dist/
npm run preview  # preview the build on the same port
```

## Deploy (Vercel)

Connect the repo to Vercel (defaults work):

- **Build command:** `npm run build`
- **Output directory:** `dist`

`vercel.json` adds caching for `/img/*` and a SPA-style rewrite.

## Stack

- Vite + vanilla JS
- GSAP + ScrollTrigger (same scroll effects from phone to desktop)
- Three.js preloader emblem
- Hash routing (`#/home`, `#/courses/...`, etc.)

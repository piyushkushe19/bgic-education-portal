# BGIC Institute

Single-file site for **BGIC Institute** (Mahavir Enclave, New Delhi).

## Files

- `index.html` — complete site (CSS + JS inlined)
- `img/` — local images (required; fixes HTTPS/Vercel mixed-content)

## Run locally

```bash
npm start
```

Open [http://127.0.0.1:43123](http://127.0.0.1:43123).

Or open `index.html` next to the `img/` folder with any static server.

## Deploy (Vercel)

Upload/connect the repo. No build step — Vercel serves `index.html` and `img/` as static files.

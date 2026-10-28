# BGIC Institute

Single-file site for **BGIC Institute** (Mahavir Enclave, New Delhi).

## Files

- `index.html` — complete site (CSS + JS inlined)
- Images load from the original site:  
  `http://mahavir-enclave-coaching-classes.bgicinstitute.com/img/…`

## Run locally

```bash
npm start
```

Open [http://127.0.0.1:43123](http://127.0.0.1:43123).

## Deploy (Vercel)

No build step — serve `index.html` as a static file.

**Note:** The original image host only serves **HTTP**. On an HTTPS Vercel URL, some browsers block those images as mixed content. Prefer opening the site over HTTP locally, or use a host that allows the hotlinks.

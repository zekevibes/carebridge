# Coming Soon page

This repository contains a minimal "Coming Soon" landing page ready for GitHub Pages.

Files:

- `index.html` — page markup
- `styles.css` — simple styles
- `CNAME` — add your custom domain here (replace with your domain)

Quick setup:

1. The repo was created and pushed for you to GitHub (see details below).
2. In the repo Settings → Pages, confirm the source is `main` branch and `/(root)`.
3. On Namecheap, add the GitHub Pages DNS records (see below).

Namecheap DNS (example for `carebridgeafrica.com`):

- Add four `A` records for the apex domain pointing to:

```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

- Add a `CNAME` record for `www` pointing to `zekevibes.github.io`.

After DNS propagates, enable HTTPS in the Pages settings and wait for the certificate.

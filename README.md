# Eternity Game Studios — Landing Page

Temporary static landing page for Eternity Game Studios, hosted on GitHub Pages while the full ASP.NET site is in development.

Plain HTML and CSS, no build step. Edit `index.html` and `css/style.css` directly; GitHub Pages redeploys on every push to `main`.

## Local preview

```bash
python -m http.server 8080
```

Then open http://localhost:8080.

## Custom domain

To serve this at `eternitygamestudios.com`, add a `CNAME` file containing the domain to the repo root, then point DNS at GitHub Pages: A records for the apex to GitHub's Pages IPs, and a `www` CNAME to `thanolion.github.io`. Enable "Enforce HTTPS" in the repo's Pages settings once DNS resolves.

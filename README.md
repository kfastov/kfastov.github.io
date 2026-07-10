# Konstantin Fastov — portfolio

Static, dependency-free portfolio for [kfastov.github.io](https://kfastov.github.io).

## Local preview

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Structure

- `index.html` — semantic single-page portfolio
- `styles.css` — responsive layout and visual system
- `404.html` — GitHub Pages fallback
- `assets/resumes/` — three role-specific, two-page PDF resumes
- `assets/favicon.svg`, `assets/og-card.svg`, and `assets/og-card.png` — local identity and social-preview assets
- `robots.txt`, `sitemap.xml`, `site.webmanifest` — discovery metadata

There is no build step, JavaScript runtime, analytics, tracking, or third-party asset dependency. GitHub Pages can serve the repository root directly.

## Content rules

- Public links must resolve without authentication.
- Private repository names, production endpoints, account data, and strategy details do not belong on the site.
- Platform scale and personal contribution are stated separately.
- Resume files are copied from the approved resume output and should only be replaced with reviewed PDFs.

## Before publishing

1. Serve locally and inspect desktop and mobile layouts.
2. Verify every internal file and external URL.
3. Confirm that the contact details and PDF versions are current.
4. Commit and push only after review; this working tree is intentionally not auto-published.

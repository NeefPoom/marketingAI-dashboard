# Project Progress Website

Static manager-facing progress dashboard for Bare + Bond AI Marketing Intelligence.

## Files

- `index.html`
- `styles.css`

No build step is required.

## Recommended GitHub Pages Setup

This repo includes `.github/workflows/pages.yml`, which deploys this folder to GitHub Pages.

1. Push the repo to GitHub.
2. Open the GitHub repository.
3. Go to **Settings** -> **Pages**.
4. Under **Build and deployment**, set **Source** to **GitHub Actions**.
5. Go to **Actions** and run or wait for **Deploy project dashboard to GitHub Pages**.
6. After it succeeds, share the Pages URL shown in the deployment summary.

Expected URL format:

```text
https://neefpoom.github.io/marketingAI-dashboard/
```

The exact URL appears in the GitHub Actions deployment output.

Official GitHub references:

- https://github.com/actions/upload-pages-artifact
- https://github.com/actions/deploy-pages

## Privacy Note

This page is designed for project management sharing. It excludes credentials, tokens, `.env` values, and raw private data. Review text before publishing if future updates add client-private details.

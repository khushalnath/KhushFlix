# Khushflix starter

A mobile-first personal movie discovery PWA.

## Included
- Netflix-inspired dark cinematic interface and Khushflix wordmark
- Responsive poster rails, movie detail sheet, search and local watchlist
- Sample catalogue for first launch
- Optional TMDB API connection for live posters, descriptions, trending/search results, TMDB ratings and official streaming-provider availability
- PWA manifest, service worker and app icons

## Deploy on GitHub Pages (iPhone-friendly)
1. Download and extract `khushflix-starter.zip`.
2. Create a GitHub repository named `khushflix` (public is simplest for GitHub Pages).
3. Open the repository, choose **Add file → Upload files**.
4. Upload the five files from this folder: `index.html`, `manifest.json`, `sw.js`, `icon-192.svg`, `icon-512.svg`.
5. Commit changes.
6. Open **Settings → Pages**. Under Build and deployment choose **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
7. Wait for deployment, then tap **Visit site**. On iPhone Safari use Share → Add to Home Screen.

If GitHub's mobile layout hides upload controls, in Safari tap **aA → Request Desktop Website**.

## Live movie metadata
1. Create/sign in to an account at themoviedb.org.
2. Request a personal API key from Account Settings → API.
3. Open your deployed Khushflix site → gear icon → paste the TMDB v3 API key → Save and connect.
4. The key is saved only in that browser's local storage, not in this GitHub repository.

This is a personal static app. A client-side API key can be inspected by anyone who uses a shared deployment. For private use, keep the site private to yourself or later move API calls behind a backend.

## Accuracy and rights
- Ratings shown from TMDB are labelled TMDB, not IMDb.
- IMDb ratings require a separate data provider and appropriate API access; do not relabel TMDB ratings as IMDb.
- Official streaming availability is shown when TMDB provides it for the selected region.
- Audio-language and video-quality information must come from verified, authorised catalogue data. This starter does not scrape unauthorised sources or index pirated media.
- TMDB attribution: This product uses the TMDB API but is not endorsed or certified by TMDB.

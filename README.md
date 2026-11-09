# Blockoryn AI Manager — starter prototype

This is a mobile-friendly Progressive Web App starter for the Blockoryn Blogger workflow.

## Included
- `index.html` — dashboard and local article-draft editor
- `manifest.webmanifest` — installable web-app metadata
- `sw.js` — basic offline app-shell cache

## Deploy with GitHub Pages
1. Upload all files to the root of the `main` branch.
2. Open repository **Settings → Pages**.
3. Under Build and deployment, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then Save.
5. Open the published HTTPS URL on Android Chrome. Use the browser menu and choose **Add to Home screen** or **Install app**.

## Important limitations
This is a front-end starter only. It does not yet connect to Blogger API, Google Search Console, Analytics, cloud storage, or an AI model. Drafts are stored in local browser storage on the current device. Do not enter passwords, API keys, or OAuth secrets in this prototype.

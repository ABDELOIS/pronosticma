PronosticMA - Cloudflare Pages static upload

IMPORTANT: This ZIP contains the frontend only, arranged at the upload root.
The /api/matches endpoint is not active until the Worker is deployed and connected.

Upload steps:
1. Extract this ZIP on your phone.
2. In Cloudflare Pages drag-and-drop upload, select the 3 frontend files (index.html, style.css, app.js) directly, not the enclosing folder.
3. Deploy the Pages site.
4. The website frontend will publish, but match data will remain unavailable until Worker/API configuration is completed.

Do not treat predictions as real until historical statistics are connected. The current interface intentionally withholds predictions.

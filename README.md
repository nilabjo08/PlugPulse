# PlugPulse - Professional Interactive Website (v3)

PlugPulse is an English-only, responsive, interactive **EV charger verification prototype**.

The project demonstrates how drivers could check connector-level availability, charger faults, queue estimates, and backup route choices before heading out. All stations, statuses, queues and routes are simulated. No real charging-network, navigation or report backend is connected.

## Quick deployment on Netlify

1. Visit https://app.netlify.com/drop.
2. Drag `PlugPulse_Professional_Website_v3.zip` into the upload area, or extract it and drag the directory containing `index.html` plus `assets/`.
3. Open the public HTTPS URL Netlify supplies and verify the hero image, station explorer, fault reporting and trip simulation.
4. Optional: change the site name to a suitable available PlugPulse URL.
5. Paste the URL into your LinkedIn post and mark it an interactive prototype.

No build tools, Node, backend, or API keys are required. Keep the assets folder adjacent to index.html.

## Brand assets

- `PlugPulse_Logo.svg` and `PlugPulse_Logo_Transparent.png`: full vector/raster brand wordmarks.
- `assets/plugpulse-mark.svg`: new custom PlugPulse brand logo (P-shaped charging cable + pulse).
- `assets/favicon.svg`: matching site favicon.
- `assets/plugpulse-charging.webp`: web-optimized version of the user-provided EV charging photo.
- `assets/share-cover.jpg`: PlugPulse social sharing preview.
- `/mnt/data/PlugPulse_LinkedIn_Cover.jpg` is also supplied as a separate download.

All user-visible website text is in English. Unicode typographic punctuation is used, not regional-language scripts.

## Test the interactive product demo

1. Search or filter chargers and click a station or map pin.
2. Inspect each connector, the reported faults, and sample queue estimates.
3. Click Plan a route -> Start demo journey -> Simulate charger fault -> Switch route.
4. Report a problem and note that it is stored only for the active session and marked unverified.
5. Save a charger, inspect watchlist, or copy feedback to share externally.

## Limitations and media

The main charging photograph comes from the project creator. Other background photographs load remotely from Unsplash, and the supplied SVG illustrations work offline. The new logo is a source-code SVG vector; it does not depend on an external image generator.

The social sharing image path is relative. If LinkedIn does not detect the image after deployment, set the `og:image` value in index.html to the absolute public URL (for example https://YOUR-SITE.netlify.app/assets/share-cover.jpg) and redeploy.

There are no live feeds, payments, real alerts or notifications, Google Maps routing, operator submissions, or server-side data persistence. Do not market the demo as a live service.

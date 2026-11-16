# Live Tracker (Phone GPS)

A simple, serverless live-GPS web app. Open it on your phone, tap **📍**, allow location, and see your live position and trail on a dark map.

- Accurate phone GPS (±meters) — not IP-based
- Trail saved locally on your device (localStorage)
- No backend, no account, no API key
- Static site — runs on GitHub Pages

## Use

1. Open the GitHub Pages URL on your phone (HTTPS).
2. Tap the **📍** button.
3. Allow location permission when the browser asks.
4. Your live position appears on the map; the trail is saved on that device.

Tap **⌖** to re-center, **🗑** to clear the saved trail.

> GPS only works on a secure page (HTTPS or localhost). GitHub Pages serves HTTPS, so this works on phones.

## Files

- `index.html` — the whole app (Leaflet + GPS + trail)
- `vendor/leaflet/` — Leaflet library (local, no CDN)

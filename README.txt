TRADEVAULT v0.1 — TEST PROTOTYPE

Files:
- index.html: main app
- manifest.webmanifest: PWA metadata
- sw.js: basic offline caching for HTTPS hosting

IMPORTANT
- This is a prototype, not a hosted service. It does not have cloud accounts, cloud sync, or group sharing yet.
- Trade records are stored in the browser's localStorage on the device/browser where you use the app.
- Export a JSON backup regularly. Clearing browser website data may erase local records.
- P&L is the reported value from the CSV/manual entry; verify whether your export P&L already accounts for fees and commissions.

TEST ON IPHONE
1. Deploy these files to a static HTTPS host (for example, GitHub Pages or Cloudflare Pages).
2. Open the deployed HTTPS website in Safari.
3. Tap Share, then Add to Home Screen.
4. Import a TopstepX CSV using Import CSV.

The site must be hosted over HTTPS for service-worker/offline features and Add to Home Screen behavior to work reliably. Opening index.html directly from the Files app is not the same as hosting it on the web.

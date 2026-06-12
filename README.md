# Greek Daily Companion — Thai Mode

## Version
V1.6 — GTA Audio Engine Patch

## Build Date
June 12, 2026

## What changed in V1.6
- Replaced the simpler Thai-mode audio engine with the more mature GTA-style Greek audio engine.
- Added encoded audio button data attributes instead of relying only on inline `speakGreek(...)` strings.
- Added speech chunking, hard reset, keep-alive/resume, watchdog reset, and soft failure handling.
- Added a visible **Test Greek Voice** button on the dashboard.
- Updated app badge to V1.6.
- Added missing `icon-512.png`; the old service worker referenced it but the uploaded ZIP only had `icon-192.png`, which could break PWA caching.
- Updated service worker cache name to force the browser to load the new files.
- Added `notranslate` protection to reduce Chrome/Google Translate interference.

## Why this patch exists
The Greek-Thai build was not truly using the same audio engine as the GTA app. The GTA app has a more robust Greek speech system that handles Safari/Chrome speech stalls better. This patch brings that GTA-style approach into Greek Daily Companion.

## Important testing notes
1. Upload the full folder to GitHub Pages or another HTTPS host.
2. Open the app in the browser.
3. Hard refresh or clear site data if an older build was loaded before.
4. Tap **Test Greek Voice**.
5. It should read: `Καλημέρα. Γεια σας. Ευχαριστώ πολύ.`
6. If the voice still sounds robotic, check the OS/browser Greek voice settings. The app can request `el-GR`, but the final sound comes from the device/browser TTS engine.

## Included files
- `index.html`
- `styles.css`
- `app.js`
- `manifest.webmanifest`
- `sw.js`
- `README.md`
- `icon-192.png`
- `icon-512.png`

## Core features
- Speak Now
- Vocab
- Matching
- Play Mode
- Review Stack
- Mastered / Needs Review / Unmarked
- Greek audio
- Voice recording fallback
- LocalStorage progress
- PWA home-screen install support

# Greek Daily Companion — Thai Mode

## Version
V1.1 — Translator / Saved Phrases Build

## Build Date
June 10, 2026

## Purpose
Greek Daily Companion — Thai Mode is a simple, audio-first and picture-first Greek learning app for a Thai speaker living in a Greek home. It supports Greek, Thai, and English so the learner can understand the meaning and the household can check the phrase accuracy.

## Main Features
- Home dashboard with simple daily practice
- Speak Now mode
- Vocab mode with pictures/icons
- Matching mode
- Play mode
- Review Stack
- Mastered / Needs Review / Unmarked status buttons
- Status color changes and localStorage persistence
- Greek speech audio using browser speech synthesis
- Record My Voice / Stop / Hear My Voice support with safe fallback
- Translator / Saved Phrases mode
- Saved phrase list stored in localStorage
- Android/Honor-friendly PWA support
- Home screen install support through manifest and service worker

## V1.1 Changes
- Added Translator / Saved Phrases mode
- Added bottom navigation Save button
- Added dashboard Translator card
- Added search across existing app phrases
- Added custom saved phrase entry fields for Greek, Thai, and English
- Added audio playback for saved Greek phrases
- Added delete function for saved phrases
- Updated service worker cache version

## Files Included
- index.html
- styles.css
- app.js
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png
- README.md

## Install on Honor Android Phone
1. Upload the full app folder to GitHub Pages or another HTTPS web host.
2. Open the app link in Chrome on the Honor phone.
3. Tap the three-dot menu.
4. Choose Add to Home screen or Install app.
5. Tap the app icon from the phone home screen.

## Important Notes
- Microphone recording usually requires HTTPS. It may not work from a local file.
- Service worker and install-to-home-screen features also require HTTPS or localhost.
- The Translator is an offline saved phrase tool. It does not automatically translate new sentences from the internet.
- Do not keep old cached versions active when uploading a new build. After upload, hard refresh or clear site data if the old version still appears.

## Content Rules
- No George mention inside the app.
- No phone-answering category.
- No visitor-heavy category.
- Café & Bakery is separate from Restaurant / Eating Out.
- Food at Home stays short and practical.
- Thai is primary for understanding, English is visible for checking, Greek audio is primary for learning.

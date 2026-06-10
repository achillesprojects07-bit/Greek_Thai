# Greek Daily Companion — Thai Mode

## Version
V1.3 — Blue Theme, Audio Setup, Saved Phrases, Merged Duplicates

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

## V1.3 Changes
- New blue and white theme across app, manifest, and theme color
- Audio Setup screen: shows detected Greek voice name, Test Greek Voice button, install instructions when no Greek voice found
- Slow voice toggle (turtle mode, rate 0.65) saved in localStorage
- Saved Phrases screen built for real: search all phrases, save them, add custom Greek/Thai/English phrases, play audio, delete; persists in localStorage
- Bottom navigation now has 6 tabs including Saved
- Merged 5 duplicate phrase cards (How much, I am hungry, I am full, This one please, Thank you very much) into single cards appearing in both categories; statuses migrate automatically; total master cards now 195
- Service worker cache bumped to v1-3-0

## V1.2 Changes
- Speak Now and Vocab are now distinct: Vocab shows words and Start Here basics only (110 cards); Speak Now keeps all sentences (105 cards); overlap reduced from 105 to 15
- Strict Greek voice detection: audio only plays with a real Greek (el-*) voice; otherwise shows a warning instead of robotic fallback
- Fixed loose voice matching that could pick a wrong-language voice
- Audio rate set to 0.9 with neutral pitch for clearer playback
- Service worker cache bumped to v1-2-0

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

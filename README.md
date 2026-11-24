# Learnt tool

A PWA package built from the supplied original HTML app.

## Files
- `index.html` — original app with its document title changed to Learnt tool and PWA links/registration added.
- `manifest.json` — installable PWA metadata.
- `service-worker.js` — caches the app shell for offline reopening.
- `icon-192.png`, `icon-512.png` — app icons.

## Publish
Upload all files in this folder to the root of a GitHub repository, then enable GitHub Pages for the `main` branch and `/ (root)`.

## Notes
- The original learning logic and `localStorage` key (`sabaq`) are retained to avoid resetting existing saved progress.
- The app shell can reopen offline after it has been loaded once online. External fonts and linked textbook/resource PDFs still require internet unless separately cached/downloaded.
- Test the published HTTPS URL on the target Android phone before generating an APK.

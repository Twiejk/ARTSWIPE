# Art Swipe

Phone-first swipe app for collecting art direction references. Type a topic, swipe right to keep and left to skip, then export the kept images as a zip with a `manifest.json` your game project can read.

- Sources: Openverse and Wikimedia Commons (no key), Pexels and Unsplash (optional free keys, stored on the device).
- Speed: shows preview-size images and keeps 12 decoded ahead of the current card.
- Export: `<topic>/images/*`, `manifest.json` (source, creator, license, skipped images as negative examples), `README.md`.

Single file, no build step: `index.html`.

CLASS 10 STUDY TRACKER — PHONE APP (PWA)

This bundle turns the tracker into an installable Progressive Web App (PWA).
It is designed for Android phones and can also work on supported iPhones.

IMPORTANT:
- To install it as an app, it must be served from an HTTPS website. Opening index.html directly from Files is not enough for PWA installation/offline caching.
- The app saves entries in browser/app local storage on that device. It does not automatically sync between phone and computer.
- Export a JSON backup regularly from Accountability & export.
- The app does not automatically contact parents or send scheduled notifications. Existing ChatGPT reminders are separate.

EASIEST FREE HOSTING OPTION: GitHub Pages
1. On your computer, sign in to GitHub and create a new public repository, e.g. class10-study-tracker.
2. Extract this ZIP and upload all four files/folders at the repository root: index.html, manifest.webmanifest, sw.js, icon.svg.
3. In the repository, open Settings → Pages.
4. Under Build and deployment, choose Deploy from a branch, select main and /(root), then Save.
5. Wait for GitHub Pages to publish the site. Open the provided HTTPS URL on your phone.
6. Android/Chrome: tap ⋮ → Add to Home screen or Install app.
   iPhone/Safari: tap Share → Add to Home Screen.
7. Launch it from the new home-screen icon.

If GitHub asks for verification or menus differ, follow the current on-screen GitHub Pages prompts.

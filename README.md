# One Bell

A one-kettlebell training app: six guided sessions, animated demos of every move, rest and AMRAP timers, and a workout log.

Everything runs in the browser. Your log is saved on the device you train on (browser storage), so it is not shared between phones.

## Run it on GitHub Pages

1. Create a new public repository, for example `one-bell`.
2. Upload all the files in this folder to the root of the repository.
3. Go to **Settings > Pages**, set **Source** to *Deploy from a branch*, branch `main`, folder `/ (root)`, and save.
4. After a minute the app is live at `https://<your-username>.github.io/one-bell/`.

## Install on your phone

Open the Pages link in Chrome on Android, then tap the menu and choose **Add to Home screen** (or **Install app**). It then opens full screen and works offline after the first visit.

## Updating

Replace `index.html` with a new version and commit. If the phone keeps showing the old version, close and reopen the app once.

## Files

- `index.html` the whole app (HTML, CSS and JavaScript in one file)
- `manifest.webmanifest` and the icons make it installable
- `sw.js` caches the app for offline use

Training plan based on the Fit Dad Company free kettlebell week and a public kettlebell foundation workout. General fitness guidance, not medical advice.

# Dance Studio To-Do

A pixel-art to-do app where each task is a dancer. Install it on Android from Chrome (⋮ → Install app).

- `index.html` is the whole app.
- `firebase-config.js` holds the Firebase web settings (not secret). Left as the placeholder, the app saves on the device only.
- `firestore.rules` should be pasted into Firebase → Firestore → Rules. It keeps each person's tasks private to them.
- `sw.js` and `manifest.webmanifest` make it installable and usable offline.

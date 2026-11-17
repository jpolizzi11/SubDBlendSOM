# SubD Blend SOM

Self-organizing map of SubD typologies → Refine → Clusters (tiling with rules for floors, doors, voids and tiers).

Live site: GitHub Pages (Settings → Pages → Deploy from branch `main`, folder `/`).

## Files
- `index.html` — the whole app (Three.js loads from a CDN).
- `firebase-config.js` — the group's shared database settings. Empty = each browser saves on its own.
- `firestore.rules` — security rules to paste into the Firebase console.

## Shared data
Clusters, refined models, saved SOM runs and the SOM bank are shared through Firebase Firestore when `firebase-config.js` is filled in.

# Auto Logo Challenge

Upload the contents of this folder to the root of a public GitHub repository.
Go to **Settings → Pages → Build and deployment → Source: GitHub Actions**.
The workflow deploys after pushing to `main`.

## Add more levels
In `index.html`, find `const LEVELS=` and append a new array of 20 unique brands. The menu and random questions adapt automatically. Optionally add a display name in the level names array.

## Important limitations
- The password gate is client-side only and does **not** protect the site or its contents from visitors who inspect the source code.
- Logo and car images are fetched from Wikimedia Commons dynamically. Wikimedia search is not guaranteed to return a matching logo/photo; missing logos are skipped, and images should be manually reviewed before treating the game as finished.
- The audio effects are generated with Web Audio API, **not Pixabay downloads**. They start on user interaction, subject to browser sound settings.
- The brand order and answer choices are randomized each round; each brand appears once per level.

# Growth Level

A standalone learning and progress tracker for mathematics, Java, coding practice, DSA, English, typing, career skills, learning resources, and news.

## Run locally

1. Download `index.html`.
2. Open it in a modern browser (Chrome, Edge, Firefox, or Safari).
3. Progress is saved in that browser's local storage. Use **Export backup** regularly.

## Publish with GitHub Pages

1. Open your repository on GitHub.
2. Upload `index.html` to the repository root (keep a backup of any existing `index.html` before replacing it).
3. Commit the change.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose your default branch (usually `main`) and folder `/(root)`, then save.
7. Wait for GitHub Pages to publish and use the **Visit site** link shown on the Pages settings screen.

## Important limitations

- Progress is stored locally in the browser and does not sync between devices.
- Browser reminders and midnight downloads require the page to remain open and the device awake.
- The news panel requests feeds through a public RSS conversion service. It may be rate-limited or unavailable; when it fails, the site shows an error rather than inventing headlines.
- Daily email backups are not configured. Email requires a secure backend or scheduled automation; do not put email passwords or API secrets in this HTML file.
- This is a standalone frontend, not a backend service. Authentication, cloud synchronization, server-side scheduled jobs, and isolated code execution are not included.
- Resource URLs are curated links; their availability can change. News excerpts are provided by external feeds and are not independently fact-checked.

## Current core features

- Day-by-day subject curriculum for the 30-day plan
- Daily checklist, progress level, calendar and history
- Resource search across curated learning links
- Daily starter quiz with answer explanations
- Online headline fetching for world, science, technology, mathematics and sports categories
- Study-season timer with sound and speech alerts
- Browser reminders and JSON export/import

## Verification

The inline JavaScript was checked for syntax with Node.js. This does not substitute for a full browser, API, accessibility, or end-to-end test suite. Test the features in your own browser before relying on reminders or backups.

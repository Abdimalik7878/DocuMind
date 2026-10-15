# DayTrack Pro

A responsive, standalone productivity and personal-finance web application.

## Features
- Task creation, editing, completion, priority, due dates and search/filtering
- Project creation and task-based completion tracking
- Income and expense records with editable categories
- Monthly budget and spending insights
- JSON export/import backups
- Responsive layout, empty states, browser-local persistence

## Run
Open `index.html` in a modern browser. No installation, account, API key or build process is required.

## Important limitations
This is a fully functional **local-first frontend release**, not a hosted multi-user service. Data lives in the current browser's localStorage. It has no cloud sync, user accounts, backend API, payment processing or encrypted storage. Use **Settings → Export JSON backup** to preserve data. Browser storage may be erased when browser data is cleared.

## Deploy
Publish the three files (`index.html`, `styles.css`, `app.js`) to GitHub Pages or any static host. No secrets or environment variables are required.

## Privacy
No analytics, external libraries or network requests are included.

# Four Colour Energy Assessment

A responsive candidate-facing assessment platform built with React and Vite.

## Features
- Clickable personality word selection
- Live Blue, Red, Yellow and Green counts and percentages
- Dynamic four-colour energy circle
- Dominant and mixed energy profile
- Candidate name and printable report / Save as PDF
- CSV export of an individual assessment
- Responsive layout for desktop and mobile

## Run locally
Install Node.js, then run:

```bash
npm install
npm run dev
```

## Deploy to GitHub Pages
1. Create a GitHub repository.
2. Upload the contents of this project folder to the repository root (including the hidden `.github` folder).
3. Open Settings → Pages and select **GitHub Actions** as the source.
4. Push/commit to the `main` branch. The included workflow builds and deploys the site.
5. Find the live URL in Settings → Pages.

## Note
This version is frontend-only. It does not include admin login, a database, or permanent online storage. Candidate selections are held in the browser while the page is open. Add a backend later if you want to save submissions centrally.

# SnapImg — Simple Social Photo Feed

This project is a minimal social/photo-sharing app intended for the DETZ AI Innovation Division prompt engineering exercise.

What it demonstrates
- Firebase Authentication (email/password)
- Firebase Realtime Database as the posts store
- ImgBB integration for hosting uploaded images
- Plain HTML/CSS/ES module JavaScript (no frameworks)

Files to edit before use
- `src/firebase.js` — replace placeholders with your Firebase project config (apiKey, authDomain, databaseURL, projectId, etc.)
- `src/upload.js` — replace `<IMGBB_API_KEY>` with your ImgBB API key

Local dev
1. Configure the files above.
2. Serve the folder via a static server (or open `index.html` directly). Note: Firebase features require a networked page.

Deploy
- Use Firebase Hosting: initialize a project with `firebase init hosting` (or use Firebase Studio as required by the assignment), then deploy.

Prompts and prompt engineering notes
- See `prompts.md` for the stepwise prompts used to generate code via Gemini and notes about outputs.

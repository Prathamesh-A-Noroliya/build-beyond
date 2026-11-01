# BuildBeyond — Editorial Blue Interactive Prototype

This is the **Vercel-ready, self-contained frontend demo**. All four workspaces are accessible: Student, Mentor, Organizer and Business. The prototype contains synthetic data and browser-only workflows; it does not have a live Supabase backend or shared persistent data.

## Easiest deployment (no GitHub needed)
1. Go to https://vercel.com/drop and sign in.
2. Drag the entire `BuildBeyond_Deploy_Directly_To_Vercel.zip` file onto Vercel Drop.
3. Choose a project name and click **Deploy**.
4. Open the new `.vercel.app` website.

Each drop creates a new Vercel project. To deploy future updates to the same URL, link the project to a GitHub repository instead.

## Use your existing GitHub repository
1. Extract this ZIP on your Mac.
2. Copy these **extracted files** directly into the root of your `BuildBeyond` repository, alongside the `.git` directory (which Finder normally hides). Do not upload only the ZIP.
3. In GitHub Desktop commit and **Push origin**.
4. In the Vercel project use Framework Preset `Other`, Root Directory `./`, no Build Command, and Output Directory `.` (dot). The included `vercel.json` also specifies these settings.
5. Inspect the latest deployment and open your site.

## Files
- `index.html` — default homepage
- `app.js` — interactive demo
- `styles.css` — Editorial Blue theme and responsive layouts
- `favicon.svg` — site icon
- `vercel.json` — static deployment settings

No npm install, environment variables, or build step required for this demo.

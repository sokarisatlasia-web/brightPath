# BrightPath React Website

A two-page nonprofit website concept built with React, Vite, React Router, Lucide icons, and responsive CSS.

## Requirements
- Node.js (LTS recommended)
- npm

## Run locally
1. Extract the ZIP file.
2. Open the extracted `brightpath-website` folder in VS Code.
3. Open a terminal in that folder.
4. Run:

   ```bash
   npm install
   npm run dev
   ```

5. Open the local URL Vite prints in your terminal (usually `http://localhost:5173`).

## Pages
- `/` — Homepage
- `/about` — About Me

## Important customization notes
- BrightPath is a sample nonprofit concept, not a claim about a real registered organization.
- The About page uses the name Lance and general background content. Edit `src/App.jsx` to personalize it.
- The email address uses `.example` intentionally; replace it with a real contact address before publishing.
- Images and Google Fonts are loaded from the internet, so an internet connection is needed for those assets.
- Replace the sample mission and proposed program descriptions with verified details if using this for a real organization.

## Production build
Run `npm run build`. Vite creates the optimized site in the `dist` folder.

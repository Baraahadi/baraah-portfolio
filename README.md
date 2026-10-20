# Baraah Portfolio — Local Project

A local Vite project based on the supplied HTML portfolio. The original HTML, styles, animations, and embedded images have been preserved in `index.html`.

## Requirements
- Node.js (LTS recommended)
- npm

## Run locally
Open a terminal in this folder and run:

```bash
npm install
npm run dev
```

Vite will print a local address (usually `http://localhost:5173`). Open it in your browser.

## Test the production build
```bash
npm run build
npm run preview
```

The production-ready website is generated in the `dist/` folder.

## Before publishing
- Check the contact details and links in `index.html`.
- Test the scrolling animation and navigation on desktop and mobile.
- You can publish the project using Vercel, Netlify, or GitHub Pages. For Vercel/Netlify, connect the Git repository and use `npm run build` as the build command and `dist` as the output directory.

## Notes
The portfolio is currently a single-page HTML/CSS/JavaScript experience. It does not need React to run. Vite is included to provide a development server and a production build.

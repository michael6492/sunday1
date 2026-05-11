# Professional Portfolio

This repository contains a professional React portfolio built with Vite.

## Features

- Glassmorphism hero and section styling
- About, Experience, Project, and Contact sections
- Contact form connected to email via Formsubmit.co
- Project cards with screenshot previews and live links
- Responsive layout for desktop and mobile

## Run locally

Install dependencies and start the development server:

```bash
npm install
npm run dev -- --host
```

Open `http://localhost:5173/` in your browser.

## Production preview

After building, the expected GitHub Pages URL is:

`https://michael6492.github.io/sunday1/`

## Build for production

```bash
npm run build
```

## Deploy to GitHub Pages

1. Create a GitHub repository and push this project.
2. Build the app:
   ```bash
   npm run build
   ```
3. Deploy the `dist` folder to GitHub Pages using one of these options:
   - Use GitHub Pages on the `main` or `gh-pages` branch
   - Use the repository settings and select the `gh-pages` branch or `docs` folder if configured

### Quick GitHub Pages workflow

```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/<yourusername>/<your-repo>.git
git push -u origin main
```

Then enable GitHub Pages in repository settings.

## Notes

- Update the project URLs in `src/App.jsx` with your real GitHub or live links.
- Update the contact email or WhatsApp number if needed.
- Replace placeholder text and project images with your own content.

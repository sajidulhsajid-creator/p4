# Sajid Portfolio Website

A React + Vite portfolio website for MD Sajidul Haque Sajid.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Deploy to GitHub Pages

1. Create a new GitHub repository.
2. Upload all files from this folder.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **GitHub Actions**.
5. Push to the `main` branch.
6. GitHub Actions will build and deploy the site automatically.

The deployment workflow is already included at `.github/workflows/deploy.yml`.

## Notes

- This version uses `lucide-react` for icons.
- The Vite `base` is set to `./`, so it should work from most GitHub Pages repository paths without editing the repo name.
- Replace the LinkedIn, GitHub, and Resume links in `src/App.jsx` before publishing.

# Whalechild – Static Site (GitHub Pages)

This repository contains a single-page static website for Whalechild, built for GitHub Pages. It features a fullscreen background image, responsive typography, and the Bebas Neue display font.

## Local preview

Open `index.html` directly in a browser, or serve the folder with any static server.

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Deploy to GitHub Pages

1. Create a new GitHub repository and push these files.
2. In the repository settings, go to Pages and set:
   - Source: `Deploy from a branch`
   - Branch: `main` (or your default), folder `/` (root)
3. Save. Your site will be available at `https://<your-username>.github.io/<repo-name>/`.

### Custom domain (optional)
If you use a custom domain, add a `CNAME` file at the repo root containing your domain, and configure DNS to point to GitHub Pages.

## Assets
- `background.png` – hero background image used sitewide
- `demo.png` – design reference only

## License
All rights reserved to Whalechild LTD.

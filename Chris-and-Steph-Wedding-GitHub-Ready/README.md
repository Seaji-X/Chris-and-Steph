# Chris & Steph — Wedding Website

Static wedding save-the-date website prepared for GitHub Pages.

## Deploy with GitHub Pages

1. Create a new GitHub repository.
2. Upload all files from this folder to the repository root, including `.nojekyll`.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then save.
6. GitHub will display the published website address when deployment finishes.

No build command or package installation is required. The production website and its image/font assets are bundled into `index.html`.

## Before sharing the link

- Open the deployed page on both a phone and a computer.
- Confirm the questionnaire submits successfully. It currently sends responses to the Formspree form configured in `index.html`.
- GitHub Pages websites are publicly accessible. The page includes `noindex` instructions to discourage search-engine indexing, but anyone with the URL can open it.

## Local preview

From this folder, run:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

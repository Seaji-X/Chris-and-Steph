# Chris & Steph — Save the Date

Static wedding website prepared for deployment on Vercel.

## Deploy through GitHub

1. Create a new GitHub repository.
2. Upload every file and folder from this package to the repository root.
3. In Vercel, select **Add New → Project** and import the GitHub repository.
4. Leave **Framework Preset** set to **Other**.
5. Leave the build command and output directory empty, then select **Deploy**.

Vercel will serve `index.html` automatically; no build process or environment variables are required.

## Before sharing the website

- Confirm the Formspree form at `https://formspree.io/f/mdenldbr` belongs to you and is accepting submissions.
- Submit one test response after deployment and confirm that it arrives correctly.
- Test the **Add to calendar** button on both a phone and a computer.

## Local preview

From this folder, run:

```bash
python3 -m http.server 3000
```

Then open `http://localhost:3000`.

The Vercel configuration discourages search-engine indexing because the site contains personal wedding information. It does not password-protect the website.

# Portfolio

Engineering Portfolio for jobs/internships.

## Files

- `/home/runner/work/Portfolio/Portfolio/index.html` - main website page
- `/home/runner/work/Portfolio/Portfolio/styles.css` - site styling
- `/home/runner/work/Portfolio/Portfolio/Huberty_Jackson_Resume.pdf` - resume download file

## Run locally

This is a static website, so you can open `index.html` directly in a browser.

If you want a local server:

```bash
cd /home/runner/work/Portfolio/Portfolio
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Launch with GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings > Pages** in the repository.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Select branch: `main` (or your default branch) and folder: `/ (root)`.
5. Save, then wait for Pages to publish.
6. Your site will be available at:
   `https://<your-github-username>.github.io/Portfolio/`

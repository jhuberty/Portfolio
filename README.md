# Jackson Huberty Engineering Portfolio

This repository is a GitHub Pages-ready engineering portfolio website for Jackson Huberty. It is designed to showcase mechanical design, manufacturing, fabrication, testing, troubleshooting, and agricultural equipment experience.

## 1) Preview locally

1. Download or clone this repository.
2. Open `/home/runner/work/Portfolio/Portfolio/index.html` directly in your browser, or run a simple local server:
   - Python: `python3 -m http.server 8000`
3. Visit `http://localhost:8000`.

## 2) Replace placeholder images

Image folders are organized in:

- `/home/runner/work/Portfolio/Portfolio/assets/images/quarter-scale/`
- `/home/runner/work/Portfolio/Portfolio/assets/images/agave-harvester/`
- `/home/runner/work/Portfolio/Portfolio/assets/images/machining/`
- `/home/runner/work/Portfolio/Portfolio/assets/images/agriculture/`
- `/home/runner/work/Portfolio/Portfolio/assets/images/experience/`
- `/home/runner/work/Portfolio/Portfolio/assets/images/profile/`

Steps:

1. Keep existing filenames (recommended), or update image paths in HTML if you rename files.
2. Replace placeholder `.svg` files with your real photos (JPG/PNG/WebP are fine).
3. Keep images web-friendly (compressed) to improve load speed.
4. Update alt text in HTML to match each real image.

## 3) Update project descriptions

Main page project cards are in:

- `/home/runner/work/Portfolio/Portfolio/index.html`

Detailed project pages are in:

- `/home/runner/work/Portfolio/Portfolio/projects/quarter-scale.html`
- `/home/runner/work/Portfolio/Portfolio/projects/agave-harvester.html`
- `/home/runner/work/Portfolio/Portfolio/projects/machining.html`
- `/home/runner/work/Portfolio/Portfolio/projects/agricultural-equipment.html`

Look for placeholders like:

- `[ADD PROJECT DESCRIPTION]`
- `[ADD SPECIFIC CONTRIBUTION]`
- `[ADD TESTING DETAILS]`
- `[ADD LESSONS LEARNED]`

Replace these with your real, factual project details.

## 4) Replace resume

1. Put your PDF here:
   - `/home/runner/work/Portfolio/Portfolio/resume/Jackson_Huberty_Resume.pdf`
2. The Resume buttons and preview already point to this file.

## 5) Update LinkedIn / GitHub / Email links

Edit these placeholders in `index.html`:

- `[ADD-LINKEDIN]`
- `[ADD-GITHUB]`
- `[ADD-EMAIL]`
- `[ADD-GITHUB-PAGES-URL]`

## 6) Publish with GitHub Pages

1. Push changes to your GitHub repository.
2. In GitHub, go to **Settings → Pages**.
3. Under **Build and deployment**, choose:
   - **Source**: Deploy from a branch
   - **Branch**: `main` (or your preferred branch)
   - **Folder**: `/ (root)`
4. Save. GitHub will publish the site and provide a URL.
5. Replace `[ADD-GITHUB-PAGES-URL]` in `index.html` with your live site URL.

## 7) Update the website later

- Content: edit `index.html` and files in `/projects/`.
- Styling: edit `/home/runner/work/Portfolio/Portfolio/styles.css`.
- Interactions (menu/lightbox): edit `/home/runner/work/Portfolio/Portfolio/script.js`.
- Add new projects by creating another `projects/*.html` page and linking it in `index.html`.

## Current structure

```text
/
  index.html
  styles.css
  script.js
  README.md
  projects/
    quarter-scale.html
    agave-harvester.html
    machining.html
    agricultural-equipment.html
  assets/images/
    quarter-scale/
    agave-harvester/
    machining/
    agriculture/
    experience/
    profile/
  resume/
```

# Siyu (Jason) Zhu — Personal Research Website

Minimal, responsive academic homepage based on the approved prototype.

## Contents

- `index.html` — complete website (HTML + CSS, no framework)
- `assets/profile.jpg` — optimized copy of the supplied LinkedIn headshot
- `favicon.svg` — SZ monogram favicon
- `.nojekyll` — disable Jekyll processing for GitHub Pages

## Preview locally

Open `index.html` in a browser, or from this folder run:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Publish with GitHub Pages

1. Create a public GitHub repository, e.g. `siyu-zhu.github.io` if that is your GitHub username, or any other repo name.
2. Upload **the contents of this folder** to the repository root and commit them.
3. Under **Settings → Pages**, select **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. If using a project repository rather than a `<username>.github.io` repository, the homepage appears under `https://<username>.github.io/<repo>/`.
5. Optionally configure a custom domain after the site is live. Do not add a CNAME file until the domain is chosen.

The site does not collect analytics, use cookies, or rely on external CSS/JS. Research/project links open in new tabs.

## Updating the site

- **Bio:** edit the two paragraphs in the `#about` section.
- **Publications:** copy one `<article class="entry">` block in `#research`, update title, URL, venue/year, and summary.
- **Projects:** copy one `<article class="project">` in `#projects`.
- **Headshot:** the supplied photo is already installed at `assets/profile.jpg`. To change it, replace that image file with another photo (keep the same filename).

- **CV:** if adding a downloadable résumé, first create a **public version without your home address or personal phone number**, add it to this folder (e.g. `cv.pdf`), and then add a `CV` link in the `.link-row`.

## Content note

Paper titles and arXiv links checked in October 2026. The "Findings of EMNLP 2026" and "EMNLP 2026" labels reflect the author's supplied acceptance information; those venue labels can be updated when official anthology links become available. Verify employer/title and all statements before public deployment.

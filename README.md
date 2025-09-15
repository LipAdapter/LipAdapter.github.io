# LipAdapter — Project Page

Minimal static project page suitable for research papers.

## Update content
- Edit `index.html`:
  - Title, authors, affiliations
  - Links for Paper, arXiv, Code, Video
  - Abstract, Method, Results, Acknowledgements
  - Replace teaser SVG and placeholders with images in `assets/`
- Edit `assets/styles.css` for branding colors if needed.
- Update BibTeX in the Citation section.

## Assets
- Put images in `assets/img/` and update paths in HTML.
- Add `assets/favicon.png` and `assets/og-image.png` if desired.

## Run locally
Open `index.html` directly in a browser or serve with Python:

```
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Deploy to GitHub Pages
- Push this repository to GitHub.
- In repository Settings → Pages, choose branch `main` and `/ (root)`.
- Wait a minute; your site will be live at the provided URL.

## License
This template is provided as-is. You may copy and adapt it.

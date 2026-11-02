# Lu Gu Academic Homepage

A buildless, responsive academic portfolio prepared from the supplied research summary and portrait. The current design follows a Minimal Light direction: a compact profile sidebar, narrow reading column, publication-first hierarchy, and restrained academic styling.

## Publish with GitHub Pages

This repository contains a standard GitHub Pages workflow. Push the repository to GitHub with `main` as the default branch, then choose **GitHub Actions** under **Settings → Pages → Build and deployment**. The workflow publishes the contents of `dist/`.

For a personal homepage URL, use a public repository named `<github-username>.github.io`.

## Preview locally

Serve the `dist` directory with any static HTTP server, for example:

```powershell
python -m http.server 4173 --directory dist
```

Then open `http://localhost:4173`.

## Content still needed

- Institutional affiliation and department
- Advisor or laboratory name, if public
- Institutional email
- GitHub, Google Scholar, ORCID, and CV links
- Approved research figures or simulation stills
- Final publication metadata, DOI, and paper links

The defence-related patent was deliberately omitted from the public-facing page pending disclosure review.


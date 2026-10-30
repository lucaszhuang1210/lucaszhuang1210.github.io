# Lucas Zhuang · Personal portfolio

A lightweight, responsive personal site for GitHub Pages. Plain HTML, CSS, and inline SVG; no build step, JavaScript, tracking, remote fonts, or package dependencies.

## Preview

Open `index.html` directly, or serve this folder:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Then visit http://127.0.0.1:8765.

## Design and content

Warm white, charcoal, muted green, generous whitespace, and editorial typography. The page moves from introduction to selected work, experience, a personal note, and contact. All artwork is original decorative SVG or explicitly labeled concept illustration, not a product screenshot. No portrait is fabricated.

Public sources and destinations:

- [GitHub profile](https://github.com/lucaszhuang1210/lucaszhuang1210): project descriptions, Yahoo Finance work, current graduate studies, education, contact and résumé links.
- [Blux](https://bluxlabs.com/) and [Lucas's discovery statement](https://bluxlabs.com/statements/saving-human-intelligence-for-discovery/).
- [Fabflix](https://github.com/lucaszhuang1210/Fabflix) and [Checkers AI](https://github.com/lucaszhuang1210/Checkers-AI-Agent).

Biography copy is a first draft for Lucas's review. The design intentionally omits private research implementations and unapproved employer material.

## Publication

The repository's existing Pages configuration publishes `main` at `/` using GitHub's built-in `pages-build-deployment` workflow. This redesign is on a feature branch. Pushing the feature branch does not update the live website. Publishing requires a separate, explicitly approved merge or change to the Pages source.

## Verification

Completed: HTML parsing, unique ID and internal-anchor checks, heading structure, `git diff --check`, successful local HTTP response, and GitHub API confirmation of both linked project repositories. There is no application JavaScript to generate runtime console errors.

Pending: desktop and mobile browser visual review, live console inspection, keyboard walkthrough, and external destination rendering. Browser access to the local preview timed out; native Chrome inspection was blocked by the host Mac's locked screen. Responsive CSS includes 800px and 580px breakpoints, but those layouts have not yet been visually verified. Do not treat the first draft as visually approved for production.

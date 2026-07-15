# Domain-Aware Scaling Laws Uncover Data Synergy — project page

Standalone project page for the paper, built on the
[Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template)
(the Nerfies-derived template used by many ML paper pages). Plain static HTML + Bulma CSS +
MathJax; no build step.

- Paper: https://arxiv.org/abs/2607.11052
- Code: https://github.com/kimiah/DataSynergy

Typeset in Palatino via [TeX Gyre Pagella](https://www.gust.org.pl/projects/e-foundry/tex-gyre)
(a free Palatino revival, bundled in `static/fonts/` so it renders without Palatino installed).

## Structure

- `index.html` — the whole page (Bulma CSS; MathJax from CDN for equations)
- `static/css/index.css` — template styles + Palatino faces, navy accent, TL;DR box
- `static/fonts/` — TeX Gyre Pagella (regular/italic/bold/bold-italic)
- `static/images/` — figures exported from the paper
- `static/pdfs/paper.pdf` — the paper (embedded in an iframe near the bottom)
- `.nojekyll` — tells GitHub Pages to serve the files as-is (no Jekyll)

## Preview locally

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

## Deploy on GitHub Pages

This page is intentionally separate from the code repo and the personal site. Create a new repo,
push, and enable Pages:

```bash
gh repo create datasynergy-page --public --source=. --remote=origin --push
# then: repo → Settings → Pages → Source "Deploy from a branch", branch main, folder / (root)
```

It will be served at `https://kimiah.github.io/datasynergy-page/`. If you deploy under a different
repo name or domain, update the `og:url` meta tag in `index.html` to match.

## License

Template licensed under [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/); keep the
footer attribution link.

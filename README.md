# Domain-Aware Scaling Laws Uncover Data Synergy - project page

Standalone project page for the paper, built on the
[Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template)
(the Nerfies-derived template used by many ML paper pages). Plain static HTML + Bulma CSS;
equations are hand-set in HTML; no build step.

- Live: [https://data-syn.github.io/](https://data-syn.github.io/)
- Paper: [https://arxiv.org/abs/2607.11052](https://arxiv.org/abs/2607.11052)
- Code: [https://github.com/kimiah/DataSynergy](https://github.com/kimiah/DataSynergy)

Typeset in Palatino via [TeX Gyre Pagella](https://www.gust.org.pl/projects/e-foundry/tex-gyre)
(a free Palatino revival, bundled in `static/fonts/` so it renders without Palatino installed).

## Structure

- `index.html` — the whole page (Bulma CSS; equations hand-set in HTML)
- `static/css/index.css` — template styles + Palatino faces, navy accent, TL;DR box
- `static/fonts/` — TeX Gyre Pagella (regular/italic/bold/bold-italic)
- `static/images/` — figures exported from the paper
- `static/pdfs/paper.pdf` — a local copy of the paper (the Paper button links to the arXiv PDF)
- `.nojekyll` — tells GitHub Pages to serve the files as-is (no Jekyll)

## License

Template licensed under [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/); keep the
footer attribution link.
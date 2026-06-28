# The Indian Mutual Fund Masterclass

**Zero to Expert — Investing, the Industry, the 2026 Law & the Problems.**

A study program (India, 2026) on mutual-fund investing, the MF industry, the **SEBI (Mutual Funds) Regulations, 2026**, and the problems faced by investors and fund houses. Built as a static [MkDocs](https://www.mkdocs.org/) + [Material](https://squidfunk.github.io/mkdocs-material/) site for GitHub Pages.

## Repository layout

```
mf-curriculum/
├── mkdocs.yml                 # site config, theme, nav, Mermaid + admonitions
├── README.md
├── requirements.txt          # mkdocs-material
├── .github/workflows/deploy.yml   # auto-build & deploy to GitHub Pages on push to main
└── docs/
    ├── index.md              # landing page (AMB logo at top → docs/assets/amb-logo.png)
    ├── assets/               # static charts/images (PNG) + amb-logo.png
    └── m00..m21 *.md         # one file per module (M0 = market intro)
```

## First-time push to GitHub (new repo, private)

> The site logo is referenced at `docs/assets/amb-logo.png` — drop your AMB PNG there first.

```bash
cd "<path>/mf-curriculum"
rm -rf .git                     # clear any partial repo, start clean
git init && git branch -M main
git add -A
git commit -m "Mutual-fund curriculum (M0–M21)"
# create an EMPTY private repo on github.com (no README/.gitignore), then:
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```

**Private repo + Pages:** GitHub Pages on a **private** repo requires a paid plan (Pro/Team/Enterprise). With that, the included Action auto-deploys on every push; set **Settings → Pages → Source = `gh-pages` branch**. Without a paid plan, either make the repo public or just preview locally with `mkdocs serve`.

## Build & preview locally

Requires Python 3.9+.

```bash
pip install mkdocs-material
cd mf-curriculum
mkdocs serve          # live preview at http://127.0.0.1:8000
```

Mermaid diagrams render via `pymdownx.superfences`; the Material theme ships Mermaid support, so no extra plugin is needed for local preview.

## Deploy to GitHub Pages

1. Create a GitHub repo and push the contents of `mf-curriculum/` to it.
2. Set `site_url` in `mkdocs.yml` to `https://<username>.github.io/<repo>/`.
3. From the repo root, run:

```bash
mkdocs gh-deploy --force
```

This builds the site and pushes it to the `gh-pages` branch. In **Settings → Pages**, confirm the source is the `gh-pages` branch. The site goes live at the `site_url` above.

### Optional: deploy via GitHub Actions

Add `.github/workflows/deploy.yml` with a job that runs `pip install mkdocs-material && mkdocs gh-deploy --force` on push to `main`. (Can be generated on request.)

## Conventions

- **Currency & grounding:** all figures current to mid-2026, sourced to AMFI/SEBI and tagged where they move.
- **Legal anchor:** SEBI (Mutual Funds) Regulations, 2026 (approved 17 Dec 2025, effective 1 Apr 2026). Each module cites the applicable provision; section numbers are used only when verified against the primary text, otherwise tagged `[verify section no.]`.
- **Not advice:** all examples are illustrative and clearly labelled. No specific buy/sell recommendations.

## License

© 2026 Biju K Mathew. This work is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)** — see [`LICENSE`](LICENSE). You may share and adapt the material with attribution, for non-commercial purposes. Educational and illustrative only; not investment, legal, or tax advice.

## Status

Scaffold + Module 2 ecosystem diagram complete. Remaining modules are written and delivered level-by-level after approval.

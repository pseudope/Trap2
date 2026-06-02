# Trap² — Making Models Unmergeable via Scaling-Sensitive Loss Landscape

Project page for **Trap²** (*Training-time Protection via Task-Robust Adversarial Perturbation*),
accepted to **ICML 2026** (Seoul).

**Authors:** Minwoo Jang, Hoyoung Kim, Jabin Koo, Jungseul Ok
(POSTECH Graduate School of AI · National AI Research Lab, Seoul · POSTECH CSE)

Trap² is an architecture-agnostic, training-time protection framework that embeds *unmergeability*
into fine-tuned updates: released weights stay useful standalone, but degrade under the re-scaling
that drives unauthorized model merging — for both adapter-only (LoRA) and full-checkpoint releases.

## Local preview

It's a static site — open `index.html` directly, or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying (GitHub Pages)

Push to the repository and enable GitHub Pages (Settings → Pages → deploy from the `master` branch root).
`.nojekyll` is included so the `static/` assets are served as-is.

## Before publishing — fill in the `TODO`s

Edit `index.html` and replace the placeholders:

- **Links** in the hero buttons: Paper (PMLR/OpenReview), arXiv, OpenReview, and the GitHub **Code** repo.
- **Images** (add your own originals):
  - `static/images/teaser.png` — overview / Figure 1
  - `static/images/method.png` — loss-landscape / Figure 2
  - `static/images/social_preview.png` — 1200×630 social card (optional)
- **`og:url` / `citation_pdf_url`** meta tags once the page is hosted.
- **`static/images/favicon.ico`** — currently the template author's favicon; replace it with your own.

## Notes

- The original manuscript PDF and any LaTeX sources are intentionally **not** part of this repo and
  are kept out of version control locally (`.git/info/exclude`).

## Credits

Built on the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template),
adapted from the [Nerfies](https://nerfies.github.io) page. Licensed under
[CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).

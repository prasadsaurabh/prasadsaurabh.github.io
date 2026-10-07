# prasadsaurabh.github.io

Website of Saurabh Prasad and the Machine Learning and Signal Processing (MLSP) Lab, University of Houston. Built with [Hugo](https://gohugo.io/) and the PaperMod theme, adapted from [hugo-website](https://github.com/pmichaillat/hugo-website). Every push to `main` rebuilds and deploys the site (see `.github/workflows/hugo.yml`).

## Common updates

- **Add a paper:** `hugo new papers/<slug>/index.md`, fill in the front matter, and save the overview figure as `cover.png` in the same folder. Add `featured: false` to give the paper its own page without listing it on the Papers page.
- **Add a news item:** add an entry at the top of `data/news.yaml` (newest first). The homepage shows the first three.
- **Edit pages:** `content/research.md`, `team.md`, `teaching.md`, `join.md`.
- **Homepage bio, menu and icons:** `config.yml`.

## Preview locally

```bash
hugo server
```

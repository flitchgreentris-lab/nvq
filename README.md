# NVQ 2357 evidence tracker — GitHub Pages

Static, offline-friendly (after loading) personal evidence tracker based on the 12 October 2026 Learning Assistant export and City & Guilds 2357 handbook v6.2.

## Publish on GitHub Pages
1. Create a public GitHub repository, for example `nvq-tracker`.
2. Upload the **contents** of this ZIP to the repository root (`index.html`, `app.js`, `style.css`, `data.js`, `criteria.json`).
3. In the repository, choose **Settings → Pages → Build and deployment → Deploy from a branch**, select `main` and `/ (root)`, then Save.
4. The website will be at `https://YOUR-USERNAME.github.io/nvq-tracker/` after GitHub deploys it.

## How progress works
- Initial entry counts are taken from the 12 October 2026 report.
- The `+`/`−` controls update entry counts; a checkbox marks personal completion.
- Assessor review statuses are separate: submitted / accepted / needs rework / signed off.
- Progress is stored in browser `localStorage` — **not** your GitHub account. Changes will not automatically sync between devices; use **Export backup** and **Import backup** in Data & backup.
- GitHub Pages is public if the repository is public. The packaged site contains assessment descriptions and counts, but no personal private evidence photos or certificates. Do not upload sensitive documents without considering privacy.
- Unit 399 / AM2 is excluded from the portfolio tracker.
- Minimum range labels are only handbook-derived guidance; seek assessor confirmation. The site does not judge final mandatory status or award verified competency.

# Portfolio — AI Orchestration & Infrastructure

A static portfolio site for AI orchestration and infrastructure skills, hosted on **GitHub Pages**.

Live site: <https://coualafool.github.io/Portfolio/>

## Pages

| File | Language | Description |
|------|----------|-------------|
| [`index.html`](index.html) | — | Landing page linking the two portfolio pages |
| [`portfolio-skills-interview.html`](portfolio-skills-interview.html) | English | Skills portfolio — AI orchestration & infrastructure |
| [`portfolio-competences-entretien.html`](portfolio-competences-entretien.html) | Français | Portfolio de compétences — orchestration IA & infrastructures |

## Run locally

No build step — it's plain static HTML. Open any file directly in a browser, or serve it:

```bash
# Python
python -m http.server 8000
# then open http://localhost:8000
```

## Deploy

GitHub Pages is configured to publish from the `main` branch, root folder (`/`). Pushing to `main` auto-deploys:

```bash
git add -A
git commit -m "Update portfolio"
git push
```

The site is served at `https://coualafool.github.io/Portfolio/` (HTTPS enforced).

## License

© Coualafool. All rights reserved.

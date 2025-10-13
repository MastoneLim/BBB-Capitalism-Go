# Modpack Wiki (MkDocs + Material)

## Local Preview
```bash
pip install mkdocs-material
mkdocs serve
```
Open http://127.0.0.1:8000

## Deploy to GitHub Pages
1. Create a repo and push these files to the root.
2. Enable GitHub Pages (Settings → Pages → 'Deploy from a branch' not needed if using workflow).
3. Push to `main`. This workflow deploys automatically.

## GitHub Actions Workflow
The repo includes `.github/workflows/deploy.yml`. It builds and publishes the site.

## Cloudflare Pages (alternative)
- Build command: `pip install mkdocs-material && mkdocs build`
- Output directory: `site`


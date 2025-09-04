# Business News Data & Graphics Style Guide (MkDocs + Material)

This repository powers a public website with standards for tables, charts, maps and number formatting for Business News. It uses **MkDocs** with the **Material** theme and deploys to **GitHub Pages** via Actions.

## Local setup

```bash
# 1) Create and activate a virtual environment (optional but recommended)
python3 -m venv .venv && source .venv/bin/activate

# 2) Install dependencies
pip install mkdocs-material

# 3) Run the site locally
mkdocs serve  # then open http://127.0.0.1:8000

# 4) Build site
mkdocs build
```

## Deploying to GitHub Pages
1. Push this repo to GitHub (public or private with Pages enabled).
2. In GitHub → Settings → Pages, set the source to **GitHub Actions**.
3. The provided workflow `.github/workflows/gh-pages.yml` will build and publish to the `gh-pages` branch on every push to `main`.

## Custom domain (optional)
- Add your domain in GitHub Pages settings and create a CNAME record pointing to `<username>.github.io`.
- MkDocs will automatically include a `CNAME` during deploy based on your `site_url` if you add a `docs/CNAME` file.

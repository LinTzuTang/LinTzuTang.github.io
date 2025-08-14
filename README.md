
# Tzu-Tang Lin — Personal Website (Hugo Profile)

This is a Hugo site using the **Hugo Profile** theme. Content is prefilled from my CV/README.

## Quick Start

```bash
# 1) Clone
git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME.github.io
cd YOUR_GITHUB_USERNAME.github.io

# 2) Copy this folder's contents in (or unzip the release here)

# 3) Commit
git add .
git commit -m "Init Hugo Profile site"
git push origin main
```

### GitHub Pages with GitHub Actions

1. Go to **Settings → Pages** and set **Source** to **GitHub Actions**.
2. On push to `main`, the provided workflow builds the site with Hugo and deploys to Pages.

> The workflow adds the theme as a git submodule automatically (`themes/hugo-profile`).

## Local Preview

```bash
brew install hugo  # or see https://gohugo.io/getting-started/installing/
hugo server -D
```

---

© {year} Tzu-Tang Lin

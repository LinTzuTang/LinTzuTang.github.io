
# Tzu‑Tang Lin — Hugo Site

This is a Hugo site using the **hugo-profile** theme. It’s pre-filled with About, Projects, and Publications pages. Your CV and Resume (docx) are downloadable from the homepage buttons.

## Quick start

```bash
# 1) Install Hugo (extended)
# macOS (brew): brew install hugo
# Ubuntu: sudo snap install hugo --channel=extended

# 2) Get the theme
git submodule add https://github.com/gurusabarish/hugo-profile themes/hugo-profile

# 3) Run locally
hugo server -D

# 4) Build
hugo --minify
```

## GitHub Pages

- For user pages, the repo should be **LinTzuTang/LinTzuTang.github.io**.
- Build to `public/` and push that to the **`main`** branch (for user pages), or use GH Actions to build from source.

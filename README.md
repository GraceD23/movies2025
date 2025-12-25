# Movie Reviews (GitHub Pages + Jekyll)

## 1) Header image
Upload your header artwork to:

- `assets/img/header-movies.png`

PNG is recommended. If your artwork is currently a PDF, export it to PNG before uploading.

Header background: `#eeece0`  
Site background: `#350a0d`

## 2) Add a review
1. Upload a poster to `assets/posters/`
2. Add a new markdown file to `_reviews/` (copy `_reviews/sample.md`)

Example:

```md
---
title: "Hot Frosty"
rating: 3
poster: /assets/posters/hot-frosty.jpg
date: 2025-12-25
---

Your short review text.
```

### How stars work
Set `rating:` to an integer 1–5:
- `rating: 3` renders ★★★☆☆

## 3) Publish on GitHub Pages
Repo → Settings → Pages
- Source: Deploy from a branch
- Branch: main
- Folder: /(root)
Save.

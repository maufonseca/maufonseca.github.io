# maubfon.github.io

Personal CV site — built with plain HTML/CSS, deployed via GitHub Pages.

## Deploy

1. Create a repo on GitHub named exactly `<your-username>.github.io`
2. Push this folder to `main`:
   ```bash
   git remote add origin https://github.com/<username>/<username>.github.io.git
   git add .
   git commit -m "init: personal cv site"
   git push -u origin main
   ```
3. Go to repo **Settings → Pages → Source: Deploy from branch → main / root**
4. Site goes live at `https://<username>.github.io` within a minute

## Structure

```
index.html   ← all content
style.css    ← all styles
```

No build tools. No dependencies. Just push and it works.

## Updating content

Edit `index.html` directly. The source of truth for raw data lives in `~/Documents/Curriculum/data/`.

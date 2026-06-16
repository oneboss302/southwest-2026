# Above It All · June 2026

A static aerial photography gallery built for GitHub Pages.

## Structure

```
/
├── index.html          ← single-page gallery
├── photos/
│   ├── full/           ← full-resolution images (for lightbox)
│   └── thumb/          ← 600px thumbnails (for grid)
└── README.md
```

## Publishing to GitHub Pages

1. Create a new repository on GitHub
2. Push this folder to the `main` branch
3. Go to **Settings → Pages**
4. Set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`
5. Save — your site will be live at `https://<username>.github.io/<repo-name>`

## Features

- Masonry photo grid organized by day
- Sticky day navigation with scroll-spy
- Full-screen lightbox with keyboard navigation (←/→/Esc) and swipe support
- Lazy-loaded thumbnails for fast page load
- Mobile responsive

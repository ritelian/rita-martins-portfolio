# Rita Martins — ISMAT Portfolio V0.3

Static GitHub Pages-ready portfolio.

## What changed in V0.3
- Native local MP4 hero video (no YouTube iframe dependency)
- 24s web-optimised videomapping montage (~3 MB)
- Full-screen sticky hero with scroll-driven parallax/scale
- Sticky interactive 3D Meshy/GLB case study
- Native short process videos from the videomapping documentation
- Responsive mobile layout and reduced-motion support
- Inline CSS/JS in `index.html`, so the preview does not break when CSS files are not loaded separately

## Publish on GitHub Pages
1. Create a public GitHub repository, e.g. `rita-martins-portfolio`.
2. Upload the contents of this folder (not the outer ZIP) to the repository root.
3. In GitHub: Settings → Pages → Build and deployment → Deploy from a branch.
4. Select `main` and `/ (root)` and save.
5. GitHub will show the live Pages URL after deployment.

The interactive 3D viewer uses the pinned `@google/model-viewer` 4.3.1 web component from `unpkg.com`; the GLB itself is local in `assets/`.

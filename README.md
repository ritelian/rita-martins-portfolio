# Rita Martins — Portfolio

Static GitHub Pages-ready portfolio.

## September 2026 portfolio update
- Eight case studies, including VOID, MOD 9966, AI-assisted learning redesign and a generative video study.
- Two actual interactive GLB models and links to four existing public web projects.
- Original MOD 9966 activity preview and supplied Runway video excerpt.
- Learning work described at a general level; no internal workshop files, source code, screenshots, client prompts or confidential production metrics are included.
- Published through the existing GitHub Pages configuration: `main`, repository root.

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

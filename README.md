# paint

Historic Automotive Greens — visualizing single-stage solid proxy candidates for the iconic 1968 Ford Highland Green (M3067).

Live: https://paint.jkre.is

## Stack

- React 18 + Vite (precompiled, no runtime JSX compilation)
- Tailwind CSS 3 (compiled at build time, no CDN dependency)
- Deployed via GitHub Pages with a CNAME to `paint.jkre.is`

## Local development

Source lives in a separate Vite project. To regenerate the production bundle from sources:

```bash
npm install
npm run build
# copy dist/* into this repo root, keep CNAME and .nojekyll
```

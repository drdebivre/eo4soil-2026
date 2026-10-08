# Poster landing page – EO4Soil 2026

Landing page for the poster *A transparent rule-based algorithm for tillage detection from Sentinel-1 time series*. The poster's QR code links here.

## Files
- `index.html`: the page. Placeholders are marked with `<!-- EDIT -->` comments.
- `poster.pdf`: the poster. Replace it with the final version, keeping the same name.
- `poster-preview.jpg`: the preview image shown on the page (about 1000 px wide).
- `contact.vcf`: the "Save contact" card.

To regenerate the preview from the final PDF:
`pdftoppm -jpeg -r 30 -singlefile poster.pdf poster-preview`

## Publish on GitHub Pages
1. Create a public repository, for example `eo4soil-2026-poster`.
2. Upload these files to the root of the `main` branch.
3. Go to Settings → Pages → Build and deployment, set Source to "Deploy from a branch", and choose `main` and `/ (root)`.
4. The page will be at `https://<username>.github.io/eo4soil-2026-poster/`. Keep that address the same after printing.

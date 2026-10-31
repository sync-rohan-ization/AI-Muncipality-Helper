# InnoVision — Pune waste inspection dashboard

Interactive map-first prototype with four illustrative reports. Each marker opens its own reference image and concept bounding boxes. Includes manual report creation, status changes, search, CSV export and browser-local persistence.

## Publish with GitHub Pages
1. Extract this ZIP.
2. Upload index.html, the assets folder, and .nojekyll to the root of a GitHub repository. Keep the assets folder structure intact.
3. In repository Settings > Pages, choose Deploy from a branch, main, / (root), then Save.
4. Wait for GitHub Pages deployment and use the resulting website URL in your application.

No build step, API key or npm installation is required. An internet connection is required for Leaflet and map tiles. You can also open index.html locally.

## Current scope
This is a browser-local demonstrator. It does not connect to a drone, run an AI model, notify municipal crews or share records between users. Sample GPS coordinates and statuses are illustrative. Reference photos were not captured at the Pune map markers. Bounding boxes are concept annotations, not model predictions.

## Image credits
- assets/site-1.jpg: Markus Spiske / Pexels — https://www.pexels.com/photo/a-pile-of-garbage-bags-4651148/
- assets/site-2.jpg: Aiden Tieulie / Pexels — https://www.pexels.com/photo/urban-construction-zone-with-caution-tape-and-cone-32537514/
- assets/site-3.jpg: Mike Bird / Pexels — https://www.pexels.com/photo/a-pile-of-trash-in-an-urban-area-6316243/
- assets/site-4.jpg: Robert So / Pexels — https://www.pexels.com/photo/pile-of-trash-with-discarded-mattress-outdoors-29348622/
Photos are provided under the Pexels License: https://www.pexels.com/license/

## Map
Leaflet 1.9.4 loads from unpkg. Esri light grey canvas map tiles and reference labels load from ArcGIS Online. Attribution is displayed in the map. Third-party imagery and software retain their original rights and terms.

## Slide image
The accompanying dashboard screenshot shows the working UI with reference photography and illustrative boxes. It is not a field trial result.

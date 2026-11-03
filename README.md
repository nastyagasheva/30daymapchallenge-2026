# 30DayMapChallenge 2026 — NG Cartography

A public cartographic notebook, published with GitHub Pages.

## Day 01 · Points

**Primorye — Settlements & Terrain.** 657 settlements in Primorsky Krai, shown
against a digital hachure drawing of the terrain. Symbol sizes use population
figures for **2020**, from the CPUR release dated 12 March 2021.

The map is an exploration of settlement patterns and landforms, not a causal model.
Twelve zero values are retained and do not establish abandonment.

The page provides a web preview, the full-resolution PNG, and an editable SVG.
The workflow uses Python and AI-assisted scripting, with iterative cartographic
review and refinement.

## Sources and licence

- Settlements: [CPUR / INID dataset record](https://data.rcsi.science/data-catalog/datasets/160/), CC BY-NC-SA 4.0.
- Terrain: [Mapzen Terrain Tiles](https://registry.opendata.aws/terrain-tiles/), SRTM/GMTED2010 courtesy USGS; ETOPO1 courtesy NOAA. [Attribution](https://github.com/tilezen/joerd/blob/master/docs/attribution.md).
- Coast and hydrography: [Natural Earth](https://www.naturalearthdata.com/), public domain.
- Boundary: [© OpenStreetMap contributors](https://www.openstreetmap.org/copyright), ODbL.

See [LICENSE.md](LICENSE.md). IBM Plex font data embedded in the SVG retain their
SIL Open Font License, included in the SVG metadata.

## Site structure

This is a buildless static site: `index.html`, `styles.css`, and `assets/`.
GitHub Pages publishes the `main` branch from the repository root. `.nojekyll`
keeps the files as a plain static website. No package installation is required.

Add future challenge days as new map entries and keep their credits, dates,
licences, and image descriptions with the published work.

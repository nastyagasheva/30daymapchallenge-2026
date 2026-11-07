# 30DayMapChallenge 2026 — NG Cartography

## Day 04 · Clusters

**Where typhoons go / Two route families, one Pacific.** One common map of 320
western Pacific cyclone life histories from 2000–2024: 112 westward, 190 turning
north, and 18 borderline assignments. Measured passage fields summarise each
family; two real medoids and all18 borderline routes remain individual lines.
Dashed segments distinguish extratropical continuations. Fields and proximity
are not hazard or forecast probabilities. Data: NOAA IBTrACS v04r01, WP, accessed
6 November 2026; dataset DOI10.25921/82ty-9e16, Knapp et al.(2010),
DOI10.1175/2009BAMS2755.1; Natural Earth; OpenStreetMap contributors / ODbL.
English PNG3780×4830, editable SVG and web preview; full method, regional
counts, limitations and credits accompany the map on the gallery page.

## Day 03 · Polygons

**Vladivostok / Between hills & bays.** Generalised building patterns across
the peninsula and islands, with flat surface-elevation bands and three
equal-scale details: central Vladivostok, Vtoraya Rechka and Patrokl Bay.
Overture 2026-10-21.0 / OpenStreetMap / Microsoft ML Buildings; OSM coastline
snapshot 2026-10-25; Copernicus GLO-30 release 2021. PNG, editable SVG and
derived fabric GeoJSON (ODbL) are linked from the gallery. Study window is
not the complete administrative city boundary; generalisation is not a
measurement of building area. Full method and attribution accompany the map.

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

## Day 02 · Lines

**Bikin / Hydrographic herbarium.** HydroRIVERS network and 88 State Water
Register tributary records: 51 left-bank, 37 right-bank, 16 unnamed. Distances
follow the register; branch lengths are schematic. HydroRIVERS source grid:
15 arc-seconds, junction-preserving smoothing. Lehner & Grill (2013),
doi:10.1002/hyp.9740. Five name links through OpenStreetMap, 25 October 2026.
Sources, method and limitations accompany the gallery map. English PNG and
editable SVG, 3360 × 3990 pixels.

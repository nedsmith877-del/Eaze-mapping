# Eaze Mapping

A browser app for mapping properties in Queensland and New South Wales from their lot/plan numbers. It uses the LAWD colour palette.

## Features
- Look up lots on the live QLD DCDB and NSW Spatial Services cadastre (e.g. `3RP123456`, `Lot 3 on SP123456`, `1/DP123456`, `1/2/DP7890`), and group several lots into one property.
- Colour properties by category, using the LAWD palette: Subject, Quote, Sale and For Sale.
- See land area in hectares, acres and km², both measured from the boundary and as the title area.
- Switch on vegetation and land layers:
  - QLD: regulated vegetation, regional ecosystems, essential habitat, wetlands, watercourses, PMAV, strategic cropping land and land types.
  - NSW: State Vegetation Type Map and land and soil capability.
- Click the map to see what each layer shows at that point, or run a per-property report of what lies inside the boundary.
- Export properties for Google Earth (KML), GIS (GeoJSON), as an area table (CSV), or as a JSON backup. Properties save in your browser automatically.

## Running it
Open `index.html` in a browser, or publish it with GitHub Pages (Settings → Pages → Deploy from branch `main`, root folder). No build step is needed.

Information comes from public government map services. It is indicative only, so check official sources before relying on it.

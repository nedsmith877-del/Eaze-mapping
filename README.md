# Easy Mapping

A browser app for mapping properties in Queensland and New South Wales from their lot/plan numbers.

## Features
- One "Find titles" box: type a single title, a list, or paste rows (name, lot/plan, type) from Excel.
- Look up lots on the live QLD DCDB and NSW Spatial Services cadastre (e.g. `3RP123456`, `Lot 3 on SP123456`, `1/DP123456`, `1/2/DP7890`), and group several lots into one property.
- Colour properties by category, Subject, Quote, Sale and For Sale.
- See land area in hectares, acres and km², both measured from the boundary and as the title area.
- Switch on vegetation and land layers:
  - QLD: regulated vegetation, regional ecosystems, essential habitat, wetlands, watercourses, PMAV, strategic cropping land, land types, land use (QLUMP), the floodplain assessment overlay and historic flood lines.
  - NSW: State Vegetation Type Map, land and soil capability, land use (2017) and council flood planning areas.
- Click the map to see what each layer shows at that point, or run a per-property report of what lies inside the boundary.
- Build a sales map: add sale price and date to properties, pick a subject, and get numbered labels with price, $/ha and distance, plus a table. Print it or save it as PDF.
- Switch base maps (QLD Globe and NSW imagery, plus free Google-style hybrid, street and terrain views). Click the map for Google Street View, Google Maps and Google Earth links.
- Export properties for Google Earth (KML), GIS (GeoJSON), as an area table (CSV), or as a JSON backup. Properties save in your browser automatically.
- 4:3 map snapshot: frame the map, then save a PNG (1024, 1600 or 2400 wide) or copy it to paste into Word/Outlook.

## Running it
Open `index.html` in a browser, or publish it with GitHub Pages (Settings → Pages → Deploy from branch `main`, root folder). No build step is needed.

Information comes from public government map services. It is indicative only, so check official sources before relying on it.

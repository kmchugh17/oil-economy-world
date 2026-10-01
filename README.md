# Global Oil Atlas

Interactive world map of oil supply, refining, demand, inventories and maritime flows.

## Run

Open `index.html` in a modern browser, or serve this directory with any static web server. No build step, backend, API key or package installation is required. D3 and TopoJSON load from public CDNs, so an internet connection is needed.

## Explore

- Dated implications: supply offsets, closures, constraints and shadow-shipping evidence.
- Oil on water: in-transit and floating-storage estimates, onshore comparisons and voyage-delay scenarios.
- Eight chokepoints: six quarterly comparisons, including crude and product breakdowns.
- National balances: 113 reporting economies, 13 product categories and historical comparisons.
- Historical ranges: compare eligible observations with prior years.

## Data and limitations

Evidence snapshot: 30 September 2026. National monthly data extend through July 2026; annual comparisons cover 2015–2025. Individual maritime observations have their own dates. Sources, definitions and calculation rules are linked inside the atlas.

This is not a live vessel-tracking feed, a complete global mass balance, or an automatically refreshed dataset. Missing observations are not treated as zero. Measurements, derived values, scenarios and interpretations are distinguished in the interface.

## Hosting

Publish this directory with a static hosting service. The entry point is `index.html`; no build command is required. Uploading this repository alone does not enable website hosting.

## Structure

`index.html` contains the standalone atlas, embedded compressed datasets and its interface. `.nojekyll` allows plain static serving on GitHub Pages. The file retains its sandboxed visualization frame.

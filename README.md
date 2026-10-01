# Oil Atlas — operating research workspace

A static global oil research website connecting offshore developments to listed-company ownership, operators and contractors. Open `index.html` through a local HTTP server or static host.

## Features

- Interactive world map, zoom, layer switching and asset inspection.
- Nine curated offshore developments and thirteen listed companies, with exchange and ticker labels.
- Separate ownership and contractor relationships, project-specific units and dated evidence.
- Near-term catalysts, long-term exposure and thesis risks, explicitly framed as research hypotheses.
- Offshore system explorer: reservoir, wells, subsea, facility, exports and economics.
- Browser-local three-company shortlist, comparison, diligence notes and JSON export.
- Twenty-one dated market signals, eight chokepoints with six quarterly comparisons, and oil-on-water observations.
- Original detailed national balance and historical research application preserved at `ledger.html`.

## Files and operation

`index.html`, `app.css`, `app.js`, `research.json`, `context.json`, `world.json`, `ledger.html` and `.nojekyll` deploy directly at the site root. No build step, API key or backend is required. D3, topojson-client and web fonts load from public CDNs; map and research data are local static files. Serve over HTTP(S), not a `file://` URL, because the application fetches JSON.

For GitHub Pages, use Settings → Pages → Deploy from a branch → main → / (root). Other static hosts can serve the same files.

## Data limitations

Research assembled 1 October 2026. This is a sourced snapshot, not an automatically updated news, AIS, pricing, company-filing or fundamental-data service. Coverage is curated, not an exhaustive asset register. Facts have individual observation dates and source links.

Capacity, actual production, estimated peak output, oil-equivalent gas and LNG tonnage are not interchangeable and must not be summed. Working interest is not net production-sharing entitlement. Contractor awards do not establish remaining backlog. Offshore coordinates are field or regional references, not platform or vessel tracking. Geography uses Natural Earth via world-atlas.

No stock ranking, valuation model, market prices or buy recommendation is supplied. Research hypotheses need current financial and valuation work. Saved notes live only in the browser unless exported.

## Validation

Desktop and mobile browser checks cover asset/company selection, ticker search, shortlist persistence, comparison notes, quarterly changes, layer switching, offshore stages, ledger access and mobile overflow. Static JavaScript syntax was checked with Node.

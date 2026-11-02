# UDOT Natural Hazards Explorer

- Old URL(s):
  - https://products.highstreet.work/exb_udot_rip_apps/hazardexplorer/
  - https://products.highstreet.work/exb_udot_rip_apps/NaturalHazardsExplorer/
- New URL: https://high-street-consulting.github.io/udot-natural-hazards-explorer/
- Migrated: 2026-11-02
- Source: IIS wwwroot folder `wwwroot\exb_udot_rip_apps\hazardexplorer`
- Framework: ArcGIS Experience Builder 1.16, build 19

## Changes from original

- `web.config` dropped (IIS-only MIME/cache/rewrite rules; GitHub Pages does not use it)
- `*.map` source maps dropped (0 files)
- empty `.nojekyll` added (skip the Jekyll build on GitHub Pages)

No application code was changed.

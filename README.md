# Die per Wafer Calculator

Counts how many complete rectangular dies fit on a wafer and finds the grid placement that fits the most.

**Live page:** [photonzq.github.io/Die_per_Wafer_Calculator](https://photonzq.github.io/Die_per_Wafer_Calculator/)

- Wafer diameter, edge exclusion, die size and scribe street width
- SEMI M1 major and minor flats (presets for 2″, 3″, 100, 125 and 150 mm), with the edge exclusion applied along the flats
- Exact optimal grid offset rather than a sampled search; the reasoning is in the comments of `index.html`
- Optional staggered layout for plasma dicing: each row (or column) is placed on its own, which usually fits a few per cent more dies
- Wafer map with die coordinates on hover, PNG export, and CSV export of die positions

Everything is in one self-contained `index.html` with no dependencies or build step, so it also works when opened locally.

Default model: one regular grid with straight X and Y dicing streets across the whole wafer, as cut by a dicing saw.

Released into the public domain under [CC0 1.0](LICENSE).

# Material Calculator

A free, browser-based material estimation tool for architects, interior designers, and contractors.

## Features

- **Ceramic & porcelain tiles:** enter room dimensions, tile sizes, pieces per box and waste allowance; get the estimated number of tiles and whole boxes to purchase.
- **SPC flooring:** enter room dimensions, plank dimensions, pieces per box and waste allowance.
- **Wall paint:** estimate paint volume using wall area, deductions for openings, coats, coverage and waste.
- Responsive UI; works without accounts, dependencies or a backend.

## Live demo

https://chenmichaels-prog.github.io/Material-Calculator/

> The demo link becomes available after enabling GitHub Pages (Settings → Pages → Deploy from a branch → main → /root).

## Usage

Open `index.html` in your browser or use the GitHub Pages link after deployment. All calculations run locally.

## Calculation assumptions

- Tiles/planks: required units = ceil((net area × (1 + waste %)) / unit area); whole boxes = ceil(required units / pieces per box).
- Paint: liters = (max(0, wall area − openings) × (1 + waste %) × coats) / manufacturer coverage.
- Dimensions assume rectangular surfaces. Tile/plank estimation does not optimize actual cutting layout; paint quantities do not include substrate-specific losses or retail pack rounding.

## Support development

If this project helps you, consider supporting its continued maintenance via [GitHub Sponsors](https://github.com/sponsors/Chenmichaels-prog). Sponsorship availability depends on GitHub approval.

## License

MIT License. See [LICENSE](LICENSE).

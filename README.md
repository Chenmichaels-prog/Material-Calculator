# Material Calculator

A free, browser-based material estimation tool for architects, interior designers, and contractors.

## Features

- **Ceramic & porcelain tiles:** enter room dimensions, tile sizes, pieces per box and waste allowance; get the estimated number of tiles and whole boxes to purchase.
- **SPC flooring:** enter room dimensions, plank dimensions, pieces per box and waste allowance.
- **Wall paint:** estimate paint volume using wall area, deductions for openings, coats, coverage and waste.
- Responsive UI; works without accounts, dependencies or a backend.

## Live demo

https://chenmichaels-prog.github.io/Material-Calculator/

## Usage

Open `index.html` in your browser or use the GitHub Pages link after deployment. All calculations run locally.

## Calculation assumptions

- Tiles/planks: required units = ceil((net area × (1 + waste %)) / unit area); whole boxes = ceil(required units / pieces per box).
- Paint: liters = (max(0, wall area − openings) × (1 + waste %) × coats) / manufacturer coverage.
- Dimensions assume rectangular surfaces. Tile/plank estimation does not optimize actual cutting layout; paint quantities do not include substrate-specific losses or retail pack rounding.

## Support development

This tool is free and open-source. If it helps with your project estimates, you can support future maintenance, documentation, fixes, and new calculators through [GitHub Sponsors](https://github.com/sponsors/Chenmichaels-prog) (once the sponsorship profile is approved and active).

Suggested monthly supporter levels:

| Level | Monthly | What your support helps fund |
| --- | ---: | --- |
| Community Supporter | $3 | Routine maintenance, bug fixes and documentation |
| Development Backer | $10 | New calculation features and improvements |
| Project Champion | $25 | Continued independent development and testing |

All tiers are voluntary contributions; the calculator remains free. These are **suggested tier descriptions**, not a claim that tiers have already been published on GitHub.

### Share feedback

Found an error or have a material type you'd like supported? [Open a GitHub issue](https://github.com/Chenmichaels-prog/Material-Calculator/issues).

## License

MIT License. See [LICENSE](LICENSE).

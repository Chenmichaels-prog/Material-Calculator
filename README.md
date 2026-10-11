# Material Calculator V2.0

A free, responsive, client-side material quantity and purchasing cost calculator for architects, interior designers, contractors and students.

**[Launch the live calculator](https://chenmichaels-prog.github.io/Material-Calculator/)** · [Support via GitHub Sponsors](https://github.com/sponsors/Chenmichaels-prog)

## Supported calculators

| Material | Calculation | Purchase unit |
| --- | --- | --- |
| Ceramic / porcelain tiles | Area, waste, tiles, packaging | Boxes |
| SPC flooring | Area, waste, planks, packaging | Boxes |
| Wall paint | Surface, openings, coverage, coats | Cans |
| Gypsum board | Area, openings, sheet size | Sheets |
| Ceiling panels | Area, panel size, packaging | Boxes |
| Wallpaper | Wall height, full-height strips and roll length | Rolls |
| AAC / lightweight blocks | Wall area, nominal block dimensions, packing | Bundles / blocks |

## Cost estimate and PDF

Supply your **price per purchasing unit** in Indonesian rupiah (IDR). The calculator first rounds up to whole purchasing units, then multiplies by the unit price. Enter `0` if no price is available.

Use **Print / Save as PDF** to open your browser's print dialog; choose `Save as PDF` as the printer. This does not depend on a remote API.

## How to use

1. Choose the material.
2. Enter dimensions and manufacturer pack coverage or product unit sizes.
3. Set the expected waste percentage and supplier price per unit.
4. Read the quantity estimate and rounded purchase cost.
5. Print or save a PDF estimate if needed.

The app is a standalone HTML file and needs no installation or database. Open `index.html` locally or use GitHub Pages.

## Important estimation assumptions

- **Area:** dimensions are rectangular and measured in meters unless specified otherwise.
- **Waste:** applied to net area *before* calculating purchasing units.
- **Boxes / bundles:** always rounded **up** to the next whole unit.
- **Wall paint:** volume = net area × (1 + waste %) × coats / coverage per coat. Cans round up based on entered can capacity.
- **Wallpaper:** estimated using complete strips at the entered wall height; deducted openings are converted to equivalent run length. Pattern repeats, wall segments, seams and unusable offcuts may require more rolls.
- **AAC:** uses nominal block face dimensions, ignoring mortar joints, cuts and reinforcement. Thickness is displayed for identification, not structural design.
- **Gypsum and ceiling panels:** count panels only, not framing, hangers, fasteners, compound or accessories.
- **Costs:** material purchase cost only; excludes labor, freight, permits and taxes unless included in the entered supplier price.
- This tool is for **preliminary estimates**, not a detailed quantity survey or purchase order. Verify against drawings, site measurements and manufacturer's datasheets.

## Support open-source development

If the tool helps your work, consider [sponsoring development](https://github.com/sponsors/Chenmichaels-prog). Sponsorship depends on the creator's GitHub Sponsors account being approved and active.

Suggested monthly support levels are $3 (Community Supporter), $10 (Development Backer) and $25 (Project Champion). These are suggestions, not a statement that tiers have been published.

## License

MIT — see [LICENSE](LICENSE).

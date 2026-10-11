# Material Calculator roadmap

Status: planning document; targets are not shipped features.

## Current baseline — V2.1
- Seven material estimators in a single client-side HTML application
- English and Indonesian UI, local language preference
- Purchasing-unit rounding, editable IDR price, browser Print / Save as PDF

## P0 — Accuracy and quality
- [ ] Fix English purchase-unit grammar and standardize release labels
- [ ] Add automated regression tests for quantities, validation and language switching
- [ ] Review paint, wallpaper, AAC, panels and tile formulas against worked examples
- [ ] Improve printable report metadata and clear labeling of assumptions

## P1 — User experience
- [ ] Keyboard and mobile accessibility audit (focus, labels, tab selection)
- [ ] Save / restore estimates locally with explicit reset controls
- [ ] Improve contextual material-specific guidance and empty states

## P2 — Additional capabilities
- [ ] Optional alternate currencies and price presentation (no assumed exchange rate)
- [ ] Multiple rooms/materials in a combined project estimate
- [ ] More precise layout-sensitive waste estimates, clearly separated from area-based estimates

## Release gates
A release requires documented changes, manual smoke testing of all seven calculators, invalid-input tests, language check, and PDF print inspection. No release should be advertised as verified before these checks are completed.

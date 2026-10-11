# Estimation guide / Panduan estimasi

## Scope / Cakupan
This calculator estimates **material purchasing quantities**, not construction specifications, labor, framing, structural safety or procurement authorization.

Kalkulator ini memperkirakan **jumlah pembelian material**, bukan spesifikasi konstruksi, upah, rangka, keamanan struktur, maupun persetujuan pembelian.

## Basic example / Contoh sederhana
A 5 m × 4 m floor has 20 m² gross area. With 10% waste allowance the required coverage is **22 m²**. For tiles sized 80 × 80 cm, each tile covers 0.64 m², so `ceil(22 / 0.64) = 35 tiles`. At 3 tiles per box, `ceil(35 / 3) = 12 boxes`. A supplier price of IDR 150,000 per box gives **IDR 1,800,000** before other costs.

Lantai 5 m × 4 m memiliki luas 20 m². Dengan cadangan 10%, kebutuhan cakupan menjadi **22 m²**. Keramik 80 × 80 cm memiliki luas 0,64 m² per keping: `ceil(22 / 0.64) = 35 keping`. Jika 3 keping/dus, diperlukan **12 dus**. Harga Rp150.000/dus menghasilkan **Rp1.800.000**, belum termasuk biaya lain.

## Material caveats / Batasan material
- **Tiles / Keramik:** ignores cutting patterns, grout width, diagonal layouts, tile shade batches and breakage beyond user-defined allowance.
- **SPC:** ignores layout direction, staggered joints, expansion gaps and usable offcuts.
- **Paint / Cat:** assumes user-entered manufacturer coverage per coat; substrate porosity and surface preparation may change actual consumption.
- **Gypsum / Gipsum:** boards only; framing, screws, joint compound, supports and cut efficiency excluded.
- **Ceiling / Plafon:** panels only, not suspension systems or perimeter trim.
- **Wallpaper:** roll yield assumes full-height strips without motif repeat; openings are modeled as equivalent wall run, which may not reflect usable cuts.
- **AAC / Bata ringan:** counts nominal block face area; excludes mortar joints, tie columns, structural design and breakage beyond chosen allowance.

## Buying and verification / Verifikasi sebelum membeli
Check on-site measurements and working drawings; confirm products, pack quantities and pricing with suppliers. Always separately budget accessories, labor, delivery, tax and contingencies.

# Product Lines

## Ellison Fluid Pant (flagship)

The brand's core, highest-volume product. Sold in multiple colorways.

**Pricing (live Aug 2026):** Sale $69.99 | Regular $124.99
**Product page:** https://ellisonandfitz.com/products/ellison-fluid-pant

**Product images by colorway:**
- Dark Grey: https://ellisonandfitz.com/cdn/shop/files/file_000000002fe4720e8333dae63c278251.png
- Light Grey: https://ellisonandfitz.com/cdn/shop/files/file_000000006a68720e99ec6af147afd958.png
- White: https://ellisonandfitz.com/cdn/shop/files/file_00000000dbfc720eaa07225e25089d76.png
- Black: https://ellisonandfitz.com/cdn/shop/files/file_000000001d34720eab26d91891e99236.png
- Mixed Color: https://ellisonandfitz.com/cdn/shop/files/Screenshot_2026-05-19_at_1.09.49_PM.png
- Royal Blue: https://ellisonandfitz.com/cdn/shop/files/Screenshot_2026-05-19_at_1.02.27_PM.png
- Fluorescent Green: https://ellisonandfitz.com/cdn/shop/files/Screenshot_2026-05-19_at_1.14.21_PM.png
- Violet Blue: https://ellisonandfitz.com/cdn/shop/files/Screenshot_2026-05-19_at_1.15.43_PM.png

**Top sellers by order volume (historical):**
| Colorway | Approx. orders |
|---|---|
| Mixed Color | ~3,537 |
| Violet Blue | ~1,798 |
| Royal Blue | ~1,541 |
| Fluorescent Green | ~856 |

**Newer colorways** (Light Grey, Black, Dark Grey, White) run at roughly
6–15% of Mixed Color's monthly volume (Mixed Color moves ~90/mo), which is
why committing to a high per-color MOQ for these is risky at current
velocity — see `05_roadmap/open_strategic_questions.md` for the
Wiio → Beehive drop-ship decision this feeds into.

**Fluid Pant return policy (Redo):** requires the branded poly bag and
thank-you card to qualify; all other products are graded on condition only.

## Denver Knit Pullover

In development / supplier-transition. Sample specs confirmed with supplier
contact Apollo; a replication brief for Cherry (primary fulfillment
supplier) is in progress so production can move off the original sample
source.

## Caden Knit / other Fluid Pant SKUs

Currently working through a fulfillment issue: 85 units ordered from
"Supplier A" are part of an active fulfillment crisis — see
`05_roadmap/open_strategic_questions.md`.

## Tapstitch collection

A 26-product collection built directly in Shopify
(`gid://shopify/Collection/516299784479`).

## Product page / theme notes

- A custom product page template (`product.aug11.json`) was built for the
  Ellison Fluid Pant, replicating Sigmas/Aug11 UI patterns.
- **Critical rule:** never push to `templates/product.aug11.json` unless
  Kevin explicitly provides the exact content to change. Always pull the
  current file state first before editing.
- Homepage redesign sections were built and pushed to the "CODE TESTING"
  draft theme (`gid://shopify/OnlineStoreTheme/181237678367`).

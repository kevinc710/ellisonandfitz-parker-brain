# E&F Product Creative Strategy Index

## CRITICAL ISOLATION RULE

Every product at Ellison & Fitz has its own creative strategy. **These strategies are completely independent and must never be mixed.**

- The hook framework for one product does NOT apply to another product.
- The editing rules for one product do NOT apply to another product.
- The footage library for one product does NOT apply to another product.
- The GOLD clip scores for one product do NOT apply to another product.
- The Hook Tournament results for one product do NOT apply to another product.

When generating a brief, hook, edit direction, or any creative output:
1. Identify the exact product being discussed.
2. Load ONLY that product's strategy file.
3. Do not reference, borrow from, or blend in any other product's strategy.
4. If no strategy file exists yet for a product, say so explicitly — do not substitute the Fluid Pant strategy or any other product's strategy as a default.

---

## Product Registry

| Product | Strategy File | Status | FITZ-CR ID Range | Notes |
|---|---|---|---|---|
| **Ellison Fluid Pant** | `03_creative/products/fluid_pant.md` | ✅ Active | CR-0061 to CR-0074, CR-0078, CR-0089, CR-0091, CR-0093, CR-0100 to CR-0107 | Full strategy: 261-clip library, GOLD scoring, 5 editing frameworks, Hook Tournament, hook-first philosophy, and the Fluid Pant Visual Test Batch 2 |
| **Tavo Stripe Short** | `03_creative/products/tavo_stripe_short.md` | 🟡 Performance data available | CR-0001 to CR-0060; CR-0075; CR-0079 to CR-0088; CR-0090; CR-0092; CR-0094 to CR-0099 | Top performers confirmed below. Dedicated footage strategy file still needs to be built before new product-specific creative is produced. |
| **Cassius Knit Polo** | `03_creative/products/cassius_knit_polo.md` | 🔲 Not yet built | CR-0077 | One tracker entry exists, but it does not replace the need for a dedicated footage library, GOLD scoring, hook framework, and editing strategy. |
| **Bren Sketch Short** | `03_creative/products/bren_sketch_short.md` | 🔲 Not yet built | CR-0076 | One tracker entry exists, but it does not replace the need for a dedicated footage library, GOLD scoring, hook framework, and editing strategy. |
| **Denzo Knit Pullover** | `03_creative/products/denzo_knit_pullover.md` | 🔲 Not yet built | None confirmed | Needs its own footage library, GOLD scoring, hook framework, and editing strategy. |

---

## FITZ-CR ID to Product Mapping

The Ad Batches tab in the Google Sheet, column O: **Product**, is the authoritative source for every product tag. IDs became noncontiguous once multiple product workflows ran in parallel. Never infer a product from an ID number or from an ad name.

| FITZ-CR IDs | Product |
|---|---|
| CR-0001 to CR-0060 | Tavo Stripe Short |
| CR-0061 to CR-0073 | Ellison Fluid Pant |
| CR-0074 | Ellison Fluid Pant |
| CR-0075 | Tavo Stripe Short |
| CR-0076 | Bren Sketch Short |
| CR-0077 | Cassius Knit Polo |
| CR-0078 | Ellison Fluid Pant |
| CR-0079 to CR-0088 | Tavo Stripe Short |
| CR-0089 | Ellison Fluid Pant |
| CR-0090 | Tavo Stripe Short |
| CR-0091 | Ellison Fluid Pant |
| CR-0092 | Tavo Stripe Short |
| CR-0093 | Ellison Fluid Pant |
| CR-0094 to CR-0099 | Tavo Stripe Short |
| CR-0100 to CR-0107 | Ellison Fluid Pant |

**When Parker is asked about product performance, it must filter using column O: Product in the Ad Batches sheet. The only permitted legacy fallback is CR-0001 to CR-0060 for Tavo Stripe Short and CR-0061 to CR-0073 for Ellison Fluid Pant.**

---

## Tavo Stripe Short — Confirmed Top Performers

These are the top-performing Tavo Stripe Short creatives based on confirmed Meta spend and ROAS data (last 30 days as of August 2026):

| Creative ID | Ad Name | Spend | ROAS | Status |
|---|---|---|---|---|
| FITZ-CR-0021 | "1" | $9,534.52 | 2.10x | Active |
| FITZ-CR-0022 | "B1" | $3,862.95 | 1.68x | Active |
| FITZ-CR-0024 | "7" | $2,400.86 | 1.90x | Active |
| FITZ-CR-0025 | "1 (AI Videos)" | $2,045.82 | 1.60x | Paused |
| FITZ-CR-0030 | "W1" | $1,217.24 | 1.53x | Active |

**Key insight:** The ad naming convention for these legacy creatives ("1", "B1", "7", "W1") does not follow the current product-first naming standard. These names are not reliable for product identification — always use column O (Product) in the sheet.

---

## How to Add a New Product Strategy

When a new product is ready for ad creative production:

1. Create a new file: `03_creative/products/{product_slug}.md`.
2. Add it to the registry table above with status ✅ Active. Do not reserve a numeric product range because creative IDs may be interleaved across product workflows.
3. Run the `ef-ad-creative` skill to build:
   - Footage tagging and GOLD library.
   - Hook Tournament clips.
   - Five editing frameworks specific to that product's differentiators.
   - Performance tracker.
4. Update the dashboard's `buildSystemPrompt` function to include the new product in the detection list.
5. Tag every new row in column O: Product of the Ad Batches sheet with the exact product name. Treat that column as the product source of truth.

---

## What "Product Differentiator" Means Per Product

Each product's creative strategy must be built around what makes **that specific product** visually and functionally different — not around the brand's general aesthetic.

| Product | Primary Differentiator | Secondary Differentiator |
|---|---|---|
| Fluid Pant | Pleated wide-leg silhouette + dual-tone color shift | Drape and movement under light |
| Tavo Stripe Short | TBD — needs footage review | TBD |
| Cassius Knit Polo | TBD — needs footage review | TBD |
| Bren Sketch Short | TBD — needs footage review | TBD |
| Denzo Knit Pullover | TBD — needs footage review | TBD |

---

## Scope Reminder

The Fluid Pant creative strategy (hooks, frameworks, GOLD clips, Hook Tournament) was built from a specific 261-clip footage library shot in August 2026. It reflects:
- That product's visual differentiators (pleats, color shift, drape)
- That product's footage characteristics (1920×1080 landscape, specific lighting conditions)
- That product's Meta testing philosophy (hook-first, variable isolation, 6–8 second edits)

**None of this transfers to other products by default.** Other products may share the same general Meta testing philosophy, but their hooks, clip selections, crop presets, and editing frameworks must be derived independently from their own footage.

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

| Product | Strategy File | Status | Notes |
|---|---|---|---|
| **Ellison Fluid Pant** | `03_creative/products/fluid_pant.md` | ✅ Active | Full strategy: 261-clip library, GOLD scoring, 5 editing frameworks, Hook Tournament (H01–H11), hook-first philosophy, 13 launch-ready ads |
| **Tavo Stripe Short** | `03_creative/products/tavo_stripe_short.md` | 🔲 Not yet built | Needs its own footage library, GOLD scoring, hook framework, and editing strategy |
| **Cassius Knit Polo** | `03_creative/products/cassius_knit_polo.md` | 🔲 Not yet built | Needs its own footage library, GOLD scoring, hook framework, and editing strategy |
| **Bren Sketch Short** | `03_creative/products/bren_sketch_short.md` | 🔲 Not yet built | Needs its own footage library, GOLD scoring, hook framework, and editing strategy |
| **Denzo Knit Pullover** | `03_creative/products/denzo_knit_pullover.md` | 🔲 Not yet built | Needs its own footage library, GOLD scoring, hook framework, and editing strategy |

---

## How to Add a New Product Strategy

When a new product is ready for ad creative production:

1. Create a new file: `03_creative/products/{product_slug}.md`
2. Add it to the registry table above with status ✅ Active
3. Run the `ef-ad-creative` skill (see `/home/ubuntu/skills/ef-ad-creative/SKILL.md`) to build:
   - Footage tagging and GOLD library
   - Hook Tournament clips
   - 5 editing frameworks specific to that product's differentiators
   - Performance tracker
4. Update the dashboard's `buildSystemPrompt` function to include the new product in the detection list

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

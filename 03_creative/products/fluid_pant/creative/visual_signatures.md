# Fluid Pant Visual Signatures

## Purpose

This file protects the visual identity of the Fluid Pant in statics, video, Nano Banana, Higgsfield, creator briefs, and editor work. It does not replace the live product page or current official imagery for colorways and exact product appearance.

## The product signatures

| Visual signature | Status | What it must look like | Why it matters |
|---|---|---|---|
| Pleated texture | **VALIDATED PRODUCT TRUTH** | Clearly visible vertical pleats that catch light or react to touch | Primary visual differentiator |
| Drape in motion | **VALIDATED PRODUCT TRUTH** | Fabric moves naturally during a stride, turn, breeze, or step | Makes the garment visually different from a basic trouser |
| Relaxed, wide straight-leg silhouette | **VALIDATED PRODUCT TRUTH** | Readable waist-to-hem or full-body proportion with generous leg volume; never skinny, tapered, cuffed, or cargo-shaped | Preserves product recognition and the exaggerated drape seen in approved references |
| Drawstring waist | **VALIDATED PRODUCT TRUTH** | Visible only when the shot naturally includes the waist; do not invent belt hardware | Product truth |
| Fine striped / micro-stripe pleated texture | **VALIDATED PRODUCT TRUTH** | Fine all-over stripe/pleat structure readable in detail or directional light | Product truth and visual novelty |
| Color shift under light | **STRONG SIGNAL** | Directional light reveals tonal depth or color variation only where the supplied colorway actually supports it | Priority hook and visual cue |
| Pocket interaction | **STRONG SIGNAL** | Hand enters or rests naturally in the pocket while the pant remains visually clear | Native, tactile product proof |

## Product fidelity rules for AI

### Preserve

- The exact silhouette and proportions of the supplied official reference.
- Relaxed, wide straight-leg volume; never slim or tapered.
- Pleated, textured, fine-striped material.
- Natural drape and believable gravity.
- Drawstring waist when the waist is visible.
- Product-dominant framing.
- Realistic fabric behavior under walking, turning, touching, and directional light.
- Authentic color shift produced by light interacting with the existing fabric/colorway.

### Do not invent

- Cargo pockets, zipper details, belt loops, logos, patches, side stripes, heavy hardware, or visible branding not shown in official product imagery.
- Skinny taper, jogger cuffs, tailored suit creases, denim texture, leather texture, parachute nylon, or athletic track-pant features.
- Liquid, melting, rubbery, gelatinous, or wave-like pleats.
- Fabric that stretches or deforms independently of the wearer's movement.
- Animated gradients or color transformations that are not caused by believable lighting.
- Impossible color gradients, printed graphics, or new colorways unless a current approved reference image is supplied.
- Accessories that block the waist, pleats, silhouette, or movement.

## AI motion fidelity

When animating an approved static or product reference, prioritize **product accuracy over dramatic motion**.

Preferred motion:

- One natural step.
- Small weight shift.
- Subtle quarter turn.
- Hand entering a pocket.
- Light fabric sway caused by the body.
- Gentle directional-light change caused by movement relative to the light source.

Avoid dramatic leg swings, aggressive fabric waves, artificial wind, morphing pleats, or large camera moves unless the source asset clearly supports them.

## Framing rules

| Asset type | Preferred framing | Avoid |
|---|---|---|
| Texture static or video | Macro or waist-to-hem, directional light on pleats | Fabric too distant to read |
| Movement asset | Low angle, mid-stride, chest-down, side profile, or tight waist-to-shoe frame | Upper-body or face-led framing where pant is secondary |
| Silhouette static | Full body or waist-to-hem against simple contrast | Busy backgrounds or dark clothing that hides the shape |
| Pocket or waistband asset | Close interaction with product dominant in frame | Hand or accessory covering product detail |
| Creator lifestyle asset | Full look plus clear product cutaway | Creator monologue without a legible pant shot |

## Reference-image rule

For AI generation, always provide the current official product image for the selected colorway when visual fidelity matters. The supplied approved reference controls exact silhouette, color, texture, and construction. The live product page controls current commercial availability.

## Required prompt language

Include this block in every image or video prompt where product fidelity matters:

```text
Preserve the exact Ellison Fluid Pant shown in the supplied reference: relaxed, wide straight-leg silhouette, visible pleated micro-stripe texture, natural drape, and adjustable drawstring waist when visible. Match the reference proportions and color exactly. Do not add cargo pockets, belt loops, zippers, logos, cuffs, denim texture, athletic side stripes, extra hardware, or a slimmer/tapered shape. Do not make the pleats liquid, wavy, rubbery, or morphing. Any color shift must come naturally from believable directional light interacting with the existing fabric, never from an animated gradient. The pant must be the primary visual subject.
```

## Pre-generation check

- [ ] Current official/reference image is available if visual accuracy matters.
- [ ] Pant proportion matches the reference and reads relaxed + wide straight-leg.
- [ ] Pleats, stripe texture, drape, or silhouette will be readable.
- [ ] Motion is restrained enough to preserve garment construction.
- [ ] The selected setting does not hide the product.
- [ ] The assignment uses one visual signature, not an overloaded list of features.

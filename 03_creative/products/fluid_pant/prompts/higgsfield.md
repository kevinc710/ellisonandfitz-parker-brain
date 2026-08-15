# Fluid Pant Higgsfield Prompt Library

## Before prompting

Use the current official product image for the selected colorway when visual fidelity matters. Read [Visual Signatures](../creative/visual_signatures.md), [Product Accuracy Rules](../product/product_accuracy_rules.md), and [Fluid Pant Master Context](../FLUID_PANT_CONTEXT.md) before generating.

## Required fidelity block

Append this block to every Fluid Pant Higgsfield prompt:

```text
Preserve the Ellison Fluid Pant's relaxed straight-leg silhouette, visible pleated micro-stripe texture, natural drape, and adjustable drawstring waist. The pants are the primary subject and occupy at least 60% of the frame whenever practical. Do not add cargo pockets, belt loops, zippers, logos, cuffs, denim texture, athletic side stripes, heavy hardware, or unapproved prints. No embedded text. No voiceover. Premium but native feel.
```

## Prompt structure

```text
Generate a 9:16 vertical Fluid Pant video.

ONE VISUAL IDEA: [PLEATS / DRAPE / COLOR SHIFT / WIDE-LEG SILHOUETTE / POCKET INTERACTION].

FIRST SECOND: [EXACT PRODUCT HOOK]. Movement already in progress. No static setup.

CAMERA: [LOW ANGLE / WAIST HEIGHT / MACRO / CHEST-DOWN POV / HANDHELD DISCOVERY].

ACTION: [STRIDE / TURN / HAND TOUCH / POCKET INTERACTION / MIRROR REVEAL].

SETTING: [SECONDARY CONTEXT]. Clean and uncluttered.

[REQUIRED FIDELITY BLOCK]
```

## Product Discovery: extreme pleat macro

```text
Generate a 9:16 vertical product-discovery video for the Ellison Fluid Pant. Begin in the first frame with an extreme macro of pleated micro-stripe fabric, close enough that the object is initially hard to identify. Directional light reveals texture and color shift. At 0.8 seconds, pull back to reveal the relaxed straight-leg Fluid Pant in motion. Continue with a low-angle stride and finish on a clear full silhouette. Handheld discovery camera, premium but native, movement already in progress.

[REQUIRED FIDELITY BLOCK]
```

## Movement: low-angle stride

```text
Generate a 9:16 vertical movement-led Fluid Pant video. Start in the first frame with a low-angle mid-stride shot. The pants dominate the frame, pleats fan naturally with each step, and the relaxed straight-leg silhouette reads clearly. Cut to a side turn, then a waist-to-hem close-up showing the fabric catching directional light. End with the person walking away in a simple architectural setting. The environment is secondary to the product.

[REQUIRED FIDELITY BLOCK]
```

## Texture: hand and pocket interaction

```text
Generate a 9:16 vertical tactile Fluid Pant video. Open on a natural hand entering the pocket while directional light catches the pleated micro-stripe texture. Cut to a close-up where the hand brushes the fabric and the pleats move naturally. Then reveal a relaxed straight-leg walking silhouette. Clean minimal setting, native product-discovery feel, no face-led introduction.

[REQUIRED FIDELITY BLOCK]
```

## Color shift: directional-light reveal

```text
Generate a 9:16 vertical Fluid Pant color-shift video. Start in the first frame with a close product crop under directional light so tonal variation and pleated texture are visible. The camera follows a small step and turn, then pulls back to a waist-to-hem silhouette in motion. The color shift is visually intriguing, but the real construction and drape remain believable. Minimal background, no stylized effects that distort the product.

[REQUIRED FIDELITY BLOCK]
```

## Static-to-video variation protocol

When testing a hook, keep the body edit constant. Generate only one changed first-second variable per variant. Name the output `FLUID_VIDEO_[HOOK]_[VARIANT]_v01` and log the exact hook in the testing record.

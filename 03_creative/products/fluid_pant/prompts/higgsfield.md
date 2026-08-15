# Fluid Pant Higgsfield Prompt Library

## Before prompting

Use the current approved product image for the selected colorway whenever visual fidelity matters. Read [Visual Signatures](../creative/visual_signatures.md), [Product Accuracy Rules](../product/product_accuracy_rules.md), and [Fluid Pant Master Context](../FLUID_PANT_CONTEXT.md) before generating.

## Generation priority

For the Fluid Pant, **product fidelity beats dramatic AI motion**. The model should animate a believable garment, not reinterpret it.

Preferred movement is restrained: one natural step, a small weight shift, a subtle quarter turn, a hand entering the pocket, or fabric sway caused by the wearer's body. Avoid dramatic fabric animation unless the source reference supports it.

## Required fidelity block

Append this block to every Fluid Pant Higgsfield prompt:

```text
Preserve the exact Ellison Fluid Pant shown in the supplied reference: relaxed, wide straight-leg silhouette, visible pleated micro-stripe texture, natural drape, and adjustable drawstring waist when visible. Match the reference proportions and color exactly. The pants are the primary subject and occupy at least 60% of the frame whenever practical. Do not add cargo pockets, belt loops, zippers, logos, cuffs, denim texture, athletic side stripes, heavy hardware, or unapproved prints. Do not make the pleats liquid, wavy, rubbery, or morphing. Fabric movement must be caused naturally by the wearer's body and gravity. Any color shift must come from believable directional light interacting with the existing fabric, never from an animated gradient. No embedded text. No voiceover. Premium but native feel.
```

## First-second benchmark

Before approving a generated hook, ask:

> **Which hook immediately communicates that these are not ordinary pants, while making me curious enough to keep watching?**

Novelty alone is insufficient. The first second must also remain relevant to the Fluid Pant.

## Prompt structure

```text
Generate a 9:16 vertical Fluid Pant video.

ONE VISUAL IDEA: [PLEATS / DRAPE / AUTHENTIC COLOR SHIFT / WIDE STRAIGHT-LEG SILHOUETTE / POCKET INTERACTION].

FIRST SECOND: [EXACT PRODUCT HOOK]. Product is visible immediately. If using movement, movement is already in progress.

CAMERA: [LOW ANGLE / WAIST HEIGHT / MACRO / CHEST-DOWN POV / TIGHT WAIST-TO-SHOE / HANDHELD DISCOVERY].

ACTION: [ONE NATURAL STEP / SMALL WEIGHT SHIFT / SUBTLE QUARTER TURN / HAND TOUCH / POCKET INTERACTION / CONTROLLED WALK].

LIGHT: [HARD DIRECTIONAL SUNLIGHT / NATURAL SIDE LIGHT / CLEAN STUDIO DIRECTIONAL LIGHT]. Light reveals the real pleats and tonal depth without changing the product design.

SETTING: [SECONDARY CONTEXT]. Clean and uncluttered.

[REQUIRED FIDELITY BLOCK]
```

## Product Discovery: extreme pleat macro

```text
Generate a 9:16 vertical product-discovery video for the Ellison Fluid Pant. Begin in the first frame with an extreme macro of the real pleated micro-stripe fabric, close enough that the object is initially difficult to identify but the texture remains believable. Hard directional light reveals the pleat geometry and authentic tonal variation. Around 0.8 seconds, make a restrained pullback that reveals the waistband or wider pant silhouette. Continue with one natural step or small weight shift. Do not make the pleats ripple independently, melt, or behave like liquid. Premium but native product discovery.

[REQUIRED FIDELITY BLOCK]
```

## Movement: low-angle stride

```text
Generate a 9:16 vertical movement-led Fluid Pant video. Start immediately on a low-angle natural mid-stride moment with the pants dominating the frame. Use only a controlled one- or two-step movement. The relaxed, wide straight-leg silhouette should read clearly and the pleats should move only as a consequence of the legs and gravity. Keep the camera close and stable enough to preserve product construction. Hard or natural directional light should reveal texture and drape. Simple architectural setting; environment secondary.

[REQUIRED FIDELITY BLOCK]
```

## Texture: hand and pocket interaction

```text
Generate a 9:16 vertical tactile Fluid Pant video. Open on a natural hand entering the pocket while directional light catches the real pleated micro-stripe texture. The hand may brush or lightly pinch the fabric once, then release it so it falls naturally under gravity. Follow with a small weight shift or one step that reveals the relaxed, wide straight-leg silhouette. No exaggerated stretch, elastic distortion, liquid pleats, or morphing fabric. Clean minimal setting, no face-led introduction.

[REQUIRED FIDELITY BLOCK]
```

## Color shift: directional-light reveal

```text
Generate a 9:16 vertical Fluid Pant color-shift video using the supplied product reference as the absolute color source. Start with a tight waist-to-knee or waist-to-shoe crop under hard directional light. The wearer makes one small step or subtle quarter turn so the existing fabric catches the light differently. The tonal/color change must arise only from the change in light angle on the real fabric. Do not animate a gradient across the pants and do not invent blue, red, purple, or other tones that are absent from the reference. Keep construction, pleats, and drape stable and believable.

[REQUIRED FIDELITY BLOCK]
```

## Static-to-video: restrained hero animation

```text
Animate the supplied approved Fluid Pant static without redesigning the garment or composition. Preserve the exact pant shape, pleat spacing, texture, waistband, color distribution, model proportions, lighting direction, and background. Add only restrained human motion: a small weight shift followed by one natural step or subtle quarter turn. Allow a slight fabric sway caused by that movement. Keep the camera mostly locked with at most a subtle natural handheld drift or micro push-in. No dramatic wind, no liquid fabric, no morphing pleats, no new garment details, no animated color gradient. The goal is to make the still image feel alive while remaining visually congruent with the source.

[REQUIRED FIDELITY BLOCK]
```

## Hook variation protocol

When testing a hook, keep the body edit, audio, offer, product/colorway, audience, and placement constant wherever possible. Change only the first 0.5–1.5 second variable. Name the output `FLUID_VIDEO_[HOOK]_[VARIANT]_v01` and log the exact hook in the testing record.

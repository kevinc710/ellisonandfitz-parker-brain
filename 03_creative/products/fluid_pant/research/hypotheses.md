# Fluid Pant Active Hypotheses

## Rule

A hypothesis is not a fact, an avatar, a customer claim, or a production rule. It must have a defined control, test, metric, owner, and review date before it affects default strategy.

## Current hypotheses

| ID | Hypothesis | Status | Fluid Pant-specific basis | Proposed control and variant | Primary metric | Promotion rule |
|---|---|---|---|---|---|---|
| FP-H01 | Visual novelty and curiosity are a major scroll-stop mechanism for the Fluid Pant. | **STRONG SIGNAL** | Macro, color-shift, low-angle, and delayed-recognition hooks are prioritized in the existing hook framework. | Control: standard product movement. Variant: macro pleat or impossible crop. | Thumb Stop Rate, then 3-second Hold Rate | Promote after repeated product-specific lift across comparable tests. |
| FP-H02 | Identity-led creator context increases desire after a product-first hook. | **HYPOTHESIS** | Creator planning suggests individuality and creative-life stories may make visual differentiation more personally relevant. | Control: product-first edit with no creator message. Variant: same product proof plus concise personal-style statement. | Hold Rate, CTR, and conversion metric | Promote only if the identity layer outperforms the matched product-only control. |
| FP-H03 | Social attention, such as people asking about the pants, is an important purchase desire. | **HYPOTHESIS** | Plausible but no Fluid Pant-specific customer evidence is recorded. | Control: visual novelty or texture claim. Variant: approved first-person social-attention line. | Conversion and comment quality | Promote only with direct customer or conversion evidence. |
| FP-H04 | Creative, music, travel, and style-forward contexts are productive creator-fit environments. | **HYPOTHESIS** | These contexts can naturally demonstrate movement, personal style, and product distinction. | Control: matched product-first creator post. Variant: context-specific product story. | Creator quality, clicks, code use, conversion | Promote only after enough comparable creator results. |
| FP-H05 | Established creative-professional creators outperform younger fashion-oriented creators. | **UNTESTED** | No Fluid Pant-specific evidence. | Test matched creator cohorts with comparable offer, product, and attribution conditions. | Conversion efficiency, content quality, and audience fit | Do not promote without a defined, sufficiently comparable test. |
| FP-H06 | Pocket interaction is a stronger first-second hook than a generic walk. | **STRONG SIGNAL** | Pocket interaction is documented as native and tactile in the existing hook library; its final relative performance is not proven. | Control: walking hook. Variant: pocket interaction hook using same body edit. | Thumb Stop Rate and 3-second Hold Rate | Promote only after matched hook results. |

## Hypothesis intake template

```text
### [FP-HXX] Hypothesis name

- Status: HYPOTHESIS or UNTESTED
- Source or origin:
- Why it is plausible:
- Cross-product contamination check: Is this based on another product? If yes, name it and keep status at HYPOTHESIS.
- Control:
- Variant:
- Product difference that remains constant:
- Audience or creator context:
- Primary metric:
- Secondary metric:
- Minimum sample or decision threshold:
- Owner:
- Review date:
- Result and next status:
```

## Status change rules

| Current status | May change to | Required evidence |
|---|---|---|
| UNTESTED | HYPOTHESIS | A coherent Fluid Pant-specific rationale and test design. |
| HYPOTHESIS | STRONG SIGNAL | At least one documented Fluid Pant result that supports the idea. |
| STRONG SIGNAL | VALIDATED | Repeated Fluid Pant-specific evidence, or one sufficiently robust study, that changes default operating behavior. |
| Any status | DEPRIORITIZED | A documented test or approved strategic decision shows it should not be the current priority. |

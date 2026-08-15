# Fluid Pant Knowledge-System Structure Map

## Recommended implementation

The proposed `fluid-pant-knowledge` hierarchy is a strong **coverage checklist**, but it is too fragmented to create as separate files before the team has evidence for every category. The recommended system keeps the same ideas while combining overlapping documents and preserving the existing detailed creative-performance memory.

| Proposed area | Recommended Fluid Pant file | Reason |
|---|---|---|
| `README.md` | [README](README.md) | One team entry point and source-of-truth rule |
| `product/product_overview.md`, `product_features.md`, `colorways.md`, `product_accuracy_rules.md` | [Product Truths and Claims Guardrails](01_product_truths_and_claims.md) | Product claims, dynamic commercial facts, and accuracy rules must stay together |
| `customer/core_icp.md`, `avatars.md`, `sub_avatars.md`, `desires.md`, `objections.md`, `voice_of_customer.md` | [Customer and Creator Segments](02_customer_and_creator_segments.md) plus future evidence-backed additions | Avoid treating early audience ideas as permanent avatar facts |
| `positioning/brand_positioning.md` | Link to root Brand Brain positioning file | Brand positioning should not be duplicated at product level |
| `positioning/product_positioning.md`, `messaging_guardrails.md` | [Product Truths and Claims Guardrails](01_product_truths_and_claims.md) and [AI Context Pack](AI_CONTEXT_PACK.md) | Product positioning and claim boundaries need a single controlled source |
| `positioning/competitor_context.md` | Future research file when source-backed competitor research exists | Do not create unsupported competitor assertions |
| `creative/creative_strategy.md`, `winning_patterns.md`, `losing_patterns.md`, `static_frameworks.md`, `video_frameworks.md`, `hook_library.md`, `visual_signatures.md`, `editor_rules.md` | [Creative Operating System](04_creative_operating_system.md) plus the detailed [Fluid Pant Creative Memory](../fluid_pant.md) | The detailed existing file already holds evidence, hooks, tests, and editor rules |
| `research/account_learnings.md`, `testing_history.md`, `hypotheses.md` | [Learning Log](06_learning_log.md) and [Fluid Pant Creative Memory](../fluid_pant.md) | Record evidence and decisions without duplicating performance history |
| `research/competitor_swipes.md` | Future source-tagged research file | Add only after collection and analysis |
| `prompts/higgsfield.md`, `nano_banana.md`, `ugc_creator_prompts.md`, `editor_prompts.md`, `ai_agent_system_prompt.md` | [AI Context Pack](AI_CONTEXT_PACK.md) plus task-specific prompt sections | Keeps shared product rules consistent across models; add model-specific syntax only when needed |
| `changelog/CHANGELOG.md` | [Learning Log](06_learning_log.md) plus Git history | Git is the version history; the log records strategic change, not every edit |

## Why not create every suggested file immediately

More files do not automatically create more clarity. If a file contains only assumptions, a VA or editor can mistake it for an approved fact. The system must distinguish:

1. **Approved product truth:** sourced from the live product page or approved internal decision.
2. **Creative evidence:** proven results from actual assets or documented tests.
3. **Working hypothesis:** a useful idea that still needs a test.
4. **Raw source material:** ChatGPT conversations, swipes, research exports, or notes that require curation.

## How to handle future ChatGPT dumps

Send the material to the owner or agent with its date and source. It will be classified as one of the four categories above, then curated into the appropriate file. Do not paste raw ChatGPT output into every canonical document.

## When to split a file

Split a file only when it becomes difficult to use in one sitting or when a single topic has enough verified material to stand alone. Good future split candidates are:

- `voice_of_customer.md`, once customer reviews, survey responses, and support language are gathered.
- `competitor_context.md`, once source-backed competitor research is available.
- `creator_case_studies.md`, once several creators have been screened and tested.
- Model-specific prompt files, once the team uses multiple models with materially different syntax or constraints.

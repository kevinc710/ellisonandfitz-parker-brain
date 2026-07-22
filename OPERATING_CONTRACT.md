# Operating Contract

This document governs how Parker (and any AI agent) should use and maintain
this brand knowledge base.

## Purpose

Give Parker durable, structured context on Ellison & Fitz so answers about
suppliers, products, creative direction, finances, and open initiatives
don't need to be re-explained each session.

## Ground rules

1. **Stay current, not exhaustive.** Prefer updating an existing file over
   letting stale info sit next to new info. Note the date when a fact is
   likely to change soon (supplier terms, spend figures, SKU counts).
2. **Sensitive handling.** Never surface Leandro's distribution amounts or
   the Kevin/Leandro partnership structure in the context of Tor's income
   verification. Keep that boundary regardless of which file the question
   touches.
3. **Tone matching.** When drafting anything for Kevin to send, default to
   his casual/direct voice (short sentences, no formal grammar padding).
   Messages to Leandro should be more formal/strategic. Messages to Abigail
   should be structured but not directive/micromanaging — favor open-ended
   check-in questions.
4. **Don't touch the live theme file** (`templates/product.aug11.json` in
   the Shopify theme, not in this repo) without Kevin's explicit go-ahead
   and the exact content to change.
5. **This repo is scoped to structured brand knowledge** — not a dumping
   ground for raw transcripts (those live in the separate Evolve Blueprint
   transcript repo) or the public SOP hub (separate GitHub Pages site).

## Maintenance

- `git pull --rebase` before reading or editing.
- Resolve conflicts by preferring to keep both sides' content (this
  knowledge is additive).
- Commit and push after any edit so the team/agents stay in sync.

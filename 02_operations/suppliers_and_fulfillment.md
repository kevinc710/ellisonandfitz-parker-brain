# Suppliers & Fulfillment

## Active suppliers

| Supplier | Slack shorthand | Role |
|---|---|---|
| Beehive | Cherry | Primary fulfillment (as of order #8995) |
| Dropsure | Leigh / Lay | Overflow fulfillment |
| Wiio | Hart | Ellison Fluid Pants — being phased out |

## Routing rule

- **Hart (Wiio)** fulfills the *complete* order any time it contains an
  Ellison Fluid Pant.
- **Cherry (Beehive)** fulfills everything else.
- Hart and Cherry should **not** be made aware of each other.

## Historical order tagging

1,533 historical Shopify orders were bulk-tagged (DROPSURE / BEEHIVE / both)
via GraphQL mutations to establish clean supplier attribution.

## Wiio → Beehive transition (in progress)

The business is moving away from Wiio/Hart for Fluid Pant fulfillment.
Open question: can Beehive/Cherry handle 4XL colorway production/drop-ship
instead of paying Wiio's 200pc/color MOQ? See
`05_roadmap/open_strategic_questions.md` for the live decision status.

## Returns — Redo (replaced Return Helper, April 27, 2026)

Full onboarding completed with contacts: Mitch, Hugh, Linus, Carl, Braden,
and Michael Hammer.

Key decisions:
- **Checkout+** opt-in rate: 4.6%
- **VIP Checkout bundle** (returns + package protection): 6.1% attach,
  promoted to production after a 48.5% attach rate vs. ~10% standalone
- **Revshare:** 1.5% of cart value on opted-in orders, plus 50/50 split on
  refulfillment revenue
- **Fluid Pant return policy:** requires branded poly bag + thank-you card;
  all other products graded on condition only
- Michael Hammer (Redo) is building an order-tracking product to replace
  ParcelPanel

**Open follow-up (pending answer from Hugh):** "With our auto-processing
settings enabled, what types of flagged returns actually require a decision
from our side vs. your team handling it internally?"

## SOPs

A Master SOP document (v3.0) covers 12 SOPs, including DNDR, WISMO, HRR
protocol, Redo returns, and sourcing messaging. The public SOP hub lives at
`kevinc710.github.io/ef-sops/` (single `index.html`), embedded in Notion.

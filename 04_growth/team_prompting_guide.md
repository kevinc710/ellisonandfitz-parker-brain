# Ellison & Fitz: Team Prompting Guide & Operating Manual

## 1. Introduction: The Manus-First Architecture
To eliminate fragmentation, the Ellison & Fitz creative operations run on a **Manus-First Operating System**. Instead of maintaining a separate, custom-built dashboard UI or managing messy spreadsheets manually, the entire team (Kevin, Daniela, Leandro) interacts directly with Manus through the shared project interface.

Manus acts as the **Creative Director, Producer, and Data Orchestrator**. Behind the scenes, Manus reads the GitHub Brand Brain, queries Meta Ads via Pipeboard, generates assets via Melius, logs data to Google Sheets, and posts alerts to Slack. 

The team's role is simple: **Talk to Manus.**

---

## 2. Core Team Roles & Chat Triggers

### Kevin (Founder & Strategist)
*   **Primary Objective:** Scaling winning ad angles, approving production batches, and reviewing macro performance.
*   **Key Prompt Templates:**
    *   *"E&F, show me the top 3 winning ads across all active products this week."*
    *   *"E&F, generate three single-variable Melius iterations for our highest-spend validated Tavo Short winner."*
    *   *"E&F, review the Google Sheet and give me a summary of what is currently 'Ready to Launch'."*

### Daniela (Video Editor & Creative Execution)
*   **Primary Objective:** Executing on visual direction, assembling master edits from Melius assets, and applying post-production text overlays (Montserrat headlines, CTA buttons).
*   **Key Prompt Templates:**
    *   *"E&F, give me the raw asset links and prompting notes for the latest batch of 'Needs Review' Tavo shorts."*
    *   *"E&F, retrieve the top 5 GOLD clips for the Ellison Fluid Pant from the asset library."*
    *   *"E&F, what are the approved colorways and typography rules for the current Tavo batch?"*

### Leandro (Media Buying & Launch)
*   **Primary Objective:** Bulk launching approved assets into Meta Ads Manager, monitoring ad set performance, and feeding ROAS data back into the system.
*   **Key Prompt Templates:**
    *   *"E&F, export all creatives currently marked 'Ready to Launch' into a clean launch manifest."*
    *   *"E&F, verify if the latest Tavo iteration batch has all required UTM parameters and asset links."*

---

## 3. The 4 Golden Rules of Prompting Manus

To ensure zero drift from the Ellison & Fitz brand identity, every prompt given to Manus should adhere to these four constraints:

### Rule 1: Always Specify the Product
Never ask for generic "ads." Always anchor the prompt to the specific product line so Manus loads the correct Product Memory (`fluid_pant.md` or `tavo_stripe_short.md`).
*   *Bad:* "Make some new iteration videos."
*   *Good:* "Generate three Melius iterations for the **Tavo Stripe Short**."

### Rule 2: Enforce Single-Variable Isolation
When iterating on a winner, never allow the AI to change everything at once. Force it to isolate one variable so you can measure what actually caused the performance lift.
*   *Allowed variables:* Hook, Copy, Visual (Colorway/Setting), Format, Product Angle, Social Proof.
*   *Prompt phrasing:* "...changing **only the hook** while keeping the visual angle identical to the parent winner."

### Rule 3: Respect the Target Avatar Filter
Every creative must pass through the psychological filter of the product's target avatar.
*   **Alex (Fluid Pant / Design Individualist):** Architectural, intentional, design-forward. No gym-bro tropes.
*   **Marco (Tavo Short / Elevated Essentialist):** Sun-drenched, effortless, nautical/lifestyle (Yacht Club, Beach). No loud discounts.

### Rule 4: Follow the 14-Step Production Protocol
Whenever Manus triggers a production batch, it automatically executes the 14-step protocol:
1. Locate Parent -> 2. Analyze Data -> 3. Context Retrieval -> 4. History Check -> 5. Avatar Alignment -> 6. Foreplay Research -> 7. Single-Variable Selection -> 8. Brief Writing -> 9. Melius Batching -> 10. Asset Logging -> 11. Creative QA -> 12. Approval Gate -> 13. Launch Logging -> 14. Learning Loop.

---

## 4. Summary of Connected Back-End Systems

For team reference, here is what Manus controls automatically behind the scenes:
*   **Google Sheets (`1eUG3iznwWgTZ_ySH14HQkfDTNturjuWgVtwBbanmRB4`):** The silent database where all briefs, asset links, and statuses are logged.
*   **GitHub Brand Brain (`kevinc710/ellisonandfitz-parker-brain`):** The persistent memory repository that updates hourly.
*   **Meta Ads (via Pipeboard):** Daily automated pulls of spend, revenue, ROAS, and purchases at 6:00 AM.
*   **Slack (`#ef-creative-ops`):** Daily automated pulse reports at 8:00 AM and instant winner alerts.
*   **Melius:** The AI visual engine used to generate cinematic video and static assets.

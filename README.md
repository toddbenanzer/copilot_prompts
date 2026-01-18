# Executive Copilot Toolkit: Marketing Analytics & Strategy

This repository contains a curated set of Microsoft Copilot prompts and workflow guides designed specifically for a **Marketing Analytics Executive** in **Retail Banking**.

It serves as your personal operating system for:
- Parsing high-volume communication to find actionable requests.
- Organizing team priorities and resource allocation.
- Tracking commitments to and from senior leadership.
- Generating strategic roadmaps and executive presentations.

## ⚙️ Your Executive Context (Quick Reference)

These prompts use placeholders (e.g., `<PLACEHOLDER>`) to remain flexible. For your specific role, use these values when running the prompts:

| Placeholder | Your Value |
| :--- | :--- |
| **`<INDUSTRY>`** | Retail Banking |
| **`<TEAM_NAME>`** | Marketing Analytics Team |
| **`<TEAM_TYPE>`** | Analytics / Data Science |
| **`<EXECUTIVE_LEVEL>`** | C-Suite / Senior Leadership |
| **`<PRIMARY_METRIC>`** | Customer Acquisition Cost (CAC), Lifetime Value (LTV) |
| **`<BUSINESS_AREA>`** | Marketing Strategy & Analytics |

> **Pro Tip:** You can paste this table into a "Custom Instruction" or "System Prompt" in Copilot so it always knows your context.

---

## 🎯 Goal-Based Prompt Library

### 1. Manage Self (Efficiency & Focus)
*Reduce noise and focus on what matters immediately.*

*   **[Outlook] Email Triage (`E1`)**: "Analyze emails... Delegate & Security Check."
    *   *Use when:* Speed-clearing the inbox. Suggests owners for delegation and flags phishing attempts.
*   **[Outlook] Commitment Scan (`E3`)**: "Review emails... Internal Asks vs Regulatory Promises."
    *   *Use when:* Distinguishing between a boss's request and a compliance mandate.
*   **[Calendar] Weekly Overview (`C2`)**: "Analyze calendar... Run vs Change Analysis."
    *   *Use when:* Monday morning planning. Ensures you aren't stuck in "Run the Bank" (Ops) mode all week.
*   **[Outlook] Daily Closure (`E2`)**: "Create end-of-day summary... Incident & Campaign Launch Check."
    *   *Use when:* Wrapping up. Ensures incidents are handled and tomorrow's campaign launches are QA'd.

### 2. Manage Team (Direction & Optimization)
*Align your reports and optimize resource allocation.*

*   **[OneNote] Banking Priority Matrix (`N1`)**: "Create priority matrix... Regulatory (Must Do) vs Growth (Strategic)."
    *   *Use when:* Setting the week's direction. Explicitly balances compliance mandates with commercial goals.
*   **[OneNote] Meeting Agenda (`N3`)**: "Create meeting agenda... Risk & Compliance Moment."
    *   *Use when:* Setting the agenda. Ensures mandatory regulatory topics are never skipped.
*   **[Teams] Analytics Team Pulse (`T1`)**: "Summarize team updates... Agile & Experimentation Velocity."
    *   *Use when:* Tracking Sprint Burndown, Experiment Win Rates, and MarTech performance.
*   **[OneNote] Resource Optimization (`N4`)**: "Create team resource... Global Delivery & Contractor Risk."
    *   *Use when:* Managing Onshore/Offshore handovers, timezone coverage, and co-employment risk.
*   **[OneNote] Performance Review (`N2`)**: "Weekly review... KRIs & Talent Pulse."
    *   *Use when:* Reviewing team wins, Model Drift, and recognizing top performers to prevent burnout.

### 3. Manage Up (Visibility & Status)
*Keep senior leadership informed and confident.*

*   **[OneNote] C-Suite Strategic Brief (`N6`)**: "Create one-page brief... Financials & Customer Trust."
    *   *Use when:* Preparing for leadership. Focuses on money, decisions, and UDAAP/Complaint signals.
*   **[OneNote] ROI & Attribution (`N7`)**: "Generate comprehensive ROI analysis... MMM & Sensitivity."
    *   *Use when:* Defending budget using Media Mix Modeling (MMM) and Experimentation Lift vs Last-Click.
*   **[OneNote] Audit & Regulatory Readiness (`N5`)**: "Generate monthly audit & regulatory status report."
    *   *Use when:* Tracking MRAs, Audit findings, and SLA breaches to stay out of "Red" status.

### 4. Strategy & Creation (Roadmap & Content)
*Deep work, planning, and content generation.*

*   **[OneNote] Banking Strategy Roadmap (`N8`)**: "Develop strategy... First-Party Data & FinOps."
    *   *Use when:* Planning for Cookie Deprecation, Identity Resolution, and Cloud Costs.
*   **[System] Data to Presentation (`data_insights.md`)**: A specialized prompt to turn a raw spreadsheet into a slide outline.
    *   *Use when:* You have a CSV of campaign results and need a presentation outline immediately.
*   **[System] Notes to Slides (`notes_to_slides.md`)**: A specialized prompt to turn your dictated brain dump into a 7-slide deck.
    *   *Use when:* You've just had a strategic epiphany and want your team to build the deck.

---

## 📚 Resources & Files

*   **[`copilot_prompts.md`](./copilot_prompts.md)**: The master list of all prompt text and the "Implementation Calendar" (Daily/Weekly routines).
*   **[`data_insights.md`](./data_insights.md)**: Advanced template for data analysis.
*   **[`notes_to_slides.md`](./notes_to_slides.md)**: Advanced template for creating presentations from voice notes.
*   **[`gtd_guide.md`](./gtd_guide.md)**: "Executive GTD for Banking" - A guide on using contexts like @Regulator and @Audit to stay compliant while moving fast.

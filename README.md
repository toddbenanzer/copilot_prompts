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

*   **[Outlook] Email Triage (`E1`)**: "Analyze my emails... categorize by Urgent/High Priority."
    *   *Use when:* Starting your day to cut through the inbox clutter.
*   **[Outlook] Commitment Scan (`E3`)**: "Review emails... Internal Asks vs Regulatory Promises."
    *   *Use when:* Distinguishing between a boss's request and a compliance mandate.
*   **[Calendar] Weekly Overview (`C2`)**: "Analyze calendar... Run vs Change Analysis."
    *   *Use when:* Monday morning planning. Ensures you aren't stuck in "Run the Bank" (Ops) mode all week.
*   **[Outlook] Daily Closure (`E2`)**: "Create end-of-day summary... Incident & Escalation Check."
    *   *Use when:* Wrapping up. Ensures no P1 incidents or missed SLAs before you log off.

### 2. Manage Team (Direction & Optimization)
*Align your reports and optimize resource allocation.*

*   **[OneNote] Banking Priority Matrix (`N1`)**: "Create priority matrix... Regulatory (Must Do) vs Growth (Strategic)."
    *   *Use when:* Setting the week's direction. Explicitly balances compliance mandates with commercial goals.
*   **[OneNote] Meeting Agenda (`N3`)**: "Create meeting agenda... Risk & Compliance Moment."
    *   *Use when:* Setting the agenda. Ensures mandatory regulatory topics are never skipped.
*   **[Teams] Analytics Team Pulse (`T1`)**: "Summarize team updates... Data Quality & Vendor Health."
    *   *Use when:* Checking data pipelines, model risk, and critical MarTech vendor performance (e.g. Adobe/Salesforce).
*   **[OneNote] Resource Optimization (`N4`)**: "Create team resource optimization... Contractor Risk."
    *   *Use when:* Managing co-employment risk and FTE vs Contractor ratios in addition to key dependencies.
*   **[OneNote] Performance Review (`N2`)**: "Weekly review... Key Risk Indicators (KRIs)."
    *   *Use when:* Reviewing team wins alongside Data Quality scores and Model Drift alerts.

### 3. Manage Up (Visibility & Status)
*Keep senior leadership informed and confident.*

*   **[OneNote] C-Suite Strategic Brief (`N6`)**: "Create one-page strategic brief... Financial Impact & Decisions."
    *   *Use when:* Preparing for non-technical leadership. Focuses on money, market opportunity, and decisions required.
*   **[OneNote] ROI & Attribution (`N7`)**: "Generate comprehensive ROI analysis... Incrementality & Lift."
    *   *Use when:* Proving the *net-new* value of marketing spend, not just last-click attribution.
*   **[OneNote] Audit & Regulatory Readiness (`N5`)**: "Generate monthly audit & regulatory status report."
    *   *Use when:* Tracking MRAs, Audit findings, and SLA breaches to stay out of "Red" status.

### 4. Strategy & Creation (Roadmap & Content)
*Deep work, planning, and content generation.*

*   **[OneNote] Banking Strategy Roadmap (`N8`)**: "Develop strategy... Buy vs Build & Regulatory Scan."
    *   *Use when:* Planning the next year. Assessing Technical Debt and deciding between vendor solutions vs in-house builds.
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

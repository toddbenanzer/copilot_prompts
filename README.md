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
*   **[Outlook] Commitment Scan (`E3`)**: "Review emails from Leadership... find direct asks."
    *   *Use when:* You need to ensure no request from the C-Suite has slipped through the cracks.
*   **[Calendar] Morning Briefing (`C1`)**: "Create my daily briefing... identify conflicts."
    *   *Use when:* Planning your day's energy and logistics.
*   **[Outlook] Daily Closure (`E2`)**: "Create end-of-day summary... draft reminders."
    *   *Use when:* Wrapping up to ensure a clean start tomorrow.

### 2. Manage Team (Direction & Optimization)
*Align your reports and optimize resource allocation.*

*   **[OneNote] Priority Matrix (`N1`)**: "Create weekly team priority matrix... Urgent vs Important."
    *   *Use when:* Setting the week's direction during your Monday team sync.
*   **[Teams] Team Status Check (`T1`)**: "Summarize team updates... identify blockers."
    *   *Use when:* You've been in meetings all day and need a quick pulse check on project execution.
*   **[OneNote] Resource Optimization (`N4`)**: "Create team resource optimization analysis."
    *   *Use when:* Balancing workload or arguing for headcount.

### 3. Manage Up (Visibility & Status)
*Keep senior leadership informed and confident.*

*   **[OneNote] Executive Brief (`N6`)**: "Create one-page executive summary... Headline Insights."
    *   *Use when:* Preparing for a monthly business review (MBR) or steering committee.
*   **[OneNote] ROI Report (`N7`)**: "Generate comprehensive ROI analysis... Campaign Performance."
    *   *Use when:* Defending your budget or highlighting marketing effectiveness.
*   **[OneNote] Governance Review (`N5`)**: "Generate monthly data governance status report."
    *   *Use when:* Reporting on compliance, privacy, and data quality (crucial in Retail Banking).

### 4. Strategy & Creation (Roadmap & Content)
*Deep work, planning, and content generation.*

*   **[OneNote] Strategy Development (`N8`)**: "Develop technology strategy roadmap... Capability Gap Analysis."
    *   *Use when:* Planning the next quarter or year.
*   **[System] Data to Presentation (`data_insights.md`)**: A specialized prompt to turn a raw spreadsheet into a slide outline.
    *   *Use when:* You have a CSV of campaign results and need a presentation outline immediately.
*   **[System] Notes to Slides (`notes_to_slides.md`)**: A specialized prompt to turn your dictated brain dump into a 7-slide deck.
    *   *Use when:* You've just had a strategic epiphany and want your team to build the deck.

---

## 📚 Resources & Files

*   **[Daily Prompts](./daily/)**: Prompts for daily executive routines.
*   **[Weekly Prompts](./weekly/)**: Prompts for weekly planning and review.
*   **[Monthly Prompts](./monthly/)**: Prompts for monthly governance and reporting.
*   **[Quarterly Prompts](./quarterly/)**: Prompts for strategic planning.
*   **[Meeting Prompts](./meetings/)**: Prompts for meeting preparation and summaries.
*   **[On-Demand Prompts](./on-demand/)**: Specialized prompts for data analysis and presentations.
*   **[`gtd_guide.md`](./gtd_guide.md)**: A deep dive into the "Getting Things Done" methodology that powers these workflows. Read this to understand the *theory* of systematic productivity.
*   **[Processed Archives](./processed/)**: Original prompt files.

INCIDENT_NAME = USER_INPUT_REQUIRED
DATE = USER_INPUT_REQUIRED
STAKEHOLDERS = USER_INPUT_REQUIRED

# INCIDENT POST-MORTEM & ROOT CAUSE ANALYSIS PROMPT

**GOAL:** Facilitate a comprehensive, blameless post-mortem review for the incident: <INCIDENT_NAME>.

## SEARCH INSTRUCTIONS
Systematically search through my **Emails**, **Teams/Slack Chats**, and **Recent Documents** (Incident Tickets, Status Pages, Logs).
- Look for the initial alert time, escalation path, resolution steps, and root cause discussions related to <INCIDENT_NAME>.
- Identify key stakeholders involved and any customer communications sent.

<DEEP_THINKING>
Please use Deep Thinking mode.

CHAIN OF THOUGHT GUIDANCE:
1.  **Construct Timeline:** Reconstruct the exact sequence of events from detection to resolution. Identify the "Time to Detect" (TTD) and "Time to Resolve" (TTR).
2.  **Determine Root Cause:** Apply the "5 Whys" methodology to dig beyond surface-level symptoms to the underlying technical or process failure. explicitly check if Technical Debt was a contributing factor.
3.  **Assess Impact:** Quantify the impact on customers (outage duration, affected users), financials (SLA credits, lost revenue), and reputation.
4.  **Detect Risks:** Explicitly scan for compliance breaches, data privacy issues (PII exposure), or regulatory reporting triggers.
5.  **Formulate Actions:** Define specific, assignable action items to prevent recurrence (Preventative) and improve detection (Detective).
</DEEP_THINKING>

## OUTPUT FORMAT

### 1. Executive Overview
(1-2 sentences summarizing the incident's impact, root cause, and the primary preventative measure being implemented.)

### 2. Summary Table
| Metric | Value | Notes |
| :--- | :--- | :--- |
| Impact Severity | [High/Medium/Low] | [Description] |
| Time to Detect (TTD) | [Duration] | [Source] |
| Time to Resolve (TTR) | [Duration] | [Source] |
| Root Cause Category | [Code/Config/Process/Vendor] | [Detail] |

### 3. Detailed Results

**Incident Timeline:**
- **[Time]** - Issue Start/Detection.
- **[Time]** - Escalation to [Team].
- **[Time]** - Mitigation applied.
- **[Time]** - Full Resolution.

**Root Cause Analysis (5 Whys):**
1.  Why did the system fail? [Answer]
2.  Why did [Previous Answer] happen? [Answer]
3.  Why did [Previous Answer] happen? [Answer]
4.  Why did [Previous Answer] happen? [Answer]
5.  **Root Cause:** [Fundamental Issue]

**Contributing Factors:**
- **Technical Debt:** [Was existing debt a factor?]
- **Process Gaps:** [Was a process missing or ignored?]
- **Vendor Dependency:** [Was a third-party service involved?]

**Impact Assessment:**
- **Customer Impact:** [Details]
- **Financial/Legal Risk:** [Details]
- **Data Integrity/Compliance:** [Check for data loss or privacy breaches]
- **Regulatory Reporting:** [Required/Not Required]

**Action Plan (Preventative & Detective):**
| Action Item | Type | Owner | Deadline | Jira/Ticket |
| :--- | :--- | :--- | :--- | :--- |
| [Action 1] | Preventative | [Owner] | [Date] | [ID] |
| [Action 2] | Detective | [Owner] | [Date] | [ID] |
| [Action 3] | Process | [Owner] | [Date] | [ID] |

**Lessons Learned:**
- **What went well:** [Successes]
- **What needs improvement:** [Failures/Gaps]

**Communication Cascades:**
- Stakeholders to update: [List]
- Public/Customer messaging required: [Yes/No]

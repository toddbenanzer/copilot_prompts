MEETING_NAME = USER_INPUT_REQUIRED
DATE = USER_INPUT_REQUIRED

# EXECUTIVE MEETING SUMMARY PROMPT

**GOAL:** Generate a structured summary from the provided meeting transcript/recording for <MEETING_NAME>.

## SEARCH INSTRUCTIONS
- Analyze the meeting transcript/recording.
- Cross-reference with **Emails**, **Teams/Slack Chats**, and **Recent Documents** if specific context or background information is referenced in the meeting but not fully explained.

<DEEP_THINKING>
Please use Deep Thinking mode.

CHAIN OF THOUGHT GUIDANCE:
1.  **Review Transcript:** Meticulous read-through to capture all discussion points, identifying who said what.
2.  **Identify Key Elements:** Distinguish between general discussion, firm decisions, and specific action items.
3.  **Contextualize:** Detailed check against recent communications (emails/chats) to ensure accurate assignment of owners and deadlines.
4.  **Synthesize:** Summarize complex discussions into clear, actionable points.
5.  **Format:** Specific alignment with the output structure below.
</DEEP_THINKING>

## OUTPUT FORMAT

### 1. Executive Overview
(Provide a 1-2 sentence summary of the meeting's main outcome and the general sentiment.)

### 2. Summary Table
| Item Type | Description | Owner | Deadline |
| :--- | :--- | :--- | :--- |
| Decision | [Decision Details] | [Decision Maker/Team] | N/A |
| Action Item | [Action Details] | [Owner] | [Date] |
| Risk | [Risk Details] | [Owner] | [Date] |

### 3. Detailed Results

**EMAIL SUBJECT:** <MEETING_NAME> - Decisions & Actions - <DATE>

**Decision Audit Log:**
| Decision | Rationale | Alternatives Considered | Decision Maker |
| :--- | :--- | :--- | :--- |
| [Decision Description] | [Rationale] | [Alternatives] | [Name] |

**Action Items:**
| Task | Owner | Deadline | Dependencies | Success Criteria |
| :--- | :--- | :--- | :--- | :--- |
| [Task Description] | [Owner] | [Deadline] | [Dependencies] | [Success Criteria] |

**Data Limitations & Confidence Scores:**
- Data Limitations: [Description of any data gaps or limitations discussed]
- Confidence Score: [High/Medium/Low] (based on the completeness of information)

**Follow-Up Required:**
- Next meeting: Date/Time.
- Preparation needed: [Document/Analysis Type].

**Parking Lot:**
- Items for future discussion.
- Unresolved questions.

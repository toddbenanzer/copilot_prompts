# EXECUTIVE MEETING SUMMARY PROMPT

**GOAL:** Generate a structured summary from the provided meeting transcript/recording for <MEETING_NAME>.

## SEARCH INSTRUCTIONS
- Analyze the meeting transcript/recording.
- Cross-reference with **Emails**, **Teams/Slack Chats**, and **Recent Documents** if specific context or background information is referenced in the meeting but not fully explained.

## CHAIN OF THOUGHT GUIDANCE
1.  **Review Transcript:** Meticulous read-through to capture all discussion points, identifying who said what.
2.  **Identify Key Elements:** Distinguish between general discussion, firm decisions, and specific action items.
3.  **Contextualize:** Detailed check against recent communications (emails/chats) to ensure accurate assignment of owners and deadlines if they were discussed previously or if context is missing.
4.  **Synthesize:** Summarize complex discussions into clear, actionable points.
5.  **Format:** Specific alignment with the output structure below.

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

**Key Decisions:**
- <AREA_1> priority changes.
- <RESOURCE_TYPE>/resource approvals.
- <COMPLIANCE_TYPE> requirements.

**Action Items:**
| Task | Owner | Deadline | Dependencies | Success Criteria |
| :--- | :--- | :--- | :--- | :--- |
| [Task 1] | [Owner] | [Deadline] | [Deps] | [Criteria] |

**Follow-Up Required:**
- Next meeting: Date/Time.
- Preparation needed: <DOCUMENT_TYPE>/Analysis.

**Parking Lot:**
- Items for future discussion about <TOPIC_AREA>.
- Unresolved <QUESTION_TYPE> questions.

---
**IMPORTANT:** Use **Deep Thinking** mode to ensure accuracy in capturing decisions and action items.

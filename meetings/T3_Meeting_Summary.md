MEETING_NAME = USER_INPUT_REQUIRED
DATE = USER_INPUT_REQUIRED

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
(List the top decisions made during the meeting, categorized by area or priority.)
- [Decision 1]
- [Decision 2]
- [Decision 3]

**Action Items:**
| Task | Owner | Deadline | Dependencies | Success Criteria |
| :--- | :--- | :--- | :--- | :--- |
| [Task] | [Owner] | [Deadline] | [Dependencies] | [Criteria] |

**Follow-Up Required:**
(Identify any required follow-ups, such as the next meeting or preparation needed.)
- Next meeting: [Date/Time/TBD]
- Preparation needed: [Documents/Analysis]

**Parking Lot:**
(List any topics that were tabled for future discussion or questions that remained unresolved.)
- [Topic 1]
- [Unresolved Question]

---
**IMPORTANT:** Use **Deep Thinking** mode to ensure accuracy in capturing decisions and action items.

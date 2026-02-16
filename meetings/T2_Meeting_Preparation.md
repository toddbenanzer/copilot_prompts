MEETING_NAME = USER_INPUT_REQUIRED
STAKEHOLDER_NAME = USER_INPUT_REQUIRED
TOPIC_AREA = USER_INPUT_REQUIRED
PROJECT_NAME = USER_INPUT_REQUIRED
TIME_PERIOD = USER_INPUT_REQUIRED
METRIC_1 = USER_INPUT_REQUIRED
METRIC_2 = USER_INPUT_REQUIRED
STATUS_METRIC = USER_INPUT_REQUIRED
INSIGHT_TYPE = USER_INPUT_REQUIRED
RECOMMENDATION_TYPE = USER_INPUT_REQUIRED
REQUEST_TYPE = USER_INPUT_REQUIRED
TOPIC_1 = USER_INPUT_REQUIRED
TOPIC_2 = USER_INPUT_REQUIRED

# EXECUTIVE MEETING PREPARATION PROMPT

**GOAL:** Prepare a comprehensive briefing for the upcoming meeting: <MEETING_NAME> with <STAKEHOLDER_NAME>.

## SEARCH INSTRUCTIONS
Systematically search through my **Emails**, **Teams/Slack Chats**, and **Recent Documents** (Word, PDF, PowerPoint, Excel).
- Look for key themes, unresolved issues, recent decisions, and action items related to <TOPIC_AREA> or <PROJECT_NAME>.
- Prioritize information from the last <TIME_PERIOD>.

## CHAIN OF THOUGHT GUIDANCE
1.  **Analyze Context:** Identify the primary purpose of the meeting and the key stakeholders involved.
2.  **Gather Information:** Scan communications and documents for recent updates, blockers, or changes in direction. Look for discrepancies between what was promised and what was delivered.
3.  **Synthesize:** Connect dots between different sources (e.g., an email mention of a delay vs. a chat discussion about a workaround).
4.  **Anticipate:** Based on the gathered info, predict potential questions or concerns the stakeholder might have.
5.  **Structure:** Organize the findings into the requested format below.

## OUTPUT FORMAT

### 1. Executive Overview
(Provide a 1-2 sentence high-level summary of the current status and the most critical point to discuss.)

### 2. Summary Table
| Category | Key Insight/Status | Source (Email/Chat/Doc) |
| :--- | :--- | :--- |
| Recent Update | [Insight] | [Source] |
| Blocker/Risk | [Insight] | [Source] |
| Key Metric | [Insight] | [Source] |

### 3. Detailed Results

**Context & Background:**
- Summary of previous meeting outcomes from <TIME_PERIOD>.
- Key takeaways from recent chat discussions about <TOPIC_AREA>.
- Highlights from shared documents/files related to <PROJECT_NAME>.

**Relevant Metrics:**
- Current <METRIC_1>: X%
- <METRIC_2>: $X
- <STATUS_METRIC>: Green/Yellow/Red

**Talking Points:**
1. <INSIGHT_TYPE> insight with supporting data.
2. <RECOMMENDATION_TYPE> recommendation.
3. <REQUEST_TYPE> request/issue.

**Likely Questions & Answers:**
- **Q:** Question about <TOPIC_1>?
- **A:** Prepared answer based on data.
- **Q:** Question about <TOPIC_2>?
- **A:** Prepared answer based on data.

---
**IMPORTANT:** Use **Deep Thinking** mode to ensure thorough analysis and connection of disparate information points.

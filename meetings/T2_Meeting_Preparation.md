MEETING_NAME = USER_INPUT_REQUIRED
STAKEHOLDER_NAME = USER_INPUT_REQUIRED
TIME_PERIOD = USER_INPUT_REQUIRED

# EXECUTIVE MEETING PREPARATION PROMPT

**GOAL:** Prepare a comprehensive briefing for the upcoming meeting: <MEETING_NAME> with <STAKEHOLDER_NAME>.

## SEARCH INSTRUCTIONS
Systematically search through my **Emails**, **Teams/Slack Chats**, and **Recent Documents** (Word, PDF, PowerPoint, Excel).
1.  **Identify Topic:** Based on the <MEETING_NAME> and <STAKEHOLDER_NAME>, infer the primary topic or project associated with this meeting.
2.  **Execute Search:** Look for key themes, unresolved issues, recent decisions, and action items related to the identified topic/project.
3.  **Prioritize:** Focus on information from the last <TIME_PERIOD>.

## CHAIN OF THOUGHT GUIDANCE
1.  **Analyze Context:** Identify the primary purpose of the meeting and the key stakeholders involved.
2.  **Gather Information:** Scan communications and documents for recent updates, blockers, or changes in direction. Look for discrepancies between what was promised and what was delivered.
3.  **Identify Metrics:** Search for the most relevant quantitative data (KPIs, budget, timeline progress) associated with the inferred topic.
4.  **Synthesize:** Connect dots between different sources (e.g., an email mention of a delay vs. a chat discussion about a workaround).
5.  **Anticipate:** Based on the gathered info (especially blockers or risks), predict the top 2-3 questions the stakeholder is likely to ask.
6.  **Structure:** Organize the findings into the requested format below.

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
- Summary of previous meeting outcomes regarding the inferred topic.
- Key takeaways from recent chat discussions and shared documents.

**Relevant Metrics:**
(Identify and list the top 3 critical metrics found in the search results, such as completion %, budget status, or performance KPIs.)
- [Metric Name]: [Value]
- [Metric Name]: [Value]
- [Metric Name]: [Value]

**Talking Points:**
(Generate 3 strategic talking points based on the findings.)
1. **Insight:** [Key observation backed by data]
2. **Recommendation:** [Proposed action or decision]
3. **Request/Issue:** [Resource need or blocker removal]

**Likely Questions & Answers:**
(Predict 2 tough questions the stakeholder might ask and provide data-backed answers.)
- **Q:** [Predicted Question 1]
- **A:** [Prepared Answer]
- **Q:** [Predicted Question 2]
- **A:** [Prepared Answer]

---
**IMPORTANT:** Use **Deep Thinking** mode to ensure thorough analysis and connection of disparate information points.

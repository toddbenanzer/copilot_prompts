MEETING_NAME = USER_INPUT_REQUIRED
STAKEHOLDER_NAME = USER_INPUT_REQUIRED
TIME_PERIOD = USER_INPUT_REQUIRED

# EXECUTIVE MEETING PREPARATION PROMPT

**GOAL:** Prepare a comprehensive briefing for the upcoming meeting: <MEETING_NAME> with <STAKEHOLDER_NAME>.

## SEARCH INSTRUCTIONS
Systematically search through my **Emails**, **Teams/Slack Chats**, and **Recent Documents** (Word, PDF, PowerPoint, Excel).
- Look for key themes, unresolved issues, recent decisions, and action items related to the meeting topic or <MEETING_NAME>.
- Prioritize information from the last <TIME_PERIOD>.

<DEEP_THINKING>
Please use Deep Thinking mode.

CHAIN OF THOUGHT GUIDANCE:
1.  **Analyze Context:** Identify the primary purpose of the meeting and the key stakeholders involved.
2.  **Gather Information:** Scan communications and documents for recent updates, blockers, or changes in direction. Look for discrepancies between what was promised and what was delivered.
3.  **Synthesize:** Connect dots between different sources (e.g., an email mention of a delay vs. a chat discussion about a workaround).
4.  **Anticipate:** Based on the gathered info, predict potential questions, counter-arguments, and technical terms that need definition.
5.  **Structure:** Organize the findings into the requested format below.
</DEEP_THINKING>

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
- Key takeaways from recent chat discussions about relevant topics.
- Highlights from shared documents/files related to the project.

**Relevant Metrics:**
- [Key Performance Metric 1]: [Value]
- [Key Financial/Operational Metric]: [Value]
- [Overall Status]: [Value] (e.g., Green/Yellow/Red)

**Talking Points & HiPPO Defense:**
1. [Key Insight] with supporting data (Data Anchoring).
2. [Strategic Recommendation].
3. [Critical Request/Issue].

**Devil's Advocate & Risk Analysis:**
- Potential counter-arguments to recommendations: [Counter-argument]
- Risk mitigation: [Mitigation]

**Likely Questions & Answers:**
- **Q:** Question about [Critical Topic 1]?
- **A:** Prepared answer based on data.
- **Q:** Question about [Critical Topic 2]?
- **A:** Prepared answer based on data.

**Data Literacy Check:**
- Definitions for technical terms/acronyms: [Term] - [Definition]

**Communication Cascades:**
- Stakeholders to update after this meeting: [Name/Team] - [Reason]

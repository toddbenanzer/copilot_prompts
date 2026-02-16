TIME_PERIOD = USER_INPUT_REQUIRED
FOCUS_AREA = USER_INPUT_REQUIRED
WORK_TYPE = USER_INPUT_REQUIRED
REGULATORY_TYPE = USER_INPUT_REQUIRED
EXECUTIVE_LEVEL = USER_INPUT_REQUIRED
CRITICAL_SYSTEM = USER_INPUT_REQUIRED
PRIMARY_METRIC = USER_INPUT_REQUIRED
STAKEHOLDER_TYPE = USER_INPUT_REQUIRED

Act as my Chief of Staff. Analyze my calendar for today, emails, chats, and recent documents from the last <TIME_PERIOD>.

<DEEP_THINKING>
Please use Deep Thinking mode.

CHAIN OF THOUGHT GUIDANCE:
1.  **Scan Inputs**: Review all provided inputs (calendar, emails, chats, documents) for the specified time period to gather context.
2.  **Identify Logistics**: Pinpoint immediate schedule requirements, including meeting times, locations, and potential conflicts.
3.  **Cross-Reference**: Match meeting topics with recent communications (emails, chats, docs) to identify necessary preparation materials or background context.
4.  **Triage**: Filter incoming requests based on urgency and sender importance (e.g., Executive leadership, Regulatory bodies). Prioritize items requiring immediate action.
5.  **Synthesize**: Combine these findings into a coherent briefing that highlights critical focus areas and potential risks.
</DEEP_THINKING>

OUTPUT FORMAT:
1.  **Executive Overview**: A 1-2 sentence high-level summary of the day's critical focus, major risks, and key priorities.
2.  **Summary Table**: A table with columns for Item, Source (Email/Chat/Doc), Urgency, and Action Required.
3.  **Detailed Results**: The comprehensive breakdown of the briefing as structured below.

DETAILED RESULTS:

DAILY BRIEFING:
- **First Focus:** Upcoming meetings with prep requirements for <FOCUS_AREA>.
- **Conflicts:** Any double bookings or travel issues?
- **Buffer:** When are my open blocks for <WORK_TYPE>?

URGENT TRIAGE (Action Today):
- <REGULATORY_TYPE>/compliance emails
- <EXECUTIVE_LEVEL> requests
- <CRITICAL_SYSTEM>/data issues

PRIORITY QUEUE (Review Later):
- <PRIMARY_METRIC> performance questions
- <STAKEHOLDER_TYPE> data requests
- Team escalations

For each urgent email: Sender | Subject | Proposed Action

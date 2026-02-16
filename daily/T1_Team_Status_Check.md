TEAM_NAME = USER_INPUT_REQUIRED
TIME_PERIOD = USER_INPUT_REQUIRED

Summarize <TEAM_NAME> team updates from past <TIME_PERIOD> across all channels (emails, chats, documents).

<DEEP_THINKING>
Please use Deep Thinking mode.

CHAIN OF THOUGHT GUIDANCE:
1.  **Aggregate Updates**: Gather information from all team channels (emails, chats, docs, status reports) for the specified period.
2.  **Assess Status**: Identify the current progress of key projects, noting ownership and completion metrics.
3.  **Detect Risks**: Explicitly look for data quality issues, compliance flags, or model risk concerns.
4.  **Identify Blockers**: Highlight any technical constraints, resource shortages, or missing stakeholder inputs hindering progress.
5.  **Pinpoint Decisions**: Isolate specific items where executive approval or prioritization decisions are required to move forward.
</DEEP_THINKING>

OUTPUT FORMAT:
1.  **Executive Overview**: 1-2 sentences summarizing the team's overall health, critical blockers, and urgent decisions needed.
2.  **Summary Table**: A table with columns for Project/Workstream, Owner, Status, and Key Issue/Blocker.
3.  **Detailed Results**: The comprehensive breakdown of the status check as structured below.

DETAILED RESULTS:

PIPELINE & DELIVERY:
Project | Owner | Status | % Complete | Next Milestone

DATA QUALITY & RISK:
- Data Integrity issues (ETL/Pipeline)
- Model Risk/Validation status
- Compliance/Privacy flags

BLOCKERS:
- Technical constraints (Cloud/Compute)
- Missing requirements from key stakeholders
- Resource bottlenecks

DECISIONS NEEDED:
- Methodology approvals
- Prioritization calls (Reg vs Comm)
- Resource allocation

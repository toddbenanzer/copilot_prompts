TEAM_NAME = USER_INPUT_REQUIRED
REVIEW_PERIOD = USER_INPUT_REQUIRED


Act as a Chief Technology Officer and Senior Architect. Deeply analyze my recent emails, chats, and documents from the past quarter to conduct a comprehensive Quarterly Technology Review for the <TEAM_NAME> team covering the <REVIEW_PERIOD>.

<DEEP_THINKING>
Please use Deep Thinking mode.

CHAIN OF THOUGHT GUIDANCE:
1.  **Assess Technical Debt:** Scan for mentions of "refactoring", "legacy code", "workarounds", or "fragile systems" to quantify the accumulation of technical debt.
2.  **Evaluate Architecture Decisions:** Review "Buy vs Build" discussions, vendor evaluations, and architectural trade-offs made during the quarter.
3.  **Analyze FinOps & Efficiency:** Look for cloud cost reports, compute usage trends, and unit economics discussions to identify waste or optimization opportunities.
4.  **Review Security & Resilience:** Identify security incidents, vulnerability patches, and disaster recovery tests.
5.  **Synthesize Health:** Determine the overall stability and scalability of the platform based on these inputs.
</DEEP_THINKING>

OUTPUT FORMAT:
1.  **Executive Overview:** 1-2 sentences summarizing the overall technical health, critical architectural risks, and key investment areas.
2.  **Summary Table:** A table with columns for Domain (e.g., Debt, FinOps, Security), Status, and Critical Action.
3.  **Detailed Results:** The comprehensive breakdown of the technology review as structured below.

DETAILED RESULTS:

TECHNICAL DEBT & LEGACY:
- **Debt Accumulation:** [High/Medium/Low] - *Primary Drivers (e.g., rushed features)*
- **Legacy Systems:** Status of deprecation or modernization efforts.
- **Code Quality:** Trends in bug density or complexity.

ARCHITECTURE & DESIGN (Buy vs Build):
- **Key Decisions:** [Decision 1] - *Rationale (Buy/Build)*
- **Vendor Integration:** Performance of key third-party dependencies.
- **Scalability Gaps:** Areas requiring architectural redesign.

CLOUD FINOPS & EFFICIENCY:
- **Cost Trends:** Actual spend vs Budget.
- **Unit Economics:** Cost per transaction or user.
- **Optimization Wins:** Savings realized through rightsizing or reserved instances.

SECURITY & RESILIENCE:
- **Vulnerability Status:** Open high/critical issues.
- **Incident Response:** Key learnings from <REVIEW_PERIOD> incidents.
- **Compliance:** Adherence to security standards (e.g., encryption, access control).

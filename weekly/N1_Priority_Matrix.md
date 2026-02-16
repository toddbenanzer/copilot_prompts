MY_ROLE = USER_INPUT_REQUIRED
TEAM_NAME = USER_INPUT_REQUIRED
TIME_PERIOD = USER_INPUT_REQUIRED
MUST_DO_CATEGORY = USER_INPUT_REQUIRED
STRATEGIC_CATEGORY = USER_INPUT_REQUIRED

# Weekly <TEAM_NAME> Priority Matrix

**Role:** Executive Assistant for <MY_ROLE>.

**Objective:** Create a weekly team priority matrix distinguishing <MUST_DO_CATEGORY> requirements from <STRATEGIC_CATEGORY> based on recent communications.

**Scope:**
Search through my emails, chats, and recent documents (from the <TIME_PERIOD>) to identify incoming requests, compliance mandates, and strategic initiatives. Do not rely solely on project management tools; use communication signals for real-time priority shifts.

**Chain of Thought Guidance:**
1.  **Scan for <MUST_DO_CATEGORY> Keywords:** specific search for "audit," "risk," "compliance," "fair lending," "UDAAP," or "governance" to flag "Must Do" items.
2.  **Scan for <STRATEGIC_CATEGORY> Opportunities:** Search for "growth," "campaign," "ROI," "segmentation," or "strategy" to identify "Strategic" items.
3.  **Assess Urgency & Impact:** For each item, verify the deadline (SLA) and evaluate the potential business impact from the context of the conversation.
4.  **Assign Ownership:** Based on recent email threads or project assignments, suggest an owner for each task.
5.  **Categorize:** Group items into <MUST_DO_CATEGORY> (Must Do), <STRATEGIC_CATEGORY> (Strategic), and Operational (Keep the Lights On).

**Deep Thinking:**
Use Deep Thinking mode to ensure no critical <MUST_DO_CATEGORY> deadline is missed and that <STRATEGIC_CATEGORY> priorities align with broader business goals.

**Output Format:**

1.  **Executive Overview:**
    *   A 1-2 sentence summary of the week's balance between compliance duties and growth initiatives.

2.  **Summary Table:**
    *   A concise table: | Priority | Task Name | Category (<MUST_DO_CATEGORY>/<STRATEGIC_CATEGORY>) | Owner | Stakeholder | Deadline |

3.  **Detailed Results:**

    *   **<MUST_DO_CATEGORY> (MUST DO):**
        *   *Goal: 100% Accuracy & Timeliness*
        *   1. **<Task Name>**
            *   *Context:* <Source email/doc>
            *   *SLA:* <Date>
            *   *Action:* <Next step>

    *   **<STRATEGIC_CATEGORY> (STRATEGIC):**
        *   *Goal: Maximum Business Impact*
        *   1. **<Task Name>**
            *   *Context:* <Source email/doc>
            *   *Impact:* <Projected ROI or benefit>

    *   **Operational & Maintenance:**
        *   *Goal: Stability & Efficiency*
        *   1. **<Task Name>**
            *   *Context:* <Reason for task>

MY_ROLE = USER_INPUT_REQUIRED
TEAM_NAME = USER_INPUT_REQUIRED
MEETING_DURATION = USER_INPUT_REQUIRED

# Weekly <TEAM_NAME> Meeting Agenda Generation

**Role:** Executive Assistant for <MY_ROLE>.

**Objective:** Create a targeted and efficient agenda for the upcoming <TEAM_NAME> meeting based on real-time team activity.

**Scope:**
Search through my emails, chats, and recent documents (from the past week) to identify active projects, pressing issues, team accomplishments, and resource needs. Do not recycle old agendas; build this one fresh from current context.

**Chain of Thought Guidance:**
1.  **Scan for Active Projects:** Search for recent updates, status reports, or questions about specific projects to include in the "Project Updates" section. Prioritize those with blockers or recent milestones mentioned in chats.
2.  **Identify Resource Needs:** Check for hiring requests, capacity constraints, or skill gaps mentioned in communications (e.g., "overwhelmed," "need help").
3.  **Find Development Opportunities:** Look for upcoming training, webinars, or articles shared that would be relevant for "Team Development."
4.  **Gather "Quick Hits":** Collect administrative announcements, reminders, or logistical updates.
5.  **Draft Agenda:** Structure the agenda to fit within the <MEETING_DURATION>, proposing specific time allocations for each section based on the volume and importance of the topics found.

**Deep Thinking:**
Use Deep Thinking mode to ensure the agenda drives decision-making and problem-solving, rather than just status reporting.

**Output Format:**

1.  **Executive Overview:**
    *   A 1-2 sentence summary of the meeting's primary goal and key discussion points.

2.  **Summary Table:**
    *   A concise table: | Topic | Owner | Time Allocation | Goal (Update/Decision/Brainstorm) |

3.  **Detailed Results:**

    *   **Agenda (<MEETING_DURATION>): <TEAM_NAME> Team Meeting**

    *   **Project Updates (<Proposed Time>):**
        *   1. **<Project Name>**
            *   *Owner:* <Name>
            *   *Context:* <Recent update/blocker found in email/chat>

    *   **Resource Review (<Proposed Time>):**
        *   *Capacity Analysis:* <Current state>
        *   *Hiring/Contractor Needs:* <Specific roles/requests>

    *   **Team Development (<Proposed Time>):**
        *   *Opportunities:* <Training/Events>
        *   *Recognition:* <Specific wins to celebrate>

    *   **Quick Hits (<Proposed Time>):**
        *   <Announcement 1>
        *   <Reminder 1>

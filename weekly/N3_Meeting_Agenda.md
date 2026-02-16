MY_ROLE = USER_INPUT_REQUIRED
TEAM_NAME = USER_INPUT_REQUIRED
MEETING_DURATION = USER_INPUT_REQUIRED
TIME_ALLOCATION_PROJECTS = USER_INPUT_REQUIRED
TIME_ALLOCATION_RESOURCES = USER_INPUT_REQUIRED
TIME_ALLOCATION_DEVELOPMENT = USER_INPUT_REQUIRED
TIME_ALLOCATION_ADMIN = USER_INPUT_REQUIRED

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
5.  **Draft Agenda:** Structure the agenda with clear time allocations based on the importance of each topic.

**Deep Thinking:**
Use Deep Thinking mode to ensure the agenda drives decision-making and problem-solving, rather than just status reporting.

**Output Format:**

1.  **Executive Overview:**
    *   A 1-2 sentence summary of the meeting's primary goal and key discussion points.

2.  **Summary Table:**
    *   A concise table: | Topic | Owner | Time Allocation | Goal (Update/Decision/Brainstorm) |

3.  **Detailed Results:**

    *   **Agenda (<MEETING_DURATION>): <TEAM_NAME> Team Meeting**

    *   **Project Updates (<TIME_ALLOCATION_PROJECTS>):**
        *   1. **<Project Name>**
            *   *Owner:* <Name>
            *   *Context:* <Recent update/blocker found in email/chat>

    *   **Resource Review (<TIME_ALLOCATION_RESOURCES>):**
        *   *Capacity Analysis:* <Current state>
        *   *Hiring/Contractor Needs:* <Specific roles/requests>

    *   **Team Development (<TIME_ALLOCATION_DEVELOPMENT>):**
        *   *Opportunities:* <Training/Events>
        *   *Recognition:* <Specific wins to celebrate>

    *   **Quick Hits (<TIME_ALLOCATION_ADMIN>):**
        *   <Announcement 1>
        *   <Reminder 1>

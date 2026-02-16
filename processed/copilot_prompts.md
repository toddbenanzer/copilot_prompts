# Microsoft Copilot Prompts: Tool-Based Organization & Implementation Calendar

## 📧 OUTLOOK EMAIL PROMPTS

### Daily Email Management

**Prompt E1: Executive Morning Start (Calendar + Email)**
```
TIME_PERIOD = USER_INPUT_REQUIRED

"Act as my Chief of Staff. Analyze my calendar for today and emails from the last <TIME_PERIOD>.

⏰ DAILY BRIEFING:
- **First Focus:** Upcoming meetings with prep requirements.
- **Conflicts:** Any double bookings or travel issues?
- **Buffer:** When are my open blocks?

🔴 URGENT TRIAGE (Action Today):
- Regulatory/compliance emails
- Executive requests
- Critical system/data issues

🟡 PRIORITY QUEUE (Review Later):
- Key performance questions
- Stakeholder data requests
- Team escalations

For each urgent email: Sender | Subject | Proposed Action"
```

**Prompt E2: Daily Closure and Tomorrow's Prep**
```
"Create my end-of-day email summary:

📋 COMPLETED TODAY:
- Key emails sent/decisions made
- Deliverables completed
- Issues resolved

⏰ TOMORROW'S EMAIL PRIORITIES:
- Emails requiring responses
- Follow-ups needed
- Reports to send

📧 DRAFT REMINDERS:
- Incomplete drafts to finish
- Scheduled sends to review"
```

**Prompt E3: Senior Leader Commitment Scan**
```
LEADERSHIP_LEVEL = USER_INPUT_REQUIRED
TIME_PERIOD = USER_INPUT_REQUIRED

"Review emails from <LEADERSHIP_LEVEL> leadership from the last <TIME_PERIOD>:

🔍 ACTIONABLE REQUESTS:
- Direct asks/tasks assigned to me
- Questions requiring my response
- Data/Information requests

📅 DEADLINES & MILESTONES:
- Specific dates mentioned
- Upcoming review meetings

🚩 IMPLIED EXPECTATIONS:
- 'Heads up' items requiring monitoring
- Strategic priorities mentioned

Table format: Request | Who | Deadline | Context/Urgency"
```

---

## 📅 OUTLOOK CALENDAR PROMPTS

### Daily & Weekly Planning

*(Note: Daily briefing is now combined with Email Triage in Prompt E1)*

**Prompt C2: Weekly Leadership Overview**
```
"Analyze my upcoming week's calendar:

📊 MEETING BREAKDOWN:
- Categorize meetings by type (e.g., Strategy, 1:1, Team, External) with hours and %.

🎯 HIGH-IMPACT MEETINGS:
Identify top 3-5 meetings requiring significant preparation or decision making.
1. <Meeting> - <Attendees> - <Prep needed>

⏱️ DEEP WORK BLOCKS:
- Available 1+ hour blocks for Deep Work
- Best times for Strategic thinking"
```

---

## 💬 MICROSOFT TEAMS PROMPTS

### Team Communication & Meeting Management

**Prompt T1: Analytics Team Pulse & Data Health**
```
TEAM_NAME = USER_INPUT_REQUIRED
TIME_PERIOD = USER_INPUT_REQUIRED

"Summarize <TEAM_NAME> team updates from past <TIME_PERIOD> across all channels:

📊 PIPELINE & DELIVERY:
Project | Owner | Status | % Complete | Next Milestone

🛡️ DATA QUALITY & RISK:
- Data Integrity issues (ETL/Pipeline)
- Model Risk/Validation status
- Compliance/Privacy flags

🚫 BLOCKERS:
- Technical constraints (Cloud/Compute)
- Missing requirements from Key Stakeholders
- Resource bottlenecks

⚡ DECISIONS NEEDED:
- Methodology approvals
- Prioritization calls (Reg vs Comm)
- Resource allocation"
```

**Prompt T2: Meeting Preparation**
```
MEETING_NAME = USER_INPUT_REQUIRED
STAKEHOLDER_NAME = USER_INPUT_REQUIRED
TIME_PERIOD = USER_INPUT_REQUIRED

"Prepare for <MEETING_NAME> with <STAKEHOLDER_NAME>:

📚 MEETING CONTEXT:
- Previous meeting outcomes from last <TIME_PERIOD>
- Recent chat discussions and shared documents related to the meeting topic

📈 RELEVANT METRICS:
- Identify key performance indicators and status metrics relevant to the discussion

💡 TALKING POINTS:
1. Key insights with supporting data
2. Strategic recommendations
3. Requests or issues to address

❓ LIKELY QUESTIONS:
- Anticipate 3 hard questions the stakeholder might ask and prepare answers"
```

**Prompt T3: Meeting Summary**
```
MEETING_NAME = USER_INPUT_REQUIRED

"Generate meeting summary from transcript/recording:

📧 EMAIL SUBJECT: <MEETING_NAME> - Decisions & Actions - [Date]

✅ KEY DECISIONS:
- Priority changes
- Resource approvals
- Compliance/Regulatory requirements

📋 ACTION ITEMS:
Task | Owner | Deadline | Dependencies | Success Criteria

📅 FOLLOW-UP REQUIRED:
- Next meeting timing
- Preparation/Analysis needed

🅿️ PARKING LOT:
- Items for future discussion
- Unresolved questions"
```

---

## 📝 ONENOTE PROMPTS

### Strategic Planning & Documentation

**Prompt N1: Banking Priority Matrix (Reg vs Growth)**
```
"Create weekly team priority matrix distinguishing Regulatory requirements from Commercial growth:

🏦 REGULATORY & COMPLIANCE (MUST DO):
- Audit/Risk findings
- Data Governance remediations
- Mandatory Reporting
*Goal: 100% Accuracy & Timeliness*

🚀 COMMERCIAL & GROWTH (STRATEGIC):
- Campaign Analytics for Key Products
- Customer Segmentation Models
- ROI/Performance Analysis
*Goal: Maximum Business Impact*

🔧 OPERATIONAL & MAINTENANCE:
- Data Pipeline stability
- Dashboard updates
- Ad-hoc requests

Visual Format: Priority | Category (Reg/Growth) | Owner | Stakeholder | Deadline"
```

**Prompt N2: Weekly Performance and Strategic Assessment**
```
"Create comprehensive weekly leadership review:

🏆 WINS & ACHIEVEMENTS:
- Quantified accomplishments with metrics

🔧 CHALLENGES & SOLUTIONS:
Challenge | Root Cause | Action Plan | Owner | Timeline

📊 STAKEHOLDER PULSE:
- Key Stakeholder Satisfaction and Feedback
- Partnership status updates

🎯 NEXT WEEK'S STRATEGIC FOCUS:
1. Key initiatives with success metrics"
```

**Prompt N3: Meeting Agenda Generation**
```
TEAM_NAME = USER_INPUT_REQUIRED
DURATION = USER_INPUT_REQUIRED

"Create <TEAM_NAME> meeting agenda (<DURATION> minutes):

📋 AGENDA: [Date] <TEAM_NAME> Team Meeting

🚀 PROJECT UPDATES:
- Status/Blockers for Key Projects

👥 RESOURCE REVIEW:
- Team capacity analysis
- Skill development needs
- Upcoming hiring/contractor needs

🎯 TEAM DEVELOPMENT:
- Training opportunities
- Recognition/celebrations
- Development discussions

⚡ QUICK HITS:
- Announcements
- Reminders
- Next meeting logistics"
```

**Prompt N4: Project Resource Optimization**
```
"Create team resource optimization analysis:

📊 CURRENT PROJECT DASHBOARD:
Project | % Complete | Team Members | Hours/Week | Target Completion

👥 TEAM CAPACITY ANALYSIS:
Team Member | Current Utilization % | Key Skills | Available Capacity

🔄 OPTIMIZATION RECOMMENDATIONS:
- Reallocation suggestions with rationale
- Skill development priorities with timeline

📈 TIMELINE IMPACTS:
- Projects that can be accelerated
- Projects requiring extension
- Resource bottlenecks and solutions"
```

**Prompt N5: Data Governance and Compliance Review**
```
"Generate monthly Data Governance & Compliance status report:

📊 COMPLIANCE DASHBOARD:
- Data Quality Score vs Target
- Validation Status
- Audit Readiness
- Privacy Compliance violations/resolutions

🚨 RISK INDICATORS:
Risk Type | Severity | Impact | Mitigation Status | Owner

⚡ IMMEDIATE ACTIONS REQUIRED:
- Action items with Deadlines and Owners

📈 TREND ANALYSIS:
- Month-over-month improvements
- Concerning patterns with action plans
- Regulatory updates affecting the business"
```

**Prompt N6: C-Suite Strategic Brief**
```
"Create a one-page strategic brief for Executive Audience (Non-Technical). Focus on financial impact and market position.

🎯 EXECUTIVE HEADLINES:
1. **Financial Impact:** Value realized from key initiatives
2. **Market Opportunity:** Potential ROI and growth areas
3. **Risk Mitigation:** Risks addressed and assets protected

📊 BUSINESS PERFORMANCE (Financials & Growth):
- Revenue/Cost vs Target
- Customer Acquisition/Retention Trends
- Market Share/Competitive Position

💡 DECISION REQUIRED:
- **Proposal:** Recommendation
- **Financial Benefit:** ROI estimate over timeline
- **Investment:** Cost (CAPEX/OPEX)

💰 RESOURCE ALLOCATION:
- Critical resource needs with business case"
```

**Prompt N7: ROI Report**
```
BUSINESS_FUNCTION = USER_INPUT_REQUIRED

"Generate comprehensive <BUSINESS_FUNCTION> ROI analysis:

📈 CHANNEL PERFORMANCE MATRIX:
Channel | Cost | Value | ROI % | Volume | Trend

🏆 INITIATIVE EFFECTIVENESS:
TOP PERFORMERS:
- Identify top 3 initiatives with ROI and key success factors

IMPROVEMENT NEEDED:
- Identify underperforming initiatives with action plans

💰 BUDGET OPTIMIZATION:
Current Allocation | Recommended | Expected Impact | Risk Level

⚖️ COMPLIANCE CONSIDERATIONS:
- Regulatory compliance status
- Monitoring results"
```

**Prompt N8: Strategy Development**
```
TECHNOLOGY_TYPE = USER_INPUT_REQUIRED
TIME_PERIOD = USER_INPUT_REQUIRED

"Develop <TIME_PERIOD> <TECHNOLOGY_TYPE> strategy roadmap:

🎯 CAPABILITY GAP ANALYSIS:
Current State | Target State | Priority | Effort Level

🛠️ TECHNOLOGY ROADMAP:
Phase 1 (Short-term): Foundation & Infrastructure
Phase 2 (Mid-term): Core Implementation
Phase 3 (Long-term): Advanced Capabilities

👥 TEAM DEVELOPMENT PLAN:
Team Member | Current Skills | Target Skills | Training Plan | Timeline

📊 SUCCESS METRICS BY PHASE:
Key Milestones | Target | Success Criteria | Risk Mitigation

💼 BUSINESS CASE:
- Investment Required: Total cost breakdown
- Expected Benefits: Quantified ROI and impact
- Risk Assessment: Likelihood and impact"
```

---

# 📅 IMPLEMENTATION CALENDAR

## Daily Routine

### Morning Startup (8:00-8:30 AM)
| Time | Tool | Prompt | Purpose |
|------|------|---------|---------|
| 8:00 AM | Outlook (Combined) | **E1: Executive Morning Start** | Unified briefing: Calendar + Inbox Triage |
| 8:20 AM | Outlook Email | **E3: Commitment Scan** | Track executive requests and asks |
| 8:25 AM | Teams | **T1: Team Status Check** | Catch up on overnight team activity |

### End of Day (5:30-6:00 PM)
| Time | Tool | Prompt | Purpose |
|------|------|---------|---------|
| 5:30 PM | Outlook Email | **E2: Daily Closure** | Prepare for tomorrow and close loops |

## Weekly Routine

### Monday - Strategic Planning
| Time | Tool | Prompt | Purpose |
|------|------|---------|---------|
| 9:00 AM | Outlook Calendar | **C2: Weekly Leadership Overview** | Week planning and time optimization |
| 9:30 AM | OneNote | **N1: Priority Matrix** | Set weekly team priorities |
| 10:30 AM | OneNote | **N3: Meeting Agenda Generation** | Prepare for weekly team meeting |

### Wednesday - Mid-Week Check
| Time | Tool | Prompt | Purpose |
|------|------|---------|---------|
| 2:00 PM | OneNote | **N4: Resource Optimization** | Assess and adjust team capacity |

### Friday - Week Closure & Review
| Time | Tool | Prompt | Purpose |
|------|------|---------|---------|
| 3:00 PM | OneNote | **N2: Weekly Performance Assessment** | Review accomplishments and plan ahead |
| 4:00 PM | Teams | **T3: Meeting Summary** | Document key decisions from weekly meetings |

## Monthly Routine

### First Monday of Month
| Time | Tool | Prompt | Purpose |
|------|------|---------|---------|
| 10:00 AM | OneNote | **N5: Data Governance Review** | Monthly compliance and quality check |
| 11:00 AM | OneNote | **N6: Executive Brief** | Prepare monthly leadership report |

### Third Friday of Month
| Time | Tool | Prompt | Purpose |
|------|------|---------|---------|
| 2:00 PM | OneNote | **N7: ROI Report** | Generate monthly performance analysis |

## Quarterly Routine

### First Week of Quarter
| Time | Tool | Prompt | Purpose |
|------|------|---------|---------|
| All Day | OneNote | **N8: Strategy Development** | Quarterly strategic planning |

## Meeting-Based Prompts

### Before Any Important Meeting
| Timing | Tool | Prompt | Purpose |
|--------|------|---------|---------|
| 30 min before | Teams | **T2: Meeting Preparation** | Research and prep for stakeholder meetings |

### After Any Important Meeting
| Timing | Tool | Prompt | Purpose |
|--------|------|---------|---------|
| Within 2 hours | Teams | **T3: Meeting Summary** | Document decisions and action items |

---

# 🚀 IMPLEMENTATION PHASES

## Phase 1: Foundation (Week 1-2)
**Goal:** Establish daily routines
- Implement daily Outlook prompts (E1, E2, C1)
- Start with basic team status check (T1)
- Focus on consistency over perfection

## Phase 2: Weekly Rhythm (Week 3-4)
**Goal:** Add weekly strategic planning
- Add weekly calendar overview (C2)
- Implement priority matrix (N1) and meeting agendas (N3)
- Begin weekly performance reviews (N2)

## Phase 3: Advanced Planning (Week 5-6)
**Goal:** Full strategic implementation
- Add resource optimization (N4)
- Implement meeting preparation and summaries (T2, T3)
- Start monthly governance reviews (N5)

## Phase 4: Strategic Excellence (Week 7-8)
**Goal:** Complete productivity system
- Add executive briefings (N6)
- Implement ROI reporting (N7)
- Begin quarterly strategy development (N8)

---

# 📊 SUCCESS METRICS

## Daily Metrics
- **Email Response Time:** Target < 4 hours for urgent emails
- **Meeting Preparation:** 100% of meetings have pre-meeting brief
- **Daily Planning:** Morning briefing completed by 8:30 AM

## Weekly Metrics
- **Priority Clarity:** 90% of team priorities clearly defined
- **Resource Utilization:** Team capacity optimized weekly
- **Strategic Focus:** 3 clear strategic initiatives identified

## Monthly Metrics
- **Compliance Score:** 95%+ on governance reviews
- **Executive Satisfaction:** Positive feedback on monthly briefs
- **ROI Visibility:** Clear performance metrics for all initiatives

## Quarterly Metrics
- **Strategic Progress:** Measurable advancement on roadmap items
- **Team Development:** Skills advancement tracked and documented
- **Business Impact:** Quantified contribution to organizational goals

---

# ⚡ AUTOMATION RECOMMENDATIONS

## Outlook Automation
- **Schedule daily email triage** at 8:15 AM
- **Auto-reminder for daily closure** at 5:30 PM
- **Weekly calendar review** every Monday at 9:00 AM

## Teams Integration
- **Channel notifications** for urgent team updates
- **Meeting recording** auto-enabled for strategy sessions
- **Status update reminders** for project owners

## OneNote Organization
- **Template library** for quick prompt access
- **Linked notebooks** for cross-reference capabilities
- **Shared sections** for team collaboration

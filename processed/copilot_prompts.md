# Microsoft Copilot Prompts: Tool-Based Organization & Implementation Calendar

## 📧 OUTLOOK EMAIL PROMPTS

### Daily Email Management

**Prompt E1: Executive Morning Start (Calendar + Email)**
```
"Act as my Chief of Staff. Analyze my calendar for today and emails from the last <TIME_PERIOD>.

⏰ DAILY BRIEFING:
- **First Focus:** Upcoming meetings with prep requirements for <FOCUS_AREA>.
- **Conflicts:** Any double bookings or travel issues?
- **Buffer:** When are my open blocks for <WORK_TYPE>?

🔴 URGENT TRIAGE (Action Today):
- <REGULATORY_TYPE>/compliance emails
- <EXECUTIVE_LEVEL> requests  
- <CRITICAL_SYSTEM>/data issues

🟡 PRIORITY QUEUE (Review Later):
- <PRIMARY_METRIC> performance questions
- <STAKEHOLDER_TYPE> data requests
- Team escalations

For each urgent email: Sender | Subject | Proposed Action"
```

**Prompt E2: Daily Closure and Tomorrow's Prep**
```
"Create my end-of-day email summary:

📋 COMPLETED TODAY:
- Key emails sent/decisions made about <PRIMARY_FOCUS>
- <DELIVERABLE_TYPE> deliverables completed
- <ISSUE_TYPE> issues resolved

⏰ TOMORROW'S EMAIL PRIORITIES:
- <NUMBER> emails requiring responses
- Follow-ups needed for <PROJECT_CATEGORY>
- <REPORT_TYPE> reports to send

📧 DRAFT REMINDERS:
- Incomplete drafts about <TOPIC_AREA> to finish
- Scheduled sends to review"
```

**Prompt E3: Senior Leader Commitment Scan**
```
"Review emails from <EXECUTIVE_LEVEL> leadership from the last <TIME_PERIOD>:

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

**Prompt C2: Weekly <ROLE_TYPE> Leadership Overview**
```
"Analyze my upcoming week's calendar:

📊 MEETING BREAKDOWN:
- <CATEGORY_1>: X hours, Y%
- <CATEGORY_2>: X hours, Y% 
- <CATEGORY_3>: X hours, Y%
- <CATEGORY_4>: X hours, Y%
- <CATEGORY_5>: X hours, Y%

🎯 HIGH-IMPACT MEETINGS (Top <NUMBER>):
1. <Meeting> - <Attendees> - <Prep needed>
2. <Meeting> - <Attendees> - <Prep needed> 
3. <Meeting> - <Attendees> - <Prep needed>

⏱️ DEEP WORK BLOCKS:
- Available <MIN_DURATION>+ hour blocks for <PRIMARY_WORK>
- Best times for <THINKING_TYPE> thinking"
```

---

## 💬 MICROSOFT TEAMS PROMPTS

### Team Communication & Meeting Management

**Prompt T1: Analytics Team Pulse & Data Health**
```
"Summarize <TEAM_NAME> team updates from past <TIME_PERIOD> across all channels:

📊 PIPELINE & DELIVERY:
Project | Owner | Status | % Complete | Next Milestone

🛡️ DATA QUALITY & RISK:
- Data Integrity issues (ETL/Pipeline)
- Model Risk/Validation status
- Compliance/Privacy flags

🚫 BLOCKERS:
- Technical constraints (Cloud/Compute)
- Missing requirements from <STAKEHOLDER_TYPE>
- Resource bottlenecks

⚡ DECISIONS NEEDED:
- Methodology approvals
- Prioritization calls (Reg vs Comm)
- Resource allocation"
```

**Prompt T2: <STAKEHOLDER_TYPE> Meeting Preparation**
```
"Prepare for <MEETING_NAME> with <STAKEHOLDER_NAME>:

📚 MEETING CONTEXT:
- Previous meeting outcomes from <TIME_PERIOD>
- Recent chat discussions about <TOPIC_AREA>
- Shared documents/files related to <PROJECT_NAME>

📈 RELEVANT METRICS:
- Current <METRIC_1>: X%
- <METRIC_2>: $X
- <STATUS_METRIC>: Green/Yellow/Red

💡 TALKING POINTS:
1. <INSIGHT_TYPE> insight with supporting data
2. <RECOMMENDATION_TYPE> recommendation
3. <REQUEST_TYPE> request/issue

❓ LIKELY QUESTIONS:
- Question 1 about <TOPIC_1> → Prepared answer
- Question 2 about <TOPIC_2> → Prepared answer"
```

**Prompt T3: Meeting Summary with <INDUSTRY> Context**
```
"Generate meeting summary from transcript/recording:

📧 EMAIL SUBJECT: <MEETING_NAME> - Decisions & Actions - <DATE>

✅ KEY DECISIONS:
- <AREA_1> priority changes
- <RESOURCE_TYPE>/resource approvals
- <COMPLIANCE_TYPE> requirements

📋 ACTION ITEMS:
Task | Owner | Deadline | Dependencies | Success Criteria

📅 FOLLOW-UP REQUIRED:
- Next meeting: Date/Time
- Preparation needed: <DOCUMENT_TYPE>/Analysis

🅿️ PARKING LOT:
- Items for future discussion about <TOPIC_AREA>
- Unresolved <QUESTION_TYPE> questions"
```

---

## 📝 ONENOTE PROMPTS

### Strategic Planning & Documentation

**Prompt N1: Banking Priority Matrix (Reg vs Growth)**
```
"Create weekly team priority matrix distinguishing Regulatory requirements from Commercial growth:

🏦 REGULATORY & COMPLIANCE (MUST DO):
- Audit/Risk findings (SLA: <SLA_DATE>)
- Data Governance remediations
- Mandatory Reporting
*Goal: 100% Accuracy & Timeliness*

🚀 COMMERCIAL & GROWTH (STRATEGIC):
- Campaign Analytics for <PRODUCT_TYPE>
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
"Create comprehensive weekly <ROLE_TYPE> leadership review:

🏆 WINS & ACHIEVEMENTS:
- Quantified accomplishment 1 with <METRIC_TYPE> metrics
- Quantified accomplishment 2 with <METRIC_TYPE> metrics  
- Quantified accomplishment 3 with <METRIC_TYPE> metrics

🔧 CHALLENGES & SOLUTIONS:
Challenge | Root Cause | Action Plan | Owner | Timeline

📊 STAKEHOLDER PULSE:
- <STAKEHOLDER_1> Satisfaction: Feedback from recent interactions
- <STAKEHOLDER_2>: <FEEDBACK_TYPE>
- <STAKEHOLDER_3> Partnership: <COLLABORATION_STATUS>

🎯 NEXT WEEK'S STRATEGIC FOCUS:
1. <INITIATIVE_TYPE> initiative with <SUCCESS_TYPE> metrics
2. <INITIATIVE_TYPE> initiative with <SUCCESS_TYPE> metrics
3. <INITIATIVE_TYPE> initiative with <SUCCESS_TYPE> metrics"
```

**Prompt N3: <TEAM_NAME> Meeting Agenda Generation**
```
"Create <TEAM_NAME> meeting agenda (<DURATION> minutes):

📋 AGENDA: <DATE> <TEAM_NAME> Team Meeting

🚀 PROJECT UPDATES (<TIME_1> minutes):
- <PROJECT_1>: <Owner> - Status/Blockers
- <PROJECT_2>: <Owner> - Status/Blockers  
- <PROJECT_3>: <Owner> - Status/Blockers

👥 RESOURCE REVIEW (<TIME_2> minutes):
- Team capacity analysis
- <SKILL_TYPE> development needs
- Upcoming hiring/contractor needs

🎯 TEAM DEVELOPMENT (<TIME_3> minutes):
- <TRAINING_TYPE> opportunities
- Recognition/celebrations
- <DEVELOPMENT_TYPE> development discussions

⚡ QUICK HITS (<TIME_4> minutes):
- Announcements
- Reminders
- Next meeting logistics"
```

**Prompt N4: <TEAM_TYPE> Project Resource Optimization**
```
"Create team resource optimization analysis:

📊 CURRENT PROJECT DASHBOARD:
Project | % Complete | Team Members | Hours/Week | Target Completion

👥 TEAM CAPACITY ANALYSIS:
Team Member | Current Utilization % | Key Skills | Available Capacity

🔄 OPTIMIZATION RECOMMENDATIONS:
- Reallocation suggestion 1 for <PROJECT_TYPE> with rationale
- Reallocation suggestion 2 for <PROJECT_TYPE> with rationale
- <SKILL_TYPE> development priority with timeline

📈 TIMELINE IMPACTS:
- Projects that can be accelerated: List with new timelines
- Projects requiring extension: List with revised dates
- Resource bottlenecks: <BOTTLENECK_TYPE> and solutions"
```

**Prompt N5: Data Governance and <COMPLIANCE_TYPE> Review**
```
"Generate monthly <GOVERNANCE_TYPE> governance status report:

📊 COMPLIANCE DASHBOARD:
- <QUALITY_METRIC> Score: X% (Target: <TARGET>%)
- <VALIDATION_TYPE> Status: X of Y complete
- <AUDIT_TYPE> Readiness: Green/Yellow/Red
- <PRIVACY_TYPE> Compliance: X violations, Y resolved

🚨 RISK INDICATORS:
Risk Type | Severity | Impact | Mitigation Status | Owner

⚡ IMMEDIATE ACTIONS REQUIRED:
- Action 1 - <Deadline> - <Owner>
- Action 2 - <Deadline> - <Owner>

📈 TREND ANALYSIS:
- Month-over-month improvements: List
- Concerning patterns: List with action plans
- <REGULATORY_TYPE> updates affecting <BUSINESS_AREA>: Summary"
```

**Prompt N6: C-Suite Strategic Brief**
```
"Create a one-page strategic brief for <AUDIENCE_LEVEL> (Non-Technical Audience). Focus on financial impact and market position.

🎯 EXECUTIVE HEADLINES:
1. **Financial Impact:** $<VALUE> value realized from <INITIATIVE_TYPE>
2. **Market Opportunity:** <OPPORTUNITY_TYPE> with potential <ROI_TYPE>
3. **Risk Mitigation:** <RISK_TYPE> addressed, protecting <ASSET_TYPE>

📊 BUSINESS PERFORMANCE (Financials & Growth):
- <METRIC_1> (Revenue/Cost): Current vs Target
- <METRIC_2> (Customer): Acquisition/Retention Trends
- <METRIC_3> (Market): Share/Competitive Position

💡 DECISION REQUIRED:
- **Proposal:** <Recommendation>
- **Financial Benefit:** <ROI estimate> over <Timeline>
- **Investment:** <Cost> (CAPEX/OPEX)

💰 RESOURCE ALLOCATION:
- <RESOURCE_TYPE_1>: <Need> - <Business case>
- <RESOURCE_TYPE_2>: <Role> - <Impact on P&L>"
```

**Prompt N7: <BUSINESS_FUNCTION> ROI Report**
```
"Generate comprehensive <BUSINESS_FUNCTION> ROI analysis:

📈 <CHANNEL_TYPE> PERFORMANCE MATRIX:
Channel | <COST_METRIC> | <VALUE_METRIC> | ROI % | Volume | Trend

🏆 <INITIATIVE_TYPE> EFFECTIVENESS:
TOP PERFORMERS:
1. <INITIATIVE_NAME> - <ROI> - Key success factors
2. <INITIATIVE_NAME> - <ROI> - Key success factors
3. <INITIATIVE_NAME> - <ROI> - Key success factors

IMPROVEMENT NEEDED:
1. <INITIATIVE_NAME> - Issues - Action plan
2. <INITIATIVE_NAME> - Issues - Action plan

💰 BUDGET OPTIMIZATION:
Current Allocation | Recommended | Expected Impact | Risk Level

⚖️ COMPLIANCE CONSIDERATIONS:
- <COMPLIANCE_AREA_1> regulations: Status
- <COMPLIANCE_AREA_2> compliance: Assessment
- <MONITORING_TYPE> monitoring: Results"
```

**Prompt N8: <TECHNOLOGY_TYPE> Strategy Development**
```
"Develop <TIME_PERIOD> <TECHNOLOGY_TYPE> strategy roadmap:

🎯 CAPABILITY GAP ANALYSIS:
Current State | Target State | Priority | Effort Level

🛠️ TECHNOLOGY ROADMAP:
Phase 1 (<TIMEFRAME_1>): <INFRASTRUCTURE_TYPE> needs
Phase 2 (<TIMEFRAME_2>): <IMPLEMENTATION_TYPE> implementation 
Phase 3 (<TIMEFRAME_3>): <CAPABILITY_TYPE> capabilities

👥 TEAM DEVELOPMENT PLAN:
Team Member | Current Skills | Target Skills | Training Plan | Timeline

📊 SUCCESS METRICS BY PHASE:
<MILESTONE_1>: <Target> | Success Criteria | Risk Mitigation

💼 BUSINESS CASE:
- Investment Required: Total cost breakdown
- Expected Benefits: Quantified <BENEFIT_TYPE>
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

---

# 🎯 Template Customization Guide

## Common Placeholder Values

### Time-Related
- `<TIME_PERIOD>`: 24 hours, 48 hours, week, month
- `<TIMEFRAME>`: 48 hours, 72 hours, end of week
- `<TIME_WINDOW>`: 2 hours, 4 hours, morning, afternoon
- `<DURATION>`: 30, 45, 60, 90 minutes

### Team & Role
- `<TEAM_NAME>`: Marketing Analytics, Sales Operations, Product Development
- `<TEAM_TYPE>`: Analytics, Marketing, Sales, Operations
- `<ROLE_TYPE>`: Analytics, Marketing, Operations, Technical

### Business Context
- `<INDUSTRY>`: Banking, Healthcare, Retail, Technology
- `<BUSINESS_AREA>`: Analytics, Marketing, Sales, Operations
- `<PRIMARY_FOCUS>`: Analytics, Marketing, Sales, Operations

### Stakeholders
- `<STAKEHOLDER_TYPE>`: Internal, External, Client, Vendor
- `<EXECUTIVE_LEVEL>`: C-suite, VP, Director, Senior Management
- `<LEADERSHIP_LEVEL>`: Executive, Senior Management, C-suite

### Metrics & Performance
- `<PRIMARY_METRIC>`: Campaign, Product, Sales, Project
- `<METRIC_TYPE>`: Performance, Financial, Quality, Efficiency
- `<SUCCESS_TYPE>`: Performance, Quality, Efficiency, Impact

### Projects & Initiatives
- `<PROJECT_TYPE>`: Analytics, Development, Implementation, Research
- `<INITIATIVE_TYPE>`: Strategic, Operational, Technical, Process

This updated format with `<placeholder>` brackets makes it much clearer which elements need to be customized for your specific use case.

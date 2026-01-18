# Microsoft Copilot Prompts: Tool-Based Organization & Implementation Calendar

## 📧 OUTLOOK EMAIL PROMPTS

### Daily Email Management

**Prompt E1: Email Triage & Delegation Assistant**
```
"Analyze my emails from the last <TIME_PERIOD> and categorize for action:

🔴 URGENT (I must do):
- <REGULATORY_TYPE>/compliance emails
- <EXECUTIVE_LEVEL> requests
- <CRITICAL_SYSTEM>/data issues
*Security Check: Does that 'Urgent Wire Request' look real? Flag if suspicious.*

🟡 DELEGATE (Team Action):
- <STAKEHOLDER_TYPE> data requests -> Suggest Owner: <TEAM_MEMBER>
- Routine performance questions -> Suggest Owner: <TEAM_MEMBER>

🟢 FYIs & NOISE (Read later/Archive):
- Meeting confirmations
- General newsletters

Table Format: Sender | Subject | My Action (Do/Delegate) | Proposed Owner"
```

**Prompt E2: Daily Closure and Tomorrow's Prep**
```
"Create my end-of-day email summary:

🚨 INCIDENT & ESCALATION CHECK:
- Any P1/P2 incidents reported today?
- Missed SLA warnings
- Pipeline/Data failure notifications

🚀 CAMPAIGN LAUNCH GO/NO-GO:
- Launching Tomorrow: <CAMPAIGN_NAME>
- QA Sign-off: <YES/NO>
- Tracking/Tags Verified: <YES/NO>

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

🔍 REGULATORY & AUDIT PROMISES (Highest Priority):
- Commitments made to Regulators/Audit
- MRA remediation dates mentioned
- Policy acknowledgments

🏢 LEADERSHIP ASKS (Strategic):
- Direct asks from <EXECUTIVE_LEVEL>
- Board material requests
- "Heads up" items requiring monitoring

📅 DEADLINES:
- Hard Compliance Deadlines
- Soft Business Milestones

Table format: Request | Who | Deadline | Context/Urgency"
```

---

## 📅 OUTLOOK CALENDAR PROMPTS

### Daily & Weekly Planning

**Prompt C1: Logistics & Prep Check**
```
"Analyze my calendar for today/tomorrow:

⚠️ PREP GAPS (Action Required):
- Meetings with <EXECUTIVE_LEVEL> where I have 0 prep time scheduled
- Documents attached to upcoming meetings I haven't opened

⏱️ LOGISTICS & BUFFER:
- Back-to-back meetings with no transition time
- Travel time conflicts

📅 SCHEDULE OPTIMIZATION:
- Suggest moving <MEETING_TYPE> to create a 2-hour deep work block
- Flag meetings that can be shortened or delegated"
```

**Prompt C2: Weekly Leadership Overview (Run vs Change)**
```
"Analyze my upcoming week's calendar:

📊 RUN vs CHANGE ANALYSIS:
- **Run the Bank (RTB):** Routine status, ops, admin (Hours/%)
- **Change the Bank (CTB):** Strategy, innovation, projects (Hours/%)
- *Goal: >30% CTB*

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

**Prompt T1: Analytics Team Pulse & Agile Metrics**
```
"Summarize <TEAM_NAME> team updates from past <TIME_PERIOD> across all channels:

🏃 AGILE VELOCITY & DELIVERY:
Project | Velocity (vs Avg) | Blocked Stories | Sprint Burndown Status
*Focus: Are we shipping code or just attending meetings?*

🧪 EXPERIMENTATION VELOCITY:
- Experiments Live: <COUNT>
- Experiments Concluded this week: <COUNT>
- Win Rate %: <PERCENTAGE>

🛡️ DATA QUALITY & RISK:
- Data Integrity issues (ETL/Pipeline)
- Model Risk/Validation status
- Compliance/Privacy flags

🏭 VENDOR & MARTECH HEALTH:
- Adobe/Salesforce/Cloud Performance Issues
- Contract Renewals approaching
- Third-Party Risk Assessment status

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

📈 DATA & CONFIDENCE:
- Current <METRIC_1>: X% (Confidence: High/Med/Low)
- <METRIC_2>: $X
- Data Limitations: Known gaps or caveats in this data

🧠 DATA LITERACY CHECK:
- Terms to Define: "Statistical Significance", "Incrementality", "Attribution Window"
- Concept Check: "Does the audience understand Correlation != Causation here?"

💡 TALKING POINTS:
1. <INSIGHT_TYPE> insight with supporting data
2. <RECOMMENDATION_TYPE> recommendation
3. <REQUEST_TYPE> request/issue

⚓ HIPPO DEFENSE (Data Anchoring):
- If <SENIOR_LEADER> says "I feel...", I counter with "The data shows..."
- Pre-emptive Fact: <STATISTIC> that disproves common misconceptions.

😈 DEVIL'S ADVOCATE (Counter-Arguments):
- Strongest argument AGAINST my proposal: <ARGUMENT>
- My Rebuttal: <DATA_POINT>
- "What if we do nothing?" -> Impact Analysis

❓ LIKELY QUESTIONS:
- Question 1 about <TOPIC_1> → Prepared answer
- Question 2 about <TOPIC_2> → Prepared answer"
```

**Prompt T3: Meeting Summary & Decision Audit Log**
```
"Generate meeting summary from transcript/recording:

📧 EMAIL SUBJECT: <MEETING_NAME> - Decisions & Actions - <DATE>

📝 DECISION AUDIT LOG:
- **Decision 1:** <DECISION_DETAILS>
  - Rationale: <WHY>
  - Alternatives Considered: <ALTERNATIVES>
  - Approver: <NAME>

📢 COMMUNICATION CASCADE:
- Who needs to know? (Risk / Legal / Ops / Sales)
- Message: <DRAFT_BLURB>
- Channel: (Email / Teams Post / Town Hall)

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

**Prompt N2: Weekly Performance & Risk Review**
```
"Create comprehensive weekly <ROLE_TYPE> leadership review:

🏆 WINS & ACHIEVEMENTS:
- Quantified accomplishment 1 with <METRIC_TYPE> metrics
- Quantified accomplishment 2 with <METRIC_TYPE> metrics

📉 KEY RISK INDICATORS (KRIs):
- Model Performance: Drift/Degradation alerts
- Data Quality Scores: <METRIC_VALUE> (Trend)
- Operational Incidents: <COUNT>

⭐ TALENT & CULTURE PULSE:
- Recognition: Who went above and beyond? (Send 'Thank You' note)
- Burnout Watch: Who is working too many hours?
- Hiring: Key open roles status

🔧 CHALLENGES & SOLUTIONS:
Challenge | Root Cause | Action Plan | Owner | Timeline

📊 STAKEHOLDER PULSE:
- <STAKEHOLDER_1> Satisfaction: Feedback from recent interactions
- <STAKEHOLDER_2>: <FEEDBACK_TYPE>

🎯 NEXT WEEK'S STRATEGIC FOCUS:
1. <INITIATIVE_TYPE> initiative with <SUCCESS_TYPE> metrics
2. <INITIATIVE_TYPE> initiative with <SUCCESS_TYPE> metrics"
```

**Prompt N3: <TEAM_NAME> Meeting Agenda Generation**
```
"Create <TEAM_NAME> meeting agenda (<DURATION> minutes):

📋 AGENDA: <DATE> <TEAM_NAME> Team Meeting

🛡️ RISK & COMPLIANCE MOMENT (5 minutes):
- Review recent incidents/near-misses
- Upcoming regulatory deadlines
- Data privacy reminders

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

**Prompt N4: Resource Optimization & Talent Risk**
```
"Create team resource optimization analysis with focus on key person dependencies:

📊 CURRENT PROJECT DASHBOARD:
Project | % Complete | Team Members | Hours/Week | Target Completion

👥 TEAM CAPACITY & RISK:
Team Member | Utilization % | Key Skills | Flight Risk (Low/Med/High)
*Flag: Who is the only person who knows <CRITICAL_SYSTEM>?*

⚖️ LABOR MIX (FTE vs Contractor):
- Current Ratio: <RATIO> (Target: <TARGET>)
- Co-Employment Risk Flags: <LIST>
- Conversion candidates: <NAMES>

🌍 GLOBAL DELIVERY & HANDOVER:
- Onshore/Offshore Ratio: <RATIO>
- Handoff friction points: Are specs clear for the overnight team?
- Timezone Coverage gaps: <HOURS>

🔄 OPTIMIZATION RECOMMENDATIONS:
- Reallocation suggestion 1 for <PROJECT_TYPE> with rationale
- Reallocation suggestion 2 for <PROJECT_TYPE> with rationale

🎓 KNOWLEDGE TRANSFER NEEDS:
- Identify single points of failure
- Paired programming/Cross-training plan for <SKILL_TYPE>

📈 TIMELINE IMPACTS:
- Projects that can be accelerated: List with new timelines
- Projects requiring extension: List with revised dates"
```

**Prompt N5: Audit & Regulatory Readiness Review**
```
"Generate monthly Audit & Regulatory Readiness status report:

📊 AUDIT FINDINGS TRACKER:
- Open MRAs (Matters Requiring Attention): <COUNT>
- Findings approaching SLA breach: <LIST>
- Validation Evidence Status: Green/Yellow/Red

🛡️ REGULATORY REPORTING HEALTH:
- <REGULATORY_REPORT_NAME> Submission Status: On-Track/Risk
- Data Lineage Gaps identified: <COUNT>
- Key Controls Testing results: Pass/Fail %

⚡ REMEDIATION ACTIONS:
- Action 1 (Audit Finding #): <Owner> - <Deadline>
- Action 2 (Data Quality): <Owner> - <Deadline>

📈 RISK PROFILE TREND:
- Repeat findings count
- Emerging regulatory obligations for <BUSINESS_AREA>"
```

**Prompt N6: C-Suite Strategic Brief**
```
"Create a one-page strategic brief for <AUDIENCE_LEVEL> (Non-Technical Audience). Focus on financial impact and market position.

🎯 EXECUTIVE HEADLINES:
1. **Financial Impact:** $<VALUE> value realized from <INITIATIVE_TYPE>
2. **Market Opportunity:** <OPPORTUNITY_TYPE> with potential <ROI_TYPE>
3. **Risk Mitigation:** <RISK_TYPE> addressed, protecting <ASSET_TYPE>

🗣️ CUSTOMER TRUST & SENTIMENT:
- Complaint Trends: <UP/DOWN> (Top complaint: <TOPIC>)
- Trust Score (NPS/CSAT): <SCORE>
- *Regulation Check: Are we seeing UDAAP signals?*

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

**Prompt N7: Marketing ROI & Attribution Analysis**
```
"Generate comprehensive ROI analysis focusing on incrementality and lift:

📈 MMM & EXPERIMENTATION RESULTS:
Channel | MMM Contribution % | Incremental Lift (Experiment) | CPA (Blended vs Marginal)
*Insight: MMM vs Last-Click delta (Where are we over-crediting?)

🏆 CAMPAIGN PERFORMANCE:
1. <INITIATIVE_NAME>: <ROI> (attributed) vs <LIFT_METRIC> (experimental) - Conf Interval: <90/95>%
2. <INITIATIVE_NAME>: <ROI> (attributed) vs <LIFT_METRIC> (experimental) - Conf Interval: <90/95>%
*Key Insight: Which campaigns drove net-new customers?*

💰 BUDGET OPTIMIZATION (Marginal Returns):
- Diminishing Returns: Channels where next $1 is inefficient
- Opportunity: Channels with capacity for scale
- Recommendation: Shift $<AMOUNT> from <CHANNEL_A> to <CHANNEL_B>

🌪️ SCENARIO ANALYSIS (Sensitivity):
- If Rates +50bps: Impact on volumes?
- If Budget -10%: What gets cut?
- If Macro Slowdown: Impact on CAC?

⚖️ COMPLIANCE CONSIDERATIONS:
- <COMPLIANCE_AREA_1> regulations: Status
- <COMPLIANCE_AREA_2> compliance: Assessment
- <MONITORING_TYPE> monitoring: Results"
```

**Prompt N8: Banking Strategy Roadmap (Reg & Tech)**
```
"Develop <TIME_PERIOD> strategy roadmap aligning Tech capabilities with Regulatory needs:

🔭 REGULATORY HORIZON SCAN:
- Upcoming Regulations (e.g., AI Act, Basel): Impact Assessment
- Compliance Deadlines: <DATE>
- Required Capability Upgrades: <LIST>

🍪 FIRST-PARTY DATA STRATEGY:
- Cookie Deprecation Risk: High/Med/Low
- Identity Resolution Capabilty: <STATUS>
- Value Exchange: How are we getting customers to log in?

🎯 CAPABILITY GAP ANALYSIS:
Current State | Target State | Priority | Effort Level

⚖️ STRATEGIC ASSESSMENT (Buy vs Build):
- Capability: <CAPABILITY_NAME>
- Recommendation: <BUY/BUILD/PARTNER>
- Rationale: Time-to-market vs IP Control vs Cost
- Tech Debt Impact: Does this increase or decrease legacy load?

🤖 ETHICAL AI & FAIR LENDING IMPACT:
- Bias Testing: Have we tested for disparate impact?
- Explainability: Can we explain the model's decision to a regulator?
- UDAAP Risk: Does this strategy treat vulnerable populations fairly?

🛠️ TECHNOLOGY ROADMAP (Inc. Debt Paydown):
Phase 1 (<TIMEFRAME_1>): <INFRASTRUCTURE_TYPE> needs + Decommissioning <LEGACY_SYSTEM>
Phase 2 (<TIMEFRAME_2>): <IMPLEMENTATION_TYPE> implementation
Phase 3 (<TIMEFRAME_3>): <CAPABILITY_TYPE> capabilities

💰 CLOUD FINOPS & UNIT ECONOMICS:
- Compute Spend Forecast: <AMOUNT> (Trend: <UP/DOWN>)
- Cost per Model Inference: <COST> vs Target
- Optimization: Reserved Instances/Spot usage status

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
| 8:00 AM | Outlook Calendar | **C1: Executive Morning Briefing** | Daily planning and conflict resolution |
| 8:15 AM | Outlook Email | **E1: Email Triage** | Prioritize inbox for the day |
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

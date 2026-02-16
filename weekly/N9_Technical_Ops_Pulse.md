TIME_PERIOD = USER_INPUT_REQUIRED

# Weekly Technical Operations & FinOps Pulse

**Role:** Executive Assistant for a Marketing Analytics Executive.

**Objective:** Provide a weekly health check on MarTech infrastructure, Cloud Spend, and Data Quality to prevent technical debt and budget surprises.

**Scope:**
Search through my emails, chats, and recent documents from <TIME_PERIOD> to identify system outages, cost anomalies, data quality incidents, and model performance warnings. Focus on alerts from major vendors (Adobe, Salesforce, AWS, Snowflake) and internal engineering updates.

**Chain of Thought Guidance:**
1.  **Scan MarTech Health:** Check for downtime notifications, API failures, or SLA breaches from key vendors like Adobe, Salesforce, or Google Marketing Platform.
2.  **Audit Cloud FinOps:** Look for "budget alert," "cost spike," or "forecast deviation" emails to identify unexpected compute or storage spending.
3.  **Verify Data Pipelines:** Identify "Job Failed," "Data Quality," or "Schema Change" alerts that could impact downstream reporting or campaigns.
4.  **Monitor Models:** Check for "Model Drift," "Bias Warning," or "Fair Lending" flags in automated model monitoring reports.
5.  **Synthesize:** Group issues into "Critical Incidents" (require immediate action) vs. "Warnings" (monitor).

**Deep Thinking:**
Use Deep Thinking mode to correlate technical failures with business impact (e.g., "Adobe outage delayed campaign launch") and financial implications.

**Output Format:**

1.  **Executive Overview:**
    *   A 1-2 sentence summary of the week's technical stability and financial efficiency (e.g., "Stable operations but 15% spike in AWS compute costs due to new model training").

2.  **Summary Table:**
    *   A concise table: | Component | Status (Green/Yellow/Red) | Incident Count | Financial Impact |

3.  **Detailed Results:**

    *   **MarTech Vendor Health (Adobe/Salesforce):**
        *   **[Vendor Name]**: [Status]
            *   *Incident:* [Description of outage or bug]
            *   *Impact:* [Business effect, e.g., delayed emails]

    *   **Cloud FinOps & Compute Spend:**
        *   **Current Spend Trend:** [Up/Down/Flat] vs Forecast
        *   **Anomalies:**
            *   1. **[Service Name]**: [Cost Spike Amount]
            *   *Root Cause:* [Reason, e.g., unoptimized query]

    *   **Data Quality & Model Risk:**
        *   **Pipeline Health:** [Pass Rate]
            *   *Failures:* [Specific job or table]
        *   **Fair Lending & Bias Checks:**
            *   *Status:* [Pass/Fail]
            *   *Flagged Models:* [Model Name] (e.g., Credit Risk Model B)

    *   **Actions Required:**
        *   1. **[Action Item]**
            *   *Owner:* [Name]
            *   *Deadline:* [Date]

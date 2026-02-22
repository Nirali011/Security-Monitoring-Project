# Security Alert Workflow

This document explains how a security alert moves inside a company from detection to closure.

---

# Alert Workflow Process

Detection
   ↓
Alert Generated
   ↓
SOC Analyst Review
   ↓
Investigation
   ↓
Action Taken
   ↓
Incident Report
   ↓
Closure

---

# Step-by-Step Explanation

1️.Detection
-- Security logs are monitored using detection rules.
-- When suspicious activity is detected (ex: multiple failed logins), the system triggers an alert.

2️.Alert Generated
-- An alert is automatically created by the monitoring system.
-- The alert contains:
       - User information
       - IP address
       - Time of activity
       - Type of suspicious action

3️.SOC Analyst Review
-- A security analyst reviews the alert.
The analyst checks:
      - Log details
      - User activity
      - IP address behavior
      - Severity level

4️.Investigation
-- The analyst investigates the incident by analyzing related logs and patterns.
Goal:
     - Confirm whether it is a real threat or false alert.

5️.Action Taken
Based on severity, actions are performed:
    - Block suspicious IP
    - Reset password
    - Isolate affected system
    - Escalate to admin

6️.Incident Report
After handling the issue, a report is created containing:
    - What happened
    - Root cause
    - Actions taken
    - Final result

7️.Closure
Once the threat is resolved and system is safe, the incident is marked as closed.

# Example Using Project Logs

Example workflow:

- Multiple failed logins detected
- Alert generated
- Analyst reviews logs
- IP found suspicious
- IP blocked and password reset
- Incident documented
- Case closed

# Conclusion

A clear workflow helps security teams respond quickly and reduce risks.
Each step ensures proper monitoring, investigation, and resolution.
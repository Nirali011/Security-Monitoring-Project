# 🔐 Security Monitoring & Incident Response Project

# Project Overview

- This project simulates how a Security Operations Center (SOC) monitors system logs, detects suspicious activity, classifies incidents, and responds to security threats.

The goal of this project is to demonstrate practical understanding of:
- Log analysis
- Detection rule creation
- Incident classification
- Incident response
- Security alert workflow

# 📂 Project Structure

Security-Monitoring-Project/
                   │
                   ├── logs.txt
                   ├── detection_rules.md
                   ├── incident_response.md
                   ├── workflow.md
                   └── README.md

# Log Analysis Summary

Sample logs were analyzed to identify:
- Successful login activity
- Multiple failed login attempts
- Admin access at unusual hours
- Suspicious external IP access

Identified Suspicious Patterns:
- Multiple failed login attempts from IP: 192.168.2.3
- Admin login at 02:15 from IP: 45.10.2.6

# Detection Logic
 Custom detection rules were created to identify:
- Brute-force login attempts
- Admin access at odd hours
- External IP access to privileged accounts

These rules help generate alerts automatically when suspicious behavior occurs.

# Incident Classification

Incidents were classified into:

- 🟢 Low Severity (Single failed login)
- 🟡 Medium Severity (Multiple failed attempts)
- 🔴 High Severity (Admin login at odd hours from external IP)

Each severity level has defined response actions such as:

- Blocking IP
- Resetting passwords
- Isolating systems
- Escalating to administrators

# Security Alert Workflow

Detection → Alert Generated → Analyst Review → Investigation → Action Taken → Incident Report → Closure

This workflow reflects how real SOC teams handle security incidents.

# 🚀 Future Improvements

- SIEM integration
- Automated alert system
- Real-time dashboard monitoring
- IP reputation checking
- AI-based anomaly detection

#🎯 Conclusion

- This project demonstrates practical SOC analyst skills including log analysis, detection logic creation, incident handling, and structured documentation.

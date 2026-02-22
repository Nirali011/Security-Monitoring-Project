Detection_Rule 

1. Multiple Failed Login Alert 
Condition 
- IF same user has 3 failed logins within 5 minutes
  THEN generate alert

Alert Type 
- Suspicious Login Attempt

Why Important ?
- Helps detect brute-force attacks and protects user account 

2. Admin Login at odd Hours
Condition
- IF Admin login happens between 1AM - 5AM
  THEN flag as suspicious

Alert Type :
- High Risk Admin Activity

Why Important ?
- Admin access at unusual time may indicate unauthorized activity

3. External IP Access
Condition
- IF admin login comes from external IP
  THEN mark suspicious

Alert type
- Suspicious Access detected

Why Important ?
- External access can indicate possible account compromise
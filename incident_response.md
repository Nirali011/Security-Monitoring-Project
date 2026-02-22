 Incident Classification & Response

This document defines incident severity levels and response actions based on security log analysis.

---

## 🟢 Low Severity Incident

### Example
Single failed login attempt.

## Reason
A single failed login may happen due to user mistake (wrong password).  
No strong evidence of attack.

### Response Actions
- Monitor user activity
- Log the event
- Notify user if required

---

## 🟡 Medium Severity Incident

### Example
Multiple failed login attempts from same IP.

Example from logs:
IP: 192.168.2.3
Time: 09:05, 09:07, 09:10

### Reason
Repeated failed logins may indicate brute-force or password guessing attack.

### Response Actions
- Block suspicious IP temporarily
- Reset user password
- Review related logs
- Monitor for further activity

---

## 🔴 High Severity Incident

### Example
Admin login at odd hours from external IP.

Example from logs:
Time: 02:15
User: admin
IP: 45.10.2.6

### Reason
Admin account has high privileges.  
Login at unusual time from external IP may indicate unauthorized access.

### Response Actions
- Isolate affected system from network
- Block IP immediately
- Reset admin password
- Escalate to senior administrator / security team
- Perform detailed investigation

---

## Severity Summary Table

| Severity | Example | Action |
|------------|------------|----------|
| Low | Single failed login | Monitor |
| Medium | Multiple failed logins | Block IP + Reset Password |
| High | Admin odd-hour login | Isolate System + Escalate |

---

## Conclusion

Incidents are classified based on risk level, user privilege, and activity pattern.  
Proper response helps reduce security risks and protect systems.
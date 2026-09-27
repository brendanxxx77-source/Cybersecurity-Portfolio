# Suspicious Login Investigation

## Objective

Investigate suspicious authentication activity involving an administrative account.

## Tools

- VS Code
- Authentication logs
- Powershell
- Basic log analysis

## Findings

Three failed login attempts were followed by a successful login to the admin account from the same IP address.

## Risk

Medium

## Conclusion

The activity was considered suspicious and required further investigation.

## Skills Demonstrated

- Log analysis
- Identifying suspicious authentication activity
- Creating an incident timeline
- Risk assessment
- Incident documentation
- Security investigation
## Terminal Investigation

Used PowerShell in the VS Code terminal to search the authentication log.

Commands used:

Select-String "Failed password" "Evidence\login.log"

Select-String "Accepted password" "Evidence\login.log"

Select-String "203.0.113.25" "Evidence\login.log"

These commands were used to identify failed logins, successful logins, and activity associated with the suspicious IP address.
---

## Certifications

### Google Cybersecurity Professional Certificate

[View my verified Credly badge](https://www.credly.com/badges/e99c17f7-0294-41fb-90d2-77ed9e3e6bab)

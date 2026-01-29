# Incident Report


## Executive Summary
A suspected brute-force authentication attempt targeting a finance user account
was detected and investigated. No successful compromise occurred, and the
incident was escalated for preventative controls and monitoring.


## Incident ID
SOC-IR-001


## Date \& Time
2026-01-20 02:14 UTC


## Analyst Name
Martins Okonkwo


## Alert Source
SIEM


## Alert Name
Multiple Failed Login Attempts


## Severity (Confirmed)
Medium


## Description
The SIEM generated an alert after detecting multiple failed login attempts 
against a finance user account from a single external IP address within 
a short time frame.



## Affected Asset(s)
- Hostname:
- IP Address:
- User:


## Investigation Summary
The investigation identified repeated failed login attempts targeting a finance
department user account from an external IP address associated with suspicious
activity. The login attempts occurred outside normal business hours, and no
successful authentication was observed.


## Indicators of Compromise (IOCs)
- IP: 185.234.218.91
- Domain: N/A
- File Hash: N/A



## Findings
- Classification: True Positive
- Reasoning:
The pattern of repeated failed login attempts from a suspicious external IP,
targeting a sensitive user account outside business hours, is consistent with
brute-force authentication attempts.


## Actions Taken
- Reviewed SIEM alert details and authentication logs
- Analysed source IP reputation and activity pattern
- Verified no successful login occurred
- Flagged source IP for monitoring and potential blocking
- Escalated incident to Tier 2 SOC for further review


## Recommendation / Next Steps
- Temporarily block the source IP at the firewall or SIEM level
- Enforce account lockout policy for repeated failed login attempts
- Recommend password reset for the affected user account
- Monitor the account for further suspicious activity
- Review authentication logs for similar patterns across other users


## Final Status
Escalated


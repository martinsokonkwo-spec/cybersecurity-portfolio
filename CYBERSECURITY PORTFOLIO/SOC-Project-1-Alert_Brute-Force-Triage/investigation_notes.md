# Investigation Notes



## Alert Overview
- Alert Name: Multiple Failed Login Attempts
- Alert ID: 78421
- Time Detected: 2026-01-20 02:14 UTC
- Source IP: 185.234.218.91
- Target User: jdoe
- Target Host: FINANCE-PC-07



## Initial Analyst Questions
- Is the login failure pattern consistent with brute-force activity?
- Is the source IP internal or external?
- Has the user successfully logged in after the failures?
- Is this normal behaviour for this user or host?



## IP Reputation Analysis
- Source IP is associated with VPN or hosting services
- Previous reports of brute-force activity
- IP considered suspicious



## User \& Host Context
- Target user belongs to Finance department
- Login attempts occurred outside normal business hours
- No successful login following failed attempts
- Affected host handles sensitive financial information


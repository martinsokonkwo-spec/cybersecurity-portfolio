# Incident Response Playbook
(NIST SP 800-61 Aligned)

## 1. Purpose
This playbook defines the standardized process for detecting, analyzing,
containing, and responding to security incidents in alignment with the
NIST Incident Response framework.

## 2. Scope
This playbook applies to security incidents involving authentication abuse,
unauthorized access, and suspected account compromise.

## 3. Incident Categories
- Brute-force authentication attempts
- Credential compromise
- Privileged account misuse
- Unauthorized system access

## 4. Incident Response Phases

### 4.1 Preparation
- Maintain updated logging and monitoring systems
- Ensure account lockout and MFA policies are enforced
- Define escalation paths and contact lists
- Conduct regular SOC readiness reviews

### 4.2 Detection & Analysis
- Monitor SIEM alerts and authentication logs
- Validate alerts to identify true vs false positives
- Analyze user behavior, source IPs, and asset sensitivity
- Assign incident severity based on impact and likelihood

### 4.3 Containment, Eradication & Recovery
- Temporarily block malicious IP addresses
- Disable or reset compromised user accounts
- Isolate affected systems if required
- Restore systems to a secure operational state

### 4.4 Post-Incident Activity
- Document incident timeline and actions taken
- Conduct lessons learned review
- Update detection rules and controls
- Report findings to stakeholders


## 5. Example Incident Application

### 5.1 Brute-Force Authentication Attempt
- Detected via SIEM alert for multiple failed logins
- Analyzed source IP reputation and login behavior
- Classified as Medium severity
- Escalated for preventative controls and monitoring

### 5.2 Privileged Account Compromise
- Identified through log analysis showing successful login after failures
- Detected access to sensitive system files
- Classified as High severity
- Recommended account disablement and forensic investigation
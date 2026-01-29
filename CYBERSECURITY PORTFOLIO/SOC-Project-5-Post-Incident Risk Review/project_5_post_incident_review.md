# Project 5 — Post-Incident Risk Review

## 1. Incident Recap
The incident involved a successful phishing attack targeting employees, resulting in compromised credentials and unauthorized access to internal systems within a mid-sized financial services company.

## 2. Scope of Review
This post-incident review focuses on:
- The phishing attack vector and affected assets
- Security controls and their effectiveness
- Organizational response and incident handling
- Lessons learned to prevent recurrence

The review does not include unrelated security events or physical security breaches.

## 3. Incident Analysis

### 3.1 Event Timeline
1. Employees received phishing emails mimicking internal HR communications.
2. One employee clicked the link and entered credentials into a fake login portal.
3. Attackers gained unauthorized access to internal business applications.
4. The SOC team detected unusual login patterns and alerted the security team.
5. Access was revoked, passwords reset, and the incident was contained.

### 3.2 Root Cause Identification
The root causes of the incident include:
- Lack of sufficient phishing awareness and training for employees.
- Absence of enforced multi-factor authentication (MFA) on critical systems.
- Limited email monitoring for suspicious activity prior to the incident.

## 4. Effectiveness of Controls

### 4.1 Controls that Worked
- SOC monitoring detected unusual login patterns promptly.
- Incident response procedures were followed correctly, containing the attack.
- Credential revocation and password resets prevented further unauthorized access.

### 4.2 Controls Needing Improvement
- Multi-factor authentication (MFA) was not enforced on all critical systems.
- Email filtering and phishing detection could have prevented the initial compromise.
- Employee awareness training was insufficient to prevent the click on the phishing email.

### 4.3 Incident Response Evaluation
Overall, the incident response was effective in containing the breach quickly. However, the incident exposed gaps in preventive controls, particularly in user awareness and access management, which require remediation to reduce residual risk.

## 5. Lessons Learned

1. **Employee Awareness is Critical:** Phishing attacks remain a top threat vector. Continuous and targeted employee training is essential.
2. **Multi-Factor Authentication (MFA) is Non-Negotiable:** MFA significantly reduces the risk of credential compromise and should be enforced on all critical systems.
3. **Monitoring Needs to Be Proactive:** SOC monitoring was effective in detection, but earlier email filtering and threat intelligence could have prevented the incident.
4. **Incident Response Procedures Work but Require Regular Testing:** The response contained the breach, but regular tabletop exercises will improve readiness for future incidents.

## 6. Recommendations

- Enforce MFA across all internal systems and critical applications.
- Implement regular, simulated phishing exercises for employees.
- Enhance email filtering and threat detection systems.
- Conduct quarterly tabletop exercises and post-incident reviews.
- Update policies and procedures based on lessons learned to continuously improve security posture.
# Risk Assessment & Control Mapping

## 1. Scenario Overview
The organization is a mid-sized financial services company that relies heavily on email communication for internal and external operations. The company has experienced an increase in phishing emails targeting employees. One phishing attack was successful, resulting in compromised employee credentials and unauthorized access to internal systems.

## 2. Scope of Assessment
This risk assessment focuses on:
- Email systems
- Employee access credentials
- Internal business applications
- Security awareness and access control mechanisms

The assessment does not cover physical security or third-party vendor risks.

## 3. Asset Identification
The key assets affected by the phishing-related risk include:

- Employee email accounts used for internal and external communication
- User credentials (usernames and passwords)
- Internal business applications accessed via employee credentials
- Sensitive company and customer data stored within internal systems
- Organizational reputation and customer trust

## 4. Risk Description
Phishing attacks targeting employees pose a significant risk to the organization. If employees are deceived into providing their login credentials, attackers may gain unauthorized access to internal systems. This could lead to data breaches, financial loss, regulatory penalties, operational disruption, and reputational damage.

## 5. Risk Impact Assessment
If phishing attacks lead to credential compromise and unauthorized system access, the potential impacts include:

- Exposure of sensitive customer and financial data
- Financial losses due to fraud or incident response costs
- Regulatory penalties for non-compliance with data protection requirements
- Operational downtime during investigation and remediation
- Loss of customer confidence and reputational damage

Overall Impact Rating: High

## 6. Risk Likelihood Assessment
Phishing attacks are a common and persistent threat facing organizations, particularly in the financial sector. Given the frequency of phishing attempts and the reliance on employee email communication, the likelihood of phishing-related incidents occurring is considered high without additional mitigating controls.

Overall Likelihood Rating: High

## 7. Inherent Risk Evaluation
The inherent risk represents the level of risk before any security controls or mitigation measures are applied.

Given that both the impact and likelihood of the phishing-related risk are rated as high, the inherent risk level for this scenario is assessed as:

Inherent Risk Rating: High

This level of inherent risk indicates that the threat poses a serious concern to the organization and requires the implementation of appropriate security controls to reduce risk to an acceptable level.

## 8. Control Identification and Mapping (NIST CSF)

To reduce the inherent risk associated with phishing attacks and credential compromise, the following security controls are recommended. These controls are aligned with the NIST Cybersecurity Framework (CSF).

### Identify (ID)
- ID.AM-2: Identify and manage information systems, assets, and data associated with email and internal applications.
- ID.RA-1: Conduct regular risk assessments to identify phishing-related threats and vulnerabilities.

### Protect (PR)
- PR.AC-1: Implement strong access control policies, including the principle of least privilege.
- PR.AC-7: Enforce multi-factor authentication (MFA) for user access to internal systems.
- PR.AT-1: Provide regular security awareness and phishing training to employees.
- PR.DS-5: Protect data through appropriate safeguards to reduce exposure from credential compromise.

### Detect (DE)
- DE.CM-1: Monitor email systems and network traffic to detect phishing attempts and suspicious login activity.
- DE.AE-2: Analyze detected events to understand potential phishing incidents.

### Respond (RS)
- RS.RP-1: Execute incident response plans when phishing or credential compromise is detected.
- RS.CO-2: Ensure internal and external communication during incident response activities.

### Recover (RC)
- RC.RP-1: Implement recovery plans to restore systems and credentials affected by phishing incidents.
- RC.IM-1: Incorporate lessons learned from phishing incidents into continuous improvement efforts.

## 9. Residual Risk Assessment
After the implementation of the identified security controls, the likelihood of successful phishing attacks and credential compromise is expected to decrease. While phishing threats cannot be completely eliminated, the impact and likelihood of the risk are reduced through preventive, detective, and responsive measures.

Residual Risk Rating: Medium

This residual risk level is considered acceptable when balanced against the organization’s risk appetite and the cost of additional controls.

## 10. Risk Treatment Decision
Based on the residual risk assessment, the organization should adopt a risk mitigation strategy. This involves maintaining and continuously improving the implemented controls, particularly employee awareness training, access control mechanisms, and incident response readiness.

The risk will be monitored regularly, and further treatment actions will be considered if the risk level increases or if significant changes occur in the threat landscape.
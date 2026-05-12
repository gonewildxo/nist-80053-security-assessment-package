# Able Behavioral Health  
# Cybersecurity Risk Assessment Report

---

# Document Information

| Field | Value |
|---|---|
| Organization | Able Behavioral Health |
| Document Title | Cybersecurity Risk Assessment Report |
| Framework | NIST SP 800-30 / NIST SP 800-53 Rev. 5 |
| Classification | Confidential |
| Version | 1.0 |
| Author | Barron Williams |
| Assessment Date | May 11, 2026 |
| Review Cycle | Annual |

---

# 1. Executive Summary

Able Behavioral Health conducted a cybersecurity risk assessment to evaluate risks affecting the confidentiality, integrity, and availability of organizational systems and HIPAA-regulated Protected Health Information (PHI).

The assessment identified several cybersecurity risks impacting the organization’s hybrid healthcare environment, including phishing threats, ransomware exposure, remote access vulnerabilities, and endpoint security risks.

Overall, the organization demonstrates a moderate cybersecurity maturity level with opportunities for improvement in vulnerability management, user awareness, access management, and incident response readiness.

---

# 2. Assessment Objectives

The objectives of this assessment include:

- Identify cybersecurity threats and vulnerabilities
- Evaluate organizational security controls
- Assess risks to business operations and PHI
- Determine likelihood and impact of identified threats
- Recommend remediation strategies
- Support HIPAA and NIST compliance efforts

---

# 3. Scope

This assessment included the following systems and environments:

- Microsoft 365 environment
- Cloud-hosted Electronic Health Record (EHR) platform
- Windows 10 and Windows 11 endpoints
- VPN remote access infrastructure
- Network infrastructure devices
- Endpoint security solutions
- File storage systems
- Backup systems

---

# 4. Methodology

The assessment methodology was based on guidance from:

- NIST SP 800-30 Risk Assessment Guide
- NIST SP 800-53 Rev. 5
- HIPAA Security Rule safeguards
- Industry cybersecurity best practices

Assessment activities included:

- Asset identification
- Threat analysis
- Vulnerability identification
- Risk scoring
- Security control evaluation
- Review of organizational policies and procedures

---

# 5. Risk Rating Methodology

Risks were evaluated using likelihood and impact ratings.

## Likelihood Ratings

| Rating | Description |
|---|---|
| Low | Unlikely to occur |
| Medium | Possible occurrence |
| High | Likely to occur |

---

## Impact Ratings

| Rating | Description |
|---|---|
| Low | Minimal operational impact |
| Medium | Moderate operational disruption |
| High | Significant business or compliance impact |

---

## Risk Levels

| Likelihood | Impact | Risk Level |
|---|---|---|
| High | High | Critical |
| Medium | High | High |
| Medium | Medium | Moderate |
| Low | Medium | Low |

---

# 6. Threat Landscape Overview

The healthcare industry remains a high-value target for cybercriminal activity due to the sensitivity of patient information and operational reliance on technology systems.

Major threat categories affecting Able Behavioral Health include:

- Phishing attacks
- Ransomware
- Credential compromise
- Insider threats
- Third-party vendor compromise
- Malware infections
- Unauthorized remote access
- Data exposure incidents

---

# 7. Identified Risks

---

# Risk 1 — Phishing and Credential Theft

| Field | Description |
|---|---|
| Threat | Phishing Attacks |
| Vulnerability | User susceptibility to phishing emails |
| Affected Assets | Microsoft 365 Accounts |
| Likelihood | High |
| Impact | High |
| Risk Level | Critical |

## Description

Employees may be targeted through phishing campaigns designed to steal credentials or distribute malware.

## Potential Impact

- Unauthorized account access
- Data breaches
- Business email compromise
- Malware infection
- HIPAA violations

## Existing Controls

- MFA enabled
- Security awareness training
- Email filtering protections

## Recommendations

- Conduct simulated phishing exercises
- Expand user awareness training
- Improve email monitoring capabilities

---

# Risk 2 — Ransomware Infection

| Field | Description |
|---|---|
| Threat | Ransomware |
| Vulnerability | Endpoint compromise through malicious files |
| Affected Assets | Endpoints and file storage systems |
| Likelihood | High |
| Impact | High |
| Risk Level | Critical |

## Description

Healthcare organizations are frequent ransomware targets due to operational urgency and sensitive data holdings.

## Potential Impact

- Operational outages
- Loss of patient data access
- Regulatory penalties
- Financial losses

## Existing Controls

- Endpoint antivirus protection
- Backup procedures
- VPN security controls

## Recommendations

- Implement endpoint detection and response (EDR)
- Conduct backup restoration testing
- Improve patch management timelines

---

# Risk 3 — Weak Access Management

| Field | Description |
|---|---|
| Threat | Unauthorized Access |
| Vulnerability | Excessive user permissions |
| Affected Assets | Internal systems and PHI |
| Likelihood | Medium |
| Impact | High |
| Risk Level | High |

## Description

Users with unnecessary access permissions may increase risks related to insider threats or account compromise.

## Potential Impact

- Unauthorized PHI exposure
- Data manipulation
- Compliance violations

## Existing Controls

- Quarterly access reviews
- MFA implementation
- Role-based access controls

## Recommendations

- Strengthen least privilege enforcement
- Increase privileged access monitoring
- Conduct monthly privileged account reviews

---

# Risk 4 — Vulnerable Endpoints

| Field | Description |
|---|---|
| Threat | Exploitation of Unpatched Systems |
| Vulnerability | Delayed patch deployment |
| Affected Assets | Windows endpoints |
| Likelihood | Medium |
| Impact | High |
| Risk Level | High |

## Description

Unpatched systems may be vulnerable to known exploits and malware infections.

## Potential Impact

- Malware infections
- Data loss
- Remote compromise
- Operational disruption

## Existing Controls

- Patch management procedures
- Antivirus protections
- Vulnerability scanning

## Recommendations

- Reduce patch deployment timelines
- Automate patch management where feasible
- Increase vulnerability scanning frequency

---

# Risk 5 — Third-Party Vendor Risk

| Field | Description |
|---|---|
| Threat | Vendor Compromise |
| Vulnerability | Limited vendor security oversight |
| Affected Assets | Cloud services and shared data |
| Likelihood | Medium |
| Impact | Medium |
| Risk Level | Moderate |

## Description

Third-party vendors may introduce cybersecurity and compliance risks if security practices are insufficient.

## Potential Impact

- Data exposure
- Service disruption
- Compliance violations

## Existing Controls

- Vendor agreements
- Security requirements within contracts

## Recommendations

- Develop formal vendor risk assessments
- Review vendor SOC reports annually
- Implement third-party security questionnaires

---

# 8. Overall Risk Summary

| Risk Area | Overall Risk |
|---|---|
| Phishing | Critical |
| Ransomware | Critical |
| Access Management | High |
| Endpoint Security | High |
| Vendor Management | Moderate |

---

# 9. Security Strengths

The organization demonstrates several positive security practices including:

- Multi-factor authentication deployment
- Security awareness training
- VPN encryption
- Endpoint antivirus protections
- Backup and recovery processes
- Formal security policies

---

# 10. Areas for Improvement

Improvement opportunities include:

- Enhanced phishing simulations
- Expanded vulnerability management
- Improved privileged access controls
- Formal vendor risk management program
- Increased logging and monitoring capabilities
- Security incident testing exercises

---

# 11. Recommended Remediation Priorities

## Immediate Priorities

- Strengthen phishing protections
- Improve endpoint monitoring
- Accelerate patch management timelines

## Short-Term Priorities

- Conduct formal access reviews
- Improve security awareness training
- Expand vulnerability scanning coverage

## Long-Term Priorities

- Develop continuous monitoring program
- Enhance vendor risk governance
- Conduct regular tabletop exercises

---

# 12. Conclusion

The cybersecurity risk assessment identified several significant threats affecting Able Behavioral Health systems and operations. While foundational security controls are in place, additional improvements are recommended to strengthen resilience against evolving cybersecurity threats and support ongoing HIPAA compliance efforts.

The organization should continue enhancing security governance, monitoring, and remediation activities to reduce organizational risk exposure and improve overall cybersecurity maturity.

---

# 13. Related Documents

- System Security Plan (SSP)
- POA&M
- Asset Inventory
- Vulnerability Management Reports
- Incident Response Policy
- Access Control Policy

---

# Revision History

| Version | Date | Description |
|---|---|---|
| 1.0 | May 11, 2026 | Initial Risk Assessment Report |

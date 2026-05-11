# Able Behavioral Health  
# System Security Plan (SSP)

---

# Document Information

| Field | Value |
|---|---|
| Organization | Able Behavioral Health |
| Document Title | System Security Plan |
| Framework | NIST SP 800-53 Rev. 5 |
| Classification | Confidential |
| Version | 1.0 |
| Author | Barron Williams |
| Effective Date | May 11, 2026 |
| Review Cycle | Annual |

---

# 1. System Identification

## System Name

Able Behavioral Health Information System Environment

## System Description

The Able Behavioral Health Information System Environment supports healthcare and group home operations across three regional facilities. The environment processes, stores, and transmits sensitive organizational and patient-related information, including HIPAA-regulated Protected Health Information (PHI).

The environment consists of:

- Microsoft 365 cloud services
- Windows-based endpoints
- VPN remote access infrastructure
- Cloud-hosted Electronic Health Record (EHR) system
- File storage services
- Network infrastructure components
- Backup and recovery systems

---

# 2. System Purpose

The purpose of this system is to support:

- Patient care operations
- Clinical documentation
- Employee communications
- Administrative functions
- Secure remote access
- Compliance and reporting activities

---

# 3. System Environment

## Operating Environment

The environment is considered a hybrid infrastructure consisting of:

- Cloud-hosted applications
- On-premises networking equipment
- Windows endpoint devices
- Remote workforce access capabilities

## Supported Locations

- Facility 1
- Facility 2
- Facility 3
- Corporate Headquarters

---

# 4. Authorization Boundary

## Included Systems

The following systems are within the authorization boundary:

- Microsoft 365 tenant
- Windows laptops and desktops
- Active Directory infrastructure
- VPN appliances
- Endpoint protection systems
- Cloud-hosted EHR platform
- Backup systems
- Internal file storage systems

## Excluded Systems

The following systems are outside the authorization boundary:

- Third-party billing vendors
- Internet service provider infrastructure
- External healthcare partners
- Personal employee devices not enrolled in MDM

---

# 5. Data Classification

The environment processes the following data classifications:

| Classification | Description |
|---|---|
| Public | Publicly available organizational information |
| Internal | Internal operational information |
| Confidential | Sensitive employee and business information |
| Restricted | HIPAA-regulated PHI and authentication credentials |

---

# 6. Roles and Responsibilities

| Role | Responsibility |
|---|---|
| Compliance Analyst | Risk assessments and compliance monitoring |
| IT Administrator | System administration and patch management |
| HR Department | Personnel onboarding and offboarding |
| Executive Leadership | Security governance oversight |
| End Users | Compliance with security policies |
| Managed Service Provider | Infrastructure support and monitoring |

---

# 7. System Architecture

## Major Components

The environment includes:

- Microsoft 365 cloud environment
- Windows 10 and Windows 11 endpoints
- VPN remote access solution
- Endpoint Detection & Response (EDR)
- Network firewalls
- Backup storage appliances
- Cloud-based EHR application

## Security Architecture

Security protections include:

- Multi-factor authentication (MFA)
- Endpoint antivirus protection
- VPN encryption
- Security awareness training
- Access control enforcement
- Centralized logging
- Vulnerability management processes

---

# 8. Security Control Implementation Summary

This section summarizes implementation of selected NIST SP 800-53 Rev. 5 controls.

---

# Access Control (AC)

## AC-2 — Account Management

User accounts are provisioned and deprovisioned through documented onboarding and termination procedures. Accounts are reviewed quarterly by IT and Human Resources.

## AC-6 — Least Privilege

Access permissions are assigned based on job responsibilities and business need-to-know principles.

## AC-17 — Remote Access

Remote access requires VPN connectivity with multi-factor authentication enabled.

---

# Identification and Authentication (IA)

## IA-2 — Identification and Authentication

All users must authenticate using unique credentials. MFA is required for remote access and administrative accounts.

## IA-5 — Authenticator Management

Password complexity standards are enforced through Active Directory Group Policy.

---

# Audit and Accountability (AU)

## AU-6 — Audit Review

Security logs are reviewed weekly for suspicious or unauthorized activity.

## AU-12 — Audit Logging

Critical systems generate audit logs for authentication events, administrative actions, and security incidents.

---

# Configuration Management (CM)

## CM-2 — Baseline Configuration

Standardized system configurations are maintained for organizational endpoints.

## CM-6 — Configuration Settings

Security hardening settings are enforced through centralized management policies.

---

# Risk Assessment (RA)

## RA-3 — Risk Assessment

Annual risk assessments are conducted to identify threats, vulnerabilities, and business impacts.

## RA-5 — Vulnerability Monitoring and Scanning

Monthly vulnerability scans are conducted using approved security scanning tools.

---

# System and Information Integrity (SI)

## SI-2 — Flaw Remediation

Critical security patches are deployed within established organizational timelines.

## SI-4 — System Monitoring

Security monitoring tools are used to detect malicious activity and policy violations.

---

# Incident Response (IR)

## IR-4 — Incident Handling

The organization maintains documented incident response procedures for cybersecurity events.

## IR-6 — Incident Reporting

Security incidents must be reported immediately to IT and Compliance personnel.

---

# Contingency Planning (CP)

## CP-9 — System Backup

Daily backups are performed for critical systems and stored securely.

## CP-10 — System Recovery

Disaster recovery procedures are documented and tested annually.

---

# Awareness and Training (AT)

## AT-2 — Security Awareness Training

Employees complete annual cybersecurity and HIPAA awareness training.

---

# 9. Risk Management Strategy

Able Behavioral Health follows a risk-based cybersecurity approach focused on:

- Protecting patient information
- Reducing operational disruptions
- Supporting HIPAA compliance
- Improving security maturity
- Mitigating ransomware threats
- Enhancing access management

Risk assessments are conducted annually or following significant system changes.

---

# 10. Vulnerability Management

The organization performs vulnerability management activities including:

- Monthly vulnerability scanning
- Patch management
- Critical vulnerability remediation tracking
- Endpoint security monitoring
- Risk prioritization using CVSS scoring

---

# 11. Incident Response

The organization maintains an Incident Response Plan addressing:

- Detection
- Containment
- Eradication
- Recovery
- Post-incident review

Security incidents involving PHI are escalated according to HIPAA breach notification requirements.

---

# 12. Business Continuity and Disaster Recovery

The organization maintains contingency planning procedures including:

- Daily backups
- Offsite backup retention
- Disaster recovery testing
- Emergency communication procedures
- Recovery prioritization for critical systems

---

# 13. Security Awareness Program

Security awareness activities include:

- Annual cybersecurity training
- HIPAA compliance training
- Phishing awareness exercises
- Acceptable use policy acknowledgments

---

# 14. Interconnection Agreements

The environment maintains external connections with:

- Cloud service providers
- EHR vendor platforms
- Managed service providers
- Third-party healthcare systems

All external connections must be approved and documented.

---

# 15. Continuous Monitoring

Continuous monitoring activities include:

- Endpoint monitoring
- Log analysis
- Vulnerability scanning
- Access reviews
- Security event alerting
- Compliance audits

---

# 16. Plan of Action and Milestones (POA&M)

Identified weaknesses and remediation activities are tracked through the organizational POA&M process.

Examples include:

- MFA expansion initiatives
- Legacy software remediation
- Patch management improvements
- Security awareness enhancements

---

# 17. System Approval

This System Security Plan represents the current security posture of Able Behavioral Health and supports ongoing cybersecurity governance, risk management, and compliance activities.

---

# Revision History

| Version | Date | Description |
|---|---|---|
| 1.0 | May 11, 2026 | Initial SSP Creation |

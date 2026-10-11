# 📜 UK Healthcare Security Policy Development

![ISO 27001](https://img.shields.io/badge/ISO%2027001-2022-blue)
![UK GDPR](https://img.shields.io/badge/UK%20GDPR-Aligned-green)
![SANS](https://img.shields.io/badge/SANS-Policy%20Templates-red)
![Project](https://img.shields.io/badge/Project-Security%20Policy-orange)

## Project Overview

This project demonstrates the development of a security policy suite for a simulated UK healthcare clinical and administrative environment.

The policies were created using **ISO 27001:2022** as the primary information-security framework and **SANS policy templates** as a structural reference. Relevant guidance from **NIST** was also considered where appropriate.

The original healthcare template was customised for the United Kingdom by incorporating the requirements and principles of the:

- UK General Data Protection Regulation (UK GDPR)
- Data Protection Act 2018
- Information Commissioner’s Office (ICO)
- ISO 27001:2022
- SANS security policy templates

The project focuses on protecting health data, controlling access, strengthening authentication, monitoring security activity and establishing an appropriate incident-notification process.

---

## 🎯 Project Objectives

The objectives of this project were to:

- Develop a structured suite of information-security policies.
- Adapt general policy templates to a UK healthcare environment.
- Apply risk-based policy development.
- Map identified risks to appropriate security controls.
- Align the policies with ISO 27001:2022 Annex A controls.
- Incorporate UK data-protection requirements.
- Define policy ownership, responsibilities and review periods.
- Produce a practical implementation plan for the policy suite.

---

## 🏥 Project Environment

The simulated organisation is a UK healthcare clinical and administrative centre that processes sensitive health and personal data.

The environment includes:

- Clinical and administrative users
- Microsoft Active Directory
- Microsoft Entra ID
- Role-Based Access Control (RBAC)
- Multi-Factor Authentication (MFA)
- Segmented network VLANs
- Splunk SIEM
- Encrypted servers and workstations
- Remote-access connections
- Clinical systems
- Staff and visitor wireless networks

---

## 📚 Frameworks and References

| Framework or Regulation | Application in the Project |
|---|---|
| ISO 27001:2022 | Primary framework for selecting and mapping information-security controls |
| SANS Policy Templates | Structural guidance for developing the policy documents |
| UK GDPR | Requirements for protecting and processing personal and health data |
| Data Protection Act 2018 | UK legal framework supporting data-protection obligations |
| ICO Guidance | Guidance for personal-data breach assessment and notification |
| NIST Guidance | Supplementary guidance used where appropriate |

---

## ⚠️ Risk-Based Approach

A risk register was used to identify six key security risks affecting the simulated organisation.

Each risk was connected to a corresponding policy and relevant ISO 27001:2022 Annex A controls. This ensured that every policy addressed an identified organisational risk instead of being created without a defined security requirement.

The risk-based approach included:

1. Identifying threats and vulnerable assets.
2. Assessing likelihood and potential impact.
3. Recording existing controls.
4. Identifying control gaps.
5. Selecting appropriate policy requirements.
6. Mapping the policies to ISO 27001:2022 controls.

---

## 📑 Security Policy Suite

Six security policies were developed:

| Policy ID | Policy |
|---|---|
| SEC-POL-001 | Health Data Access Control Policy |
| SEC-POL-002 | Health Data Encryption Policy |
| SEC-POL-003 | Authentication and Password Policy |
| SEC-POL-004 | Audit Logging and Monitoring Policy |
| SEC-POL-005 | Breach Notification Policy |
| SEC-POL-006 | Acceptable Use Policy |

---

## 🔐 Key Security Requirements

### Access Control

- Role-Based Access Control
- Least-privilege access
- Access approval and regular reviews
- Joiner, mover and leaver controls
- Restricted access to health data
- Segmentation of clinical, administrative, staff and visitor networks

### Encryption

- Encryption of health data at rest and in transit
- TLS 1.2 or higher for network communications
- Controlled encryption-key management
- Protection of servers, workstations and remote connections

### Authentication

- Multi-Factor Authentication
- Minimum 14-character passwords
- Compromised-password screening
- Privileged-account protection
- Microsoft Entra ID and Active Directory controls

### Logging and Monitoring

- Centralised security logging
- Splunk SIEM monitoring
- Health-data access alerts
- Authentication and privileged-activity monitoring
- Security-event investigation and escalation

### Breach Notification

- Incident assessment and documentation
- Internal escalation procedures
- ICO reporting process
- Notification templates for affected individuals
- Regulatory notification within 72 hours where required

### Acceptable Use

- Appropriate use of organisational systems
- Protection of credentials and sensitive information
- Restrictions on unauthorised software and devices
- Remote-working requirements
- Staff acknowledgement and security awareness training

---

## 🗺️ ISO 27001:2022 Control Mapping

| Policy | ISO 27001:2022 Annex A Controls |
|---|---|
| SEC-POL-001 – Health Data Access Control | A.5.15, A.5.16, A.8.2 |
| SEC-POL-002 – Health Data Encryption | A.8.12, A.8.24 |
| SEC-POL-003 – Authentication and Password | A.5.17, A.8.5 |
| SEC-POL-004 – Audit Logging and Monitoring | A.8.15, A.8.16 |
| SEC-POL-005 – Breach Notification | A.5.24, A.5.26 |
| SEC-POL-006 – Acceptable Use | A.5.1, A.6.3 |

---

## 🚀 Implementation Plan

The implementation plan assigns technical actions, responsible owners and completion timelines.

Planned activities include:

- Creating Active Directory RBAC groups.
- Reviewing user access quarterly.
- Auditing systems that process health data.
- Deploying TLS 1.2 or higher.
- Enforcing Microsoft Entra ID MFA.
- Applying the defined password requirements.
- Configuring Splunk Universal Forwarder.
- Creating SIEM alerts for security monitoring.
- Establishing an ICO breach-reporting process.
- Distributing the Acceptable Use Policy to staff.
- Collecting signed staff acknowledgements.
- Delivering security-awareness training.

---

## 🧠 Key Lessons Learned

This project demonstrated that:

- Templates provide structure, but policies must be customised for the organisation.
- ISO 27001 and SANS policy templates are complementary.
- A risk register should drive policy development.
- Encryption reduces the impact of unauthorised data disclosure.
- Policies require ownership, implementation, monitoring and regular review.
- Regulatory and organisational changes should trigger policy reviews.
- Technical controls and written policies must support each other.

---

## 📁 Repository Contents

```text
UK-Healthcare-Security-Policy-Development/
│
├── README.md
├── Saheed_Bakare_UK_Healthcare_Security_Policy_Development_Project.pdf
└── policies/
    ├── SEC-POL-001-Health-Data-Access-Control.pdf
    ├── SEC-POL-002-Health-Data-Encryption.pdf
    ├── SEC-POL-003-Authentication-and-Password.pdf
    ├── SEC-POL-004-Audit-Logging-and-Monitoring.pdf
    ├── SEC-POL-005-Breach-Notification.pdf
    └── SEC-POL-006-Acceptable-Use.pdf

```
## 👤 Author

**Saheed Bakare**  
IT Support Engineer | Cybersecurity Analyst | IAM & Cloud Security Practitioner


# SimplifyIAM – IAM Implementation Portfolio

> End-to-end Identity and Access Management (IAM) implementation portfolio built using **midPoint**, **OpenLDAP**, **Auth0**, and a simulated HR system.  
> This repository demonstrates real-world IAM concepts including identity lifecycle management, automated provisioning, reconciliation, RBAC, federation, OIDC, and SAML integrations.

---

## 👨‍💻 Candidate Information

- **Cohort:** SimplifyIAM Live Cohort 1
- **Completed:** May 2026
- **Name:** Upendra Kumar Sharma
- **LinkedIn:** https://www.linkedin.com/in/upendrasharma1/

---

# 📌 Project Overview

Over five live implementation sessions, I designed and deployed a complete IAM lab environment from scratch on a dedicated cloud server.  

The project simulates how enterprise IAM platforms integrate with HR systems, directories, and identity providers to automate user onboarding, role changes, access provisioning, and deprovisioning.

This repository serves as:
- A hands-on IAM implementation portfolio
- Evidence of practical IAM engineering skills
- A walkthrough of provisioning and federation workflows
- A technical showcase for IAM Analyst / IAM Engineer / IGA Consultant roles

---

# 🏗️ Solution Architecture

## Core Components

| Component | Purpose |
|---|---|
| **midPoint** | Identity Governance & Administration (IGA) platform used for lifecycle management, provisioning, reconciliation, and RBAC |
| **SimplifyHR (Flask App)** | Simulated HR source system acting as the authoritative identity source |
| **OpenLDAP** | Target directory where user accounts are provisioned and managed |
| **Auth0** | Access Management platform used for OIDC and SAML federation |
| **Cloud VM** | Dedicated infrastructure hosting the IAM environment |

---

# 🔄 IAM Workflow Implemented

The following enterprise IAM workflows were implemented:

- Joiner workflow automation
- Mover workflow automation
- Leaver workflow automation
- HR-driven provisioning
- Automated reconciliation
- Identity correlation
- Role-Based Access Control (RBAC)
- LDAP account lifecycle management
- OIDC federation
- SAML federation
- JWT claim validation
- Identity synchronization between systems

---

# 📂 Repository Structure

```bash
├── architecture/
├── screenshots/
│   ├── week1/
│   ├── week2/
│   ├── week3/
│   ├── week4/
│   └── week5/
├── midpoint-config/
├── ldap-config/
├── auth0-config/
├── mappings/
├── workflows/
└── README.md
```

---

# 🚀 Session Deliverables

# Week 1 – Environment Setup & Architecture

## Deliverables
- IAM architecture design
- midPoint installation and configuration
- OpenLDAP setup and OU structure
- SimplifyHR integration setup
- Initial connectivity validation

## Evidence
- Architecture diagram
- midPoint admin console screenshots
- SimplifyHR dashboard screenshots
- OpenLDAP OU structure screenshots

## What I Built
Implemented the foundational IAM lab environment including identity governance, HR source integration, and LDAP target directory setup. Established connectivity between core IAM systems to support lifecycle automation.

## Resume Bullet
Designed and deployed a complete IAM lab environment using midPoint, OpenLDAP, and a simulated HR system on a cloud VM to demonstrate enterprise identity lifecycle workflows.

---

# Week 2 – Joiner Workflow Automation

## Deliverables
- HR source connector configuration
- Identity correlation rules
- Inbound attribute mappings
- Automated provisioning workflow
- LDAP reconciliation

## Evidence
- Connector configuration screenshots/XML
- Correlation rule definitions
- Inbound mapping tables
- Provisioned LDAP account screenshots

## What I Built
Configured HR-driven identity onboarding workflows where new employees created in SimplifyHR were automatically provisioned into OpenLDAP through midPoint reconciliation.

## Resume Bullet
Implemented automated Joiner workflows using midPoint reconciliation and provisioning to create LDAP accounts from HR source data with identity correlation and inbound mappings.

---

# Week 3 – Mover & Leaver Workflows

## Deliverables
- Role definitions
- RBAC implementation
- Mover workflow automation
- Leaver deprovisioning process
- Reconciliation validation

## Evidence
- Role configuration screenshots/XML
- Workflow screenshots
- Disabled/deleted account screenshots
- Reconciliation results

## What I Built
Built automated Mover and Leaver workflows enabling role changes, access updates, and account deactivation based on HR status changes.

## Resume Bullet
Configured RBAC-driven Mover and Leaver workflows to automate access modifications and account deprovisioning across connected systems.

---

# Week 4 – Access Management & Federation

## Deliverables
- Auth0 tenant configuration
- OIDC application setup
- SAML federation setup
- JWT validation
- Assertion testing

## Evidence
- Auth0 configuration screenshots
- OIDC application setup
- SAML assertion screenshots
- JWT claim screenshots

## What I Built
Integrated Auth0 with IAM components using both OIDC and SAML protocols to simulate enterprise-grade authentication and federation workflows.

## Resume Bullet
Implemented OIDC and SAML federation using Auth0, including JWT validation and assertion-based authentication flows.

---

# Week 5 – Career Preparation & Portfolio Finalization

## Deliverables
- IAM-focused resume bullets
- LinkedIn optimization
- Mock interview preparation
- Technical walkthrough preparation

## Evidence
- Resume updates
- LinkedIn headline updates
- Interview reflection notes

## What I Built
Prepared a production-style IAM portfolio demonstrating practical implementation experience across identity governance, provisioning, and federation technologies.

## Resume Bullet
Built and documented a complete IAM implementation portfolio demonstrating practical experience in identity governance, provisioning automation, reconciliation, RBAC, and federation.

---

# 🧠 Key IAM Concepts Demonstrated

- Identity Lifecycle Management (JML)
- Identity Correlation
- Reconciliation
- Provisioning & Deprovisioning
- RBAC (Role-Based Access Control)
- LDAP Administration
- OIDC Authentication
- SAML Federation
- JWT Claims Validation
- HR-Driven Provisioning
- IAM Architecture Design

---

# 🛠️ Technologies Used

| Technology | Category |
|---|---|
| midPoint | Identity Governance |
| OpenLDAP | Directory Services |
| Auth0 | Access Management |
| Flask | HR Simulation Application |
| Linux | Infrastructure |
| XML | IAM Configuration |
| SAML | Federation Protocol |
| OAuth2 / OIDC | Authentication Protocol |
| JWT | Token Validation |

---

# 📸 Screenshots

> Add screenshots under the `/screenshots` directory for each implementation phase.

Recommended screenshots:
- midPoint dashboards
- LDAP user creation
- HR onboarding records
- Reconciliation results
- Auth0 applications
- SAML assertions
- JWT tokens
- RBAC role assignments

---

# 🎯 Skills Demonstrated

## IAM & Security
- Identity Governance Administration (IGA)
- Access Management
- Federation
- Authentication & Authorization
- Identity Lifecycle Automation

## Technical
- System Integration
- XML Configuration
- Directory Services
- Cloud VM Administration
- Troubleshooting & Reconciliation

## Professional
- Documentation
- Solution Architecture
- IAM Workflow Design
- Technical Demonstration
- Portfolio Presentation

---

# 📈 My Transformation

## Where I Started
[Describe your starting point — previous role, IAM exposure, technical limitations, or concepts you were unfamiliar with before joining the cohort.]

## Where I Am Now
I can now independently explain and demonstrate:
- IAM architecture design
- Joiner/Mover/Leaver workflows
- Automated provisioning and reconciliation
- LDAP integrations
- OIDC and SAML federation
- Enterprise IAM implementation concepts

I also have a fully functional IAM lab environment that can be demonstrated during technical interviews.

## Roles I Am Targeting
- IAM Analyst
- IAM Engineer
- Identity Governance Consultant
- IGA Implementation Consultant
- Cybersecurity IAM Specialist
- Access Management Engineer

---

# 📄 Resume-Ready Summary

```text
• Designed and deployed a complete IAM environment using midPoint, OpenLDAP, Auth0, and a simulated HR system on a cloud VM.
• Implemented automated Joiner, Mover, and Leaver workflows using reconciliation and provisioning capabilities in midPoint.
• Configured RBAC models, identity correlation rules, inbound mappings, and LDAP account lifecycle management.
• Integrated Auth0 using OIDC and SAML federation protocols with JWT validation and assertion testing.
• Built a production-style IAM implementation portfolio demonstrating practical identity governance and access management experience.
```

---

# 🔐 Disclaimer

This repository is intended for educational and portfolio purposes only.  
Any sensitive information, credentials, tokens, or personal data shown in screenshots should be redacted before publishing.

---

# ⭐ Final Notes

This project represents practical implementation experience rather than theoretical IAM learning.  
The objective was to build, configure, troubleshoot, and document a working IAM ecosystem similar to what is used in enterprise environments.

If you're a recruiter, hiring manager, or IAM professional reviewing this repository, feel free to connect with me on LinkedIn.

---

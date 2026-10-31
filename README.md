# 🖥️ IT Help Desk & Service Desk Portfolio | SysDesk Lab Simulation

[![IT Support](https://img.shields.io/badge/Role-Tier%201%20Service%20Desk%20Analyst-blue?style=for-the-badge&logo=windows)](https://github.com)
[![Platform](https://img.shields.io/badge/Simulation-SysDesk%20Console-informational?style=for-the-badge)](https://sysdesks.com)
[![Standard](https://img.shields.io/badge/Framework-ITIL%20%2F%20ITSM-green?style=for-the-badge)](https://github.com)
[![Security](https://img.shields.io/badge/Discipline-Security%20Incident%20Triage-red?style=for-the-badge)](https://github.com)

Welcome to my **IT Help Desk & Service Desk Portfolio**. This repository documents hands-on technical support tickets, security incident escalations, and customer service workflows completed inside the **SysDesk** enterprise simulation environment (`northline.corp`).

The purpose of this portfolio is to showcase practical, real-world competencies required for an **IT Support Specialist, Service Desk Technician (Tier 1), or Helpdesk OJT/Internship role**, focusing on troubleshooting methodology, security incident response, structured ticketing documentation, and end-user empathy.

---

## 🗂️ Solved Ticket Catalog

| Ticket ID | Category | Issue Summary | Priority | Key Skills Demonstrated | Status / Link |
| :--- | :--- | :--- | :---: | :--- | :---: |
| **INC8539798** | `Security > Ransomware` | **Suspected Ransomware on Shared `S:\` Drive**<br>Encrypted `.lckd` files and ransom notes on department file share | `P2 High` | • Rapid Network Isolation<br>• Evidence Preservation<br>• User De-escalation & Empathy<br>• Tier 2 / SecOps Escalation | [**View Case Study ➡️**](tickets/002-ransomware-on-shared-drive/README.md) |
| *Upcoming* | `Hardware / Peripherals` | *Laptop Touchpad & Input Troubleshooting* | `P3 Normal` | • Hardware Diagnostics<br>• Driver Reinstallation<br>• Device Manager Triage | *In Progress* |
| *Upcoming* | `Identity & Access` | *Active Directory Password Reset & Account Lockout* | `P3 Normal` | • Identity Verification<br>• AD Domain Services<br>• Access Management | *Queued* |

---

## 🛠️ Core Competencies & Skills Matrix

### 1. Technical & Systems Support
- **Incident Triage & Classification:** Identifying severity, impact, and urgency in enterprise environments according to ITIL standards.
- **Cybersecurity Fundamentals:** Recognizing Indicators of Compromise (IoCs), ransomware signatures, phishing attempts, and maintaining strict containment procedures without altering forensic evidence.
- **Enterprise Network & Sharing:** Diagnosing shared network drive (`SMB/CIFS`) issues, mapped drives, and IP subnet scoping.
- **Operating Systems & Hardware:** Troubleshooting Windows workstations, peripherals, and device management.

### 2. Service Desk Tools & Operations
- **Ticketing & Incident Management:** Utilizing enterprise ticket consoles (SysDesk) to manage ticket states (`Assigned`, `Work in Progress`, `Pending`, `Escalated`, `Resolved`).
- **Communication & Mail Systems:** Managing asynchronous communications via corporate email (`NorthMail`).
- **Standardized Escalation Notes:** Documenting structured handoffs using the **SBAR / ITIL** format (Symptoms, Timeline, Source, Actions Taken, and Explicit Next Steps).

### 3. Customer Service & Soft Skills
- **Plain-Language Translation:** Explaining complex technical problems in simple, reassuring terms for non-technical users.
- **User Empathy & De-escalation:** Calming frustrated or anxious users under high-stress business downtime scenarios.
- **Expectation & SLA Management:** Setting realistic update schedules and keeping the requester informed throughout the ticket lifecycle.

---

## 🏢 Simulated Enterprise Environment: `northline.corp`

The tickets in this repository are performed within the **SysDesk** enterprise infrastructure, which simulates real enterprise corporate operations:

```text
Enterprise Domain: northline.corp
├── Network Services: File Servers, Shared Drives (S:\), Active Directory, DNS/DHCP
├── Departmental Segments: Operations, Logistics, Sales, IT Support, Security Operations (SecOps)
├── Endpoints: Deltatek Workstations, Corporate Laptops, Mobile Devices
└── Support Hierarchy:
    ├── Tier 1: Service Desk (First-Contact Triage, Containment, Common Fixes)
    └── Tier 2 / Tier 3: SysAdmins, Network Engineers, Security Operations Center (SOC)
```

---

## 📁 Repository Structure

```text
Helpdesk-Lab-Project-SysDesk-/
├── README.md                                  # Portfolio Landing Page & Ticket Catalog
└── tickets/
    └── 002-ransomware-on-shared-drive/        # Ticket INC8539798 Case Study
        ├── README.md                          # Detailed Case Study & Technical Analysis
        └── screenshots/                       # Step-by-step visual proofs
            ├── 01-ticket-intake-overview.png
            ├── 02-initial-containment-email.png
            ├── 03-investigation-triage-email.png
            ├── 04-de-escalating-frustrated-user.png
            ├── 05-security-escalation-notes.png
            └── 06-final-user-wrapup-email.png
```

---

## 👤 About the Author

- **Role Aspirations:** IT Support Technician \| Service Desk Tier 1 \| Helpdesk Analyst \| IT Operations
- **GitHub:** [@tormis-neil](https://github.com/tormis-neil)
- **Email:** [Contact via Email](mailto:tormisneilmayo@gmail.com)
- **LinkedIn:** [LinkedIn Profile Placeholder](https://linkedin.com)

---
*Developed as part of practical IT Service Desk and Helpdesk professional training using the SysDesk simulation platform.*

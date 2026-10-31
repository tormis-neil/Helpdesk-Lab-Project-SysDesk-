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
| **INC6272241** | `Mobile Devices > SlatePad Wi-Fi` | **Managed Tablet Joined to Guest Wi-Fi (App Offline)**<br>Inventory Scan app offline while public internet browsed | `P3 Moderate` | • Network Segmentation (Guest vs Corp)<br>• MDM & 802.1X Certificate Verification<br>• Remote Device Assistance<br>• User Pacing & Proactive Guidance | [**View Case Study ➡️**](tickets/003-wifi-connectivity/README.md) |
| *Upcoming* | `Hardware / Peripherals` | *Laptop Touchpad & Input Troubleshooting* | `P3 Normal` | • Hardware Diagnostics<br>• Driver Reinstallation<br>• Device Manager Triage | *In Progress* |
| *Upcoming* | `Identity & Access` | *Active Directory Password Reset & Account Lockout* | `P3 Normal` | • Identity Verification<br>• AD Domain Services<br>• Access Management | *Queued* |

---

## 🛠️ Core Competencies & Skills Matrix

### 1. Technical & Systems Support
- **Incident Triage & Classification:** Identifying severity, impact, and urgency in enterprise environments according to ITIL standards.
- **Enterprise Network Segmentation:** Diagnosing VLAN/SSID isolation (Guest vs. Corporate), subnet scopes (`172.18.x.x` vs. `10.30.x.x`), and private DNS/service reachability.
- **Mobile Device Management (MDM):** Inspecting managed profile compliance, supervised device states, and 802.1X EAP-TLS identity certificates without destructive resets.
- **Cybersecurity Fundamentals:** Recognizing Indicators of Compromise (IoCs), ransomware signatures, phishing attempts, and maintaining strict containment procedures without altering forensic evidence.
- **Enterprise Network & Sharing:** Diagnosing shared network drive (`SMB/CIFS`) issues, mapped drives, and IP subnet scoping.
- **Operating Systems & Hardware:** Troubleshooting Windows workstations, SlatePads/tablets, peripherals, and device management.

### 2. Service Desk Tools & Operations
- **Ticketing & Incident Management:** Utilizing enterprise ticket consoles (SysDesk) to manage ticket states (`Assigned`, `Work in Progress`, `Pending`, `Escalated`, `Resolved / Solved Permanently`).
- **Remote Desktop & Touch Support:** Requesting consent and navigating remote control sessions on enterprise tablet devices to inspect configuration settings.
- **Communication & Mail Systems:** Managing asynchronous communications via corporate email (`NorthMail`).
- **Standardized Escalation & Closure Notes:** Documenting structured ticket resolutions using the **ITIL / SBAR** format (Cause, Action Taken, Multi-layer Verification).

### 3. Customer Service & Soft Skills
- **Plain-Language Translation:** Explaining complex technical problems in simple, reassuring terms for non-technical users.
- **User Empathy & De-escalation:** Calming frustrated or anxious users under high-stress business downtime scenarios.
- **Adaptive Communication Pacing:** Breaking down multi-step troubleshooting into single, easy-to-follow questions to avoid overwhelming end-users.
- **Proactive Enablement:** Providing post-resolution tips (e.g. what to do after reboot) to prevent repeat tickets.

---

## 🏢 Simulated Enterprise Environment: `northline.corp`

The tickets in this repository are performed within the **SysDesk** enterprise infrastructure, which simulates real enterprise corporate operations:

```text
Enterprise Domain: northline.corp
├── Network Services: File Servers, Shared Drives (S:\), Active Directory, DNS/DHCP, SSIDs (Corp / Guest)
├── Departmental Segments: Operations, Logistics, Sales, IT Support, Security Operations (SecOps)
├── Endpoints: Deltatek Workstations, Orchard SlatePads (Tablets), Corporate Laptops, Mobile Devices
└── Support Hierarchy:
    ├── Tier 1: Service Desk (First-Contact Triage, Containment, Common Fixes, Remote Support)
    └── Tier 2 / Tier 3: SysAdmins, Network Engineers, Security Operations Center (SOC)
```

---

## 📁 Repository Structure

```text
Helpdesk-Lab-Project-SysDesk-/
├── README.md                                  # Portfolio Landing Page & Ticket Catalog
└── tickets/
    ├── 002-ransomware-on-shared-drive/        # Ticket INC8539798 Case Study
    │   ├── README.md                          # Detailed Case Study & Technical Analysis
    │   └── screenshots/                       # Step-by-step visual proofs (01 - 06)
    └── 003-wifi-connectivity/                 # Ticket INC6272241 Case Study
        ├── README.md                          # Detailed Case Study & Technical Analysis
        └── screenshots/                       # Step-by-step visual proofs (01 - 10)
```

---

## 👤 About the Author

- **Role Aspirations:** IT Support Technician \| Service Desk Tier 1 \| Helpdesk Analyst \| IT Operations
- **GitHub:** [@tormis-neil](https://github.com/tormis-neil)
- **Email:** [Contact via Email](mailto:tormisneilmayo@gmail.com)
- **LinkedIn:** [LinkedIn Profile Placeholder](https://linkedin.com)

---
*Developed as part of practical IT Service Desk and Helpdesk professional training using the SysDesk simulation platform.*

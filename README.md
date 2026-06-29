# Hi — I'm Kia | Identity, Access & Cloud Security

IT professional building hands-on skills in **identity and access management (IAM)**, **cloud security**, and **Windows infrastructure** — backed by a foundation in IT audit and enterprise access administration.

My background combines **IT General Controls (ITGC) auditing**, **enterprise access administration**, and **SQL-based reporting** — now applied directly to building and securing identity and cloud infrastructure. I'm focused on the place where identity *is* the security perimeter: controlling who can access what, proving those controls work, and understanding the systems and network underneath them.

🎯 **Targeting:** IAM Engineer / Cloud Security Engineer
📜 **Certification path:** AZ-900 (Azure Fundamentals) → SC-900 (Security, Compliance & Identity Fundamentals) → SC-300 (Identity & Access Administrator)

---

## 🧪 Hands-on Lab Portfolio

A progressive series of hands-on labs where I build, configure, and secure real IT and cloud infrastructure from the ground up — each one documented step by step, with architecture diagrams and clear explanations meant to be easy to follow and replicate.

### 🔐 Lab 1 — Active Directory Domain Services
*Repo: [`it-homelab/active-directory`](https://github.com/kia-reed/it-homelab/tree/main/active-directory)*

Built a **Windows Server 2025 domain controller** in Microsoft Azure and stood up a complete Active Directory environment — then proved the security controls actually enforced on a real client machine.

- Promoted a server to a **domain controller**, creating the forest and `lab.local` domain
- Built the directory structure: **organizational units (OUs)**, security groups, and users
- Created and linked a **Group Policy Object (GPO)** enforcing password length, complexity, screen-lock, and USB restrictions
- **Joined a separate client machine** to the domain and verified the policy applied end to end with `gpresult`
- Ran day-one identity tasks in **PowerShell**: password resets, account unlocks, offboarding (disable + verify), and access-governance reports (stale accounts, group-membership audits)

*Skills: Active Directory · identity & access management · Group Policy · PowerShell · Azure · access governance*

### 🛰️ Lab 2 — Wireshark & Network Analysis
*Repo: [`it-homelab/wireshark`](https://github.com/kia-reed/it-homelab/tree/main/wireshark)*

Used **Wireshark** to capture and analyze live network traffic packet by packet — the network-layer visibility that complements the identity work in Lab 1.

- Captured and dissected a **DNS (Domain Name System) lookup**, matching the response record to the resolved IP address
- Identified the **TCP three-way handshake** (SYN → SYN-ACK → ACK) and explained what each packet means
- Demonstrated why **HTTPS matters** by capturing login credentials in **plaintext** over unencrypted HTTP (on a deliberately vulnerable test site)
- Reassembled a full conversation with **Follow TCP Stream** and identified it as Azure platform-management traffic

*Skills: network analysis · packet capture · TCP/IP · DNS · traffic analysis · security fundamentals*

### 🔎 Lab 3 — Splunk SIEM (Security Information and Event Management) & Log Analysis

*Repo:* `it-homelab/splunk`

Built a working **SIEM** by forwarding Windows **Active Directory** security logs into Splunk and detecting identity-based attacks — the monitoring side of the identity work in Lab 1.

- Deployed **Splunk Enterprise** on a Linux machine and installed the **Universal Forwarder** on the Active Directory server
- Configured **cross-VNet (Virtual Network) peering** so the forwarder could reach Splunk privately — diagnosed and fixed a real routing failure
- Wrote **SPL (Search Processing Language)** detections for brute force, account lockouts, and suspicious logins
- Built a **four-panel security dashboard** and an **automated brute-force alert**

*Skills: SIEM · log analysis · SPL · Windows Event IDs · detection engineering · Azure networking*

> 🚧 **More labs in progress** — this portfolio grows as I work through SIEM (Security Information and Event Management), IT service management (ITSM) workflows, vulnerability scanning, and cloud identity (Microsoft Entra ID).

---

## 📈 Current Focus

- Expanding **hybrid identity** knowledge — on-premises Active Directory plus **Microsoft Entra ID** (cloud identity)
- Advanced **Group Policy** and security-baseline configuration
- Strengthening **cloud networking fundamentals** — DNS, virtual networks (VNets), network security groups (NSGs), and TCP/IP
- Working toward my **AZ-900 → SC-900 → SC-300** certification path

---

## 🎯 Career Direction

Targeting an **IAM (Identity and Access Management) Engineer** or **Cloud Security Engineer** role, where I can apply identity and access design, security controls, and cloud infrastructure skills — bringing an audit-trained eye for "who has access to what, and should they?"

---

## 🛠️ Skills

**Identity & Access:** Active Directory · Group Policy · access control · provisioning/deprovisioning · access reviews
**Cloud:** Microsoft Azure (VMs, virtual networks, network security groups) · working toward Entra ID
**Security:** packet analysis · network security fundamentals · IT General Controls (ITGC) auditing
**Tools & scripting:** PowerShell · Wireshark · SQL

---

## 📫 Connect

🔗 LinkedIn: www.linkedin.com/in/kreedn

*More labs added over time.*

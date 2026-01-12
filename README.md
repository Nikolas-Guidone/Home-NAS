# Network Attached Storage

## Overview

My personal Network Attached Storage project aimed to not only provide hands-on experience for networking, CLI, etc. but was a valuable opportunity for me to explore how setting up servers work, as well as maintaining, updating, protecting, and running various apps and jobs simultaneously on my home network.

### Skills Learned

- Practiced understanding of physical networking.
- Configuring network interfaces with static IP's to ensure reachability.
- Configuring manual DNS to route all network traffic to correct end destination.
- Monitoring all inbound and outbound network traffic with various tools such as Wireshark.
- Practiced access control and permissions to ensure applications and users had access to only what is needed.
- Configuring RAID backups for redundency
- Read and analyze logs to understand issues
- Learned the basics of dockers and containers to run and deploy applications


/*
---

## 🧠 Skills Demonstrated

List **technical and security skills** recruiters should notice immediately.

* Network Security
* Access Control & Permissions
* Encryption (at rest / in transit)
* Backup & Disaster Recovery
* Threat Modeling
* Logging & Monitoring
* Incident Response Planning
* Linux / NAS / Virtualization / Containers

---
*/
## 🛠️ Technologies Used

Document the stack clearly.

| Category   | Technology                      |
| ---------- | ------------------------------- |
| OS         | TrueNAS SCALE / Ubuntu / Debian |
| Storage    | ZFS / RAID                      |
| Networking | VLANs, Firewall Rules           |
| Security   | VPN, ACLs, Encryption           |
| Services   | SMB, NFS, Docker                |
| Monitoring | Prometheus, Grafana, Logs       |

---

## 🏗️ Architecture Diagram

Include or link an architecture diagram.

```text
[Internet]
    |
[Firewall / Router]
    |
[VLAN / Isolated Network]
    |
[ NAS Server ]
  ├── Storage Pools (ZFS)
  ├── Backup Jobs
  ├── Monitoring
  └── Access Control
```

> 📷 Include images in `/docs/diagrams/`

---

## 🔒 Threat Model

Describe realistic threats and risks.

### Assets

* Sensitive files
* Backups
* User credentials
* Configuration files

### Threats

* Unauthorized access
* Ransomware
* Data corruption
* Insider misuse
* Network-based attacks

### Mitigations

* Least-privilege permissions
* Immutable backups
* Network segmentation
* Encrypted datasets
* Monitoring & alerts

---

## ⚙️ Security Controls Implemented

Detail **what you actually secured**.

### Access Control

* Role-based access control (RBAC)
* Separate admin and user accounts
* Disabled anonymous access

### Network Security

* Firewall rules
* VLAN isolation
* VPN-only admin access

### Data Protection

* ZFS encryption
* Encrypted backups
* Snapshot retention policies

### Monitoring & Logging

* System logs
* Access logs
* Alerts for failed logins

---

## 🧪 Testing & Validation

Explain how you verified security.

* Permission testing (read/write denial)
* Simulated failed login attempts
* Backup restore tests
* Network isolation tests

---

## 🚨 Incident Response Considerations

Show that you think like a defender.

* Backup restoration procedure
* Compromised account response
* System rebuild strategy
* Log review process

---

## 📂 Repository Structure

Make the repo professional and clean.

```text
cybersecurity-project/
├── README.md
├── docs/
│   ├── diagrams/
│   ├── threat-model.md
│   └── architecture.md
├── configs/
│   ├── firewall/
│   ├── permissions/
│   └── backups/
├── scripts/
│   ├── hardening.sh
│   ├── backup.sh
│   └── monitoring.sh
├── logs/
│   └── samples/
└── lessons-learned.md
```

---

## 📈 Results & Improvements

Explain outcomes.

* Reduced attack surface
* Improved backup reliability
* Faster incident recovery
* Better visibility into system activity

---

## 🧩 Lessons Learned

Be honest and reflective.

* What didn’t work
* What you would improve
* Tradeoffs made

---

## 🚀 Future Enhancements

Demonstrates growth mindset.

* SIEM integration
* MFA enforcement
* Automated compliance checks
* Offsite immutable backups

---

## 📚 References

Link standards and documentation.

* NIST CSF
* CIS Benchmarks
* Vendor documentation

---

## 👤 Author

**Name:** Your Name
**Focus:** Cybersecurity / Blue Team / Infrastructure Security
**LinkedIn:** link
**GitHub:** link

---

> ✅ This repository is intended for **educational and portfolio purposes**. No sensitive or production credentials are included.


# 🛡️ Cyber Lab — SOC / Blue Team

Hands-on cybersecurity laboratory built around a concrete career target: **Analista de SOC (Blue Team)**.

> **Purpose:** document practical learning, investigations, detections, incident response and security engineering exercises while transitioning from software engineering to cybersecurity.

## 🎯 Target Role

This lab is intentionally aligned with the requirements of a SOC Analyst position involving:

- alert and event monitoring;
- identification, triage and treatment of security incidents;
- low/medium-complexity incident response;
- SIEM, EDR and SOAR concepts;
- vulnerability management;
- firewalls and network perimeter security;
- Windows and Linux;
- containers;
- security reports, health checks and SOC documentation;
- continuous improvement and security automation.

The repository does **not** claim professional SOC experience. It provides reproducible evidence of practical training in a controlled environment.

## 🧭 Career Roadmap

| Area | Status | Evidence we will build |
|---|---|---|
| Networking & Linux | 🟡 In progress | TCP/IP, DNS, HTTP, Linux security |
| SOC / SIEM | 🟡 Next | Logs, alerts, correlation, triage |
| Incident Response | 🔴 Planned | Investigation, containment, reporting |
| MITRE ATT&CK | 🔴 Planned | Technique mapping and detections |
| Windows Security | 🔴 Planned | Authentication, processes, event logs |
| Vulnerability Management | 🔴 Planned | Scanning, CVEs, CVSS, remediation |
| Network Security | 🔴 Planned | Firewall, WAF, VPN, IDS/IPS |
| EDR / XDR | 🔴 Planned | Endpoint telemetry and response concepts |
| SOAR / Automation | 🔴 Planned | Playbooks and Python automation |
| Containers | 🟡 In progress | Container security and monitoring |
| DevSecOps | 🔴 Planned | SAST, SCA, secrets, container security |
| Cloud Security | 🔴 Planned | IAM, logging, secrets, least privilege |

## 🗂️ Repository Structure

```text
cyber-lab/
├── 01-foundations/
│   ├── networking/
│   ├── linux/
│   └── windows/
├── 02-soc-blue-team/
│   ├── siem/
│   ├── logs/
│   ├── alert-triage/
│   ├── incident-response/
│   ├── mitre-attack/
│   └── documentation/
├── 03-vulnerability-management/
│   ├── scanning/
│   ├── cve-cvss/
│   └── remediation/
├── 04-network-security/
│   ├── firewall/
│   ├── ids-ips/
│   ├── waf/
│   └── vpn/
├── 05-endpoint-security/
│   ├── edr/
│   └── xdr/
├── 06-devsecops/
│   ├── sast/
│   ├── dependency-scanning/
│   ├── secret-scanning/
│   ├── container-security/
│   └── security-pipeline/
├── 07-security-automation/
│   └── python/
└── docs/
    ├── methodology.md
    ├── learning-roadmap.md
    └── soc-interview-qa.md
```

## 🔬 Lab Standard

Every significant exercise should document:

1. **Objective**
2. **Environment**
3. **Procedure**
4. **Evidence**
5. **Analysis**
6. **Severity / Risk**
7. **MITRE ATT&CK mapping**, when applicable
8. **Recommended response**
9. **Lessons learned**

## ⚠️ Ethics & Scope

All activities are restricted to authorized laboratory environments, local machines, intentionally vulnerable systems, CTFs and defensive/security-learning scenarios.

Never store real credentials, API keys, private tokens or personal data.

## 👨‍💻 About

**Tarcísio Valentim**

Experienced software engineer transitioning into cybersecurity, with a background in backend/mobile development, APIs, Cloud, Kubernetes, CI/CD and production systems.

**Current target: SOC / Blue Team → Incident Response → Security Engineering**

- LinkedIn: https://linkedin.com/in/devtvas
- GitHub: https://github.com/devtvas

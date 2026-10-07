# SOC / Blue Team Learning Roadmap

This roadmap was redesigned around the target role **Analista de SOC**.

## Phase 1 — Foundations

- TCP/IP
- DNS
- HTTP/HTTPS
- Linux
- Windows
- Authentication
- Processes and services
- Basic cryptography
- Security principles
- Network perimeter

## Phase 2 — SOC Core

- Security events vs alerts
- Log sources
- Normal vs suspicious behavior
- Alert triage
- Severity and prioritization
- False positives
- IOC analysis
- Correlation
- Escalation
- SOC documentation
- Security health checks

## Phase 3 — SIEM

- SIEM architecture
- Log ingestion
- Parsing and normalization
- Search and investigation
- Detection rules
- Correlation
- Dashboards
- Alert lifecycle
- Incident creation
- Reporting

**Primary practical goal:** build a functional SIEM lab and investigate simulated incidents.

## Phase 4 — Incident Response

- Preparation
- Identification
- Triage
- Containment
- Eradication
- Recovery
- Lessons learned
- Evidence preservation
- Incident report

Practice with low and medium-complexity scenarios.

## Phase 5 — MITRE ATT&CK

- Tactics
- Techniques
- Sub-techniques
- Detection opportunities
- Mapping observed behavior
- Building analyst hypotheses

## Phase 6 — Windows & Linux Security

### Windows

- Security Event Log
- Authentication
- PowerShell
- Processes
- Services
- Scheduled tasks
- Accounts and privileges

### Linux

- auth logs
- syslog/journal
- SSH
- processes
- services
- permissions
- suspicious authentication

## Phase 7 — Vulnerability Management

- Asset inventory
- Vulnerability scanning
- CVE
- CVSS
- Risk prioritization
- Remediation
- Validation
- Security reporting

## Phase 8 — Network Security

- Firewalls
- NGFW concepts
- IDS/IPS
- WAF
- VPN
- XDR concepts
- Network segmentation
- DNS security
- HTTP/HTTPS inspection concepts

## Phase 9 — Endpoint Security

- EDR architecture
- Endpoint telemetry
- Process trees
- Detection
- Investigation
- Containment
- XDR concepts

## Phase 10 — SOAR & Security Automation

- SOAR concepts
- Playbooks
- Enrichment
- IOC lookups
- Alert automation
- Python
- REST APIs
- Log parsing
- Automated reporting

## Phase 11 — Containers & Cloud

- Container isolation
- Image vulnerabilities
- Runtime security
- Kubernetes security fundamentals
- IAM
- Secrets
- Cloud logging
- Least privilege

## Phase 12 — Interview Readiness

The final stage is not just memorization.

We will practice:

- technical questions;
- incident scenarios;
- alert-triage scenarios;
- SIEM investigations;
- behavioral questions;
- explaining investigations clearly;
- presenting the GitHub laboratory as evidence.

### Rule

**No fake experience.**

If a skill was learned through the lab, we will describe it as practical laboratory experience, not professional production experience.

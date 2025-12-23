# Engineering Portfolio — James Hwang

Curated portfolio of **production-style engineering projects** focused on cloud infrastructure, endpoint operations, automation, and security-aware operational tooling.

These repositories are designed to be **reviewable and runnable** (locally or via mock modes where applicable), and to demonstrate how I structure tools intended for real operational use — not one-off scripts.

---

## Contents
- [Focus Areas](#focus-areas)
- [Projects](#projects)
- [Design Principles](#design-principles)
- [How to Review](#how-to-review)
- [Contact](#contact)

---

## Focus Areas

- Cloud & Infrastructure Operations
- Endpoint & Fleet Management
- Automation (PowerShell, AWS tooling)
- Security-aware operational design (auditability, safe defaults)
- Testable, repeatable workflows

---

## Projects

### AWS SSM Fleet Ops Toolkit (PowerShell)
**Repository:** [aws-ssm-fleet-ops-ps](https://github.com/jamhwang/aws-ssm-fleet-ops-ps)  
**Status:** Active

**Summary:**  
Production-style PowerShell tooling modeled after AWS Systems Manager (SSM) Run Command workflows. Demonstrates structured fleet targeting, command execution tracking, and audit-friendly result exports.

**Key concepts:**
- Tag-based fleet targeting
- Separation of core module logic and CLI entry points
- Mock backend for local execution without an AWS account
- JSON/CSV export of operational artifacts
- Pester tests validating expected behavior

**Why this matters:**  
Fleet operations commonly degrade into ad-hoc scripts and inconsistent logging. This project demonstrates a structured, auditable approach designed for operational reliability.

---

### Network Diagnostics Automation (Windows / PowerShell)
**Repository:** [network-diagnostics-automation](https://github.com/jamhwang/<repo-name>)  
**Status:** Planned / In Progress

**Summary:**  
Reusable **Windows-focused** PowerShell network diagnostics toolkit designed to standardize first-response troubleshooting on enterprise Windows endpoints.

Automates collection of Windows network state including IP configuration, DNS resolution, and gateway/external reachability, exporting structured logs suitable for escalation and audit.

**Key concepts:**
- Deterministic, repeatable diagnostics for first-response operations
- Native Windows networking cmdlets (Get-NetIPConfiguration, Test-NetConnection)
- Structured output (CSV/JSON/logs) for escalation workflows
- Parameterized execution paths (diagnostics vs guided remediation)
- Designed for use by non-engineers without sacrificing rigor

**Why this matters:**  
Inconsistent first-response diagnostics create noisy escalations and slower resolution. This project focuses on improving operational signal quality at the endpoint layer.

---

## Design Principles

- **Clarity over cleverness**  
  Code should be readable and explainable under review.

- **Operational realism**  
  Workflows mirror how tools are used in production environments.

- **Testability**  
  Mock modes and tests are included where practical.

- **Auditability**  
  Outputs are structured, exportable, and review-friendly.

---

## How to Review

Each project repository includes:
- Context and usage examples in the README
- A clear folder structure
- Runnable demos or mock workflows
- Notes on tradeoffs and planned extensions

Suggested review flow:
1. Read the README and run the mock or demo workflow
2. Inspect the core module logic (functions, parameterization, error handling)
3. Review exported artifacts (reports/logs) for auditability

---

## Contact

- GitHub: [github.com/jamhwang](https://github.com/jamhwang)  
- LinkedIn: https://www.linkedin.com/in/james-h-02b904103/

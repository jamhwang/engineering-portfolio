# Engineering Portfolio — James Hwang

Curated portfolio of **production-style engineering projects** focused on cloud infrastructure,
IT operations, automation, and security-aware operational tooling.

These repositories are designed to be **reviewable and runnable**, and to demonstrate how I
structure tools intended for real operational use — not one-off scripts or labs.

---

## Contents
- [Focus Areas](#focus-areas)
- [Projects](#projects)
- [Design Principles](#design-principles)
- [How to Review](#how-to-review)
- [Contact](#contact)

---

## Focus Areas

- Cloud & Infrastructure Operations (AWS)
- IT Operations & Endpoint Diagnostics
- Automation (PowerShell, AWS tooling)
- Security-aware operational design (auditability, safe defaults)
- Testable, repeatable workflows

---

## Projects

### AWS SSM Fleet Ops Toolkit (PowerShell)
**Repository:** [aws-ssm-fleet-ops-ps](https://github.com/jamhwang/aws-ssm-fleet-ops-ps)  
**Status:** Active

**Summary:**  
Production-style PowerShell tooling modeled after AWS Systems Manager (SSM) Run Command workflows.
Demonstrates structured fleet targeting, execution tracking, and audit-friendly result exports.

**Key concepts:**
- Tag-based fleet targeting
- Separation of core module logic and CLI entry points
- Mock backend for local execution without an AWS account
- JSON/CSV export of operational artifacts
- Pester tests validating expected behavior

**Why this matters:**  
Fleet operations often degrade into ad-hoc scripts and inconsistent logging.
This project demonstrates a structured, auditable approach designed for operational reliability.

---

### IT Operations Tools (PowerShell)
**Repository:** [it-operations-tools](https://github.com/jamhwang/it-operations-tools)  
**Status:** Active

**Summary:**  
Consolidated PowerShell tooling used in **IT support and escalation workflows (Tier 2/3)**.
Focuses on incident diagnostics, evidence collection, and standardized first-response troubleshooting
on Windows endpoints.

Includes tooling for:
- Network diagnostics and reachability testing
- Windows Event Log collection
- Operator-guided remediation workflows

**Key concepts:**
- Deterministic diagnostics for consistent escalation signal
- Native Windows and PowerShell tooling
- Structured outputs suitable for tickets and RCA
- Safe, operator-driven execution (no silent destructive actions)

**Why this matters:**  
Inconsistent first-response diagnostics create noisy escalations and slow resolution.
This project improves signal quality and repeatability at the endpoint and operations layer.

---

## Design Principles

- **Clarity over cleverness**  
  Code should be readable and explainable under review.

- **Operational realism**  
  Workflows mirror how tools are actually used in production environments.

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
1. Read the project README
2. Run the mock or demo workflow (where applicable)
3. Inspect core logic (parameterization, error handling, structure)
4. Review exported artifacts (logs/reports) for auditability

---

## Contact

- GitHub: https://github.com/jamhwang  
- LinkedIn: https://www.linkedin.com/in/james-h-02b904103/

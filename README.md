# Engineering Portfolio — James Hwang

This repository serves as a curated portfolio of **production-style engineering projects** focused on cloud infrastructure, endpoint operations, automation, and security-aware tooling.

The intent is to demonstrate how I design and structure real-world operational tooling — with an emphasis on reliability, auditability, and maintainability — rather than isolated demos or one-off scripts.

---

## Scope & Focus

Projects in this portfolio emphasize:

* Cloud & infrastructure operations
* Endpoint and fleet management
* Automation using PowerShell and AWS tooling
* Security-aware operational design
* Testable, repeatable workflows

Each linked repository is self-contained, documented, and runnable (locally or in mock mode where applicable).

---

## Projects

### AWS SSM Fleet Ops Toolkit (PowerShell)

**Repository:**
[https://github.com/jamhwang/aws-ssm-fleet-ops-ps](https://github.com/jamhwang/aws-ssm-fleet-ops-ps)

**Summary:**
Production-style PowerShell tooling modeled after AWS Systems Manager (SSM) Run Command workflows. Demonstrates structured fleet targeting, command execution tracking, and audit-friendly result exports.

**Key concepts demonstrated:**

* Tag-based fleet targeting
* Separation of core module logic and CLI entry points
* Mock backend for local execution without an AWS account
* JSON/CSV export of operational artifacts
* Pester tests validating expected behavior

**Why this matters:**
Fleet operations are a common failure point in large environments. This project demonstrates a structured, auditable approach to fleet-scale operations rather than ad-hoc scripting.

---

### Network Diagnostics Automation (PowerShell)

**Repository:**
[https://github.com/jamhwang/](https://github.com/jamhwang/)<repo-name>

**Summary:**
Reusable PowerShell-based network diagnostics toolkit designed to standardize first-response troubleshooting in enterprise endpoint environments.

Automates collection of IP configuration, DNS resolution, and gateway/external reachability checks, exporting structured logs suitable for escalation and audit.

**Key concepts demonstrated:**

* Deterministic, repeatable diagnostics for first-response operations
* Structured output (CSV/JSON/logs) for escalation workflows
* Parameterized execution paths (diagnostics vs. guided remediation)
* Designed for use by non-engineers without sacrificing rigor

**Why this matters:**
Inconsistent first-response diagnostics lead to noisy escalations and delayed resolution. This project shows how lightweight automation can improve signal quality and operational reliability at the edge.

---

## Design Principles

Across all projects, I prioritize:

* **Clarity over cleverness** — code should be readable and reviewable
* **Operational realism** — workflows reflect production usage
* **Testability** — mock modes and tests are included where practical
* **Auditability** — outputs are structured, exportable, and review-friendly

---

## How to Review

Each project repository includes:

* A README with context and usage examples
* A clear folder structure
* Runnable demos or mock workflows
* Notes on design tradeoffs and potential extensions

Reviewers can:

1. Read the project README
2. Run the demo or mock workflow
3. Inspect the core module logic

---

## About

I have experience in:

* Enterprise endpoint and fleet operations
* Cloud infrastructure and automation
* Security tooling and operational support
* PowerShell automation in production environments

This portfolio reflects **how I approach engineering problems**, not just final outputs.

---

## Contact

* GitHub: [https://github.com/jamhwang](https://github.com/jamhwang)
* LinkedIn: [https://linkedin.com/in/]([https://linkedin.com/in/](https://www.linkedin.com/in/james-h-02b904103/))

---


# Engineering Portfolio — James Hwang

This repository serves as a curated portfolio of **production-style engineering projects** focused on
cloud infrastructure, endpoint operations, automation, and security-adjacent tooling.

The goal of this portfolio is to demonstrate:
- How I structure real-world projects
- How I think about operational reliability and auditability
- How I design tooling that is testable, maintainable, and automation-friendly

Each linked repository is self-contained and runnable, with clear documentation.

---

## Core Focus Areas

- Cloud & Infrastructure Operations
- Endpoint & Fleet Management
- Automation (PowerShell, AWS tooling)
- Security-aware operational design
- Testable, repeatable workflows

---

## Projects

### 🔹 AWS SSM Fleet Ops Toolkit (PowerShell)
**Repository:**  
https://github.com/jamhwang/aws-ssm-fleet-ops-ps

**Summary:**  
Production-style PowerShell tooling modeled after AWS Systems Manager (SSM) Run Command workflows.
Demonstrates fleet targeting, command execution tracking, and audit-friendly result exports.

**Key concepts demonstrated:**
- Tag-based fleet targeting
- Separation of module logic vs. CLI entrypoints
- Mock backend for local testing (no AWS account required)
- JSON/CSV export of operational artifacts
- Pester tests validating behavior

**Why this matters:**  
Fleet operations are a common failure point in large environments. This project shows a structured,
auditable approach rather than ad-hoc scripting.

---

## Design Philosophy

Across all projects in this portfolio, I prioritize:

- **Clarity over cleverness**  
  Code should be readable and explainable under review.

- **Operational realism**  
  Projects mirror how tools are actually used in production environments.

- **Testability**  
  Mock modes and tests are included where possible.

- **Auditability**  
  Outputs are structured, exportable, and review-friendly.

---

## How to Review These Projects

Each project repository includes:
- A README with context and usage examples
- A clear folder structure
- Runnable demos or mock workflows
- Notes on planned extensions or production considerations

Reviewers are encouraged to:
- Skim the README
- Run the demo commands
- Inspect the module / core logic

---

## About Me

I am an engineer with experience in:
- Enterprise endpoint and fleet operations
- Cloud infrastructure and automation
- Security tooling and operational support
- PowerShell-based automation in production environments

This portfolio reflects **how I work**, not just what I can build in isolation.

---

## Contact

- GitHub: https://github.com/jamhwang
- LinkedIn: *(add your LinkedIn URL here)*



# NexaCore IAM Governance & Access Review Assessment

> **Simulated Cybersecurity GRC / IAM Governance Project**

A practical, evidence-driven IAM Governance and Access Review assessment conducted for a fictional mid-sized SaaS organization, **NexaCore Technologies**.

The project simulates the work of a **Junior Cybersecurity GRC / IAM Governance Analyst** responsible for evaluating identity and access governance, reviewing access controls, assessing evidence, identifying risks, documenting findings, and developing remediation recommendations.

---

## Project Overview

Identity and access management is not only a technical function.

From a GRC perspective, an organization must be able to demonstrate that:

> **The right identities have the right access, for the right business reasons, with appropriate approval, periodic review, and timely removal.**

This project evaluates that principle across a simulated organization.

The assessment follows an evidence-driven GRC lifecycle:

```text
Business Environment
        ↓
IAM Governance
        ↓
Identity Lifecycle
        ↓
Access Controls
        ↓
Access Review
        ↓
Evidence & Control Testing
        ↓
Findings & Risk
        ↓
Remediation
        ↓
Framework Mapping
        ↓
Executive Reporting
````

The final objective is to produce a complete, portfolio-ready **IAM Governance & Access Review Assessment**.

---



# Project Role

Throughout this assessment, the learner acts as:

> **Junior Cybersecurity GRC / IAM Governance Analyst**

The role is intentionally governance-focused rather than IAM engineering-focused.

Responsibilities simulated in this project include:

* Understanding the IAM environment
* Defining IAM governance expectations
* Reviewing identity lifecycle processes
* Evaluating access controls
* Performing access reviews
* Reviewing IAM evidence
* Testing control operation
* Identifying control weaknesses
* Assessing IAM risks
* Mapping controls to relevant frameworks
* Documenting findings
* Developing remediation actions
* Reporting results to management

The project does **not** simulate production administration of Microsoft Entra ID, Active Directory, AWS IAM, Okta, or other IAM platforms.

---

# Assessment Scope

The assessment focuses on the governance and control aspects of IAM.

## In Scope

### Identity Governance

* IAM roles and responsibilities
* Ownership
* Accountability
* Access approval
* Access governance

### Identity Lifecycle

* Joiners
* Movers
* Leavers
* Access requests
* Provisioning
* Access modification
* Deprovisioning
* Contractors
* Dormant accounts
* Orphaned accounts

### Access Governance

* Least privilege
* Need-to-know
* RBAC
* Basic ABAC considerations
* Segregation of Duties
* Privileged access
* Service accounts
* Break-glass accounts

### Authentication Governance

* MFA
* SSO
* Federation
* Authentication control requirements

### Assessment Activities

* User access reviews
* Control assessment
* Evidence evaluation
* Control testing
* Risk identification
* Findings development
* Remediation tracking
* Validation

### Framework Alignment

Where relevant, IAM controls are mapped to:

* ISO/IEC 27001:2022
* NIST Cybersecurity Framework (CSF) 2.0

Framework mapping is used to support assessment criteria rather than to force every IAM activity into a framework control.

---

# Assessment Methodology

The project uses a practical GRC methodology:

```text
Requirement
     ↓
Control Objective
     ↓
Control Owner
     ↓
Expected Evidence
     ↓
Control Test
     ↓
Result
     ↓
Finding
     ↓
Risk
     ↓
Remediation
     ↓
Validation
```

The central assessment principle is:

> **A policy statement is not evidence that a control operates.**

For example, if NexaCore states:

> "All employees use MFA."

The assessment does not simply accept the statement.

Evidence may include:

* MFA coverage reports
* Exception lists
* Identity inventories
* Privileged account reports
* Access review records
* Approval records
* HR termination records
* Deprovisioning logs

The objective is to determine whether the control is actually operating and whether the available evidence supports that conclusion.

---

# Initial IAM Control Objectives

The project begins with six core IAM control objectives.

| ID    | Control Objective                            | Risk Addressed         |
| ----- | -------------------------------------------- | ---------------------- |
| CO-01 | Access is authorized before provisioning     | Unauthorized access    |
| CO-02 | Access follows least privilege               | Excessive privileges   |
| CO-03 | Access is reviewed periodically              | Access drift           |
| CO-04 | Terminated access is removed timely          | Residual access        |
| CO-05 | Privileged access is controlled and reviewed | Privileged access risk |
| CO-06 | MFA is enforced on active accounts           | Authentication risk    |

These objectives form the initial control baseline and are progressively tested and expanded throughout the project.

---


---

# Repository Structure

The repository is organized around the final assessment rather than individual lessons.

```text
nexacore-iam-governance-assessment/
│
├── README.md
├── DISCLAIMER.md
│
├── 01-organization/
│   ├── organization-profile.md
│   ├── iam-environment-register.md
│   ├── stakeholders.md
│   └── scope.md
│
├── 02-governance/
│   ├── iam-governance-model.md
│   ├── iam-control-objectives-register.md
│   └── iam-raci-matrix.md
│
├── 03-identity-lifecycle/
│   ├── jml-procedure.md
│   ├── access-request-workflow.md
│   └── identity-lifecycle-register.csv
│
├── 04-access-controls/
│   ├── access-control-matrix.csv
│   ├── role-permission-matrix.csv
│   ├── sod-matrix.csv
│   ├── privileged-access-register.csv
│   └── service-account-register.csv
│
├── 05-access-review/
│   ├── access-review-methodology.md
│   ├── user-access-review.csv
│   ├── evidence-register.csv
│   └── control-assessment.csv
│
├── 06-risk-findings/
│   ├── iam-risk-register.csv
│   ├── findings-register.csv
│   └── risk-analysis.md
│
├── 07-remediation/
│   ├── remediation-tracker.csv
│   ├── capa-tracker.csv
│   └── validation-results.md
│
├── 08-framework-mapping/
│   ├── iso-27001-mapping.csv
│   └── nist-csf-mapping.csv
│
├── 09-reporting/
│   ├── iam-assessment-report.md
│   ├── executive-summary.md
│   └── iam-kpi-kri-dashboard.csv
│
├── 10-portfolio/
│   ├── case-study.md
│   ├── linkedin-post.md
│   ├── technical-insight.md
│   └── infographic-concept.md
│
└── evidence/
    ├── evidence-index.md
    ├── sample-access-data.csv
    ├── sample-mfa-report.csv
    ├── sample-jml-data.csv
    └── sample-privileged-access.csv
```

The repository will be populated progressively as the assessment develops.

---

# Core Assessment Artifacts

The project prioritizes meaningful professional artifacts rather than creating documents simply to increase the file count.

Expected high-value artifacts include:

* IAM Governance Model
* IAM Control Objectives Register
* IAM Environment Register
* IAM RACI Matrix
* JML Procedure
* Access Request Workflow
* Access Control Matrix
* Role-Permission Matrix
* SoD Matrix
* Privileged Access Register
* Service Account Register
* User Access Review
* Evidence Register
* IAM Control Assessment
* IAM Risk Register
* Findings Register
* ISO/NIST Mapping
* Remediation Tracker
* CAPA Tracker
* IAM Assessment Report
* Executive Summary
* IAM KPI/KRI Dashboard

Only artifacts that contribute to the assessment will be retained.

---



# Example Assessment Logic

A simple IAM assessment may look like:

```text
Requirement:
Access must be authorized.

        ↓

Expected Control:
Application owner approves access before provisioning.

        ↓

Expected Evidence:
Access request + approval record.

        ↓

Test:
Sample user accounts and inspect approval evidence.

        ↓

Result:
3 of 20 sampled accounts lacked documented approval.

        ↓

Finding:
Access approval evidence is not consistently maintained.

        ↓

Risk:
Unauthorized or inappropriate access may be provisioned without
demonstrable business approval.

        ↓

Remediation:
Require documented approval before provisioning and implement
periodic exception monitoring.

        ↓

Validation:
Re-test a sample after remediation.
```

This approach is used throughout the project.

---



# Disclaimer

**NexaCore Technologies is a fictional organization created exclusively for educational and portfolio purposes.**

All employees, departments, applications, identity populations, access records, evidence, findings, metrics, and assessment results are simulated.

No real organization's systems, credentials, personal information, confidential information, or production environments were accessed or assessed.

This project demonstrates simulated practical GRC/IAM assessment capability and should not be represented as production IAM implementation or professional audit work.

---

## Author

**Aryan Neupane**

Cybersecurity GRC · IAM Governance · ISO/IEC 27001 · NIST · Risk & Compliance

---

**Project Type:** Simulated IAM Governance & GRC Assessment
**Organization:** NexaCore Technologies
**Focus:** IAM Governance · Access Management · Risk · Compliance · Audit · Evidence
**Status:** In Progress



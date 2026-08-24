# NexaCore Technologies — IAM Governance & Access Review Assessment

A simulated, end-to-end IAM Governance & GRC engagement — built over a 7-day practical program — covering identity governance design, access control assessment, evidence-based control testing, risk-rated findings, remediation, and executive reporting for a fictional SaaS organization.

> **⚠️ Disclaimer:** NexaCore Technologies is entirely fictional. All identities, access records, findings, metrics, evidence, and management responses in this repository are simulated for educational and portfolio purposes. No production environment, real company, or real individual was accessed or represented. This project demonstrates IAM governance and assessment **methodology** — it is not a claim of production IAM implementation or employment experience.

---

## Project Overview

**Project:** IAM Governance & Access Review Assessment
**Organization:** NexaCore Technologies — Simulated SaaS Environment
**Role:** Junior Cybersecurity GRC / IAM Governance Analyst
**Format:** A single continuous 7-day simulated engagement, followed by a consolidated revision/interview-prep pack

NexaCore's leadership asked the (simulated) Junior GRC/IAM Governance Analyst to determine, ahead of an internal compliance review, whether the organization's identity and access management controls were appropriately governed — specifically whether access was authorized, followed least privilege, was reviewed on a defined cadence, and could be supported by evidence rather than assumption.

This repository is **not** a collection of unrelated exercises. Every day built directly on the artifacts, findings, and risks produced by the day before it, culminating in one coherent assessment report and portfolio package.

---

## Organization Background — NexaCore Technologies

| | |
|---|---|
| **Type** | Fictional mid-sized SaaS / technology company |
| **Size** | ~150 employees |
| **Departments** | Executive Leadership, Engineering, IT, Finance, HR, Sales, Customer Support |
| **Applications in scope** | Microsoft 365, GitHub, Jira, Salesforce, HRIS, Finance Platform, Cloud Environment |
| **Identity populations** | Employees, Contractors, Privileged Users, Service Accounts |

All systems, users, roles, findings, and evidence referenced throughout this project are fictional and were created specifically to support this exercise.

---

## The 7-Day Journey

Each day produced its own artifacts, which the following day extended rather than replaced — the same organization, roles, applications, and identities carry through the entire project.

| Day | Focus | Key Outputs |
|---|---|---|
| **Day 1** | IAM Fundamentals & Governance | IAM Governance Model, IAM Control Objectives Register (CO-01–06), NexaCore Environment Register, initial risk observations |
| **Day 2** | Identity Lifecycle & Access Governance | JML Procedure, Access Request Workflow, User Lifecycle Register, control objectives IAM-07–12 |
| **Day 3** | Access Controls, Privileged Access & Authentication Governance | NexaCore Role Model, Role-Permission Matrix, SoD Matrix, Privileged Access Register, Service Account Register, Authentication Control Register, control objectives IAM-13–17 |
| **Day 4** | IAM Assessment, Access Review & Risk | 24-record Access Review Register, Evidence Pack & Register, IAM Control Assessment, Findings Log, IAM Risk Register |
| **Day 5** | IAM Audit, Control Testing, Framework Mapping & Remediation | Design vs. operating effectiveness testing, 6 formal findings (FND5-01–06), ISO/IEC 27001 & NIST CSF 2.0 mapping, CAPA/Remediation Tracker |
| **Day 6** | IAM Governance Program, Exceptions, Metrics & Executive Reporting | Updated RACI Matrix, Governance Calendar, Exception Register, 12-metric KPI/KRI Dashboard, Governance Committee Charter, Executive IAM Summary |
| **Day 7 (Final)** | IAM Governance & Access Review Capstone | Final 18-record assessment dataset, 7 consolidated findings, final Control Assessment, final Risk Register, final CAPA Tracker, Final Assessment Report structure, Executive Summary, portfolio package |
| **Bonus** | Revision, Interview Prep & Capstone Defense Pack | Synthesized IAM/GRC revision guide, curated interview question bank, 8 scenario walkthroughs, 50-question rapid-fire round, one-page cheatsheet, capstone defense Q&A, revision plans |

### What Each Stage Actually Did

1. **Governance Baseline (Day 1)** — Established NexaCore's environment, governance roles, and six foundational control objectives (access authorized, least privilege, periodic review, timely deprovisioning, privileged access controlled, MFA enforced).
2. **Identity Lifecycle (Day 2)** — Documented the Joiner-Mover-Leaver process and tested a 12-event lifecycle dataset, surfacing early gaps (a mover's old access not removed, a contractor with no expiration date, an undocumented privileged grant).
3. **Access Control Model (Day 3)** — Built the reference model everything downstream would be tested against: role catalog, Role-Permission Matrix, SoD Matrix, Privileged Access Register, Service Account Register, and Authentication Control Register.
4. **Access Review (Day 4)** — Conducted an actual review of a 24-record population against that reference model, built an evidence pack (with two deliberate coverage gaps), and produced the first Findings Log and IAM Risk Register.
5. **Control Testing & Remediation (Day 5)** — Distinguished control *design* from *operating* effectiveness, tested 9 controls, consolidated the raw observations into 6 defensible findings, mapped them to ISO/IEC 27001:2022 and NIST CSF 2.0, and built the CAPA remediation tracker.
6. **Governance Program (Day 6)** — Turned point-in-time findings into an ongoing program: a refined RACI, a risk-based governance cadence, a formal exception-management process, a 12-metric KPI/KRI dashboard, and a governance committee charter.
7. **Capstone (Day 7)** — Assembled everything into one final assessment: an 18-record final dataset, 7 consolidated risk-rated findings, a final control assessment, a final remediation tracker, an executive summary, and the complete portfolio package (README, GitHub structure, LinkedIn content, interview walkthrough).
8. **Revision Pack (Bonus)** — Synthesized all seven days into a standalone study, interview-preparation, and project-defense resource.

---

## Repository Structure

```
iam-governance-grc-nexacore/
│
├── README.md                          ← you are here
│
├── day-01/                            IAM Fundamentals & Governance Baseline
├── day-02/                            Identity Lifecycle & JML
├── day-03/                            Access Controls & Privileged Access
├── day-04/                            Access Review, Evidence & Risk
├── day-05/                            Control Testing, Findings & Remediation
├── day-06/                            Governance Program, Exceptions & Metrics
├── day-07/                            Final Capstone Assessment & Portfolio
│
├── assessment/
│   ├── IAM-Assessment-Report.md
│   ├── Executive-Summary.md
│   ├── Findings-Register.csv
│   └── CAPA-Remediation-Tracker.csv
│
├── governance/
│   ├── IAM-Governance-Model.md
│   ├── IAM-Governance-Program.md
│   └── IAM-RACI-Matrix.csv
│
├── identity-lifecycle/
│   ├── JML-Procedure.md
│   ├── Access-Request-Workflow.md
│   └── User-Lifecycle-Register.csv
│
├── access-governance/
│   ├── Access-Control-Matrix.csv
│   ├── Role-Permission-Matrix.csv
│   ├── SoD-Matrix.csv
│   ├── Privileged-Access-Register.csv
│   └── Service-Account-Register.csv
│
├── evidence/
│   ├── Evidence-Register.csv
│   └── Control-Assessment.csv
│
├── risk/
│   └── IAM-Risk-Register.csv
│
├── framework-mapping/
│   └── IAM-Control-Mapping.csv
│
├── metrics/
│   └── IAM-KPI-KRI-Dashboard.csv
│
├── docs/
│   └── assessment-methodology.md
│
└── revision-and-interview-prep/
    └── IAM-GRC-Revision-Interview-Pack.html
```

> Folder names above are a recommended structure. If your working repository is already organized differently, there's no need to reorganize it just to match this layout — clarity matters more than exact folder naming.

---

## Methodology

Every control tested throughout this project followed the same reasoning chain:

```
Requirement → Control Objective → Control → Owner → Evidence →
Test → Result → Finding → Risk → Remediation → Validation
```

And every access decision was evaluated against the same core distinction that runs through the entire project:

> **"Does the user have access?"** is a different question from **"Does the user have appropriate access — authorized, least-privilege, owned, reviewed, and evidenced?"**

Findings were never written from observation alone. Each one traces to specific evidence, states a clear criteria (what should have existed), identifies a root cause (not just a symptom), and carries a defensible — not mathematically precise — risk rating.

---

## Key Results Summary

| Area | Result |
|---|---|
| Control objectives established | 17 (CO-01–06, IAM-07–17) |
| Access population reviewed (Day 4) | 24 records |
| Final assessment population (Day 7) | 18 records |
| Controls tested | 9 |
| Control test outcomes | 0 fully Effective · majority Partially Effective · 2 Ineffective |
| Formal findings (final, consolidated) | 7 (3 High risk, 4 Medium, 0 Critical) |
| Remediation actions tracked | 7–9 (varies by day; final tracker has 7) |
| Frameworks referenced | ISO/IEC 27001:2022, NIST CSF 2.0 (relevance mapping only) |
| Governance metrics tracked | 12 (KPI/KRI dashboard) |

These figures reflect a fictional sample population used to demonstrate methodology — they are not a claim about any real organization's security posture.

---

## Frameworks Used

- **ISO/IEC 27001:2022** — referenced for access control, identity management, authentication information, privileged access rights, and access-rights termination topic areas.
- **NIST CSF 2.0** — referenced primarily under the Protect function's Identity Management, Authentication, and Access Control (PR.AA) category.

Framework references in this project establish **relevance**, not compliance. Control effectiveness was established only through the evidence-based testing performed in Days 4, 5, and 7 — never by the framework mapping alone.

---

## Deliverables

**Governance:** IAM Governance Model · RACI Matrix · Control Objectives Register · Governance Committee Charter · Governance Calendar

**Identity Lifecycle:** JML Procedure · Access Request Workflow · User Lifecycle Register

**Access Governance:** Access/Role-Permission Matrix · SoD Matrix · Privileged Access Register · Service Account Register · Authentication Control Register

**Assessment:** Access Review Register · Evidence Register · IAM Control Assessment · Exception Register

**Risk & Remediation:** Findings Register · IAM Risk Register · CAPA/Remediation Tracker

**Reporting:** Final IAM Assessment Report · Executive Summary · KPI/KRI Dashboard · ISO/NIST Framework Mapping

**Portfolio:** This README · GitHub repository · Portfolio website project summary · LinkedIn content · Revision & Interview Preparation Pack

---

## Lessons Learned

- Most real IAM gaps come from **inconsistent execution of reasonably well-designed controls** — not from controls being entirely absent.
- **Policy evidence is not operating evidence.** A written requirement proves intent; only sampled, current, traceable evidence proves the control actually works.
- **A single root cause can explain multiple, seemingly unrelated findings** — for example, one missing HR-to-IAM automation trigger explained both a terminated employee's residual access and an ended contractor's residual access.
- **An observation is not a finding until it's investigated.** Several items in this project (a dormant-but-employed account, an ambiguous production access grant) deliberately stayed open as "requires investigation" rather than being forced into conclusions the evidence didn't yet support.
- **A metric moving in the "wrong" direction isn't automatically bad news** — in this project, MFA coverage appeared to dip and open findings appeared to rise in the same month a more rigorous assessment began actually testing the population directly. Detection improved; the environment didn't necessarily get worse.

---

## Limitations

This is a self-directed learning project using a fictional dataset, not a real client engagement. Sample sizes were kept intentionally small (18–24 records) to remain completable within a focused study session, and no control owners were actually interviewed — all management responses and risk acceptances are explicitly simulated. This project demonstrates the **methodology** an entry-level IAM/GRC analyst would apply, not the scale or rigor of a full enterprise engagement.

---

## About This Project

This project was completed as a structured, self-paced learning exercise to build practical, job-ready IAM Governance & GRC capability — the ability to assess whether access is appropriate, authorized, least-privileged, properly owned, adequately reviewed, and supported by evidence, and to communicate the results professionally to both technical and executive audiences.

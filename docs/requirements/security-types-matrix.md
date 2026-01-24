# Security Requirement Types Matrix  
## Conceptual Exoskeleton Platform

> **Important Note:**  
> This matrix classifies identified security requirements by the primary security properties they support.  
> Classification is analytical in nature and does not imply implementation or validation.

---

## Evidence Source
This matrix is derived from the original academic deliverable:

- Exoskeleton Security Requirements Exercise (PDF)

An unmodified copy of the original submission is available in:

assets/original-deliverables/

---

## Purpose
The purpose of this matrix is to demonstrate how each security requirement contributes to one or more security objectives, including:

- Confidentiality (C)  
- Integrity (I)  
- Availability (A)  
- Authentication (AuthN)  
- Authorization (AuthZ)  
- Auditability (Audit)  
- Safety (Safety)

Some requirements support multiple objectives; classification reflects the **primary** focus identified during analysis.

---

## Security Requirement Classification

| Security Requirement | C | I | A | AuthN | AuthZ | Audit | Safety |
|----------------------|---|---|---|-------|--------|-------|--------|
| SR001 – Role-Based Access Control |   | ✔ |   |   | ✔ |   |   |
| SR002 – Multi-Factor Authentication |   |   |   | ✔ |   |   |   |
| SR003 – Auditing and Traceability |   | ✔ |   |   |   | ✔ |   |
| SR004 – Tool and Interface Validation |   | ✔ |   |   | ✔ |   |   |
| SR005 – Secure Communications | ✔ | ✔ |   |   |   |   |   |
| SR006 – Safe Failure Behavior |   |   | ✔ |   |   |   | ✔ |
| SR007 – Secure Maintenance Mode |   | ✔ |   |   | ✔ |   |   |
| SR008 – Network Segmentation |   |   | ✔ |   |   |   |   |
| SR009 – Data Archival Protection | ✔ | ✔ |   |   |   |   |   |
| SR010 – Secure Local Storage | ✔ | ✔ |   |   |   |   |   |
| SR011 – Secure Remote Access | ✔ | ✔ |   | ✔ |   |   |   |
| SR012 – Failure and Anomaly Alerts |   |   | ✔ |   |   | ✔ |   |
| SR013 – Input Validation |   | ✔ |   |   |   |   | ✔ |

---

## Interpretation Notes
- A checkmark indicates that the requirement primarily supports the listed security objective.
- Absence of a checkmark does not imply no contribution, only that the objective was not the primary focus.
- Safety is treated as a first-class concern due to the cyber-physical nature of the system.

---

## Relationship to Other Artifacts
This classification supports:
- Risk impact analysis
- Abuse case prioritization
- Security architecture reasoning
- Lessons learned and tradeoff discussions


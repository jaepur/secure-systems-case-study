# Types of Security Requirements to Security Requirements Matrix  
## NextGen Exoskeleton Navigator (Academic Case Study)

> **Important Note:**  
> This matrix represents a classification of identified security requirements against
> industry-accepted security requirement types as part of an academic design-time analysis.
> The categories below are used strictly for analytical coverage and traceability.
> This matrix does not imply implementation, enforcement, or validation of any control.

---

## Evidence Source
This document is derived directly from the original academic deliverable:

- *Types of Security Requirements to Security Requirements Matrix*  
  (NextGen Exoskeleton Navigator – Security Requirements Exercise)

An unmodified copy of the original submission is available in:

---

## Purpose
The purpose of this matrix is to provide a **visual relational mapping** between identified
security requirements and recognized security requirement types. This classification supports
analysis of coverage across multiple security dimensions relevant to a cyber-physical system.

Each mapping reflects how a given security requirement was **categorized** during the original
exercise, not how it would be technically implemented.

---

## Security Requirements Classification Matrix

| Req.  | C | I | A | T | AU | AO | SES | ER | CPM | ST | AR | INT | DE |
|------:|:-:|:-:|:-:|:-:|:--:|:--:|:---:|:--:|:---:|:--:|:--:|:---:|:--:|
| SR001 |   |   |   |   | ✔ | ✔ |     |    |     |    |    |     |    |
| SR002 | ✔ |   |   |   | ✔ | ✔ |     |    |     |    |    |     |    |
| SR003 |   |   |   | ✔ |    |    |     |    |     |    |    |     |    |
| SR004 |   |   |   |   | ✔ |    |     |    |     |    |    |     |    |
| SR005 | ✔ | ✔ |   |   |    |    |     |    |     |    |    |     |    |
| SR006 | ✔ | ✔ |   |   |    |    |     | ✔ |     |    |    |     |    |
| SR007 |   |   |   | ✔ | ✔ |    | ✔   |    |     |    |    |     |    |
| SR008 | ✔ | ✔ |   |   |    | ✔ |     |    | ✔   |    |    |     | ✔  |
| SR009 |   |   |   |   |    |    | ✔   |    |     |    | ✔  |     |    |
| SR010 | ✔ | ✔ | ✔ |   |    |    |     |    |     |    | ✔  |     |    |
| SR011 | ✔ | ✔ |   |   | ✔ | ✔ | ✔   |    |     |    |    |     |    |
| SR012 |   |   |   |   |    |    |     | ✔ |     |    |    |     | ✔  |
| SR013 |   | ✔ | ✔ |   |    |    |     | ✔ |     |    |    |     |    |

---

## Security Requirement Type Legend

- **C** – Confidentiality  
- **I** – Integrity  
- **A** – Availability  
- **T** – Traceability  
- **AU** – Authentication  
- **AO** – Authorization  
- **SES** – Session Management  
- **ER** – Error, Exception, and Management  
- **CPM** – Configuration Parameters Management  
- **ST** – Sequencing and Timing  
- **AR** – Archiving Requirements  
- **INT** – International  
- **DE** – Deployment Environment  

---

## Interpretation Notes
- A checkmark (✔) indicates that the security requirement was classified under the
  corresponding security requirement type in the original exercise.
- A security requirement may map to multiple types.
- The absence of a mapping does not imply irrelevance, only that the category was not
  associated with that requirement during analysis.
- These categories are used for **analytical classification only** and do not represent
  implemented system features.

---

## Relationship to Other Artifacts
This matrix supports and complements:
- Security Requirements
- Software-to-Security Traceability Matrix
- Threat Identification and Risk Analysis

It provides context for understanding how security concerns were distributed across
functional and non-functional dimensions during the assessment.

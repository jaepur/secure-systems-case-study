
# Software-to-Security Traceability Matrix  
## Conceptual Exoskeleton Platform

> **Important Note:**  
> This matrix represents a design-time mapping between functional software requirements and identified security requirements.  
> Mappings indicate conceptual dependency, not implemented enforcement.

---

## Evidence Source
This traceability matrix is derived from the original academic deliverable:

- Exoskeleton Security Requirements Exercise (PDF)

An unmodified copy of the original submission is available in:

assets/original-deliverables/

---

## Purpose
The purpose of this matrix is to demonstrate how security requirements directly support and constrain functional software requirements.

Each mapping reflects the rationale that failure to meet the associated security requirement could compromise the corresponding software requirement.

---

## Traceability Matrix

| Software Requirement | Description (Summary)                     | Supporting Security Requirements |
|---------------------|-------------------------------------------|----------------------------------|
| R001 | Pilot role adaptability | SR001, SR002 |
| R002 | Human-controlled operation | SR001, SR003, SR006 |
| R003 | Remote operation | SR001, SR002, SR005, SR011 |
| R004 | Autonomous operation | SR001, SR003, SR006 |
| R005 | Mode transition capability | SR001, SR003, SR013 |
| R006 | Operational feedback | SR003, SR005 |
| R007 | Command acceptance | SR001, SR013 |
| R008 | Maintenance mode support | SR001, SR004, SR007 |
| R009 | Maintenance diagnostics | SR004, SR007 |
| R010 | Data collection | SR003, SR005 |
| R011 | Data storage | SR009, SR010 |
| R012 | Fault detection | SR003, SR012 |
| R013 | Safe failure behavior | SR006 |
| R014 | Recovery capability | SR006, SR007 |
| R015 | Multi-environment operation | SR005, SR008, SR011 |

---

## Interpretation Notes
- A single software requirement may depend on multiple security requirements.
- Security requirements may support multiple software requirements.
- The absence of a mapping does not imply irrelevance, only that no direct dependency was identified during this assessment.

---

## Relationship to Other Artifacts
This matrix directly links:

- `software-requirements.md`
- `security-requirements.md`

It also informs:
- Use and abuse case modeling
- Threat identification
- Risk prioritization

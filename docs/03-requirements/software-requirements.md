# Software Requirements  
## Conceptual Exoskeleton Platform

> **Important Note:**  
> This document records functional software requirements identified during an academic design-time assessment.  
> These requirements represent *modeled system behavior* and do not imply implementation or deployment.

---

## Evidence Source
This document is derived from the original academic deliverable:

- Exoskeleton Security Requirements Exercise (PDF)

An unmodified copy of the original submission is available in: 
docs/original-deliverables/

---

## Requirement Scope
The software requirements listed below define expected system behavior related to operation, control, monitoring, and maintenance of the modeled exoskeleton platform.

They do **not** define:
- Specific hardware implementations
- Network protocols
- Security controls (addressed separately)
- Performance benchmarks

---

## Software Requirements

### R001 – Pilot Role Adaptability
The system shall support role-based interaction to allow different categories of authorized users to operate or interact with the exoskeleton platform in accordance with their assigned role.

---

### R002 – Human-Controlled Operation
The system shall support direct human operation in which the exoskeleton responds to physical input from the operator.

---

### R003 – Remote Operation
The system shall support remote operation, allowing authorized users to issue commands to the exoskeleton without physical presence.

---

### R004 – Autonomous Operation
The system shall support autonomous operation in which the exoskeleton performs actions based on predefined logic without continuous human input.

---

### R005 – Mode Transition Capability
The system shall allow transitions between human-controlled, remote-controlled, and autonomous modes when authorized and appropriate system conditions are met.

---

### R006 – Operational Feedback
The system shall provide feedback regarding operational status, system health, and fault conditions to authorized users.

---

### R007 – Command Acceptance
The system shall accept operational commands only when received through supported interfaces and during valid operational states.

---

### R008 – Maintenance Mode Support
The system shall support a maintenance mode intended for diagnostics, configuration, and repair activities.

---

### R009 – Maintenance Diagnostics
The system shall provide diagnostic information during maintenance activities to support troubleshooting and recovery.

---

### R010 – Data Collection
The system shall collect operational and telemetry data relevant to system performance and status.

---

### R011 – Data Storage
The system shall store collected data locally or within a supporting environment for later review or analysis.

---

### R012 – Fault Detection
The system shall detect fault conditions that may impact safe or reliable operation.

---

### R013 – Safe Failure Behavior
The system shall enter a defined safe state when critical faults are detected or when safe operation cannot be assured.

---

### R014 – Recovery Capability
The system shall support recovery from fault or failure conditions following corrective action.

---

### R015 – Multi-Environment Operation
The system shall support operation across multiple environments, including field deployment, command oversight, and maintenance contexts.

---

## Notes on Interpretation
- Requirement identifiers are retained to support traceability across project artifacts.
- These requirements represent *what the system is expected to do*, not *how it does it*.
- Security requirements that constrain or protect these behaviors are documented separately.

---

## Relationship to Other Artifacts
The software requirements defined in this document are referenced by:

- Security Requirements  
- Software-to-Security Traceability Matrix  
- Use and Abuse Case Models  
- Threat Catalog  
- Risk Register


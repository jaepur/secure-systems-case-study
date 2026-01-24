# Use Case Modeling  
## NextGen Exoskeleton Navigator (Academic Case Study)

> **Important Note:**  
> The use cases documented below are reproduced from the original academic submission
> with formatting changes only. No content has been added, removed, or reinterpreted.

---

## Evidence Source
This document is derived directly from the original academic deliverable:

- *NextGen Exoskeleton Navigator – Use & Abuse Case Modeling Report*  
  (CEN 4078, Spring 2024)

An unmodified copy of the original submission is available in:

assets/original-deliverables/

---

## Use Case Table

Documented below is a subset of use cases identified as fundamental use cases relative to
the NextGen Exoskeleton Navigator system. The ten cases are organized by ID, name, actor,
goal, precondition, and postcondition.

---

### UC-1 — Exoskeleton Login
**Actor:** User  

**Goal:**  
Log user into NextGen exoskeleton.

**Preconditions:**  
Exoskeleton is powered on and fully functional.

**Postconditions:**  
Authorized user is logged in to the NextGen Exoskeleton.

---

### UC-2 — Scientist Tool Attachment
**Actor:** Scientist  

**Goal:**  
Attach scientist personnel tools.

**Preconditions:**  
Exoskeleton is powered on, and user is logged in.

**Postconditions:**  
Scientific personnel tool has been attached.

---

### UC-3 — Engineer Tool Attachment
**Actor:** Engineer  

**Goal:**  
Attach engineering personnel tools.

**Preconditions:**  
Exoskeleton is powered on and user is logged in.

**Postconditions:**  
Engineering personnel tool has been attached.

---

### UC-4 — Security Tool Attachment
**Actor:** Security Personnel  

**Goal:**  
Attach security personnel tools.

**Preconditions:**  
Exoskeleton is powered on, and user is logged in.

**Postconditions:**  
Security personnel tool has been attached.

---

### UC-5 — Tool Attachment Request
**Actor:** Exoskeleton User  

**Goal:**  
Submit tool attachment requests.

**Preconditions:**  
User has logged in and has been authorized.

**Postconditions:**  
Tool attachment request has been successfully sent to upper management.

---

### UC-6 — Drone Remote Control
**Actor:** Drone Operator  

**Goal:**  
Initiate remote control of NextGen Exoskeleton.

**Preconditions:**  
Exoskeleton is powered on, and DOC controller is logged in.

**Postconditions:**  
DOC operator is remotely controlling the NGEN drone.

---

### UC-7 — DOC Drone Subnet Assignment
**Actor:** Drone Operator  

**Goal:**  
Assign individual drones.

**Preconditions:**  
NGEN drones are powered on but not yet deployed.

**Postconditions:**  
NGEN drones have been assigned to their designated group subnet.

---

### UC-8 — Drone Maintenance Mode
**Actor:** Maintenance  

**Goal:**  
Emplace NGEN Drone into maintenance mode.

**Preconditions:**  
NGEN drones are powered off and connected to a workstation in the maintenance shop.

**Postconditions:**  
Drone is in a dormant maintenance mode state.

---

### UC-9 — Exoskeleton Autonomous Mode
**Actor:** Drone Operator  

**Goal:**  
Initiate autonomous drone operations.

**Preconditions:**  
Drone is powered on and connected to the NextGen network.

**Postconditions:**  
NGEN drone operates autonomously via NGENius AI.

---

### UC-10 — Exoskeleton Connectivity
**Actor:** NGENius Logic System  

**Goal:**  
Initiate network connectivity mode changeover.

**Preconditions:**  
Exoskeleton is powered on, logged into, and connected to the NextGen network.

**Postconditions:**  
The NGENius logic system changes network connectivity modes.

---

## Use Case Coverage Summary

The documented use cases represent core functional behaviors of the
NextGen Exoskeleton Navigator system as modeled in the original academic
exercise.

Collectively, the use cases cover:

- User authentication and system access
- Role-specific tool attachment workflows
- Remote and autonomous operational modes
- Network connectivity and subnet assignment
- Maintenance and recovery-related activities

These use cases establish a baseline understanding of intended system
operation prior to introducing misuse, abuse, and adversarial scenarios.

## Security-Relevant Observations

Review of the legitimate use cases highlights several areas with
security relevance:

- UC-1 (Exoskeleton Login) is a prerequisite for multiple downstream
  actions, making identity verification a foundational dependency.
- UC-2 through UC-5 imply role differentiation between users based on
  tool attachment permissions.
- UC-6 (Drone Remote Control) and UC-9 (Autonomous Operation) introduce
  remote and non-local control paths that expand the system’s attack surface.
- UC-7 and UC-8 involve configuration and maintenance activities that
  assume elevated privileges.
- UC-10 reflects dynamic network connectivity behavior, which has
  implications for trust boundaries and control flow.

These observations were used to guide subsequent abuse case modeling,
threat identification, and risk analysis.

## Relationship to Abuse Case Modeling

Each use case documented above was evaluated to identify corresponding
abuse cases representing misuse, unauthorized actions, or failure scenarios.

Abuse cases were derived by examining:
- Violations of stated preconditions
- Unauthorized attempts to achieve legitimate goals
- Abuse of elevated privileges or trust assumptions

The resulting abuse cases are documented separately and reference
these use cases as their operational baseline.

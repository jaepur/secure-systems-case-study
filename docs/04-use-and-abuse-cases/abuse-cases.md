# Abuse Case Modeling  
## NextGen Exoskeleton Navigator (Academic Case Study)

> **Important Note:**  
> The abuse cases documented below are reproduced from the original academic submission
> with formatting changes only. No content has been added, removed, or reinterpreted.

---

## Evidence Source
This document is derived directly from the original academic deliverable:

- *NextGen Exoskeleton Navigator – Use & Abuse Case Modeling Report*  
  (CEN 4078, Spring 2024)

An unmodified copy of the original submission is available in:

assets/original-deliverables/

---

## Abuse Case Table

The abuse cases below represent misuse, malicious actions, or failure scenarios
derived from the legitimate use cases documented previously. These cases model
how system functionality could be abused if assumptions are violated.

---

### AC-1 — Unauthorized Exoskeleton Login
**Actor:** Unauthorized User  

**Goal:**  
Gain access to the NextGen exoskeleton without authorization.

**Preconditions:**  
Exoskeleton is powered on and connected to the network.

**Postconditions:**  
Unauthorized user is logged into the NextGen Exoskeleton.

---

### AC-2 — Unauthorized Tool Attachment
**Actor:** Unauthorized User  

**Goal:**  
Attach unauthorized personnel tools to the exoskeleton.

**Preconditions:**  
User has gained access to the exoskeleton.

**Postconditions:**  
Unauthorized tool has been attached.

---

### AC-3 — Privilege Escalation via Tool Request
**Actor:** Authorized User  

**Goal:**  
Gain unauthorized access to restricted tools.

**Preconditions:**  
User is logged in with standard privileges.

**Postconditions:**  
User has access to tools beyond assigned role.

---

### AC-4 — Remote Control Hijacking
**Actor:** Malicious Remote Actor  

**Goal:**  
Take control of the exoskeleton remotely.

**Preconditions:**  
Remote control capability is enabled.

**Postconditions:**  
Attacker is issuing remote commands.

---

### AC-5 — Subnet Reassignment Abuse
**Actor:** Unauthorized User  

**Goal:**  
Reassign drones to unauthorized subnets.

**Preconditions:**  
User has access to subnet assignment interface.

**Postconditions:**  
Drone subnet assignments are altered.

---

### AC-6 — Maintenance Mode Abuse
**Actor:** Unauthorized User  

**Goal:**  
Enter maintenance mode without authorization.

**Preconditions:**  
Exoskeleton or drone is connected to a maintenance workstation.

**Postconditions:**  
System is placed into maintenance mode.

---

### AC-7 — Autonomous Mode Manipulation
**Actor:** Malicious Actor  

**Goal:**  
Manipulate autonomous operation behavior.

**Preconditions:**  
Autonomous mode is enabled.

**Postconditions:**  
System operates under altered autonomous parameters.

---

### AC-8 — Network Connectivity Disruption
**Actor:** Malicious Actor  

**Goal:**  
Disrupt network connectivity modes.

**Preconditions:**  
System is connected to the NextGen network.

**Postconditions:**  
Connectivity mode is altered or disrupted.

---

### AC-9 — Diagnostic Data Misuse
**Actor:** Unauthorized User  

**Goal:**  
Access or misuse diagnostic data.

**Preconditions:**  
System is in maintenance or diagnostic mode.

**Postconditions:**  
Sensitive diagnostic data is accessed.

---

### AC-10 — Denial of Operation
**Actor:** Malicious Actor  

**Goal:**  
Prevent normal operation of the exoskeleton.

**Preconditions:**  
System is operational.

**Postconditions:**  
Exoskeleton operation is degraded or unavailable.

## Abuse Case Coverage Summary

The documented abuse cases model a range of misuse scenarios, including:

- Unauthorized access and authentication bypass
- Privilege escalation through legitimate workflows
- Remote command and control abuse
- Misuse of maintenance and diagnostic capabilities
- Disruption of network connectivity and operational availability

These abuse cases reflect realistic failure and threat scenarios that may arise
when trust assumptions are violated in a cyber-physical system.

## Security-Relevant Observations

Analysis of the abuse cases highlights several recurring themes:

- Authentication-related abuse (AC-1) enables multiple downstream attacks.
- Tool attachment and role misuse (AC-2, AC-3) indicate the importance of
  role differentiation and authorization boundaries.
- Remote and autonomous operation abuse (AC-4, AC-7) introduce high-impact
  safety and control risks.
- Maintenance and diagnostic access (AC-6, AC-9) represent elevated-risk
  scenarios due to increased system privileges.
- Network-related abuse cases (AC-5, AC-8, AC-10) emphasize the importance
  of maintaining operational availability and integrity.

These observations informed subsequent threat identification and risk analysis.

## Relationship to Other Artifacts

The abuse cases documented in this file directly informed:

- Threat identification and vulnerability analysis
- Risk register development and prioritization
- Security requirement justification and refinement

Each abuse case is traceable to one or more legitimate use cases and highlights
potential consequences of insufficient security controls or failed assumptions.

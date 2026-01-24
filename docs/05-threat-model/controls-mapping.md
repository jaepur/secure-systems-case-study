# Controls Mapping  
## NextGen Exoskeleton Navigator (Academic Case Study)

> **Important Note:**  
> This document consolidates and categorizes mitigation strategies identified
> in the original threat analysis. It does not introduce new controls, nor does
> it imply implementation, validation, or testing of any mitigation.

---

## Evidence Source
This document is derived directly from the original academic deliverable:

- *NextGen Exoskeleton Navigator – Security Threat Exercise*

An unmodified copy of the original submission is available in:

assets/original-deliverables/

---

## Purpose
The purpose of this document is to organize the mitigation strategies identified
in the Threat Catalog into logical control groupings. This supports:

- Understanding how threats are addressed conceptually
- Identifying common mitigation themes
- Informing later risk prioritization

---

## Control Groupings

### Physical Security Controls
Mitigations addressing threats involving physical access to system components.

**Derived from:**
- T-01 (Physical Access to Exoskeleton)

**Mitigation Themes:**
- Physical barriers
- Guards and monitoring
- Environmental protections

---

### Communication Protection Controls
Mitigations addressing threats involving interception or manipulation of data in transit.

**Derived from:**
- T-02 (Interception of Communication)
- T-10 (Data Tampering)

**Mitigation Themes:**
- Encryption of data in transit
- Secure communication channels

---

### Identity and Access Controls
Mitigations addressing unauthorized access and misuse of system privileges.

**Derived from:**
- T-03 (Unauthorized Remote Access)
- T-05 (Insider Threat)
- T-06 (Maintenance Interface Abuse)

**Mitigation Themes:**
- Authentication mechanisms
- Role-based access restrictions
- Auditing and access monitoring

---

### Session Management Controls
Mitigations addressing threats involving active session compromise.

**Derived from:**
- T-04 (Session Hijacking)

**Mitigation Themes:**
- Session control mechanisms
- Session monitoring

---

### Configuration and Integrity Controls
Mitigations addressing unauthorized modification of system logic or parameters.

**Derived from:**
- T-07 (Autonomous Logic Manipulation)
- T-10 (Data Tampering)

**Mitigation Themes:**
- Integrity protection
- Configuration safeguards

---

### Network Segmentation Controls
Mitigations addressing propagation of compromise across environments.

**Derived from:**
- T-08 (Network Segmentation Failure)

**Mitigation Themes:**
- Logical separation of operational environments
- Isolation between trust zones

---

### Availability and Monitoring Controls
Mitigations addressing disruption of system availability.

**Derived from:**
- T-09 (Denial of Service)

**Mitigation Themes:**
- Monitoring mechanisms
- Availability protections

---

## Relationship to Other Artifacts
This controls mapping:
- References mitigations documented in the Threat Catalog
- Informs impact assessment in the Risk Register
- Supports discussion of layered defense concepts without implying implementation

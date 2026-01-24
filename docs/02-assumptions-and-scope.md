# Assumptions and Scope

## Purpose of This Document
This document explicitly defines the assumptions and boundaries used throughout this security assessment.  
All subsequent artifacts—including requirements, use/abuse cases, threat models, and risk analysis—are derived from the assumptions listed here.

No assumptions beyond those documented below were used.

---

## Evidence Sources
The assumptions documented in this section are derived directly from the following original academic deliverables:

- Exoskeleton Security Requirements Exercise (PDF)  
- Exoskeleton Use & Abuse Case Modeling Report (PDF)  
- Exoskeleton Threat Analysis Exercise (PDF)  
- Exoskeleton Risk Management Exercise (PDF)  

Original, unmodified versions of these documents are available in:


---

## System Assumptions

### A1. Conceptual System Representation
The exoskeleton platform is modeled as a conceptual cyber-physical system for academic analysis purposes.

- No real hardware, firmware, or software implementation is evaluated
- No vendor-specific technologies are assumed
- Architectural representations are logical rather than physical

This assumption applies globally across all project artifacts.

---

### A2. Multi-Mode Operation
The system is assumed to support multiple operational modes:

- Human-controlled operation
- Remote-controlled operation
- Autonomous operation

Security analysis assumes that transitions between these modes are possible and require authorization, but the specific mechanisms for transition are not defined.

---

### A3. Distributed Deployment Environment
The system is assumed to be deployed across multiple environments, including:

- Field-deployed exoskeleton units
- Command and control environments
- Maintenance and support environments

These environments are treated as logically distinct trust zones for analysis purposes.

---

### A4. Network Connectivity
It is assumed that exoskeleton units communicate with supporting systems over networked connections.

- Communication may occur over potentially untrusted or contested networks
- Network availability and integrity cannot be guaranteed at all times

Specific protocols, bandwidth constraints, and physical network implementations are not specified.

---

### A5. Role-Based Access
The system is assumed to support multiple user roles, including but not limited to:

- Human operators
- Remote supervisors
- Maintenance personnel
- Administrative or command staff

Access privileges are assumed to vary by role, but detailed role definitions are abstracted.

---

### A6. Physical Accessibility
Field-deployed exoskeleton units are assumed to be physically accessible to authorized users and potentially to unauthorized individuals.

- Physical access is treated as a realistic threat vector
- Physical security controls are considered but not validated

---

### A7. Maintenance and Recovery Interfaces
The system is assumed to include maintenance, diagnostics, and recovery interfaces.

- These interfaces are assumed to require elevated privileges
- Misuse or abuse of maintenance access is treated as a high-risk scenario

---

## Security Analysis Assumptions

### S1. Design-Time Analysis Only
All security analysis in this project is performed at design time.

- No live system testing is conducted
- No penetration testing or exploitation is performed
- Findings represent potential risks, not confirmed vulnerabilities

---

### S2. Control Recommendations Are Not Implementations
Security controls identified in this project are recommendations based on analysis.

- Controls are not implemented or validated
- Effectiveness is reasoned conceptually, not empirically

---

### S3. Adversary Modeling
Adversaries are modeled abstractly and may include:

- External attackers
- Insider threats
- Malicious or negligent users

No specific threat actor groups or real-world intelligence sources are assumed.

---

## Out of Scope

The following items are explicitly out of scope for this project:

- Real-world deployment or operational evaluation
- Hardware-level fault analysis
- Firmware reverse engineering
- Live exploitation or red-team activity
- Compliance certification or accreditation

---

## Impact on Subsequent Artifacts
All subsequent documents in this repository inherit the assumptions defined here.

If an assumption listed in this document were to change, the following artifacts would require re-evaluation:

- Software and security requirements
- Use and abuse cases
- Threat catalog
- Risk register and prioritization

This document serves as the authoritative scope boundary for the entire project.

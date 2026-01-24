# Risk Register  
## NextGen Exoskeleton Navigator (Academic Case Study)

> **Important Note:**  
> The risks documented below are reproduced from the original academic submission
> with formatting changes only. No content has been added, removed, or reinterpreted.

---

## Evidence Source
This document is derived directly from the original academic deliverable:

- *NextGen Exoskeleton Navigator – Risk Management Exercise*  
  (CEN 4078, Spring 2024)

An unmodified copy of the original submission is available in:

assets/original-deliverables/

---

## Purpose
The purpose of this document is to catalog and prioritize technical risks
identified for the NextGen Exoskeleton Navigator system. Risks are evaluated
based on their potential impact to business functions and the likelihood
of realization.

---

## Technical Risk Register

---

### Technical Risk 01 — Session and Permission Transition Failure
**Risk ID:** TeR-01  

**Technical Security Risk:**  
Failure to properly transition between pilot sessions and their designated permissions.

**Business Impact(s):**  
Potential financial costs due to tool misuse and system/property damage.  
Possible non-compliance violations if security personnel tools are accessed.

**Risk Realization Point:**  
Remote or physical session management interfaces within NGEN Navigator Exoskeleton suits.

**InfoSec Triad Impact:**  
- **Confidentiality:** Unauthorized access to pilot session data containing PII.  
- **Availability:** Unauthorized tool usage may damage equipment and property.  
- **Integrity:** Non-applicable.

**Business Impact Scores:**  
- Financial Damages: 3  
- Reputational Damages: 9  
- Non-compliance: 5  
- Privacy Violation: 0  

**Overall Likelihood:** 4.25

---

### Technical Risk 02 — Communication Interception
**Risk ID:** TeR-02  

**Technical Security Risk:**  
Threat actor interception of communications on insecure lines between NGEN Exoskeletons and DOCs.

**Business Impact(s):**  
Possible financial costs due to reputational damages and non-compliance charges.

**Risk Realization Point:**  
Wireless or physical data transmission links between NGEN Exoskeletons and Drone Operations Centers.

**InfoSec Triad Impact:**  
- **Confidentiality:** Exposure of PII, confidential, and restricted data.  
- **Availability:** Non-applicable.  
- **Integrity:** Non-applicable.

**Business Impact Scores:**  
- Financial Damages: 7  
- Reputational Damages: 9  
- Non-compliance: 7  
- Privacy Violation: 9  

**Overall Likelihood:** 8

---

### Technical Risk 03 — Unauthorized Exoskeleton Access
**Risk ID:** TeR-03  

**Technical Security Risk:**  
Unauthorized access to NGEN Exoskeletons by non-NextGen personnel.

**Business Impact(s):**  
Unauthorized use of NGEN property and tools resulting in financial and reputational damage.

**Risk Realization Point:**  
Remote or physical session management interfaces within NGEN Navigator Exoskeleton suits.

**InfoSec Triad Impact:**  
- **Confidentiality:** Unauthorized access to sensitive information.  
- **Availability:** System misuse or disruption.  
- **Integrity:** Compromise of local data storage.

**Business Impact Scores:**  
- Financial Damages: 3  
- Reputational Damages: 5  
- Non-compliance: 7  
- Privacy Violation: 3  

**Overall Likelihood:** 4.5

---

### Technical Risk 04 — Power System Failure
**Risk ID:** TeR-04  

**Technical Security Risk:**  
NGEN Exoskeleton system power failure.

**Business Impact(s):**  
Financial costs due to asset damage or personnel harm and loss of productivity.

**Risk Realization Point:**  
NGEN Navigator Exoskeleton power supply/system.

**InfoSec Triad Impact:**  
- **Confidentiality:** Non-applicable.  
- **Availability:** System becomes unresponsive.  
- **Integrity:** Potential data corruption.

**Business Impact Scores:**  
- Financial Damages: 2  
- Reputational Damages: 1  
- Non-compliance: 2  
- Privacy Violation: 0  

**Overall Likelihood:** 1.25

---

### Technical Risk 05 — Deprecated Encryption Standards
**Risk ID:** TeR-05  

**Technical Security Risk:**  
Data breach resulting from the use of deprecated encryption standards.

**Business Impact(s):**  
Financial, privacy, non-compliance, and reputational damages.

**Risk Realization Point:**  
Databases within NGEN Exoskeletons, DOCs, and Command Centers.

**InfoSec Triad Impact:**  
- **Confidentiality:** Exposure of private and restricted data.  
- **Availability:** Non-applicable.  
- **Integrity:** Potential data tampering.

**Business Impact Scores:**  
- Financial Damages: 6  
- Reputational Damages: 9  
- Non-compliance: 7  
- Privacy Violation: 9  

**Overall Likelihood:** 7.75

---

### Technical Risk 06 — Untraceable User Activity
**Risk ID:** TeR-06  

**Technical Security Risk:**  
Unsupervised and untraceable activity on NextGen software systems.

**Business Impact(s):**  
Financial and privacy damages.

**Risk Realization Point:**  
User access surfaces such as workstations and exoskeleton GUIs.

**InfoSec Triad Impact:**  
- **Confidentiality:** Inability to trace unauthorized access.  
- **Availability:** Non-applicable.  
- **Integrity:** Unaccountable data modification.

**Business Impact Scores:**  
- Financial Damages: 2  
- Reputational Damages: 4  
- Non-compliance: 5  
- Privacy Violation: 9  

**Overall Likelihood:** 5

---

### Technical Risk 07 — Improper Error Handling
**Risk ID:** TeR-07  

**Technical Security Risk:**  
Unauthorized access due to inadequate handling of software errors.

**Business Impact(s):**  
Financial and reputational damages via privacy violations and data exfiltration.

**Risk Realization Point:**  
Software interfaces such as login screens and exoskeleton GUIs.

**InfoSec Triad Impact:**  
- **Confidentiality:** Disclosure of internal system information.  
- **Availability:** System crashes.  
- **Integrity:** Data corruption.

**Business Impact Scores:**  
- Financial Damages: 3  
- Reputational Damages: 4  
- Non-compliance: 2  
- Privacy Violation: 7  

**Overall Likelihood:** 4

---

### Technical Risk 08 — Malicious Hardware Insertion
**Risk ID:** TeR-08  

**Technical Security Risk:**  
Threat actors inserting malicious USB drives or hardware.

**Business Impact(s):**  
Loss, corruption, or destruction of critical data and property.

**Risk Realization Point:**  
Human-to-software interfaces such as workstations, exoskeletons, and devices.

**InfoSec Triad Impact:**  
- **Confidentiality:** Data exfiltration.  
- **Availability:** System disruption.  
- **Integrity:** Data corruption.

**Business Impact Scores:**  
- Financial Damages: 7  
- Reputational Damages: 4  
- Non-compliance: 5  
- Privacy Violation: 7  

**Overall Likelihood:** 5.75

---

### Technical Risk 09 — Insider Threat
**Risk ID:** TeR-09  

**Technical Security Risk:**  
Internal threats leading to privilege abuse and data breach.

**Business Impact(s):**  
Financial and reputational damages.

**Risk Realization Point:**  
Internal user interfaces such as workstations and servers.

**InfoSec Triad Impact:**  
- **Confidentiality:** Internal sabotage or data breach.  
- **Availability:** Asset destruction.  
- **Integrity:** Unauthorized data modification.

**Business Impact Scores:**  
- Financial Damages: 7  
- Reputational Damages: 9  
- Non-compliance: 5  
- Privacy Violation: 9  

**Overall Likelihood:** 7.5

---

### Technical Risk 10 — Natural Disaster Communication Failure
**Risk ID:** TeR-10  

**Technical Security Risk:**  
Failure of network communication links due to natural disasters.

**Business Impact(s):**  
Loss of productivity and inability to control exoskeletons remotely.

**Risk Realization Point:**  
All NGEN deployment sites.

**InfoSec Triad Impact:**  
- **Confidentiality:** Non-applicable.  
- **Availability:** Loss of communication and control.  
- **Integrity:** Non-applicable.

**Business Impact Scores:**  
- Financial Damages: 5  
- Reputational Damages: 0  
- Non-compliance: 0  
- Privacy Violation: 0  

**Overall Likelihood:** 1.25

---

## Risk Prioritization Summary

- **Highest Priority Risk:**  
  Technical Risk 02 — Interception of communications between NGEN Exoskeletons and DOCs.

- **Lowest Priority Risk:**  
  Technical Risk 10 — Communication failures due to natural disasters.

---

## Relationship to Other Artifacts
This risk register:
- Is derived from identified threats and abuse cases
- Is informed by mitigation groupings in the Controls Mapping
- Supports structured risk prioritization without implying mitigation implementation

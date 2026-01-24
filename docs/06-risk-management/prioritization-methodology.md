# Risk Prioritization Method  
## NextGen Exoskeleton Navigator (Academic Case Study)

> **Important Note:**  
> This document describes the risk prioritization approach used in the original
> academic submission. It does not introduce new scoring models, frameworks,
> or recalculated values.

---

## Evidence Source
This document is derived directly from the original academic deliverable:

- *NextGen Exoskeleton Navigator – Risk Management Exercise*  
  (CEN 4078, Spring 2024)

An unmodified copy of the original submission is available in:

assets/original-deliverables/

---

## Purpose
The purpose of this document is to explain **how technical risks were prioritized**
during the academic exercise and how relative risk severity was determined.

This document is descriptive in nature and reflects the methodology applied at
the time of submission.

---

## Risk Identification Basis
Risks were identified based on:

- Modeled system behavior
- Documented use cases and abuse cases
- Identified security threats
- Assumed operational and deployment environments

Each technical risk represents a potential condition under which system security,
safety, or operational integrity could be compromised.

---

## Impact Evaluation Criteria
Each technical risk was evaluated against multiple business impact dimensions,
as documented in the original exercise:

- **Financial Damages**  
- **Reputational Damages**  
- **Non-compliance Impact**  
- **Privacy Violation Impact**

Scores for each category were assigned using a relative scale to reflect
the potential severity of impact should the risk be realized.

---

## Likelihood Assessment
Each risk was assigned an **overall likelihood value**, representing the assessed
probability of risk realization based on:

- Exposure of attack surfaces
- Accessibility of affected interfaces
- Frequency of relevant operational scenarios
- Plausibility of misuse or failure

Likelihood values were not derived from empirical data and represent analytical
judgment applied during the academic exercise.

---

## Risk Prioritization Approach
Risk prioritization was performed by considering:

- The cumulative impact across business impact categories
- The assessed likelihood of realization
- The potential for cascading or high-consequence effects

Risks with higher combined impact and likelihood values were treated as higher
priority for mitigation consideration.

---

## Prioritization Outcomes
Based on the applied methodology:

- **Communication interception risks** were identified as the highest priority
  due to their high likelihood and broad impact across confidentiality, compliance,
  and privacy dimensions.
- **Environmental and natural disaster risks** were identified as lower priority
  due to lower likelihood and more limited scope of impact.

These outcomes are documented explicitly in the Risk Register.

---

## Limitations of the Method
The prioritization approach applied in this project is subject to several limitations:

- Risk scoring is qualitative and relative, not quantitative
- No empirical incident data was available
- Impact estimates are hypothetical and scenario-based
- Results reflect academic analysis rather than operational validation

---

## Relationship to Other Artifacts
This prioritization method supports and contextualizes:

- The Technical Risk Register
- Threat Identification and Controls Mapping
- Lessons Learned and reflective analysis

It completes the risk management portion of the academic case study.

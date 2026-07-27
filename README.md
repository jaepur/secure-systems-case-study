# Secure Systems Engineering Case Study
## NextGen Exoskeleton Navigator

A structured security engineering assessment of a conceptual cyber-physical exoskeleton platform, developed as part of an academic capstone. This is a design-time analysis — no real system was built or tested.

The project applies the full secure systems engineering lifecycle: from requirements and traceability through adversarial modeling, threat identification, controls mapping, and quantified risk prioritization. The system analyzed — a multi-mode exoskeleton with remote operation, autonomous behavior, and networked command infrastructure — presents a realistic set of cyber-physical attack surfaces and safety-critical constraints.

---

## Skills Demonstrated

- **Security requirements engineering** — functional software requirements mapped to explicit security requirements with full traceability across all downstream artifacts
- **Use case and abuse case modeling** — legitimate operational behaviors paired with adversarial misuse scenarios to identify security gaps early in the design process
- **Threat identification and controls mapping** — threat catalog covering physical, network, session, insider, and availability attack vectors, organized into logical control groupings
- **Risk assessment and prioritization** — technical risk register scored across financial, reputational, compliance, and privacy impact dimensions using NIST CSF and OWASP Risk Rating methodology
- **Technical documentation with traceability** — every artifact traces back to original deliverables; assumptions are explicitly bounded and inherited consistently across all documents

---

## What This Project Includes

### Core Deliverables
- Functional software requirements (R001–R015)
- Security requirements (SR001–SR013)
- Software-to-security traceability matrix
- Use cases and abuse cases (AC-1 through AC-10)
- Threat catalog (T-01 through T-10) and controls mapping
- Technical risk register (TeR-01 through TeR-10) and prioritization methodology

### Supporting Documentation
- Executive summary
- System overview with trust boundary analysis
- Explicit assumptions and scope boundary document
- Analytical commentary clearly separated from original submission content

Original, unmodified PDF submissions are preserved in `original-deliverables/` as primary evidence.

---

## Repository Structure

```
secure-systems-case-study/
├── docs/
│   ├── 00-executive-summary.md
│   ├── 01-system-overview.md
│   ├── 02-assumptions-and-scope.md
│   ├── 03-requirements/
│   │   ├── software-requirements.md
│   │   ├── security-requirements.md
│   │   ├── traceability-matrix.md
│   │   └── security-types-matrix.md
│   ├── 04-use-and-abuse-cases/
│   │   ├── use-cases.md
│   │   └── abuse-cases.md
│   ├── 05-threat-model/
│   │   ├── threat-catalog.md
│   │   └── controls-mapping.md
│   └── 06-risk-management/
│       ├── risk-register.md
│       └── prioritization-methodology.md
└── original-deliverables/
    ├── donlon-exoskeleton-security-requirements-exercise.pdf
    ├── donlon-exoskeleton-security-threat-exercise.pdf
    ├── donlon-exoskelton-security-risk-exercise.pdf
    └── donlon_exoskeleton_use_abuse.pdf
```

---

## How to Navigate This Repository

Recommended reading order:

1. **[Executive Summary](docs/00-executive-summary.md)** — High-level findings and methodology overview
2. **[System Overview](docs/01-system-overview.md)** — Conceptual system components and trust boundaries
3. **[Assumptions & Scope](docs/02-assumptions-and-scope.md)** — Boundaries and constraints inherited by all artifacts
4. **[Requirements](docs/03-requirements/)** — Functional and security requirements with traceability matrix
5. **[Use & Abuse Cases](docs/04-use-and-abuse-cases/)** — Intended and adversarial system behavior
6. **[Threat Model & Controls Mapping](docs/05-threat-model/)** — Identified threats, vulnerabilities, and mitigation groupings
7. **[Risk Management](docs/06-risk-management/)** — Risk register, scoring, and prioritization methodology

---

## Key Findings

- **Communication interception** (TeR-02) ranked as the highest-priority risk — high likelihood combined with broad impact across confidentiality, compliance, and privacy dimensions
- **Insider threat and deprecated encryption** (TeR-09, TeR-05) ranked second and third, driven by elevated privilege exposure and data breach impact
- **Session and permission transition failure** (TeR-01) identified as a critical safety risk due to the system's direct physical actuation of the operator
- **Maintenance interface abuse** emerged as a recurring high-risk theme across threat, abuse case, and risk artifacts — elevated privilege with limited monitoring creates a consistent attack surface

---

## Why Cyber-Physical Security Analysis Matters

Digital compromise in cyber-physical systems does not stop at data loss — it translates directly to unsafe physical behavior, mission failure, or personnel harm. This project treats security as a core system property, not an afterthought, and demonstrates how structured analysis at design time produces a defensible, traceable security posture before a line of code is written.

The methods applied here are directly relevant to defense systems, industrial and operational technology (OT) environments, robotics, and medical devices — domains where the cost of a security gap is measured in more than money.

---

## Academic Integrity Statement

All GitHub-native documentation is derived from the author's original academic submissions. Verbatim content is clearly labeled; analytical commentary is explicitly separated from source material. No third-party or proprietary material is included.

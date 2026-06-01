# NIST AI Risk Management Framework (AI RMF) Mapping

## Overview

This document maps the AI Security Risk Assessment Framework to the National Institute of Standards and Technology (NIST) Artificial Intelligence Risk Management Framework (AI RMF).

The NIST AI RMF provides organizations with guidance for identifying, assessing, managing, and governing risks associated with Artificial Intelligence systems.

---

# NIST AI RMF Core Functions

The framework consists of four primary functions:

1. Govern
2. Map
3. Measure
4. Manage

---

# GOVERN

## Objective

Establish organizational structures, policies, procedures, and accountability mechanisms for AI systems.

### Implemented Controls

| Control | Description |
|----------|----------|
| AI Governance Policy | Establishes acceptable AI usage requirements |
| Vendor Risk Assessments | Reviews third-party AI providers |
| Security Reviews | Evaluates AI systems before deployment |
| Compliance Oversight | Ensures regulatory alignment |
| Executive Reporting | Provides leadership visibility into AI risks |

### Related Repository Documents

- AI-Governance-Policy.md
- Security-Control-Catalog.md

---

# MAP

## Objective

Identify AI risks, stakeholders, business context, and system impacts.

### Implemented Controls

| Control | Description |
|----------|----------|
| Threat Modeling | Identifies AI attack vectors |
| Risk Assessments | Evaluates business and security risks |
| Attack Surface Analysis | Reviews AI exposure points |
| Data Classification Reviews | Determines data sensitivity |

### Related Repository Documents

- AI-Threat-Model.md
- AI-Risk-Assessment.md

---

# MEASURE

## Objective

Analyze, assess, and prioritize identified AI risks.

### Implemented Controls

| Control | Description |
|----------|----------|
| Risk Matrix | Prioritizes risks by likelihood and impact |
| Security Reviews | Measures control effectiveness |
| Monitoring Controls | Tracks AI activity |
| Logging & Auditing | Supports risk analysis |

### Related Repository Documents

- AI-Risk-Assessment.md
- Security-Control-Catalog.md

---

# MANAGE

## Objective

Implement controls and ongoing activities to reduce AI risk.

### Implemented Controls

| Control | Description |
|----------|----------|
| Prompt Filtering | Reduces prompt injection risks |
| DLP Controls | Protects sensitive information |
| Human Approval Workflows | Prevents unauthorized actions |
| Incident Response Procedures | Supports rapid containment |
| Continuous Monitoring | Detects suspicious activity |

### Related Repository Documents

- Security-Control-Catalog.md
- AI-Governance-Policy.md

---

# Risk-to-Control Mapping

| Risk | NIST Function | Primary Controls |
|----------|----------|----------|
| Prompt Injection | Manage | Prompt Filtering, Monitoring |
| Data Leakage | Manage | DLP, Encryption |
| Excessive Agency | Manage | Human Approval Workflows |
| Insider Threat | Measure / Manage | Logging, Monitoring |
| Third-Party Risk | Govern | Vendor Assessments |
| Model Misuse | Measure / Manage | Monitoring, Governance |

---

# Framework Alignment Summary

| NIST Function | Repository Coverage |
|----------|----------|
| Govern | AI Governance Policy |
| Map | Threat Modeling & Risk Assessment |
| Measure | Risk Matrix & Monitoring Controls |
| Manage | Security Controls & Incident Response |

---

# Conclusion

This framework aligns AI security governance, risk assessment, monitoring, and security controls with the NIST AI Risk Management Framework. The objective is to support secure enterprise AI adoption while maintaining oversight, accountability, and operational resilience.

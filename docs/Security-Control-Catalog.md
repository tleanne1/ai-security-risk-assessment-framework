# Security Control Catalog

## Overview

This document defines security controls designed to reduce risks associated with enterprise AI adoption, Large Language Models (LLMs), AI assistants, and third-party AI services.

The controls are categorized into Preventive, Detective, Corrective, and Administrative controls.

---

# Preventive Controls

Preventive controls are designed to stop security incidents before they occur.

## Identity & Access Management

| Control | Description |
|----------|----------|
| Multi-Factor Authentication (MFA) | Require MFA for all AI platforms and administrative accounts |
| Role-Based Access Control (RBAC) | Restrict access based on business need |
| Least Privilege | Limit permissions to only what is necessary |
| Privileged Access Reviews | Conduct periodic access reviews |

---

## Data Protection Controls

| Control | Description |
|----------|----------|
| Data Classification | Classify data before use in AI systems |
| Data Loss Prevention (DLP) | Prevent unauthorized sharing of sensitive information |
| Encryption | Encrypt data in transit and at rest |
| Data Retention Policies | Define retention requirements for prompts and outputs |

---

## AI-Specific Controls

| Control | Description |
|----------|----------|
| Prompt Filtering | Detect and block malicious prompts |
| Human Approval Workflows | Require approval for high-risk actions |
| Output Validation | Verify AI-generated outputs before execution |
| Third-Party Risk Assessments | Evaluate AI vendors before adoption |

---

# Detective Controls

Detective controls identify suspicious or malicious activity.

## Monitoring & Logging

| Control | Description |
|----------|----------|
| Audit Logging | Record AI activity and user actions |
| User Activity Monitoring | Monitor interactions with AI systems |
| API Monitoring | Monitor AI API usage |
| SIEM Integration | Forward logs to centralized monitoring platforms |

---

## Threat Detection

| Control | Description |
|----------|----------|
| Anomaly Detection | Identify unusual AI usage patterns |
| Prompt Injection Detection | Detect attempts to manipulate AI behavior |
| Data Exfiltration Monitoring | Monitor for unauthorized data transfers |
| Insider Threat Monitoring | Identify suspicious internal activity |

---

# Corrective Controls

Corrective controls reduce the impact of incidents after they occur.

## Incident Response

| Control | Description |
|----------|----------|
| Incident Response Procedures | Establish AI-specific response processes |
| Session Revocation | Terminate active sessions during incidents |
| Account Suspension | Disable compromised accounts |
| Containment Procedures | Isolate affected systems when necessary |

---

## Recovery Controls

| Control | Description |
|----------|----------|
| Backup & Recovery | Maintain recovery capabilities |
| Model Rollback | Revert to approved model versions |
| Configuration Restoration | Restore secure configurations |
| Business Continuity Planning | Maintain critical operations during disruptions |

---

# Administrative Controls

Administrative controls establish governance and oversight.

## Governance

| Control | Description |
|----------|----------|
| AI Security Policy | Define acceptable AI usage |
| Risk Assessments | Conduct periodic AI risk reviews |
| Vendor Reviews | Evaluate third-party providers |
| Compliance Reviews | Assess regulatory obligations |

---

## Training & Awareness

| Control | Description |
|----------|----------|
| AI Security Training | Educate employees on AI risks |
| Acceptable Use Guidance | Define approved usage practices |
| Security Awareness Programs | Reinforce secure behaviors |
| Executive Reporting | Provide AI risk visibility to leadership |

---

# Control Mapping

| Risk | Primary Controls |
|----------|----------|
| Prompt Injection | Prompt Filtering, Output Validation, Monitoring |
| Data Leakage | DLP, Encryption, Data Classification |
| Excessive Agency | RBAC, Human Approval Workflows |
| Insider Threat | Monitoring, Logging, Access Reviews |
| Third-Party Risk | Vendor Assessments, Governance Reviews |
| Model Misuse | Monitoring, Acceptable Use Policies |

---

# Conclusion

Organizations should implement layered security controls that combine technical safeguards, monitoring capabilities, governance processes, and human oversight to securely support AI adoption.

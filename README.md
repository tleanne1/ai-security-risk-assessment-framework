# AI Security Risk Assessment Framework

![AI Security](https://img.shields.io/badge/Domain-AI%20Security-blue)
![NIST AI RMF](https://img.shields.io/badge/Framework-NIST%20AI%20RMF-green)
![Threat Modeling](https://img.shields.io/badge/Focus-Threat%20Modeling-orange)
![Governance](https://img.shields.io/badge/Category-AI%20Governance-purple)

---

## Overview

This project demonstrates how organizations can securely adopt Artificial Intelligence (AI) technologies through structured risk assessment, threat modeling, governance, and security control design.

The framework evaluates risks associated with Large Language Models (LLMs), AI assistants, enterprise AI platforms, and third-party AI services while aligning recommendations with the NIST AI Risk Management Framework (AI RMF).

---

## Business Scenario

A fictional enterprise plans to adopt Large Language Models (LLMs), AI assistants, and third-party AI services to improve productivity and automate business processes.

Security leadership requested a comprehensive assessment of AI-related risks, governance requirements, security controls, vendor risks, and compliance considerations before deployment.

This repository documents the assessment process, findings, and recommended controls.

---

## Objectives

- Identify AI-specific threats and attack vectors
- Assess risks associated with enterprise AI adoption
- Develop governance requirements
- Design security controls for AI-enabled systems
- Map controls to NIST AI RMF
- Improve organizational AI security posture

---

## Enterprise AI Security Architecture

```text
Users
   |
   v
Enterprise AI Assistant
   |
   +---- Prompt Filtering
   |
   +---- DLP Controls
   |
   +---- Audit Logging
   |
   +---- Human Approval Layer
   |
   +---- SIEM Monitoring
   |
   v
LLM Provider
```

---

## Threat Landscape

The following threats were evaluated:

- Prompt Injection
- Data Leakage
- Excessive Agency
- Model Misuse
- Insider Threats
- Third-Party Dependencies
- Hallucinations
- Training Data Poisoning

---

## Repository Structure

```text
docs/
├── Executive-Summary.md
├── AI-Threat-Model.md
├── AI-Risk-Assessment.md
├── Security-Control-Catalog.md
├── AI-Governance-Policy.md
└── NIST-AI-RMF-Mapping.md
```

---

## Framework Alignment

| NIST AI RMF Function | Repository Coverage |
|----------------------|---------------------|
| Govern | AI Governance Policy |
| Map | Threat Modeling |
| Measure | Risk Assessment |
| Manage | Security Controls |

---

## Security Domains Covered

- AI Governance
- AI Risk Management
- Threat Modeling
- Security Architecture
- Data Protection
- Vendor Risk Management
- Incident Response
- Compliance Alignment

---

## Key Deliverables

### Executive Summary

Provides a high-level overview of enterprise AI security risks and governance considerations.

### Threat Model

Identifies AI-specific attack vectors and threat scenarios.

### Risk Assessment

Evaluates risks using likelihood and impact analysis.

### Security Control Catalog

Defines preventive, detective, corrective, and administrative controls.

### Governance Policy

Establishes enterprise AI usage requirements and oversight mechanisms.

### NIST AI RMF Mapping

Maps controls and governance activities to NIST AI RMF functions.

---

## Key Risks Evaluated

| Risk | Severity |
|--------|--------|
| Prompt Injection | Critical |
| Data Leakage | Critical |
| Excessive Agency | Critical |
| Third-Party AI Risk | High |
| Insider Threat | High |
| Model Misuse | High |
| Hallucinations | Moderate |
| Training Data Poisoning | High |

---

## Security Frameworks Referenced

- NIST AI Risk Management Framework (AI RMF)
- NIST Cybersecurity Framework (CSF)
- OWASP Top 10 for LLM Applications
- MITRE ATLAS
- Enterprise Security Governance Principles

---

## Future Enhancements

- MITRE ATLAS Attack Mapping
- OWASP LLM Top 10 Deep Dive
- AI Incident Response Playbook
- AI Vendor Assessment Checklist
- AI Security Architecture Diagrams
- Security Copilot Governance Assessment
- Third-Party AI Risk Review Framework

---

## Author

**Tracey Buentello**

Cybersecurity Engineer | Security Automation | AI Security | Threat Detection | Risk Management

GitHub: https://github.com/tleanne1

LinkedIn: https://linkedin.com/in/tleanne

---

## Disclaimer

This project is intended for educational, governance, and security assessment purposes. The framework demonstrates how organizations can evaluate and manage risks associated with enterprise AI adoption and does not constitute legal or regulatory guidance.

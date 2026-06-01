# AI Threat Model

## Overview

This threat model identifies potential security threats associated with enterprise adoption of Artificial Intelligence (AI) systems, Large Language Models (LLMs), AI assistants, and third-party AI services.

The objective is to understand how attackers may target AI systems and determine appropriate security controls to reduce risk.

---

## Threat Landscape

| Threat | Description | Impact |
|---------|-------------|---------|
| Prompt Injection | Malicious prompts manipulate model behavior and bypass safeguards | High |
| Data Leakage | Sensitive information exposed through prompts or outputs | Critical |
| Model Misuse | Authorized users abuse AI functionality | High |
| Hallucinations | AI generates inaccurate or misleading information | Medium |
| Excessive Agency | AI performs actions beyond intended authority | Critical |
| Third-Party Dependencies | External AI providers introduce risk | High |
| Insider Threat | Internal users misuse AI systems | High |
| Training Data Poisoning | Malicious data influences model behavior | Critical |

---

## Attack Surface Analysis

### User Prompts

Users may intentionally or unintentionally submit malicious instructions designed to manipulate model behavior.

### Uploaded Documents

Sensitive documents uploaded to AI systems may expose confidential business information.

### APIs & Integrations

Connected applications may provide attackers with additional paths to access sensitive data.

### Third-Party Providers

Organizations rely on external AI vendors that may introduce security, privacy, or compliance risks.

### AI Outputs

Incorrect or manipulated outputs may influence business decisions and operational processes.

---

## OWASP LLM Top 10 Mapping

| Risk | OWASP Category |
|--------|--------|
| Prompt Injection | LLM01: Prompt Injection |
| Sensitive Data Exposure | LLM02: Sensitive Information Disclosure |
| Supply Chain Risk | LLM05: Supply Chain Vulnerabilities |
| Excessive Agency | LLM06: Excessive Agency |
| Insecure Plugin Design | LLM07: Insecure Plugin Design |
| Model Theft | LLM10: Model Theft |

---

## MITRE ATLAS Mapping

| Threat | MITRE ATLAS Technique |
|----------|----------|
| Prompt Injection | Manipulate Model Input |
| Data Leakage | Exfiltration |
| Model Poisoning | Data Poisoning |
| Model Abuse | Resource Manipulation |
| Unauthorized Access | Credential Access |

---

## Recommended Security Priorities

1. Prompt Injection Prevention
2. Data Loss Prevention (DLP)
3. Human Approval Workflows
4. AI Activity Monitoring
5. Vendor Risk Management
6. AI Governance Controls

---

## Conclusion

Organizations adopting AI technologies should perform ongoing threat modeling exercises to identify emerging risks and maintain appropriate security controls throughout the AI lifecycle.

# AI Risk Assessment

## Overview

This assessment evaluates security risks associated with enterprise adoption of Artificial Intelligence (AI) technologies, Large Language Models (LLMs), AI assistants, and third-party AI services.

The objective is to identify, prioritize, and mitigate risks that could negatively impact confidentiality, integrity, availability, compliance, or business operations.

---

## Risk Assessment Methodology

Risk scores are determined using the following formula:

**Risk = Likelihood × Impact**

### Likelihood Ratings

| Rating | Description |
|----------|----------|
| Low | Unlikely to occur |
| Medium | Could reasonably occur |
| High | Expected to occur without controls |

### Impact Ratings

| Rating | Description |
|----------|----------|
| Low | Minimal business impact |
| Medium | Noticeable operational impact |
| High | Significant business disruption |
| Critical | Severe business, legal, or regulatory impact |

---

## Risk Matrix

| Risk | Likelihood | Impact | Risk Level |
|----------|----------|----------|----------|
| Prompt Injection | High | High | Critical |
| Data Leakage | High | Critical | Critical |
| Model Misuse | Medium | High | High |
| Hallucinations | Medium | Medium | Moderate |
| Excessive Agency | High | Critical | Critical |
| Third-Party AI Compromise | Medium | High | High |
| Insider Threat | Medium | High | High |
| Training Data Poisoning | Low | Critical | High |

---

## High Priority Risks

### Prompt Injection

Attackers manipulate prompts to bypass intended controls and influence model behavior.

**Potential Impact**

- Unauthorized actions
- Policy bypass
- Sensitive information disclosure
- Incorrect responses

**Recommended Controls**

- Prompt filtering
- Human approval workflows
- Output validation
- Monitoring and logging

---

### Data Leakage

Sensitive information may be exposed through prompts, outputs, uploaded documents, or third-party AI services.

**Potential Impact**

- Loss of confidential data
- Regulatory violations
- Intellectual property exposure

**Recommended Controls**

- Data classification
- DLP controls
- Access restrictions
- Encryption

---

### Excessive Agency

AI systems may possess permissions beyond their intended purpose.

**Potential Impact**

- Unauthorized actions
- Privilege abuse
- Business disruption

**Recommended Controls**

- Least privilege access
- RBAC
- Human-in-the-loop approvals
- Activity monitoring

---

## Risk Treatment Strategy

The following treatment options should be considered:

| Strategy | Description |
|----------|----------|
| Mitigate | Reduce risk through controls |
| Transfer | Shift risk to third parties |
| Accept | Accept residual risk |
| Avoid | Eliminate the activity causing risk |

---

## Recommended Actions

1. Establish AI governance policies
2. Implement prompt injection protections
3. Deploy DLP controls
4. Restrict AI permissions
5. Perform vendor risk assessments
6. Enable AI activity monitoring
7. Conduct periodic risk reviews

---

## Conclusion

AI technologies introduce unique risks that require dedicated governance, monitoring, and security controls. Organizations should continuously assess AI-related threats and adapt security practices as AI capabilities evolve.

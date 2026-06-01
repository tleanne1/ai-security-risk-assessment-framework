# Enterprise AI Security Architecture

## Overview

This diagram illustrates a secure enterprise AI deployment architecture with layered security controls designed to reduce risks associated with Large Language Models (LLMs) and AI assistants.

---

```text
+------------------------------------------------+
|                    Employees                   |
+------------------------------------------------+
                       |
                       v

+------------------------------------------------+
|              Enterprise AI Assistant           |
+------------------------------------------------+
                       |
       +---------------+---------------+
       |               |               |
       v               v               v

+-------------+ +-------------+ +-------------+
| Prompt      | | DLP         | | Audit       |
| Filtering   | | Controls    | | Logging     |
+-------------+ +-------------+ +-------------+

                       |
                       v

+------------------------------------------------+
|             Human Approval Layer              |
+------------------------------------------------+
                       |
                       v

+------------------------------------------------+
|             OpenAI / LLM Provider             |
+------------------------------------------------+
                       |
                       v

+------------------------------------------------+
|      Microsoft Sentinel / SIEM Monitoring     |
+------------------------------------------------+
```

---

## Security Layers

### Prompt Filtering

Prevents prompt injection attempts and malicious instructions from reaching AI models.

### Data Loss Prevention (DLP)

Protects sensitive information from unauthorized disclosure.

### Audit Logging

Captures user activity, prompts, outputs, and administrative actions.

### Human Approval Layer

Requires human review before high-risk actions are executed.

### SIEM Monitoring

Provides centralized visibility, alerting, and incident detection.

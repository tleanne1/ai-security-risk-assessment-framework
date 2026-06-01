# AI Threat Model

## Overview

This diagram highlights major attack paths and risks associated with enterprise AI deployments.

---

```text
                 +------------------+
                 |      User        |
                 +------------------+
                           |
                           v

                 +------------------+
                 |   AI Platform    |
                 +------------------+
                           |
       +-------------------+-------------------+
       |                   |                   |
       v                   v                   v

+--------------+  +--------------+  +--------------+
| Prompt       |  | Data         |  | Excessive    |
| Injection    |  | Leakage      |  | Agency       |
+--------------+  +--------------+  +--------------+

       |                   |                   |
       +-------------------+-------------------+
                           |
                           v

                 +------------------+
                 | Business Impact  |
                 +------------------+
```

---

## Primary Threats

- Prompt Injection
- Data Leakage
- Model Misuse
- Excessive Agency
- Insider Threat
- Third-Party Risk
- Hallucinations
- Training Data Poisoning

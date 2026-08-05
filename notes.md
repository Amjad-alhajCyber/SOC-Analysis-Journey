# Junior Security Analyst Intro

## Objective
Understand the responsibilities of a Junior Security Analyst and how a Security Operations Center (SOC) operates.

## Key Concepts

### What is a SOC?
A Security Operations Center (SOC) is responsible for monitoring, detecting, investigating and responding to cyber threats.

### Main Responsibilities

- Monitor security alerts
- Investigate suspicious activity
- Escalate incidents
- Document findings
- Communicate with team members

### SOC Roles

- L1 Analyst
- Senior Analyst (L2)
- SOC Engineer
- Incident Responder
- SOC Manager

### Skills Required

- Networking
- Windows Logs
- SIEM
- Incident Response
- Communication
- Critical Thinking

### Daily Workflow

Alert
↓

Investigation
↓

Classification
↓

Escalation
↓

Remediation
↓

Documentation

## Key Takeaways

- SOC is a team effort.
- Every alert must be investigated.
- Documentation is critical.
- Continuous learning is part of the job.

```mermaid
graph TB
    subgraph STAGE1 [" PHASE 1: DETECTION & INITIAL TRIAGE "]
        A["<b>1. Alert Generated</b>"] --> B["<b>2. Alert Triage</b>"]
    end
    subgraph STAGE2 [" PHASE 2: INVESTIGATION & VALIDATION "]
        B --> C["<b>3. Log Analysis</b>"]
        C --> D{"<b>4. Threat Validation</b>"}
    end
    subgraph STAGE3 [" PHASE 3: INCIDENT RESPONSE "]
        D -- Yes --> E["<b>5. Escalation</b>"]
        E --> F["<b>6. Containment</b>"]
    end
    subgraph STAGE4 [" PHASE 4: CLOSURE & REMEDIATION "]
        F --> G["<b>7. Incident Report</b>"]
        G --> H["<b>8. Lessons Learned</b>"]
    end
    D -- No --> X["<b>Closed (False Positive)</b>"]
```

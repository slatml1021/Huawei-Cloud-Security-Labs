# Lab 03 – Huawei Cloud Incident Response Runbook

## Objective

Create a structured incident response runbook for a fictional retail company, Acme Retail Inc., using Huawei Cloud monitoring, logging, identity, storage, and security services.

The runbook reconstructs a multi-stage cloud security incident and documents the correct action, Huawei Cloud service, query or filter, expected evidence, containment step, and recovery approach for each event.

## Scenario

Acme Retail Inc. is a 2,000-employee online clothing retailer running on Huawei Cloud in the TR-Istanbul region.

During a three-hour incident, the security team must investigate:

- A sustained CPU spike
- A brute-force login attack
- A SQL injection attempt blocked by WAF
- A suspicious IAM user action involving deletion of an OBS backup bucket

## Deliverables

- Incident response runbook
- LTS SQL investigation queries
- Evidence collection plan
- CEO-focused executive summary
- Optional SecMaster SOAR playbook

## Huawei Cloud Services

- Cloud Eye
- Elastic Cloud Server (ECS)
- Host Security Service (HSS)
- Log Tank Service (LTS)
- Web Application Firewall (WAF)
- SecMaster
- Cloud Trace Service (CTS)
- Identity and Access Management (IAM)
- Object Storage Service (OBS)
- Cloud Firewall (CFW)
- Simple Message Notification (SMN)

## Investigation Structure

Each event is documented using the following structure:

1. Action
2. Huawei Cloud service
3. Console path
4. Query or filter
5. Expected evidence
6. Containment or recovery action

## Incident Timeline

| Time | Event |
|---|---|
| 03:14 UTC | CPU usage reaches 95% |
| 03:18 UTC | Brute-force login attack detected |
| 03:32 UTC | SQL injection attempt blocked by WAF |
| 04:47 UTC | IAM user deletes an OBS backup bucket |

## Key Learning Outcomes

- Investigating infrastructure anomalies
- Writing LTS SQL queries
- Correlating security alerts in SecMaster
- Collecting forensic evidence using CTS and LTS
- Containing compromised IAM identities
- Evaluating OBS recovery options
- Preparing concise executive incident briefings

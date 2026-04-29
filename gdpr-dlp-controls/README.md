# GDPR + DLP Implementation Model

## Objective

Protect sensitive data across its lifecycle:

- at rest
- in use
- in transit

## Core GDPR Mapping

- Article 5 → data minimization
- Article 25 → privacy by design
- Article 32 → security of processing
- Article 33 → breach reporting

## DLP Layers

### Discovery
- Macie (PII detection)

### Access Control
- RBAC
- row/column masking

### Monitoring
- CloudTrail
- SIEM

### Prevention
- API restrictions
- export controls

## Key Metrics

- % data classified
- unauthorized access attempts
- data exposure incidents

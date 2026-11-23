# Microsoft Defender for Endpoint

> Personal knowledge base for Microsoft Defender for Endpoint configuration, investigation, troubleshooting, scripts, queries, screenshots, and lab findings.

## Overview

Microsoft Defender for Endpoint (MDE) is the endpoint security workload within the Microsoft Defender ecosystem. This section of the knowledge base will document how features work, how I configure and validate them, problems encountered, and reusable administration resources.

## Knowledge Areas

### Vulnerability Management

Documentation and practical notes for discovering, prioritising, investigating, and remediating vulnerabilities and security recommendations.

**Planned content**
- Device exposure and security recommendations
- Software inventory
- Vulnerability assessment
- Remediation workflows
- Exceptions and accepted risk
- Validation and reporting
- Screenshots and troubleshooting

Folder: `vulnerability-management/`

### Attack Surface Reduction (ASR)

Configuration and testing of controls designed to reduce the attack surface of Windows endpoints.

**Planned content**
- Attack Surface Reduction rules
- Audit, Warn, and Block testing
- Microsoft Intune policy configuration
- Controlled Folder Access
- Network Protection
- Web Protection
- Device Control
- Exploit Protection
- Troubleshooting policy application
- Defender Advanced Hunting validation

Folder: `attack-surface-reduction/`

### Endpoint Detection and Response (EDR)

Investigation and response capabilities used to detect and investigate endpoint activity and respond to threats.

**Planned content**
- Device onboarding and offboarding
- Device inventory
- Device page and timeline
- Alerts and investigations
- Automated investigation and remediation
- Response actions
- Live Response
- EDR in block mode
- Troubleshooting sensor and telemetry issues

Folder: `endpoint-detection-response/`

## Administration and Validation

As this knowledge base grows, guides should capture the full operational process rather than only the configuration steps:

1. **Purpose** - What the feature does and why I would use it.
2. **Prerequisites** - Licensing, roles, supported platforms, and dependencies.
3. **Configuration** - Portal, Intune, PowerShell, API, or other implementation steps.
4. **Screenshots** - Important portal screens and configuration evidence.
5. **Testing** - A safe method for confirming expected behaviour.
6. **Validation** - Evidence that the configuration is actually working.
7. **Troubleshooting** - Symptoms, investigation, root cause, and resolution.
8. **Scripts and queries** - PowerShell, KQL, Microsoft Graph, or other reusable resources.
9. **References** - Relevant Microsoft documentation and supporting resources.

## Screenshots and Sensitive Information

Before committing screenshots or exported configuration, review them for sensitive information such as user names, email addresses, device names, IP addresses, tenant identifiers, internal domains, incident details, access tokens, credentials, and private keys.

Never store passwords, client secrets, API keys, access tokens, certificates containing private keys, or other credentials in this repository.

## Navigation

- [Back to MSFT-Defender-KB](../README.md)

---

**Status:** Work in progress. This page will evolve as Microsoft Defender for Endpoint features are documented and tested.

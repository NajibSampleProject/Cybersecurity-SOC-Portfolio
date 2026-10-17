# Microsoft 365 Security Monitoring Lab

## Overview

This project demonstrates the configuration and validation of foundational
Microsoft 365 security monitoring capabilities.

The lab focused on enabling and verifying:

- Microsoft 365 audit logging
- User and administrator activity monitoring
- Microsoft Defender for Cloud Apps file monitoring
- Security event validation
- Microsoft 365 security administration

---

## Objectives

The objectives of this lab were to:

1. Access and administer a Microsoft 365 tenant.
2. Verify Microsoft 365 unified audit logging.
3. Configure file monitoring through Microsoft Defender for Cloud Apps.
4. Generate test administrative activity.
5. Validate that security-related activity was recorded.
6. Document the implementation for a cybersecurity portfolio.

---

## Environment

Technologies used:

- Microsoft 365
- Microsoft Entra ID
- Microsoft Defender
- Microsoft Defender for Cloud Apps
- Microsoft Purview Audit
- Microsoft Authenticator

---

## Architecture

Microsoft 365 Tenant

        |
        +---- Microsoft Purview
        |        |
        |        +---- Audit Logging
        |                 |
        |                 +---- User Activity
        |                 +---- Administrator Activity
        |
        +---- Microsoft Defender
                 |
                 +---- Defender for Cloud Apps
                          |
                          +---- Information Protection
                                   |
                                   +---- File Monitoring

---

## Implementation

### 1. Microsoft 365 Administration

Accessed the Microsoft 365 Admin Center using an administrative account
protected by multi-factor authentication.

### 2. Microsoft 365 Audit Logging

Accessed Microsoft Purview Audit and verified that Microsoft 365 auditing
was enabled.

Audit logging provides visibility into user and administrator activities
across Microsoft 365 services.

### 3. Audit Validation

Generated administrative activity in the test tenant and reviewed the
Microsoft 365 audit logs to confirm that the activity was recorded.

### 4. Microsoft Defender for Cloud Apps

Accessed Microsoft Defender and navigated to:

Settings → Cloud Apps → Information Protection → Files

File monitoring was enabled to provide additional visibility into
file-related activity.

---

## Security Value

Audit logging and file monitoring provide important visibility for:

- Incident response
- Threat investigation
- Administrative activity monitoring
- User activity monitoring
- Insider-risk investigations
- Compliance investigations
- Security operations

---

## Skills Demonstrated

- Microsoft 365 administration
- Microsoft Entra ID
- Microsoft Defender
- Microsoft Purview
- Audit-log investigation
- Cloud security monitoring
- Security event validation
- Identity and access security

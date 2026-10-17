# Microsoft Entra ID — MFA & Self-Service Password Reset

## Overview

Implemented and tested Self-Service Password Reset (SSPR) in Microsoft
Entra ID using group-based access and Microsoft Authenticator.

The project demonstrates practical identity security, authentication,
password recovery and audit monitoring skills.

## What I Implemented

- Enabled SSPR for a selected security group
- Added a test user to the SSPR-enabled group
- Configured password reset authentication requirements
- Registered Microsoft Authenticator as a security method
- Tested self-service password recovery
- Verified successful authentication after password reset
- Reviewed SSPR audit logs and usage insights

## Architecture

```text
Microsoft Entra ID
        |
        +--- SSPR Security Group
        |        |
        |        +--- Test User
        |
        +--- Microsoft Authenticator
        |        |
        |        +--- Identity Verification
        |
        +--- Self-Service Password Reset
        |        |
        |        +--- Password Recovery
        |
        +--- Audit Logs
                 |
                 +--- SSPR Activity Monitoring

## Evidence

### SSPR Enabled

![SSPR Enabled](screenshots/SSPR-Security-Group)

### SSPR Group Membership

![SSPR Group Membership](screenshots/SSPR-Security-Group-02)

### Microsoft Authenticator Registration

![Authenticator Registered](screenshots/SSPR-Security-Group-03)

### Audit Logs and Usage & Insights

![Audits Logs and Usage](screenshots/SSPR-Security-Group-04)
![Audits Logs and Usage](screenshots/SSPR-Security-Group-05)




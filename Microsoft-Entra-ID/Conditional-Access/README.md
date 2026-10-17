# Microsoft Entra ID — Conditional Access

## Overview

Implemented and tested a Microsoft Entra Conditional Access policy
to restrict access to Microsoft administrative portals for a selected
test user.

The project demonstrates access-control policy configuration,
resource targeting, enforcement, MFA awareness and Zero Trust concepts.

## What I Implemented

- Created a Conditional Access policy
- Scoped the policy to a selected test user
- Targeted Microsoft Admin Portals
- Reviewed network and sign-in conditions
- Configured the policy to block access
- Enabled and validated the policy
- Tested the policy from the user perspective
- Confirmed that access to the Azure admin portal was denied

## Policy Logic

```text
IF
User = Selected Test User

AND

Resource = Microsoft Admin Portals

THEN

Block Access

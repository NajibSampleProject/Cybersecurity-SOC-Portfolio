
# Microsoft Purview – Insider Risk Management Lab

## Project Overview

This project documents a hands-on Microsoft Purview Insider Risk Management lab conducted in a Microsoft 365 training environment.

The lab focused on exploring insider risk security controls, reviewing administrative permissions, configuring policy indicators, and creating a custom data-leak risk policy.

## Technologies Used

- Microsoft Purview
- Insider Risk Management
- Microsoft 365
- Data Loss Prevention (DLP)
- Role-Based Access Control (RBAC)
- Risk Indicators and Detection Policies

## Lab Objectives

- Review insider risk administrative roles
- Examine privacy and anonymisation controls
- Configure Office activity indicators
- Explore policy detection timeframes
- Review intelligent detection settings
- Create a custom insider risk policy
- Configure DLP-based triggering events
- Examine activity scoring capabilities

## Practical Lab Activities

### 1. Review Security Role Permissions
Examined Insider Risk Management role groups and verified existing administrator membership.

### 2. Explore Insider Risk Settings
Reviewed privacy controls, Office policy indicators, policy timeframes, and intelligent detection options.

### 3. Create a Custom Insider Risk Policy
Created `SC900-InsiderRiskPolicy` using the Data Leaks template.

Configured the following options:

- Policy template: Data Leaks
- Users: All users and groups
- Content prioritisation: None
- Trigger: DLP policy match
- DLP policy: U.S. Financial Data
- Indicators: Configured Office indicators
- Thresholds: Microsoft-provided defaults

### 4. Review Risk Scoring
Explored the administrative option for starting risk scoring without waiting for an initial trigger.

No manual risk scoring was initiated.

## Screenshot Evidence

For a detailed walkthrough with screenshots:

[View Lab Implementation and Evidence](screenshots/README.md)

## Cybersecurity Skills Demonstrated

- Insider Risk Management
- Data Loss Prevention
- Microsoft Purview Administration
- Role-Based Access Control
- Sensitive Data Protection
- Security Policy Configuration
- Insider Threat Detection Concepts
- Risk-Based Monitoring
- Security Governance

## Lab Scope

This was a guided training exercise.

A custom insider risk policy was created, but the lab did not involve triggering an alert, conducting an insider threat investigation, or initiating manual activity scoring.

## Conclusion

I developed this portfolio project to demonstrate my practical experience with Microsoft Purview Insider Risk Management and my understanding of enterprise information security controls.

The documented configuration activities and screenshots provide evidence of my hands-on technical skills in security policy management, sensitive data protection, role-based permissions, and insider risk detection concepts.

This project contributes to my broader cybersecurity portfolio and demonstrates skills relevant to SOC Analyst, Cybersecurity Analyst, and Microsoft 365 Security positions.

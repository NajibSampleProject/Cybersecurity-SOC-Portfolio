# Microsoft Entra ID — Identity & User Management Lab

## Overview

This project demonstrates hands-on administration of Microsoft Entra ID identities.

The lab focused on creating and configuring a cloud user, assigning security group membership, reviewing administrative roles, assigning a Microsoft product licence, and validating the user's first successful sign-in.

This project demonstrates practical Identity and Access Management (IAM) skills in a Microsoft cloud environment.

---

## Objectives

The objectives of this lab were to:

- Create a new Microsoft Entra ID cloud user
- Configure user identity properties
- Configure the user's usage location
- Understand Member and Guest identity types
- Create and assign security group membership
- Review Microsoft Entra administrative roles
- Apply least-privilege principles
- Assign an available Microsoft licence
- Validate the account through successful first sign-in

---

## Technologies Used

- Microsoft Entra ID
- Microsoft 365 Admin Center
- Microsoft 365
- Microsoft Entra Security Groups
- Microsoft Authentication
- Identity and Access Management (IAM)

---

## Lab Architecture

Microsoft Entra ID
        |
        |
        +------ Administrator
        |
        +------ Security Group
        |          |
        |          +------ GRP-Operations
        |                     |
        |                     +------ Entra Lab User
        |
        +------ User Identity
        |          |
        |          +------ Member account
        |          +------ Usage Location: Australia
        |
        +------ Microsoft 365
                   |
                   +------ Product Licence
                   |
                   +------ First Sign-In Validation

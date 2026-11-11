# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
The problem in this project was related to a fictional company called Northstar Medical Group. They are a fast growing company who delegated their Identity Lifecycle workflow to a third-party MSP. In the beginning this was fine. But as they grew the issues began to show. They had NO RBAC policy in place. Users were assigned access AD-HOC. There was NO Audit trails. And HIPAA Risks.

## Solution Overview
The solution was to build out a basic employee onboarding pipeline in active directory. I set up the RBAC matrix and ensured users were given access ONLY according to their role. I also simulated a mock ticket where a user was provisioned the incorrect level of access!

## Video Walkthrough
[placeholder]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Designed department-based OU structure (Finance, HR, IT, Operations)
* Implemented RBAC with security groups mapped to each department
* Provisioned 15 user accounts with consistent naming conventions and attribute standards
* Diagnosed and resolved a multi-cause access issue (wrong OU + missing group membership)
* Documented full incident resolution with root cause analysis


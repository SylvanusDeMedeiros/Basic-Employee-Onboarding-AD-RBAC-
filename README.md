
# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* The previous MSP in charge of the IT operation at Northstar Medical Group had their entire environement disorganized. Users were being added manually with no proper documentation. Putting the company at risk of HIPPA Compliance

## Solution Overview
* To fix the proplem, I built a new domain and a Basic Onboarding System in active directory using RBAC. I created four differents organizational units (OUs), with four respective security groups where I placed each users depending of their role. During the same week, I received a ticket where a user was having access denied on all her shared resources. After investigating, I was able to diagnosed the issue which she was assigned to the wrong OUs and Group. I fixed it by placing her in the right OUs and Groups.   
## Video Walkthrough
(https://www.loom.com/share/f7365fe60f984b629e93cbc69788344c)

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
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






# Entra ID User & Group Management (IAM Fundamentals)
# Overview
This project demonstrates foundational Identity and Access Management (IAM) operations using Microsoft Entra ID. The lab focuses on creating cloud identities, organizing users with security groups, and validating group-based access control in a sandbox Azure environment.
The lab was completed using Microsoft Learn sandbox environments, which provide a temporary Azure tenant without requiring a credit card.
## Motivation / Goal
Identity is the first security boundary in cloud environments. This project was designed to:
Understand how cloud identities are created and managed
Practice group-based access control for scalability
Build a foundation for Azure RBAC, MFA, and Conditional Access labs
Gain hands-on experience with enterprise IAM workflows
## Tools Used
Microsoft Entra ID
Azure Portal (Microsoft Learn Sandbox)
Web browser
GitHub (documentation & version control)
## Lab Setup
# Environment
Microsoft Learn Sandbox (temporary Azure subscription)
Built-in Entra ID tenant
No credit card required
# Pre-requisites
Microsoft Learn account
Basic understanding of IAM concepts
## Step-by-Step Setup
1. Launch Azure Sandbox
Accessed a Microsoft Learn module with “Launch sandbox” enabled
Activated sandbox and opened Azure Portal
📸 Screenshot: Sandbox activation confirmation <img width="720" height="1650" alt="Sandbox activation confirmation" src="https://github.com/user-attachments/assets/13339c67-fd72-49cf-bf1c-a9d334647a43" />


2. Create Entra ID User
Navigated to Microsoft Entra ID → Users
Created a new user:
Username: Alex
Display name: Alex
Password: Auto-generated
Account enabled
📸 Screenshot: User “Alex” overview page <img width="720" height="1650" alt="User -Alex- overview page" src="https://github.com/user-attachments/assets/14a3969c-82ab-4904-81d7-7c88c351c804" />

3. Create Security Group
Navigated to Microsoft Entra ID → Groups
Created a new Security Group:
Group name: IT Department
Membership type: Assigned
📸 Screenshot: IT Department group overview <img width="720" height="1650" alt="IT Department group overview" src="https://github.com/user-attachments/assets/df5adae7-f7e8-4a50-ae25-faa116cd6d80" />

4. Assign User to Group
Added user Alex to IT Department group
Verified group membership from user profile
📸 Screenshot: Group membership verification
Running the Lab <img width="1650" height="720" alt="Group membership verification" src="https://github.com/user-attachments/assets/a88d8875-1672-4717-842f-377ea5667aab" />

This lab does not require custom code execution.
All tasks were performed through:
Azure Portal (sandbox)
Microsoft Entra ID management interface
## To reproduce:
Launch a Microsoft Learn sandbox
Repeat the user and group creation steps
Validate group membership
Detection / Results
User Alex successfully created in Entra ID
Security group IT Department created
Group-based assignment verified from both group and user perspectives
These results confirm proper identity lifecycle management and group-based access control.
## Lessons Learned
Cloud IAM relies heavily on groups, not individual user assignments
Group-based access improves scalability and security
Sandbox environments can fully simulate real enterprise Azure tenants
Proper documentation is as important as technical execution
Real-World Security Relevance
Used in enterprise onboarding/offboarding workflows
Foundation for Azure RBAC enforcement on resources
Prepares for MFA, Conditional Access, and Privileged Identity Management
Directly applicable to SOC Analyst and Cloud Security roles
## Next Improvements
Assign RBAC roles to the IT Department group on a VM
Enable MFA for privileged users
Review Entra ID audit logs for user and group changes
## 📌 Note
This lab was completed using Microsoft Learn sandbox environments, which provide temporary Azure tenants for hands-on learning without requiring payment information.

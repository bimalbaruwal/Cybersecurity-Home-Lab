# Lab 03 - Active Directory Administration

## Objective

Build a structured Active Directory environment by creating Organizational Units (OUs), security groups, and user accounts. This lab simulates how an organization organizes and manages its Active Directory infrastructure.

---

## Environment

- Hypervisor: VMware Workstation Pro 17
- Domain Controller: DC01
- Operating System: Windows Server 2022 Standard Evaluation
- Domain: homelab.local
- Management Tool: Active Directory Users and Computers (ADUC)

---

## Tasks Performed

- Opened Active Directory Users and Computers
- Created the Company Organizational Unit (OU)
- Created departmental OUs:
  - IT
  - HR
  - Finance
  - Sales
  - Servers
  - Workstations
  - Groups
  - Service Accounts
- Created security groups
- Created domain user accounts
- Added users to their appropriate security groups

---

## Active Directory Structure

```
homelab.local
│
├── Company
│   ├── IT
│   ├── HR
│   ├── Finance
│   ├── Sales
│   ├── Servers
│   ├── Workstations
│   ├── Groups
│   └── Service Accounts
```

---

## Skills Learned

- Active Directory administration
- Organizational Unit (OU) management
- User account creation
- Security group management
- Domain administration

---

## Screenshots

Add screenshots in the `images` folder.

Examples:

- Active Directory Users and Computers
- OU structure
- User creation
- Group creation
- User added to group

---

## Lessons Learned

- Organizational Units help organize users and computers.
- Security groups simplify permission management.
- Active Directory allows centralized administration of users and computers.

---

## Next Lab

Lab 04 – Group Policy (GPO)
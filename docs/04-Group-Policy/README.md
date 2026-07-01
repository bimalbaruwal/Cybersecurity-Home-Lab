# Lab 04 - Group Policy

## Objective

Learn how to create, configure, and deploy a Group Policy Object (GPO) to manage Windows clients centrally.

## Environment

- Windows Server 2022 (DC01)
- Windows 10 (Domain Joined)
- Domain: homelab.local

## Tasks Performed

- Created a new GPO
- Configured Control Panel restrictions
- Linked the GPO to the Company OU
- Updated Group Policy on the client
- Verified the policy

## Verification

Confirmed that Control Panel access was blocked for the targeted user.

## Lessons Learned

- GPOs provide centralized management.
- Linking a GPO to an OU limits its scope.
- Policies can be refreshed immediately with `gpupdate /force`.

## Screenshots

(Add screenshots here.)

## Interview Questions

**Q:** What is a Group Policy Object (GPO)?

**A:** A GPO is a collection of configuration settings that administrators use to centrally manage users and computers in an Active Directory domain.

**Q:** Why link a GPO to an OU instead of the entire domain?

**A:** Linking a GPO to an OU applies the settings only to the users and computers within that OU, reducing the risk of unintentionally affecting the entire organization.
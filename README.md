# Active Directory & Windows Server Lab

## Overview

A hands-on Windows Server lab built to develop practical experience with **Active Directory Domain Services (AD DS)**, centralized user management, security groups, organizational units, domain authentication, and SMB file sharing.

The environment consists of a Windows Server Domain Controller and a Windows 11 domain client using the `LAB.local` domain.

## Lab Environment

| Component         | Configuration                    |
| ----------------- | -------------------------------- |
| Server            | Windows Server                   |
| Client            | Windows 11                       |
| Domain            | `LAB.local`                      |
| Directory Service | Active Directory Domain Services |
| File Sharing      | SMB                              |
| Departments       | HR, IT, Finance, Sales           |

## What I Built

### Active Directory Domain

* Installed Windows Server and promoted it to a Domain Controller.
* Created the `LAB.local` Active Directory domain.
* Created and managed user accounts.
* Created departmental security groups for HR, IT, Finance, and Sales.
* Added users to the appropriate security groups.
* Created **Organizational Units (OUs)** and nested OUs to logically organize directory objects.

### Domain Client

* Joined a Windows 11 workstation to the `LAB.local` domain.
* Logged into the workstation using domain user accounts.
* Practiced managing user passwords, account lockouts, and account expiration.

### File Sharing & Access Control

Created departmental SMB file shares for HR, IT, Finance, and Sales.

Access was assigned to the corresponding AD security groups rather than individual users. This provided centralized, group-based access control.

Share permissions were configured with appropriate levels of Read, Change, and Full Control, and the shares were mapped as network drives on the Windows 11 client.

### Troubleshooting

Practiced resolving common administrative issues involving:

* User passwords
* Account lockouts
* Account expiration
* User and group membership
* Access to departmental network shares

## Key Concepts

This lab has provided Hands-on practical experience with the relationship between users, Security Groups and resources.

Security groups were used to manage resource access, while OUs were used to provide logical organization and a structure for future administrative policies such as Group Policy.

## Skills Demonstrated

* Windows Server administration
* Active Directory Domain Services
* Domain Controller deployment
* User and group management
* Security groups and group membership
* Organizational Units and nested OUs
* Domain joining and authentication
* SMB file sharing
* Share permissions
* Network drive mapping
* Basic Active Directory troubleshooting

## Future Considerations

Planned extensions to the lab include:

* Group Policy Objects (GPOs)
* NTFS permissions
* PowerShell-based AD administration
* More advanced DNS configuration and troubleshooting
* Additional client and administrative scenarios

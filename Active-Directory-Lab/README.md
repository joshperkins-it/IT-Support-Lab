# Active Directory Lab

## Setup
Launched a Windows Server 2019 EC2 instance (t2.micro) and connected via RDP. Installed AD Domain Services with PowerShell and promoted the server to a domain controller (`lab.local`).

## Practice
- Created new user accounts with naming conventions.  
- Set temporary passwords with “must change at next login.”  
- Disabled and re-enabled accounts.  
- Reset passwords and unlocked accounts.  
- Created security groups and added users.  
- Deleted test accounts.

## Notes
Running the PowerShell commands felt straightforward once I remembered to use admin privileges. Creating groups first made it easier to manage permissions.

## What I Learned
This lab showed me how AD handles user provisioning and password resets. It gave me a better sense of how group membership controls access.

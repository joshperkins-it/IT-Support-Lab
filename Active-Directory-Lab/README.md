Active Directory Lab
Setup
Created free AWS account.
Launched Windows Server 2019 EC2 instance using t2.micro.
Connected via RDP using Microsoft Remote Desktop on macOS.
Ran PowerShell command to install Active Directory Domain Services:
Install-WindowsFeature -Name AD-Domain-Services -IncludeManagementTools
Promoted server to domain controller using:
Install-ADDSForest -DomainName "lab.local"
Server restarted and domain controller confirmed active.
Practice Completed
Opened Active Directory Users and Computers.
Created new user accounts following naming conventions.
Set temporary passwords with must change at next login enabled.
Disabled and re-enabled user accounts.
Reset user passwords.
Created security groups and added users to groups.
Deleted test user accounts.
Key Skills Demonstrated
User provisioning and deprovisioning
Password reset procedures
Account lockout resolution
Group management and access control
Screenshots
See screenshots uploaded in this folder.

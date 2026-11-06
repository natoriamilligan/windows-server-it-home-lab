# Security Groups and Sharing Folders (NTFS)

# Objective
Set up security groups so that authorized members can access shared folders.

# Environment
- Windows Server 2025
- Active Directory Users and Computers

# Tasks Completed
- Created IT shared folder and added path descriptions
- Created IT security group and added the helpdesk user to it
- Disabled inheritance for IT shared folder, deleted unauthorized principals, and added IT security group as a principal to folder
- Mapped shared folder to Z drive for users in IT security group

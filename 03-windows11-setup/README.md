# Set up Windows 11

# Objective
Set up Windows 11 for a helpdesk tech to have access to selected Active Directory services.

# Environment
- Windows 11 2026

# Tasks Completed
- Installed Windows 11 2026 on client VM
- Installed RSAT tools so that the client has access to manage select Windows Server features
- Joined PC to domain
- Changed group policy password max age, account lockout threshold, account lockout duration, and account lockout counter
- Locked and account and unlocked it again
- Triggered a reset password for a user

## Troubleshooting
- I could not install Windows 11 on a VirtualBox VM. I tried changing the amount of RAM and storage allocated but I kept being met with a black screen. When I switched to VMware Workstation, Windows 11 worked but Windows Server would not. I realized that I needed to press any key quickly to enter the boot manager which was probably my problem when installing Windows 11 in VirtualBox.
- I created a helpdesk account but could not login. I realized I had not enabled the account which you can do by right clicking the user in Active Directory Users and Computers.
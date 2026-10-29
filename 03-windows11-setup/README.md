# Set up Windows 11

# Objective
Set up Windows 11 for a helpdesk tech to have access to selected Active Directory services.

# Environment
- Windows 11 2026

# Tasks Completed
- Installed Windows 11 2026 on client VM

## Troubleshooting
- I could not install Windows 11 on a VirtualBox VM. I tried changing the amount of RAM and storage allocated but I kept being met with a black screen. When I switched to VMware Workstation, Windows 11 worked but Windows Server would not. I realized that I needed to press any key quickly to enter the boot manager which was probably my problem when installing Windows 11 in VirtualBox.

## Lessons Learned
- If you encounter a black screen when first booting up a VM, trying entering the boot manager.
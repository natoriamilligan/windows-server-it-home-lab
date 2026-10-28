# VirtualBox and Windows Server 2025 Setup

## Objective
Configure a virtual machine using VirtualBox and install Windows Server 2025 onto it.

## Environment
- VirtualBox
- Windows Server 2025 (Desktop Experience) ISO
    - RAM: 4GB
    - Storage: 50GB
    - CPUs: 2
- Windows 11 ISO
    - RAM:4GB
    - Storage: 25
    - CPUs: 2

## Tasks Completed
- Installed VirtualBox
- Created server and client VM
- Installed Windows Server 2025 (Desktop Experience) onto server VM
- Renamed server computer to human friendly name
- Installed Windows 11 onto client VM

## Troubleshooting
- I could not install Windows 11 on a VirtualBox VM. I tried changing the amount of RAM and storage allocated but I kept being met with a black screen. When I switched to VMware Workstation, Windows 11 worked but Windows Server would not. I realized that I needed to press any key quickly to enter the boot manager which was probably my problem when installing Windows 11 in VirtualBox.
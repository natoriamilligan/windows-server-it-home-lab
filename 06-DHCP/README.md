# DHCP

# Objective
Set up a DHCP server and configure reservations for devices on the network.

# Environment
- Windows 11 2026

# Tasks Completed
- Add DHCP service to run on the DC01 server
- Created address scope 
- Added printer reservation
- Disabled VMware DHCP
- Configured CLIENT01 to use DHCP instead of static IP 

# Troubleshooting
- I tried to add the DHCP server using the Windows Administrative tool but it would not work because I had not yet installed the DHCP service in Server Manager.
- When creating the scope ranges, I kept encountering errors regarding the IP addresses. I was using including the broadcast address in the range which you cannot do.
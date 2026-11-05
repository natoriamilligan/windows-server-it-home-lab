# DNS

# Objective
Explore DNS server and confirm computers names resolve.

# Environment
- Windows 11 2026
- Windows Server 2025
- DNS Server

# Tasks Completed
- Confirmed both the server and client were using the correct DNS server

# Troubleshooting
- I originally could not c$ from the server into CLIENT01. However, I could ping to the computer and checked that both computers were using the correct DNS server. It turned out that the Windows 11 firewall was restricting the server from reaching it. I had to change the ICMP and File and Print Sharing rules in Windows Defender.
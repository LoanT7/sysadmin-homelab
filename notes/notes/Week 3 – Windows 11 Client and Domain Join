# Goal
The goal of Week 3 was to set up a Windows 11 client and join it to the Active Directory domain.


## Client Setup
- VM Name: WIN11-CLIENT01
- OS: Windows 11 Pro
- Network: Internal Network (AD-LAB)

Windows 11 Home was removed because it cannot join a domain.  
The client was reinstalled using Windows 11 Pro.

Because DHCP is not set up yet, a static IP address was used.

Client IP Settings:
IP Address: 192.168.10.20
Subnet Mask: 255.255.255.0
DNS Server: 192.168.10.10
# Connectivity Testing

Connectivity was tested using ping:
- Client to Server: Working
- Server to Client: Working

Firewall settings were adjusted to allow ping for testing.


## Domain Join

The client was joined to the domain:
lab.local
The domain administrator account was used to join the domain.
After restarting, the client successfully

## Problems and Fixes
- Windows 11 Home could not join the domain → Reinstalled Windows 11 Pro
- Network issues → Fixed IP and firewall settings
- Login issues → Reset domain admin password


## What I Learned
- Windows edition matters in domain environments
- DNS must point to the domain controller
- Firewalls can block network traffic
- Troubleshooting step by step is important


## Next Steps
- Create users and organizational units
- Apply Group Policy

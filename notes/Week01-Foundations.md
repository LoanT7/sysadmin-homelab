# Week 1 – Lab Foundations

# Objective
Setting up a system administration home lab with virtualization, operating systems, and documentation structure.

# Environment
- Host OS: Windows (10/11)
- Hypervisor: VirtualBox
- Server OS: Windows Server 2022 (Evaluation)
- Client OS: Windows 11

# Lab Setup Summary
- Installed VirtualBox
- Created Windows Server VM
- Created Windows 11 client VM
- Resolved virtualization and installer issues
- Created GitHub repository for documentation

# Issues Encountered
- Windows Server installer error 
- Windows 11 TPM and Secure Boot requirement
- VirtualBox memory crash issue

# Resolutions
- Recreated VM and verified ISO integrity
- Bypassed TPM and Secure Boot checks for lab environment
- Disabled 3D acceleration and Hyper-V conflicts

# Lessons Learned
- Virtualization conflicts can cause misleading OS errors
- Lab documentation is as important as configuration
- Windows 11 security requirements affect VM installs

# Next Steps
- Configure internal networking
- Assign static IP to Windows Server
- Prepare server for Active Directory Domain Services

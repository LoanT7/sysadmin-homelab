# Week 2 – Networking and Active Directory Basics

## Goal
The goal of Week 2 was to connect my virtual machines together, give my server a static IP address, and set up Active Directory so the server can manage users and computers.


## Lab Setup
- Hypervisor: VirtualBox
- Network Type: Internal Network
- Network Name: AD-LAB

## Virtual Machines
- WS2022-DC01 , Windows Server 2022 (Domain Controller)
- WIN11-CLIENT01 , Windows 11 (Client computer)

## Network Configuration

Both virtual machines were connected to the same **Internal Network** in VirtualBox.  
This allows them to communicate with each other but keeps the lab separate from my home network.

## Static IP Address (Server)

The Windows Server was given a static IP address so it does not change.  
This is important because Active Directory and DNS need a stable IP address to work correctly.

IP Settings Used was : IP Address: 192.168.10.10
Subnet Mask: 255.255.255.0
DNS Server: 192.168.10.10

server name: WS2022-DC01 

## Installing Active Directory

The Active Directory Domain Services (AD DS) role was installed using Server Manager.  
DNS was added automatically because Active Directory depends on DNS to function.


## Creating the Domain

The server was promoted to a Domain Controller with these settings:
- New domain created
- Domain name: `lab.local`
- DNS enabled
- Global Catalog enabled

After installation, the server restarted and I logged in using: LAB/Administrator


## Problems and Fixes

- Networking options were not visible at first because the VM was running  
  -> Fixed by powering off the VM and using full VirtualBox settings

- DNS warning during promotion  
  -> This is normal in a lab environment and did not cause issues


## What I Learned
- Domain Controllers must use a static IP address
- Active Directory depends heavily on DNS
- Internal networks are useful for safe lab testing
- Verifying services after setup is very important

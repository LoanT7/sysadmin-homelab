# Week 4 – Users, Groups, and Group Policy

## Goal
The goal of Week 4 was to manage users and computers in Active Directory and apply basic Group Policy settings.


## Organizational Units (OUs)

The following OUs were created to keep Active Directory organized:
- Users
- Computers
- Admins
- Domain Controllers

These OUs help organize objects and allow policies to be applied later.


## User and Group Setup

A standard domain user was created:
- Username: adoe

A security group was created:
- Group name: Employees

The user was added to the Employees group to manage permissions using groups instead of individual users.

---

## Computer Organization

The Windows 11 client was renamed correctly and moved into the Computers OU.  
This ensures that computer-based policies can be applied in the future.

---

## Shared Folder and Permissions

A shared folder was created on the server:
C:\Shared\Employees


Permissions were assigned using the Employees group:
- Users can read the folder
- Users cannot modify or delete files

Access was tested successfully from the client using the domain user account.

## Group Policy

A Group Policy Object (GPO) was created and linked to the Users OU.  
The policy was used to restrict user actions.

The policy was confirmed as applied using:
gpresult


A visible restriction was used to verify that Group Policy was working on Windows 11.

---

## What I Learned
- OUs help organize users and computers
- Users should get access through groups
- Permissions should be assigned to groups, not users
- Group Policy can control user behavior across the domain
- Windows 11 may handle some policies differently

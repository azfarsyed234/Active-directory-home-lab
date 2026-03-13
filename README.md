# Active Directory Home Lab

This project demonstrates the deployment of a basic Windows Active Directory environment using virtualization.

## Environment

Virtualization: Oracle VirtualBox  
Domain Controller: Windows Server  
Client Machine: Windows 10  

## Network Configuration

Internal Network: 172.16.0.0/24

Domain Controller
- IP: 172.16.0.1
- Roles Installed:
  - Active Directory Domain Services
  - DNS
  - DHCP

Client Machine
- IP assigned via DHCP
- Joined to Active Directory domain

## Active Directory Configuration

Created Organizational Units and managed user accounts and security groups.

Example structure:

Employees
- ablackwater
- llaflamme
- lolson

Security Group:
- IT-Staff

## Features Demonstrated

- Domain Controller deployment
- DHCP configuration
- DNS configuration
- Client domain join
- Active Directory user management
- Organizational Units
- Security groups

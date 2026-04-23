Active Directory Homelab (Azure)

Objective
Hands-on practice building an Active Directory environment using Microsoft Azure Virtual Machines.  
Simulates a real enterprise setup with a Domain Controller and client machine for IT systems administration training.

Skills Practiced
- Active Directory Domain Services (AD DS)
- Domain Controller setup
- User and group management
- Group Policy (GPO)
- Domain join process
- Azure networking basics (VNet, Subnets)

Platform
- Microsoft Azure

Architecture
- 1 Domain Controller (Windows Server 2022)
- 1 Client Machine (Windows 10/11)
- Virtual Network (VNet)
- Subnet (internal communication)

Setup Steps
1. Azure Infrastructure
- Create Resource Group
- Create Virtual Network
- Create Subnet

2. Domain Controller
- Deploy Windows Server VM
- Install Active Directory Domain Services (AD DS)
- Promote server to Domain Controller
- Create domain (e.g., `raylab.local`)

3. Client Machine
- Deploy Windows 10/11 VM
- Join domain

4. Active Directory Configuration
- Create users and groups
- Configure Organizational Units (OU)
- Apply Group Policy Objects (GPO)

---

Status
In progress...


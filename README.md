# azure-active-directory-homelab
Enterprise-style Active Directory lab built in Microsoft Azure featuring DNS, OU design, security groups, domain-joined endpoints, Group Policy, and account lockout troubleshooting.

    Project Overview 

This project demonstrates the deployment and administration  of an enterprise-style Windows Active Directory environment hosted entirely in Microsoft Azure. The lab was designed to simulate many of the core responsibilities performed by IT support, Systems Administration, and Infrastructure teams in a production environment. 

The environment consists of a WIndows Server 2022 Domain Controller and a Windows 11 client joined to the westonlab.local Active Directory domain. Within the domain, I created a multi-branch organizational structure, configured user and computer accounts, implemented centralized Group Policy Objects (GPOs), validated DNS functionality, and deployed endpoint security configurations. 

To simulate real-world administration, I configured domain-wide account lockout policies, location-specific workstation policies, Remote Desktop access, and performed trouvleshooting using PowerShell and built-in Windows admin tools. 

Throughout the project I validated each configuration using command-line tools, Active Directory administrative console, Group Policy reporting, and authentication testing to ensure every component functioned as expected.


------------------------------------------- Objectives -----------------------------------------------
The primary goals of this project were to:

* Deploy an enterprise Active Directory Domain Services (AD DS) environment in Microsoft Azure
* Configure centralized identity management using Active Directory
* Design an Organizational Unit (OU) structure for multiple office locations
* Implement Security Groups for role-based administration
* Configure DNS services for domain authentication
* Join Windows client systems to the Active Directory domain
* Deploy and validate Group Policy Objects (GPOs)
* Configure workstation security settings using centralized policy
* Implement a domain-wide account lockout policy
* Demonstrate troubleshooting using PowerShell and Windows administrative tools

--------------------------------------- Technologies Used --------------------------------------------
Cloud
* Microsoft Azure
* Azure Virtual Machines
* Azure Virtual Network
* Azure Network Security Groups

Operating Systems
* Windows Server 2022
* Windows 11 Enterprise

Active Directory Services
* Active Directory Domain Services (AD DS)
* Active Directory Users and Computers
* Group Policy Management
* DNS Server

Administration Tools
* PowerShell
* Remote Desktop Protocol (RDP)
* Server Manager
* Group Policy Management Console (GPMC)

Networking
* DNS
* DHCP (Azure-managed)
* IPv4
* Private Virtual Networks

-------------------------------------- Skills Demonstrated -------------------------------------------
* Active Directory administration
* User and computer account management
* Organizational Unit (OU) design
* Security Group administration
* Domain authentication
* DNS configuration and troubleshooting
* Windows Server administration
* Azure virtual networking
* Remote Desktop administration
* Group Policy deployment
* Endpoint configuration management
* Account lockout policy implementation
* PowerShell validation and troubleshooting
* Enterprise identity management
* Technical documentation

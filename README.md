# -active-directory-lab
Active Directory home lab with file server and GPO
# Active Directory Home Lab

##  Overview

This project demonstrates a complete Active Directory lab environment built using VirtualBox.

##  Infrastructure

* **DC01** – Domain Controller (AD DS, DNS)
* **FS01** – File Server (Shares + NTFS permissions)
* **CL01** – Client machine (domain joined)

##  Features Implemented

* Active Directory Domain Services
* DNS configuration
* Organizational Units (IT, HR, Sales)
* Users and Security Groups
* NTFS & Share Permissions
* File Server deployment
* Group Policy (GPO) drive mapping
* Troubleshooting (authentication, DNS, permissions)

##  File Server Structure

\FS01\Shares

* IT
* HR
* Sales

##  GPO

* Automatically maps Z: drive for IT users
* Path: \FS01\Shares\IT

##  Skills Demonstrated

* Windows Server Administration
* Active Directory Management
* Group Policy Configuration
* File Server Management
* Troubleshooting IT Infrastructure

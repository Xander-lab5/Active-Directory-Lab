# Domain Controller Setup



## Overview

Set up a Windows Server 2019 virtual machine to act as a Domain Controller.



## Steps

- Installed Windows Server 2019 (Desktop Experience)

- Renamed server to DC01  
![Rename DC](../screenshots/domain-controller-setup/DC01_rename.png)

- Configured static IP:
     - IP: 192.168.10.10

    - Subnet: 255.255.255.0

    - DNS: 127.0.0.1

       ![Static IP](../screenshots/domain-controller-setup/Configured_static_IP.png)

Configured_static_IP

- Installed Active Directory Domain Services (AD DS)



## Outcome

Server prepared for promotion to Domain Controller.

[← Back to README](../README.md)
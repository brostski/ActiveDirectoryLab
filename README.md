<h1>Active Directory Home Lab</h1>

<h2>Description</h2>
This project is an Active Directory home lab setup on a personal computer using VirtualBox. The goal is to simulate a domain environment with a Domain Controller running Windows Server 2019 and a client machine running Windows 10. The lab includes the configuration of Active Directory, DHCP, NAT, and Routing, as well as user account creation via PowerShell. The domain is configured as mydomain.com with a private network for communication between the Domain Controller and client machine. The project demonstrates networking, user management, and the interaction between different virtual machines within a controlled environment.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Batch/Shell scripting</b>
- <b>Server 2019 configuration tools (GUI/CLI for AD setup, DHCP, and NAT)</b>

<h2>Environments Used </h2>


- <b>Windows 10</b> (Client Machine)
- <b>Windows Server 2019</b> (Domain Controller)
- <b>VirtualBox</b>


<h2>Program walk-through:</h2>

<p align="center">
Setup VirtualBox: <br/>
<img src="https://i.imgur.com/tzkPWLq.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Install Server 2019 on the Domain Controller:  <br/>
<img src="https://i.imgur.com/ldtmmLF.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Configure Network Adapters for the Domain Controller: <br/>
<img src="https://i.imgur.com/UFJoHjV.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Configure Routing and NAT on the Domain Controller:  <br/>
<img src="https://i.imgur.com/Rc8Lzmr.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Setup Active Directory and Domain on Server:  <br/>
<img src="https://i.imgur.com/gxualO4.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Configure DHCP on the Domain Controller:  <br/>
<img src="blob:https://imgur.com/f294309a-544f-45d4-bff4-a73cab48db96" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Create PowerShell Script for User Creation:  <br/>
<img src="https://i.imgur.com/GNrVkLQ.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
 <br />
<br />
Create and Configure the Client 1 VM:  <br/>
<img src="https://i.imgur.com/78G2yTS.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Login to Client 1 Using a Domain User:  <br/>
<img src="https://i.imgur.com/mEPmFeV.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Verify Network and Domain Connection:  <br/>
<img src="https://i.imgur.com/l8Kdu0m.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

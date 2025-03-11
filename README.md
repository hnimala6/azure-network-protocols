<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

https://youtu.be/Mu_2UnOdVHM?si=19Q1mxO4bRiaRzRb
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1: Configuring a Firewall [Network Security Group]
- Step 2: Observe SSH Traffic
- Step 3: Observe DHCP Traffic
- Step 4: Observe DNS Traffic

<h2>Actions and Observations</h2>

Initiate a perpetual/non-stop ping from your Windows 10 VM to your Ubuntu VM

![image](https://github.com/user-attachments/assets/65c8f933-529f-49e0-acf3-d39d17d536a8)

Open the Network Security Group your Ubuntu VM is using and disable incoming (inbound) ICMP traffic

![image](https://github.com/user-attachments/assets/2fc11594-eb1d-430f-a5b2-969cb9b1b3ba)

![image](https://github.com/user-attachments/assets/cf1d24db-7869-44c6-b206-f3bd7d1e03e0)

Re-enable ICMP traffic for the Network Security Group your Ubuntu VM by deleting the rule and the trafic should start working normaly again. 

![image](https://github.com/user-attachments/assets/9c7ce64c-d8ba-48de-9595-4ba3fa2364d9)

![image](https://github.com/user-attachments/assets/a2c4771a-1123-4d44-9a39-1b87bf664f58)


<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

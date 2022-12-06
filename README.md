<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Wireshark (Protocol Analyzer)
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)


<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1: Create Virtual Network
- Step 2: Utilizing Remote Desktop to connect to Windows 10 Virtual Machine
- Step 3: Observe SSH Traffic 
- Step 4: Observe DNS Traffic

<h2>Actions and Observations</h2>

<p>
<img src="https://imgur.com/AXAMlgd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<h2>Completed Virtual Network </h2>
<p> 
 First, a resource group was created in Azure. Inside the virtual network, there is a subnet with two virtual machines. One VM is running Windows 10 (VM1) and the other is running Linux Ubuntu (VM2). There is an NSG in between the two, a firewall. Configurations were made to the firewall to connect the two machines and to analyze the traffic using Wireshark.

</p>
<br />

<p>
<img src="https://i.imgur.com/CCF6HZz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<h1> Utilizing Remote Desktop to connect to Windows 10 Virtual Machine </h1>
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/Z4Ii33x.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<h1> Wireshark (Protocol Analyzer) and Traffic Analysis </h1>
<p>

</p>
<br />

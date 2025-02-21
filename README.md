<h1>Setting Up a VPN in a Virtual Machine</h1>

<h2>Description</h2>
This repository documents the process of setting up a **Virtual Private Network (VPN) within a Virtual Machine (VM)** to ensure **secure, encrypted remote access** to networks. The project demonstrates the deployment of a VPN server within a VM, proper firewall configurations, and traffic analysis using **Wireshark** to monitor encrypted connections.
<br />

<h2>Key Features & Configurations</h2>

- <b>VPN Server Deployment:</b> Configured a VPN inside a **Windows** and **Linux-based** VM.
- <b>Protocol Support:</b> Implemented **OpenVPN, WireGuard, and IPsec** for secure tunneling.
- <b>Firewall & Port Forwarding:</b> Configured firewall rules to allow VPN traffic while securing other ports.
- <b>User Authentication & Access Control:</b> Implemented **password-based and certificate-based authentication**.
- <b>Remote Access & Secure Browsing:</b> Ensured safe remote connections via **VPN tunneling**.
- <b>Network Traffic Monitoring:</b> Used **Wireshark** to analyze encrypted packets and detect anomalies.

<h2>Environments Used</h2>

- <b>Windows Server 2022</b> (VPN Server)
- <b>Ubuntu 20.04 LTS</b> (Linux-based VPN)
- <b>VirtualBox / VMware Workstation</b> (VM Hosting)
- <b>Wireshark</b> (Network Traffic Analysis)

<h2>Project Walkthrough:</h2>

<p align="center">
Deploying the Virtual Machine: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="VM Deployment"/>
<br />
<br />
Installing & Configuring OpenVPN:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="VPN Setup"/>
<br />
<br />
Firewall & Port Forwarding Settings: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Firewall Configuration"/>
<br />
<br />
Connecting to VPN Securely:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="VPN Connection"/>
<br />
<br />
Monitoring Encrypted Packets with Wireshark:  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Wireshark Analysis"/>
</p>

<h2>Step-by-Step Deployment Guide</h2>

<h3>1. Setting Up a Virtual Machine</h3>
<ul>
    <li>Install and configure **VirtualBox** or **VMware Workstation**.</li>
    <li>Deploy a **Windows Server 2022** or **Ubuntu 20.04** VM.</li>
    <li>Ensure proper network configurations (NAT or Bridged Mode).</li>
</ul>

<h3>2. Installing VPN Software</h3>
<ul>
    <li>For **Windows**, install **OpenVPN Access Server**.</li>
    <li>For **Linux**, use **WireGuard** or **StrongSwan (IPsec)**.</li>
    <li>Generate VPN keys and configure server-side authentication.</li>
</ul>

<h3>3. Configuring Firewall & Port Forwarding</h3>
<ul>
    <li>Allow VPN traffic (ports **1194/UDP for OpenVPN**, **51820/UDP for WireGuard**).</li>
    <li>Block unauthorized external access.</li>
    <li>Enable NAT for proper VPN traffic routing.</li>
</ul>

<h3>4. Connecting to the VPN</h3>
<ul>
    <li>Install the **VPN client** on a remote device.</li>
    <li>Import VPN configuration files (.ovpn, .conf, etc.).</li>
    <li>Authenticate using **username/password or certificates**.</li>
</ul>

<h3>5. Monitoring VPN Traffic with Wireshark</h3>
<ul>
    <li>Start a **Wireshark** packet capture session.</li>
    <li>Filter traffic using **UDP port 1194 (OpenVPN)** or **UDP 51820 (WireGuard)**.</li>
    <li>Verify encrypted tunnel packets for security monitoring.</li>
</ul>

<h2>How to Deploy This Project</h2>
<ol>
    <li>Set up a **Virtual Machine (VM)** on VirtualBox/VMware.</li>
    <li>Install and configure **OpenVPN, WireGuard, or IPsec**.</li>
    <li>Adjust **firewall & port forwarding** settings.</li>
    <li>Establish a **VPN connection** from a remote client.</li>
    <li>Use **Wireshark** to analyze VPN traffic.</li>
</ol>

<h2>Conclusion</h2>
This project demonstrates the **secure setup of a VPN inside a virtual machine**, ensuring **encrypted remote access, secure browsing, and traffic monitoring**. The implementation enhances privacy, prevents unauthorized access, and enables safe communication across networks.

<!--
```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@

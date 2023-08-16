<h1>Capturing Live Network Trafffic in Linux Environment</h1>
<h2>Project Description</h2>
For this task, I used tcpdump to capture and analyze live network traffic from a Linux virtual machine. Tcpdump is a network protocol analyzer that is accessed using the command-line interface. Similar to wireshark, but tcpdump has more functinalities that enable us to capture, filter, and analyze network traffic.<br />

<h2>Environments and Technologies Used</h2>

- (Virtual Machines/Computer)
- Linux Command-Line
- Remote Desktop
- Tcpdump

<h2>Operating Systems Used</h2>

- Linux Operating System (Bash Shell)

<h2>High Level-Steps</h2>

- Identified Network Interfaces
- Inspect Network Interface Traffic with Tcpdump
- Capture Network Traffic with Tcpdump
- Filtered Captured Packet Data

<h2>Task Overview</h2>

<p>
<img src="https://i.imgur.com/Bl3mW3o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/GpUDTpP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, I identified the network interfaces that could be used or that are running for packet data capturing in my organization systems. In doing that, I used the sudo command + tcpdump -D, to gain privilege to access the available interfaces i.e (sudo tcpdump -D). This then outputs all the available interfaces on my directory. Furthermore, I needed to inspect network traffic in my selected network interface which was eth0 (Ethernet network interface), using TCPDUMP protocol analyzer. In doing that, I used the sudo tcpdump -i eth0 -v -c5 commands with some options. After my inspection, I then captured some network traffic (HTTP web TCP port 80) on my selected interface eth0 using tcpdump,
</p>
<br />

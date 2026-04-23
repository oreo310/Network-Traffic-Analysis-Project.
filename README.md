Network Traffic Analysis and Lab Monitoring.*

Project objective:
This project demonstrates the monitoring and analysis of network traffic between a host machine and a virtualized lab environment (Parrot/Metasploitable2) using sniffnet and wireshark.

Tools Used:

Sniffnet. High level traffic visualization and alerting.
Wireshark. Deep packet inspection and protocol analysis.
VirtualBox. Lab environment hosting.
Npcap. Packet capture engine for windows host.

Lab Topology.

Host. Lenovo ThinkPad E15 Gen3 (Windows/Linux)

Target VM
Metasploitable2 (Internal Network/Bridged)

Analysis VM
Parrot OS.

Key Findings

Protocol identification using wireshark, I successfully identified the following protocols during an active scan:
ARP. Mapping MAC addresses within the local subnet.
TCP. [SYN/ACK]: Standard three-way handshake validation.
DNS. Resolution of telemetery domains.

Traffic Visualization.

Image
Captured real-time spikes during Nmap scanning, validating the alerting system's responsiveness.


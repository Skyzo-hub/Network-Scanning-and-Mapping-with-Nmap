# Network Scanning and Mapping with Nmap

## Objective

The objective of this lab is to perform network scanning and mapping using Nmap to identify devices, services, and potential vulnerabilities within a network.

### Skills Learned

- Network reconnaissance.
- Network discovery, port scanning, and understanding basic TCP/IP.
- Proficiency in analyzing and interpreting network logs.
- Security auditing.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Offensive and defensive network security.

### Tools Used

- Nmap (Network Mapper) for log ingestion and analysis.
- Zenmap.
- Traceroute
- Metasploit
- OpenVAS (Open Vulnerability Assessment System)
- Wireshark

## Steps
![image](https://github.com/user-attachments/assets/dfb8cf0f-1533-4b71-b8e2-b9ecfa1831c2)

1. Install Nmap and Wireshark on Kali Linux
![image](https://github.com/user-attachments/assets/88623883-36d1-4fd6-a400-f38d859cdce2)
Use commands like nmap -A <target IP address> 192.168.18.76 for OS detection, version detection, script
scanning, and traceroute.
![image](https://github.com/user-attachments/assets/a3d33de8-42d0-447d-a859-96f7c6107fb4)
nmap -sS <target IP address> 192.168.18.76 for TCP SYN (half-open) scanning
![image](https://github.com/user-attachments/assets/425b74c9-e695-4e33-b2eb-05c2cb72a805)
Allow specific IP addresses in the Firewall (UFW):
![image](https://github.com/user-attachments/assets/b175c668-e1e1-4de0-a519-777a62f40d54)
Install Wireshark in Ubuntu and capture traffic
![image](https://github.com/user-attachments/assets/128c3c47-5f58-4be2-8944-c1f6312fa7cc)
Simulate attack from Kali Linux and defend using Ubuntu and capture traffic with Wireshark.
![image](https://github.com/user-attachments/assets/bda44b0e-46f3-4d93-8185-3c01d834547b)
Practice on Virtual Lab like VMware® Workstation 17 Pro
6. Document findings, including open ports, protocols, and services.

Network Diagram
![image](https://github.com/user-attachments/assets/000a4070-a550-47f4-9ea3-dfffcc2e5c96)





















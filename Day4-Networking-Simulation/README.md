# Day 4 – Networking & Port Simulation Using Git Bash (Windows)

Simulated cloud virtual machine networking using Git Bash on Windows  
Verified network connectivity and DNS resolution  
Checked system identity and IP configuration  
Explored open network ports using `netstat`  
Documented the entire simulation with screenshots

---

## Commands Used:

whoami             # Shows current user
hostname           # Shows computer name
ping -n 4 google.com  # Sends 4 ICMP packets to Google's server
nslookup google.com  # Resolves domain name to IP
ipconfig           # Displays IP and network adapter info
netstat -an        # Lists open and listening ports

## Key Cloud Concepts Simulated:

| Cloud Concept       | Linux/Git Bash Command | Purpose                               |
| ------------------- | ---------------------- | ------------------------------------- |
| VM Identity         | `whoami`, `hostname`   | Who you are and what system you’re on |
| Server Connectivity | `ping`                 | Check if a server is reachable        |
| DNS Lookup          | `nslookup`             | See which IP a domain resolves to     |
| Network Info        | `ipconfig`             | View your system's IP details         |
| Port Inspection     | `netstat`              | List active connections and ports     |


Reflection:
Today I simulated a real-world cloud virtual machine’s networking behavior using Git Bash on Windows. I tested connectivity to Google's servers, resolved domain names with nslookup, and listed open ports using netstat. These tasks mimic what cloud engineers do to debug deployments, monitor availability, and secure network traffic in platforms like Google Cloud or AWS.

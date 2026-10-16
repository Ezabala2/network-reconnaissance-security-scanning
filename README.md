# Network Reconnaissance & Security Scanning

## Project Overview
This project documents hands-on network reconnaissance and security scanning activities performed in an authorized virtual lab environment using Kali Linux and Nmap.

## Objectives
- Discover active hosts on a network
- Identify open ports and running services
- Perform operating system detection
- Analyze scan results and document security observations
- Develop practical network security assessment skills

## Tools & Technologies
- Kali Linux
- Nmap
- Linux Terminal
- Virtual Lab Environment

## Methodology

### 1. Network Discovery
Identify active hosts within an authorized lab subnet.

```bash
nmap -sn 192.168.10.0/27
```

### 2. Port Scanning
Identify common open TCP ports on a lab target.

```bash
nmap 192.168.10.10
```

### 3. Service Version Detection
Identify services and their reported versions.

```bash
nmap -sV 192.168.10.10
```

### 4. Operating System Detection
Perform OS fingerprinting where authorized.

```bash
sudo nmap -O 192.168.10.10
```

## Results & Findings
To be completed using verified results from the lab.

## Screenshots
Sanitized screenshots demonstrating the scanning process and results will be added.

## Key Takeaways
- Understanding network discovery techniques
- Learning how to interpret Nmap scan results
- Identifying services that may require further security review
- Practicing ethical and authorized network assessment

## Ethical Considerations
All scans documented in this project are intended for authorized lab environments only. Sensitive information and credentials will not be published.

## Author
Elijah Zabala
  

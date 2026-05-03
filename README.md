# SOC Lab with Wazuh

## Overview
Built a hands-on SOC environment to detect and analyze cyber attacks using Wazuh.

## Architecture
- SIEM: Wazuh (Ubuntu)
- Attacker: Kali Linux
- Target: Ubuntu Machine

## Simulated Attacks
- SSH brute force
- Nmap network scan

## Detection & Analysis
- Alerts generated in Wazuh
- Log correlation and investigation

## Tools Used
- Wazuh
- Kali Linux
- Nmap

## Screenshots

### Wazuh Dashboard
![Dashboard](/wazuh.dashboard.png)
Wazuh detected repeated failed SSH login attempts, indicating a brute force attack.

### Nmap scan 
![Nmap](/attack.scan.png)

### SSH Brute Force Detection
![SSH Attack](/alert.png)


# Windows 7 SMBv1 (MS17-010) — Educational Lab

## Overview
This repository documents my penetration testing lab exercise on the **EternalBlue vulnerability (MS17-010)** in Windows 7.  
The goal of this project is **educational and portfolio demonstration only**.

## Objectives
- Understand how SMBv1 and MS17-010 work.
- Perform reconnaissance and detection of the vulnerability.
- Show proof of concept through screenshots (no exploit code).
- Provide remediation recommendations.

## Lab Setup
- **Target:** Windows 7 (unpatched, SMBv1 enabled).  
- **Attacker:** Kali Linux (Metasploit & Nmap).  
- **Environment:** Isolated virtual lab, no internet exposure.

## Methodology
1. **Scan target:** Check open ports and SMB service.  
2. **Verify vulnerability:** Identify MS17-010 exposure.  
3. **Exploit (lab only):** Demonstrate shell access (lab-only evidence shown as screenshots).  
4. **Documentation:** Save screenshots for reporting.  

## Screenshots
All evidence from the lab is included in the [`/screenshots`](./screenshots) folder:
- Service scan results  
- Vulnerability detection  
- Shell session established  

## Remediation
- Apply Microsoft patch **MS17-010**.  
- Disable SMBv1.  
- Restrict TCP port 445.  
- Enable SMB signing.  

## Disclaimer
⚠️ This work was performed in a **controlled lab environment**.  
It is shared for **educational purposes only**.  
Never attempt these steps on systems you do not own or have explicit permission to test.

## Screenshots

![Scan results](screenshots/Screenshot%202025-09-10%20210659.png)
![Shell evidence](screenshots/WhatsApp%20Image%202025-08-14%20at%206.20.42%20PM.jpeg)


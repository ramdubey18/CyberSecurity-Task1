# Cyber Security Internship - Task 1  
*Objective:* Discover open ports in the local network using Nmap (TCP SYN scan).  

## 🔹 Scan Performed
- Command used: nmap -sS 10.95.159.136/24  
- Tool: Zenmap (Nmap GUI)  

## 🔹 Findings
- Open Ports found:
  - 53/tcp (domain)
  - 135/tcp (msrpc)
  - 139/tcp (netbios-ssn)
  - 445/tcp (microsoft-ds)

## 🔹 Conclusion
- Open ports were successfully identified.
- These ports may expose services that need to be secured.

## 🔹 Files Included
- scan_results.txt – Full Nmap output
- open_ports.txt – List of discovered open ports
- scan_screenshot.png – Screenshot of scan output

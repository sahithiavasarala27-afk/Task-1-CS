# Cyber Security Internship — Task 1
**Objective:** Scan local network to discover open ports and evaluate exposure.

## Environment
- Nmap 
- Wireshark
- Local network: 192.168.1.0/24

## Commands run
- nmap -sS 192.168.1.0/24 
- nmap -sS 192.1.0/24 -oN scan_results.txt
- nmap -sS 192.1.0/24 -oX scan_results.txt

## Top findings
PORT NO.  SERVICE  STATE
23 TCP     Telnet  Filtered
53 TCP     Domain   Open
80 TCP     HTTP     Open
443 TCP    HTTPS    Open

## Files included
- scans/*.txt, scans/*.xml
- pcap/*.pcap (if any)
- screenshots/*.png
- interview_answers.md

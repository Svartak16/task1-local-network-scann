# task1-local-network-scann
# Task 1 — Local network scan (sejal vartak)

Scanned network: 192.168.31.0/24
Scanner host: 192.168.31.78
Date: 2025-10-20

Commands used:
- nmap -sn 192.168.31.0/24 -oN nmap_hosts_up.txt
- nmap -sS -T4 192.168.31.0/24 -oA nmap_quickscan
- nmap -sS -p- -T4 -A 192.168.31.1 -oA nmap_router_192-168-31-1
- nmap -sS -p- -T4 -A 192.168.31.78 -oA nmap_self_192-168-31-78

Files:
- nmap_quickscan.* , nmap_router_192-168-31-1.*, nmap_self_192-168-31-78.* 
- scan_capture.pcap
- screenshots/

Findings & recommendations: (add your findings here after running the scans)

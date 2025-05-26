🔍 Task 1 – Port Scanning with Nmap
**Elevate Labs Cyber Security Internship**

✅ Objective
Perform a TCP SYN scan using Nmap on my local network to discover open ports and assess possible security exposure.

---

🧰 Tools Used
- **Nmap** v7.95 (command-line)
- **OS:** Kali Linux
- **Network Interface:** eth0

---

🖥️ My Local Network Info
- **IP Address:** 192.168.43.8
- **Subnet:** 255.255.255.0 → `192.168.76.0/24`

---

🧪 Scan Command Used
bash: nmap -sS 192.168.43..0/24 -oN portscan.txt

🧪 Wireshark Analysis
I used Wireshark to observe network traffic during my Nmap TCP SYN scan.


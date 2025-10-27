# cs-task5
# 🧠 Task 5: Capture and Analyze Network Traffic Using Wireshark

## 🎯 Objective
To capture live network packets using *Wireshark*, analyze them, and identify different protocols and types of network traffic.

---

## 🛠 Tools Used
- *Wireshark* (Free Network Protocol Analyzer)
- *Windows/Linux/MacOS*
- *Web Browser / Command Prompt*

---

## 🧩 Steps Followed

### *Step 1: Installed and Launched Wireshark*
- Opened Wireshark and viewed available network interfaces.
- Selected the *active network (Wi-Fi)* interface for live capture.

### *Step 2: Captured Network Traffic*
- Started packet capture.
- Browsed websites (like google.com, youtube.com) and used the ping command to generate traffic.
- Stopped capture after about 1 minute.

### *Step 3: Applied Filters*
Used filters to view specific protocols:
| Filter | Description |
|--------|--------------|
| http | Shows web traffic (browsing) |
| dns | Shows domain name resolution traffic |
| tcp | Shows TCP connection packets |

### *Step 4: Identified Protocols*
Observed multiple protocols in the captured packets:
1. *DNS* – Resolves domain names (e.g., www.google.com → IP address)
2. *HTTP* – Used for loading web pages
3. *TCP* – Provides reliable communication between systems

### *Step 5: Analyzed Packets*
For each protocol:
- *DNS Packet:* Query sent to 8.8.8.8 asking for Google’s IP.  
- *HTTP Packet:* GET request made to Google’s web server.  
- *TCP Packet:* Established connection (3-way handshake) between my device and Google server.

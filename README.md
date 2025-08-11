# Task 5: Capture and Analyze Network Traffic Using Wireshark

## Objective
Capture live network packets, identify basic protocols, and understand traffic types.

---

## Tools Used
- **Wireshark** (Free Network Protocol Analyzer)
- **Command Prompt** (Windows) for generating ICMP traffic using `ping`
- **Operating System**: Windows 10

---

## Steps Followed
1. Installed Wireshark from the official site.
2. Started packet capture on my active Wi-Fi interface.
3. Generated network traffic by:
   - Visiting multiple websites (HTTP/HTTPS).
   - Pinging a server using `ping google.com` to generate ICMP packets.
4. Stopped capture after ~1 minute.
5. Filtered packets by protocol (`http`, `dns`, `tcp`, `icmp`).
6. Identified at least 3 different protocols in the capture.
7. Exported the capture files as `.pcapng`.
8. Summarized findings in this README.

---

## Screenshots

### 1. Capturing DNS Traffic
![DNS traffic capture](screenshots/dns.png)  
Captured DNS queries and responses for domain name resolution.

---

### 2. Generating ICMP Packets Using Ping
![ICMP traffic capture](screenshots/ICMP%20packets.png)  
Used `ping google.com` to generate ICMP packets.

---

### 3. Capturing HTTP Traffic
![HTTP traffic capture](screenshots/http.png)  
Captured HTTP GET requests and responses.

---

### 4. Capturing TCP Traffic
![TCP traffic capture](screenshots/tcp.png)  
Applied filter `tcp` to inspect TCP connection setup and teardown.

---

## Protocols Identified
| Protocol | Description | Example Usage |
|----------|-------------|--------------|
| HTTP     | Web traffic | Browsing unencrypted websites |
| DNS      | Resolves domain names to IP addresses | Accessing google.com |
| TCP      | Reliable data transfer protocol | Web browsing, file transfers |
| ICMP     | Internet Control Message Protocol | Ping command for connectivity check |

---

## Files in This Repo
- `dns.pcapng` – DNS packet capture.
- `http.pcapng` – HTTP packet capture.
- `tcp.pcapng` – TCP packet capture.
- `ICMP packets.png` – Screenshot of ICMP ping test.
- `README.md` – Instructions, steps, and screenshots.

---

## Key Learning
- How to capture and analyze network packets using Wireshark.
- How to use filters (`dns`, `http`, `tcp`, `icmp`) to isolate specific traffic.
- Understanding of basic network protocols.

---

## Author
K.Nashitha – Cyber Security Internship Task 5

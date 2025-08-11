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
1. **Installed Wireshark** from the official site.
2. **Started packet capture** on my active Wi-Fi interface.
3. **Generated network traffic** by:
   - Visiting multiple websites (HTTP/HTTPS).
   - Pinging a server using `ping google.com` to generate ICMP packets.
4. **Stopped capture** after ~1 minute.
5. **Filtered packets by protocol** (`http`, `dns`, `tcp`).
6. **Identified at least 3 protocols** in the capture.
7. **Exported the capture** to a `.pcap` file.
8. **Summarized findings** in this report.

---

## Screenshots

### 1. Capturing DNS Traffic
![DNS traffic capture](screenshots/1.pcap)  
Captured DNS queries and responses resolving domain names.

---

### 2. Generating ICMP Packets Using Ping
![Ping command output](screenshots/2.pcap)  
Used `ping google.com` to generate ICMP traffic for analysis.

---

### 3. Capturing HTTP Traffic
![HTTP traffic capture](screenshots/3.pcap)  
Captured HTTP GET requests and responses.

---

### 4. Filtering DNS Packets
![DNS filtered packets](screenshots/4.pcap)  
Applied filter `dns` to view only DNS-related packets.

---

### 5. Capturing TCP Traffic
![TCP traffic capture](screenshots/5.pcap)  
Applied filter `tcp` to inspect TCP connection setup and teardown.

---

## Protocols Identified
| Protocol | Description | Example Usage |
|----------|-------------|--------------|
| HTTP     | Web traffic | Browsing websites |
| DNS      | Resolves domain names to IP addresses | Accessing google.com |
| TCP      | Reliable data transfer protocol | Web browsing, file transfers |
| ICMP     | Internet Control Message Protocol | Ping command for connectivity check |

---

## Files in This Repo
- `capture.pcap` – The raw packet capture.
- `README.md` – Instructions, steps, and screenshots.

---

## Key Learning
- How to capture and analyze network packets.
- How to use filters in Wireshark.
- Basic understanding of TCP/IP protocols and ICMP.



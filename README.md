# 🛡️ SOC Network Traffic Analysis Labs

This repository contains **Wireshark labs and reports** focused on analyzing network traffic for security monitoring and SOC practices. Labs include **DNS, HTTP, TCP, and general network traffic analysis**, with detailed packet inspection and observations.

---

## 📂 Labs & Focus Areas

| Lab | Focus | SOC Relevance / Wireshark Filter |
|-----|-------|---------------------------------|
| **DNS Traffic Capture** | Capture and analyze DNS queries and responses | Detect suspicious domain lookups, malware C2 activity `dns` |
| **HTTP Capture** | Capture HTTP traffic to identify visited websites | Monitor web traffic for anomalies `http` |
| **HTTP Request Capture** | Inspect GET/POST requests, headers, and URLs | Identify potential data exfiltration or unauthorized requests `http.request` |
| **HTTP Response Capture** | Inspect server responses and payloads | Detect unusual server behavior or sensitive info leaks `http.response` |
| **HTTP Response Codes** | Track status codes like 200, 404, 500 | Spot misconfigurations, failed logins, or attacks `http.response.code` |
| **Network Traffic Capture** | Capture TCP, UDP, ICMP traffic | Monitor network baseline, detect scans or unusual traffic `tcp`, `udp`, `icmp` |
| **TCP Length Analysis** | Analyze TCP segment sizes | Identify abnormal packet sizes, fragmentation, or exfil attempts `tcp.len > 0` |
| **TCP Stream Capture** | Reconstruct full TCP conversations | Analyze session content, detect malware or suspicious communications Right-click → Follow → TCP Stream |


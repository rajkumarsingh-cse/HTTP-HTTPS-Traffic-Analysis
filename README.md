# HTTP vs HTTPS Traffic Analysis Using Wireshark

## Project Overview
This project focuses on capturing and analysing HTTP and HTTPS network traffic using Wireshark in a Kali Linux environment. The objective is to understand how data travels across a network and compare unencrypted HTTP communication with encrypted HTTPS communication.

## Objectives
- Capture live network packets using Wireshark.
- Analyse HTTP requests and server responses.
- Inspect HTTPS traffic and TLS handshake information.
- Understand the differences between encrypted and unencrypted communication.
- Use Wireshark display filters to analyse network traffic.

## Tools and Technologies
- **Operating System:** Kali Linux
- **Network Analysis Tool:** Wireshark
- **Protocols:** HTTP, HTTPS, TLS
- **Environment:** Oracle VirtualBox

## Practical Implementation

### 1. HTTP Traffic Analysis
- Captured HTTP packets using Wireshark.
- Applied the `http` display filter.
- Examined HTTP GET requests and HTTP 200 OK server responses.
- Observed source and destination IP addresses and packet details.
- Inspected HTTP request headers.

### 2. HTTPS Traffic Analysis
- Captured HTTPS-related traffic using Wireshark.
- Applied the `tls` display filter.
- Observed TLS Client Hello messages and handshake-related packets.
- Identified TLS 1.2 and TLS 1.3 traffic.
- Observed encrypted Application Data packets.

## HTTP vs HTTPS Comparison

| Feature | HTTP | HTTPS |

| Security | Unencrypted | Encrypted using TLS |
| Data visibility | Readable application data | Application data is encrypted |
| Default port | 80 | 443 |
| Protection | No TLS encryption | TLS encryption |

## Key Learnings
- Learned how to capture live network packets.
- Understood HTTP GET requests and server responses.
- Learned to apply Wireshark display filters.
- Observed TLS handshake messages.
- Understood how HTTPS protects application data through encryption.

## Conclusion
Through this hands-on project, I gained practical experience in network traffic monitoring and protocol analysis using Wireshark. I also developed an understanding of the security differences between HTTP and HTTPS communication.

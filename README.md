# Network Packet Analysis using Wireshark

## Project Overview

This project demonstrates basic **network traffic analysis** using Wireshark. The objective is to capture and analyze network packets to understand how devices communicate over a network and identify different communication protocols.

## Objective

* Capture network packets from a live network interface
* Analyze common network protocols
* Understand communication between client and server
* Observe how DNS and HTTP requests work

## Tools Used

* Wireshark
* Kali Linux

## Methodology

1. Launched Wireshark and selected the active network interface.
2. Started packet capture to monitor real-time network traffic.
3. Generated network activity by visiting websites in the browser.
4. Applied filters in Wireshark to analyze specific protocols such as DNS, HTTP, and TCP.
5. Examined packet details including source IP, destination IP, protocol type, and packet structure.

## Filters Used

DNS traffic:

```bash
dns
```

HTTP traffic:

```bash
http
```

TCP packets:

```bash
tcp
```

## Key Observations

* Observed DNS queries used for domain name resolution.
* Captured HTTP communication between client and web server.
* Analyzed TCP packets involved in establishing network connections.

## Learning Outcomes

* Understanding how network traffic flows between systems.
* Learning how to capture and inspect packets using Wireshark.
* Gaining basic knowledge of network protocols and packet structure.

## Screenshots

Screenshots of packet capture and analysis are available in the **screenshots** folder.

Example screenshots include:

* Packet capture in progress
* DNS packet analysis
* TCP packet details

## Disclaimer

This project was performed in a controlled environment on my own system for educational and learning purposes only.

# wireshark-simple-writeup.
A beginner-friendly Wireshark practical lab exploring TCP 3-Way Handshake, HTTP, DNS, packet analysis, Export Objects, network statistics, and VPN traffic behavior. Documented in Sinhala and English.

# 🔍 Wireshark Practical Lab – Sinhala Write-up

A beginner-friendly practical guide to understanding network traffic analysis using **Wireshark**.

This project documents my hands-on learning experience with Wireshark while exploring network communication, packet analysis, HTTP requests, DNS queries, and VPN traffic behavior.

**Author:** Malith Lakshan Wijekoon  
**Tool:** Wireshark  
**Test Website:** [neverssl.com](http://neverssl.com)  
**Date:** November 12–13, 2026

---

## 🎯 Lab Objectives

- Understand how network packets work.
- Explore TCP 3-Way Handshake.
- Analyze HTTP Request and Response.
- Understand DNS queries and responses.
- Explore HTTP Object Exporting.
- Analyze network protocols using Statistics.
- Observe network traffic changes when using a VPN.

## 🧪 Practical Activities

### 1. TCP 3-Way Handshake
Understanding how a TCP connection is established using:

- SYN
- SYN-ACK
- ACK

![TCP 3-Way Handshake](images/handshake.jpg)

### 2. HTTP Request & Response Analysis

Analyzing HTTP communication between a browser and a web server.

Topics explored:
- HTTP GET requests
- HTTP status codes (301, 200)
- Server information disclosure
- Apache server headers

![HTTP Analysis](images/http_request.jpg)

### 3. DNS Analysis

Understanding how domain names are resolved into IP addresses.

Topics explored:
- DNS Queries
- DNS Responses
- A Records
- IPv4 Address Resolution

![DNS Analysis](images/dns_answer.jpg)

### 4. Export Objects

Exploring Wireshark's Export Objects feature to extract transferred HTTP files.

**Steps:**
1. Apply the `http` display filter.
2. Navigate to File → Export Objects → HTTP.
3. Select an available object.
4. Export the selected file.

![Export Objects](images/export_objects.jpg)

### 5. Network Statistics

Exploring Wireshark Statistics to understand captured network traffic.

- Protocol Hierarchy
- Conversations
- Protocol distribution
- Communication between IP addresses

![Protocol Hierarchy](images/protocol_hierarchy.jpg)

### 6. VPN Traffic Analysis

Comparing network traffic before and after enabling Bright VPN.

Topics explored:
- HTTP traffic visibility
- Encrypted network traffic
- UDP / QUIC traffic
- Changes in observed network connections

**Before VPN:**

![Before VPN](images/before_vpn.jpg)

**After VPN:**

![After VPN](images/after_vpn_encrypted.jpg)

---

## 📚 Key Learning Outcomes

Through this practical lab, I explored:

- How TCP connections are established.
- How HTTP requests and responses work.
- How DNS resolves domain names.
- How server information can be exposed through HTTP headers.
- How files can be extracted from captured HTTP traffic.
- How Wireshark Statistics helps analyze network communication.
- How VPN usage changes the visibility and characteristics of network traffic.

## 🛠️ Tools & Technologies

- Wireshark
- HTTP
- DNS
- TCP/IP
- UDP
- QUIC
- Bright VPN

## ⚠️ Disclaimer

This practical exercise was conducted on my own network using the intentionally HTTP-based practice website `neverssl.com`.

The purpose of this lab was educational, focusing on network traffic analysis and cybersecurity fundamentals.

No exploitation or unauthorized access was performed.

---

## 🚀 Learning Journey

This is one of my beginner-level practical cybersecurity learning projects.

I'm continuously learning, practicing, and improving my knowledge in networking and cybersecurity.

**Learn • Practice • Analyze • Improve**


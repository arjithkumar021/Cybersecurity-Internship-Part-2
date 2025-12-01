# Packet Analysis with Wireshark

This folder contains packet capture analysis performed using Wireshark.

## Contents

- **http-traffic.png** - HTTP traffic analysis
- **ftp-credentials.png** - FTP credential capture (demonstrating insecure protocols)
- **dns-queries.png** - DNS query analysis
- **syn-flood-wireshark.png** - SYN flood attack detection

## Overview

Wireshark is a powerful network protocol analyzer used to capture and examine network traffic in detail.

## Analysis Performed

### 1. HTTP Traffic Analysis
- Captured unencrypted HTTP traffic
- Analyzed HTTP requests and responses
- Identified potential security issues with clear-text transmission

### 2. FTP Credential Capture
- Demonstrated vulnerability of FTP protocol
- Captured credentials transmitted in clear text
- Highlighted importance of using secure protocols (SFTP, FTPS)

### 3. DNS Queries
- Analyzed DNS resolution process
- Identified DNS queries and responses
- Examined potential DNS-based attacks

### 4. SYN Flood Detection
- Identified SYN flood attack patterns
- Analyzed abnormal TCP connection attempts
- Demonstrated DoS attack detection capabilities

## Key Findings

- Insecure protocols expose sensitive information
- Network traffic analysis is crucial for security monitoring
- Wireshark is essential for incident response and forensics

## Tools Used

- Wireshark
- tcpdump (for packet capture)

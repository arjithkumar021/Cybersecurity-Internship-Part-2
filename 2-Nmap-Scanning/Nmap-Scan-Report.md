# Nmap Scanning Report

## Executive Summary

This report documents the network scanning activities performed using Nmap on the target network.

## Scan Types Performed

### 1. TCP SYN Scan (-sS)
- **Purpose**: Stealth scanning to identify open TCP ports
- **Screenshot**: `nmap-sS.png`

### 2. UDP Scan (-sU)
- **Purpose**: Identify open UDP ports
- **Screenshot**: `nmap-sU.png`

### 3. Version Detection (-sV)
- **Purpose**: Detect service versions running on open ports
- **Screenshot**: `nmap-sV.png`

### 4. OS Detection (-O)
- **Purpose**: Identify operating system of target hosts
- **Screenshot**: `nmap-OS.png`

### 5. Aggressive Scan (-A)
- **Purpose**: Comprehensive scan including OS detection, version detection, script scanning, and traceroute
- **Screenshot**: `nmap-A.png`

## Key Findings

- Open ports and services discovered
- Operating system identification
- Service version information
- Potential vulnerabilities identified

## Recommendations

Based on the Nmap scan results, recommendations for security hardening are provided in the findings summary.

---

*Refer to `findings-summary.txt` for detailed results.*

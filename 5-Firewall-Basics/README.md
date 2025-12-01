# Firewall Configuration Basics

This folder contains firewall configuration examples using iptables on Linux.

## Contents

- **iptables-allow-rule.png** - Example of allow/accept rules
- **iptables-deny-rule.png** - Example of deny/drop rules
- **iptables-list.png** - Complete iptables rule listing

## Overview

iptables is a powerful firewall utility for Linux systems that allows administrators to configure packet filtering rules.

## Key Concepts

### 1. Allow Rules
- Permit specific traffic to pass through the firewall
- Essential for allowing legitimate services
- Screenshot demonstrates allowing specific ports/services

### 2. Deny Rules
- Block unwanted or malicious traffic
- Default deny policy for security hardening
- Screenshot shows blocking specific traffic

### 3. Rule Management
- Viewing current firewall rules
- Understanding rule order and priority
- Proper rule organization for security

## Common iptables Commands

```bash
# List all rules
sudo iptables -L -v -n

# Allow incoming SSH
sudo iptables -A INPUT -p tcp --dport 22 -j ACCEPT

# Block incoming traffic from specific IP
sudo iptables -A INPUT -s 192.168.1.100 -j DROP

# Save rules
sudo iptables-save > /etc/iptables/rules.v4
```

## Best Practices

- Implement default deny policy
- Allow only necessary services
- Log dropped packets for monitoring
- Regularly review and update rules
- Test rules before applying to production

## Tools Used

- iptables
- netfilter

# Domain 4: Network Security

## How to Use This Domain

Use this domain to study network basics, common protocols, network threats, and defensive controls. Network security is heavily tested because many attacks, logs, alerts, and investigations involve communication between systems.

## Section 1: Network Concepts

### What You Should Understand

A network connects systems so they can communicate and share resources. Security depends on understanding how devices, addresses, protocols, and traffic work together.

### Key Concepts

- Networks connect endpoints, servers, and services.
- LANs cover local areas; WANs connect larger areas.
- Routers move traffic between networks.
- Switches connect devices within a network.
- Firewalls filter traffic.
- Network segmentation separates systems to reduce risk.

### Important Terms

- LAN - Local Area Network.
- WAN - Wide Area Network.
- Router - Connects networks and forwards traffic.
- Switch - Connects devices in a local network.
- Firewall - Filters traffic based on rules.
- Endpoint - User device or system.
- Server - System that provides services.
- Segmentation - Dividing a network into smaller sections.

### What To Practice

- Draw a small network with laptop, switch, router, firewall, server, and internet.
- Explain how traffic moves from a laptop to a website.
- Identify why segmentation helps protect sensitive systems.

### Quick Check

1. What is a network?
2. What is the difference between a router and a switch?
3. What does a firewall do?
4. Why is segmentation useful?
5. What is an endpoint?

## Section 2: Protocols, Ports, and Network Services

### What You Should Understand

Protocols are rules for communication. Ports identify services. Analysts use protocols and ports to understand logs, firewall rules, alerts, and network behavior.

### Key Concepts

- IP addresses identify systems on a network.
- DNS translates names to IP addresses.
- DHCP assigns IP configuration.
- TCP is connection-oriented.
- UDP is connectionless and often faster.
- Common ports help identify services.

### Common Ports

| Port | Protocol | Common Use |
| --- | --- | --- |
| 22 | SSH | Secure remote administration |
| 25 | SMTP | Email sending |
| 53 | DNS | Name resolution |
| 80 | HTTP | Web traffic |
| 110 | POP3 | Email retrieval |
| 143 | IMAP | Email retrieval |
| 443 | HTTPS | Secure web traffic |
| 3389 | RDP | Windows remote desktop |

### Important Terms

- IP address - Logical network address.
- MAC address - Hardware address of a network interface.
- DNS - Domain Name System.
- DHCP - Dynamic Host Configuration Protocol.
- TCP - Transmission Control Protocol.
- UDP - User Datagram Protocol.
- Port - Number identifying a network service.

### What To Practice

- Memorize the most common ports.
- Read a simple firewall log and identify source, destination, protocol, port, and action.
- Explain why HTTPS is preferred over HTTP.

### Quick Check

1. What does DNS do?
2. What does DHCP do?
3. What port is commonly used for HTTPS?
4. What is the difference between TCP and UDP?
5. Why do analysts care about ports?

## Section 3: Network Threats and Attacks

### What You Should Understand

Attackers target networks to steal information, disrupt service, move inside environments, or gain unauthorized access. Recognizing common attack types helps analysts interpret alerts and logs.

### Key Concepts

- DoS and DDoS attacks target availability.
- Spoofing impersonates a trusted source.
- Man-in-the-middle attacks intercept communication.
- Packet sniffing captures traffic.
- Malware may communicate over the network.
- Lateral movement uses internal network access to reach more systems.

### Important Terms

- DoS - Denial of Service.
- DDoS - Distributed Denial of Service.
- Spoofing - Impersonating another source.
- MITM - Man-in-the-middle attack.
- Packet sniffing - Capturing network packets.
- Malware - Malicious software.
- Lateral movement - Moving from one compromised system to another.
- Exfiltration - Unauthorized data transfer out of an environment.

### What To Practice

- Identify signs of DDoS in logs or dashboards.
- Explain how encryption reduces packet-sniffing risk.
- List suspicious network indicators such as unusual ports, rare destinations, or large outbound transfers.

### Quick Check

1. What security principle does DDoS attack?
2. What is spoofing?
3. What is a man-in-the-middle attack?
4. What is exfiltration?
5. Why is lateral movement dangerous?

## Section 4: Network Security Controls

### What You Should Understand

Network security controls reduce attack surface, filter traffic, protect communication, and detect suspicious activity. Strong network defense uses layered controls.

### Key Concepts

- Firewalls allow or block traffic based on rules.
- VPNs protect remote connections with encrypted tunnels.
- IDS detects suspicious traffic.
- IPS can block suspicious traffic.
- Network access control verifies whether devices should connect.
- Wireless security protects Wi-Fi networks.
- Secure configuration reduces unnecessary exposure.

### Important Terms

- VPN - Virtual Private Network.
- IDS - Intrusion Detection System.
- IPS - Intrusion Prevention System.
- NAC - Network Access Control.
- WPA2/WPA3 - Wireless security standards.
- DMZ - Network area for public-facing services.
- Defense in depth - Multiple layers of security.
- Attack surface - All possible entry points for attack.

### What To Practice

- Create firewall rules for a public web server.
- Compare IDS and IPS.
- Explain how VPN, MFA, and logging work together for remote access.
- Identify hardening steps for a wireless network.

### Quick Check

1. What is the difference between IDS and IPS?
2. Why is VPN useful for remote access?
3. What is a DMZ?
4. What does defense in depth mean?
5. How does secure configuration reduce risk?

## Domain Review Checklist

- I can explain LAN, WAN, routers, switches, firewalls, and endpoints.
- I understand IP addresses, MAC addresses, DNS, DHCP, TCP, UDP, and ports.
- I know common ports used in basic security analysis.
- I can identify common network attacks.
- I understand firewalls, VPNs, IDS, IPS, NAC, and wireless security.
- I can explain segmentation, DMZ, defense in depth, and attack surface.

## Quick Revision

Network security protects communication between systems. Important areas include network devices, protocols, ports, common attacks, and layered controls. Analysts use network knowledge to understand traffic, investigate alerts, configure defenses, and reduce exposure.
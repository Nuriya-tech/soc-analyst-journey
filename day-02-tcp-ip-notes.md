# Day 02 – TCP/IP Fundamentals

## Key Learnings
- The OSI model has 7 layers, TCP/IP model has 4 (Application, Transport, Internet, Network Access).
- TCP is connection-oriented (SYN, SYN-ACK, ACK); UDP is connectionless.
- Common ports: HTTP (80), HTTPS (443), DNS (53), SSH (22), RDP (3389).
- IP addresses and subnets – basic CIDR notation (/24, /16).
- Encapsulation and decapsulation flow across layers.

## Hands-on
- Used Wireshark to capture and inspect a TCP three-way handshake.
- Examined HTTP and DNS packets with filters: `tcp.port == 80`, `dns`.

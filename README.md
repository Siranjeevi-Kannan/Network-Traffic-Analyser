# Network Traffic Analysis using Wireshark

## Objective
To capture and analyze HTTP, HTTPS, and DNS traffic in order to understand
network communication and the impact of encryption on data visibility.

## Tools Used
- Kali Linux
- Wireshark

## Methodology
- Captured live network traffic on an active interface
- Visited HTTP and HTTPS websites
- Applied protocol-based filters (http, tls, dns)

## Observations
- HTTP traffic exposed readable request headers such as Host and User-Agent
- HTTPS traffic encrypted application data using TLS
- DNS queries revealed domain resolution prior to encrypted communication


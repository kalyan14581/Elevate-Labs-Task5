# Elevate-Labs-Task5


# Wireshark Network Packet Analysis

## Project Title
Wireshark Packet Capture and Protocol Analysis

## Objective
The objective of this exercise was to analyze network traffic using Wireshark by capturing real-time packets, filtering them by protocol, identifying common protocols in use, and exporting the capture for documentation and analysis.

## Tools Used
- **Wireshark
- **Network Interface** – Wi-Fi (Wireless Adapter)
- **Operating System** –  Windows

## Steps Performed

1. **Installed Wireshark** from the official source.
2. **Captured live packets** on the Wi-Fi interface.
3. **Generated traffic** by browsing websites and pinging servers.
4. **Stopped the capture** after approximately one minute.
5. **Filtered protocols** using Wireshark filters: `http`, `dns`, `tcp`, etc.
6. **Identified three or more protocols** present in the capture.
7. **Exported the capture** as `wifi packets.pcapng`.

## Protocols Identified

1. **DNS (Domain Name System):** Used for domain name resolution.
2. **TCP (Transmission Control Protocol):** Handles reliable data transmission.
3. **ICMP (Internet Control Message Protocol):** Used for ping and diagnostic messages.
4. **HTTP (HyperText Transfer Protocol):** Web browsing traffic (if visible).
5. **TLS (Transport Layer Security):** Encrypted communication (HTTPS traffic).



> You can view these in Wireshark’s “Info” column and expand the packet layers for details.

## Capture File Info

- **File Name:** `wifi packets.pcapng`
- **File Format:** PCAPNG (Wireshark Next Generation Capture Format)
- **Size:** [Autofill based on your OS]
- **Tool:** Saved using Wireshark File → Save As option.

## Summary

This network analysis showed how various protocols are involved in routine network activity. DNS requests resolved domain names, TCP provided reliable connections, and TLS secured the data transfer. Wireshark is highly useful for protocol analysis, network troubleshooting, and cybersecurity research.

## Notes

- Ensure sensitive data (such as IPs or credentials) is anonymized.
- For deeper inspection, revisit the `.pcapng` file using Wireshark filters like `tcp.port == 443`, `icmp`, `dns`, etc.

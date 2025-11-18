# Azure Packet Capture Lab

This lab demonstrates how to implement **Packet Capture** in **Microsoft Azure** to monitor and troubleshoot VM network traffic **without third-party tools like Wireshark**.

## Lab Overview

- **Packet Capture Name:** `PACKET_CAPTURE`
- **Virtual Machine Name:** `khempacket`
- **Enabled Ports:** HTTPS (443), HTTP (80), RDP (3389)
- **Traffic Type:** Inbound & Outbound
- **Filtering:** 5-tuple rule
  - Protocol: TCP/UDP
  - Local IP Address
  - Remote IP Address
  - Local Port
  - Remote Port

## Objectives

- Capture and analyze network packets in Azure.
- Troubleshoot VM connectivity issues.
- Detect suspicious or abnormal network traffic.

## Steps Performed

1. Navigate to the Azure Portal and open your VM (`khempacket`).
2. Create a **Packet Capture** instance (`PACKET_CAPTURE`).
3. Configure the capture filters based on:
   - Protocols: TCP/UDP
   - Ports: HTTP, HTTPS, RDP
   - IP Addresses: Local and Remote
4. Start packet capture and monitor inbound/outbound traffic.
5. Stop the capture and download results for analysis.

## Benefits

- Native packet capture without installing third-party tools.
- Real-time monitoring of traffic.
- Simplified troubleshooting for networking issues.

## Lab Diagram

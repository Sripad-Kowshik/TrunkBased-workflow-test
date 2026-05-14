# DHCP (Dynamic Host Configuration Protocol)

## Overview
DHCP is a network management protocol that automatically assigns IP addresses and other network configuration parameters to devices on a network.

## How It Works
1. **Discover** – Client broadcasts a request to find available DHCP servers.
2. **Offer** – Server responds with an available IP address and lease details.
3. **Request** – Client formally requests the offered IP address.
4. **Acknowledge** – Server confirms the assignment; client configures its network settings.

## Key Components
- **DHCP Server** – Manages and distributes IP addresses from a defined pool.
- **DHCP Client** – Any device that requests network configuration automatically.
- **IP Address Pool** – Range of addresses the server can assign.
- **Lease Time** – Duration for which an IP address is assigned to a client.

## Information Provided by DHCP
- IP address and subnet mask
- Default gateway
- DNS server addresses
- Lease duration

## Ports
- **UDP 67** – Server listens for client requests.
- **UDP 68** – Client listens for server responses.

## Advantages
- Eliminates manual IP configuration and reduces human error.
- Centralizes network address management.
- Supports large networks with dynamic device connections.

## Common Use Cases
- Home and enterprise networks
- Wi-Fi hotspots
- Cloud and virtualized environments

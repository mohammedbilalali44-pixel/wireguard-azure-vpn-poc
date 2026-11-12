## WireGuard VPN on Microsoft Azure
A practical WireGuard VPN deployment lab demonstrating secure remote connectivity using an Ubuntu-based WireGuard server hosted in Microsoft Azure.

This repository contains deployment guides, architecture diagrams, and configuration examples for multiple WireGuard client scenarios.

## Overview
WireGuard is a modern VPN solution designed to provide secure, high-performance encrypted networking with a minimal configuration footprint.

This project demonstrates:

WireGuard Server deployment on Azure Ubuntu VM
VPN connectivity using Linux clients
VPN connectivity using Windows clients
Azure networking and NSG configuration
Client and server configuration examples
Connectivity validation and testing
## Architecture
## Azure Ubuntu Server → Linux Client
![Linux Client Architecture](images/Linux%20Client%20Architecture.png)

Reference architecture showing a WireGuard VPN tunnel between an Azure-hosted Ubuntu server and a remote Linux client.

## Azure Ubuntu Server → Windows Client
![Windows Client Architecture](images/Windows%20Client%20Architecture.png)

Reference architecture showing a WireGuard VPN tunnel between an Azure-hosted Ubuntu server and a remote Windows client.

## Key Features
Secure VPN connectivity using WireGuard
Lightweight and high-performance deployment
Cross-platform VPN support
Azure-hosted infrastructure
Encrypted communication using modern cryptography
Simple and reproducible configuration
Testing Performed
## The lab was validated using:

1. WireGuard tunnel status verification

2. Endpoint connectivity testing

3. ICMP reachability tests

4. SSH connectivity validation

5. VPN peer handshake validation

6. Internet access testing through the tunnel

## Documentation
Detailed deployment guides are available in the docs directory.

## Security Notice
This repository contains example configurations only.
The following items have been intentionally excluded:

1. Private keys

2. Public IP addresses

3. Azure Subscription IDs

4. Resource Group names

5. Production DNS records

6. Tenant information

7. Sensitive customer data
Replace all placeholder values with your own lab or production settings before deployment.

## Disclaimer
This project is intended for educational, testing, and proof-of-concept purposes. Review and adjust the configuration to meet your organization's security and compliance requirements before production use.

## Author
Mohammed Bilal Ali

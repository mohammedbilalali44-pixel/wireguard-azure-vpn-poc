##WireGuard VPN on Microsoft Azure

##Overview 
This project demonstrates the deployment and validation of a WireGuard VPN tunnel between Microsoft Azure regions.

The objective was to evaluate secure connectivity and measure latency between a client hosted in India and a WireGuard VPN server hosted in East US.

##Business Scenario :
A customer wanted to understand:

What latency should users in India expect when connecting to a WireGuard VPN gateway hosted in East US?

Rather than relying on estimates, a Proof of Concept was built and tested using Azure virtual machines.

##Architecture : 

<img width="176" height="242" alt="architecture" src="https://github.com/user-attachments/assets/022d4f1b-725e-4caa-9c58-88398ed5d6a0" />


##Test Results :
Metric	Result

Tunnel Status	Successful

Packet Loss	0%

Average RTT	229.367 ms

Minimum RTT	229.281 ms

Maximum RTT	229.639 ms

Jitter	0.074 ms

##Key Findings
The majority of the observed latency originated from the geographical distance between India and East US rather than VPN processing overhead.

WireGuard introduced negligible additional latency while maintaining secure encrypted communication.

##Project Deliverables
WireGuard VPN Proof of Concept Documentation
WireGuard VPN Deployment Guide
Azure Network Security Configuration
WireGuard Server Configuration
WireGuard Client Configuration
Latency Analysis and Validation Results

##Repository Structure 

docs/
    Project Documentation

configs/
    Sample WireGuard Configurations

images/
    Screenshots and Architecture Diagrams
    
##Outcome
Successfully deployed and validated WireGuard VPN connectivity between Azure regions with 0% packet loss and stable cross-region performance.

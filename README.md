# SecureDeptNet
## Description
>SecureDeptNet is a secure and efficient network infrastructure designed for an organization with four departments: HR, Finance, Business, and Admin. The network utilizes Inter-VLAN technology to enable communication between different departments while ensuring security and isolation. Additionally, two servers are hosted in the Data Centre's DMZ zone: a Web Server and a Mail Server.

## Installation
To set up SecureDeptNet, follow these steps:

- Download and install Cisco Packet Tracer (version X.X or higher) from Cisco's official website.
- Clone this repository to your local machine.
- Open the project file in Cisco Packet Tracer.
- Configure the network devices according to the provided topology and security guidelines.
- Test the network configuration to ensure proper functionality.

## Usage
To use SecureDeptNet:

- Power on all network devices.
- Verify connectivity between devices within the same VLAN.
- Test access to resources across different VLANs.
- Monitor network traffic and security logs for any anomalies.
- Regularly update security policies and configurations as needed.

## Network Topology

This network topology consists of:

- ``Core Router``: Handles inter-VLAN routing and connectivity to external networks.
- ``Distribution Switch``: Aggregates connections from access switches and implements VLANs.
- ``Access Switches``: Connects end-user devices within each department's VLAN.
- ``Servers``: Hosts critical applications and network services.
- ``Printers``: Network-capable printers accessible within their respective VLANs.

## Security Measures
SecureDeptNet implements the following security measures:

- VLAN segmentation to isolate departments and reduce broadcast domain size.
- Access control lists (ACLs) to control traffic flow between VLANs and enforce security policies.
- Port security features like MAC address filtering and sticky MAC addresses to prevent unauthorized access.
- Regular security audits and updates to maintain network integrity.

## Routing Protocol
SecureDeptNet utilizes the OSPF routing protocol for dynamic routing within the network.

## Remote Access
PC8, located outside the company's network, can access the company's PC and ASA Firewall through SSH.

## DMZ Configuration
Inside systems can communicate with servers located in the DMZ zone. However, outside networks are restricted from accessing the inside network.

## Contributing
Contributions to SecureDeptNet are welcome! To contribute, fork this repository, make your changes, and submit a pull request. Please follow the project's coding standards and guidelines.

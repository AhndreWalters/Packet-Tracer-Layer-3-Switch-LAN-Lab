# Packet Tracer Layer 3 Switch LAN Lab

## Overview
Cisco Packet Tracer lab for the Networking II course at T.A. Marryshow Community College. Demonstrates configuring a LAN using a Layer 3 switch as the default gateway with VLAN creation and SVI setup.

## Lab Objectives
- Configure Layer 3 switch as default gateway
- Create VLANs and assign ports
- Set up Switched Virtual Interfaces (SVIs)
- Test inter-VLAN connectivity

## Files Included
- `W1_L3SwitchLAN_AhndreWalters.pkt` - Cisco Packet Tracer topology file
- `W1_L3SwitchLAN_AhndreWalters Documentation.pdf` - Complete lab documentation
- `LICENSE` - MIT License file

## Network Configuration
### IP Address Table
| Device | Interface | IP Address | Subnet Mask | Gateway |
|--------|-----------|------------|-------------|---------|
| Switch1 | VLAN 10 | 192.168.10.1 | 255.255.255.0 | N/A |
| Server1 | FastEthernet0 | 192.168.10.10 | 255.255.255.0 | 192.168.10.1 |
| PC1 | FastEthernet0 | 192.168.10.11 | 255.255.255.0 | 192.168.10.1 |
| PC2 | FastEthernet0 | 192.168.10.12 | 255.255.255.0 | 192.168.10.1 |

**Note**: Server1 DNS = 127.0.0.1

## Lab Features
- VLAN 10 configuration on Layer 3 switch
- Inter-VLAN routing using SVIs
- Ping connectivity testing
- Proper gateway configuration

## Technology
- **Cisco Packet Tracer** - Network simulation
- **Layer 3 Switching** - Inter-VLAN routing
- **VLAN Configuration** - Network segmentation
- **SVI Implementation** - Switched Virtual Interfaces

## Educational Purpose
Demonstrates practical networking concepts including:
- Layer 2 vs Layer 3 switching
- VLAN creation and management
- IP addressing and subnetting
- Basic network troubleshooting

## Requirements
- Cisco Packet Tracer (version 7.0 or higher)
- Basic networking knowledge

## Usage
1. Open `W1_L3SwitchLAN_AhndreWalters.pkt` in Cisco Packet Tracer
2. Review the topology and configuration
3. Test connectivity using ping commands

## License
Educational project for networking demonstration.

<strong>[© 2026 Ahndre Walters](https://github.com/AhndreWalters/Packet-Tracer-Layer-3-Switch-LAN-Lab/blob/main/LICENSE) · Packet Tracer Layer 3 Switch LAN Lab · TAMCC Networking II Course · College Course Assignment</strong>

VLAN Segmentation:

VLAN 1 - GUESTS
- this VLAN is designed for guests using their private devices like a laptop, phone, consoles, IoT not related to Homelab.
Assumptions:
- access to the Internet (only)
- no access to Management VLAN
- no access to Active Directory

Sample configuration:
VLAN ID: 1
Network: 10.10.1.0/24
Gateway: 10.10.1.1
DHCP: 10.10.1.100-10.10.1.200

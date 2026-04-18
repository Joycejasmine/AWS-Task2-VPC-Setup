# AWS Task 2 - VPC Setup

## Architecture:
- VPC: 10.0.0.0/16
- Public Subnet: 10.0.1.0/24
- Private Subnet: 10.0.2.0/24
- Internet Gateway attached
- Route Table configured (0.0.0.0/0 → IGW)

## EC2:
- Launched in public subnet
- Security Group:
  - SSH (22) open
  - HTTP (80) open

## Verification:
- Connected using EC2 Instance Connect
- Internet verified using ping

## Screenshots:
All outputs are available in the /Screenshots folder

# Day 02 – AWS VPC & Networking

## Concepts Covered
- What is VPC
- CIDR blocks
- Public vs Private Subnets
- Internet Gateway (IGW)
- Route Tables
- Subnet associations
- Security Groups vs NACLs
- Launching EC2 inside a custom VPC

## Hands-on Work
- Created custom VPC (10.0.0.0/16)
- Created public subnet (10.0.1.0/24)
- Enabled auto-assign public IP
- Created Internet Gateway and attached to VPC
- Created Route Table with IGW route
- Associated public subnet with route table
- Launched EC2 inside custom VPC
- Installed NGINX and verified in browser

## Architecture Diagram (Text)
VPC (10.0.0.0/16)
  └── Public Subnet (10.0.1.0/24)
        └── EC2 Instance (Nginx installed)
  └── Internet Gateway (IGW)
  └── Route Table (0.0.0.0/0 → IGW)

## Screenshots
Stored inside `screenshots/`

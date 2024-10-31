# AWS VPC Setup Task

This repository contains the setup for a Virtual Private Cloud (VPC) with both public and private subnets, an internet gateway, and a Linux EC2 instance, as per the requirements of GUVI's AWS Task 2.

## Architecture Diagram

The following diagram illustrates the architecture of the VPC setup:

![Architecture Diagram](https://github.com/user-attachments/assets/ef48fc1d-f766-44d7-9a7f-30f83aeda9fd)

## Steps and Resources

1. **VPC**: Created a VPC with CIDR block `10.0.0.0/16`.
2. **Subnets**:
   - **Public Subnet**: 256 IP addresses (`10.0.1.0/24`).
   - **Private Subnet**: 256 IP addresses (`10.0.2.0/24`).
3. **Internet Gateway**: Attached to the VPC for internet connectivity.
4. **Route Table**: Configured to route traffic from the public subnet to the internet through the internet gateway.
5. **EC2 Instance**: Launched a Linux instance in the public subnet.

## Conclusion
All steps were successfully completed, and the EC2 instance is accessible via SSH.

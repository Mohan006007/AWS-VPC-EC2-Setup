# AWS VPC and EC2 Setup

This project demonstrates the setup of a Virtual Private Cloud (VPC) with an Internet Gateway, Public and Private Subnets, Route Table, and launching an EC2 instance in AWS.

## Task Description
1. Set up a VPC with an Internet Gateway.
2. Create a Public Subnet and a Private Subnet (each with 256 IP addresses).
3. Create a Route Table linking the Internet Gateway and the Public Subnet.
4. Launch a Linux EC2 instance using the created VPC and Public Subnet.

## Screenshots
- **VPC Configuration**: Shows the setup of the VPC.
- **Internet Gateway**: Configuration of the Internet Gateway.
- **Public Subnet**: Public Subnet with 256 IPs.
- **Private Subnet**: Private Subnet with 256 IPs.
- **Route Table**: Route configuration for Internet access.
- **EC2 Instance**: Launched Linux EC2 instance in the Public Subnet.
- **Server Connectivity**: SSH connection to verify the instance is reachable.

## Steps
1. Created a VPC with CIDR block `10.0.0.0/16`.
2. Set up an Internet Gateway and attached it to the VPC.
3. Configured Public and Private Subnets with CIDR blocks `10.0.1.0/24` and `10.0.2.0/24`.
4. Created a Route Table and added a route to the Internet Gateway for the Public Subnet.
5. Launched an EC2 instance in the Public Subnet and verified connectivity.

## Conclusion
All steps were successfully completed, and the EC2 instance is accessible via SSH.

## References
- [AWS VPC Documentation](https://docs.aws.amazon.com/vpc/index.html)

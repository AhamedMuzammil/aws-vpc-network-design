AWS VPC Network Design and Security Configuration

## Project Overview
This project demonstrates the design and configuration of an Amazon Virtual Private Cloud (VPC) using the AWS Management Console. It includes public and private subnets, an Internet Gateway, route tables, and security group configuration.

## Objectives
- Create a custom AWS VPC.
- Configure public and private subnets.
- Set up an Internet Gateway.
- Configure routing for public and private subnets.
- Review security group rules.

## AWS Services Used
- Amazon VPC
- Subnets
- Internet Gateway (IGW)
- Route Tables
- Security Groups

## Network Configuration
| Component | Configuration |
|---|---|
| VPC CIDR | 10.0.0.0/16 |
| Public Subnet CIDR | 10.0.1.0/24 |
| Private Subnet CIDR | 10.0.2.0/24 |
| Public Route Table | Local route and Internet Gateway route |
| Private Route Table | Local route only |

## Implementation Steps
1. Created a custom VPC.
2. Created public and private subnets.
3. Created and attached an Internet Gateway.
4. Configured the public route table with an Internet Gateway route.
5. Configured the private route table with a local route only.
6. Reviewed security group inbound and outbound rules.
7. Verified route table configurations in the AWS Console.

## Results
Successfully configured and verified the basic AWS VPC network architecture with separate public and private subnets and different routing configurations.

## Screenshots
AWS Console screenshots documenting the configuration are included in the `screenshots` folder.

## Limitations
- EC2 instances were not deployed.
- VPC Flow Logs were not enabled.
- Live network traffic monitoring and testing were not performed.

## Cost Considerations
The project was designed to avoid additional potentially chargeable resources such as EC2 instances, NAT Gateways, and VPC Flow Logs. Actual AWS costs depend on account usage and any other active resources.

## Skills Demonstrated
AWS networking fundamentals, VPC configuration, subnet design, route table configuration, Internet Gateway setup, and security group basics.

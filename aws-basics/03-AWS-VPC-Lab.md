# AWS VPC Lab

## Date

May 29, 2026

## Goal

Learn the fundamentals of Amazon VPC, create networking components, and understand how EC2 instances connect to the internet.

## AWS Services Used

- Amazon VPC
- Subnet
- Internet Gateway
- Amazon EC2

## What I Did

- Explored the default VPC configuration.
- Learned how VPCs provide isolated networking environments.
- Reviewed CIDR blocks and subnet configuration.
- Learned how Internet Gateways provide internet access.
- Completed the KodeKloud lab questions.
- Created a subnet within a VPC.
- Launched an EC2 instance.

## What I Learned

- A VPC (Virtual Private Cloud) is a secure, isolated network hosted within AWS.
- VPCs allow customers to customize networking resources.
- VPC networking components include:
    - Subnets
    - Route Tables
    - Security Groups
    - Network ACLs (NACLs)
    - Internet Gateways
- VPCs are specific to a single AWS region.
- CIDR blocks define the IP address range available within a VPC.
- Internet Gateways allow resources inside a VPC to communicate with the internet.
- Different VPCs cannot communicate unless connectivity is explicitly configured.

## Problems I Ran Into

I was initially confused about what subnet configuration was required for EC2 instances to have internet access.

### Issue Breakdown

- **Problem Encountered:** Understanding how EC2 instances gain internet connectivity.
- **Why It Happened:** I was still learning the relationship between VPCs, subnets, and public IP addresses.
- **How I Investigated It:** Reviewed the KodeKloud lab questions and AWS networking concepts.
- **How I Solved It:** Learned that the subnet must be configured to automatically assign a public IPv4 address.
- **What I Learned:** Internet access depends on proper VPC, subnet, and public IP configuration.

## Key Lab Question

### Question

What subnet configuration must be enabled for EC2 resources to have internet access?

### Answer

Auto-assign public IPv4 address.

## Screenshots

Screenshots were not captured during this lab.

This lab focused on learning AWS VPC fundamentals, including:

- VPC configuration
- Subnets
- CIDR blocks
- Internet Gateways
- Public IPv4 addressing
- EC2 internet connectivity

Future labs will include screenshots of key configuration steps and successful completion.

## Key Takeaways

- VPCs provide secure and isolated networking in AWS.
- Subnets divide a VPC into smaller network segments.
- Internet Gateways provide internet connectivity.
- CIDR blocks define available IP address ranges.
- Public IPv4 addressing is required for direct internet access.

## Skills Practiced

- AWS Networking
- Amazon VPC
- Subnet Configuration
- EC2 Networking
- Cloud Fundamentals
- Troubleshooting

## Reflection

Today I learned how AWS networking is organized through VPCs and subnets. 
The most challenging concept was understanding how EC2 instances gain internet access, but working through the lab helped me connect VPC, subnet, and public IP concepts together. 
This lab gave me a stronger understanding of AWS networking fundamentals.

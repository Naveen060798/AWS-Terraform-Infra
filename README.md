AWS Infrastructure Deployment with Terraform
This project automates the provisioning of a secure, scalable AWS environment. It includes a custom VPC, multiple public subnets for high availability, an Application Load Balancer (ALB), and S3 integration.

Architecture Overview
The infrastructure consists of the following components:

VPC: A dedicated Virtual Private Cloud (CIDR: 172.16.0.0/16).

Public Subnets: Two subnets (e.g., 172.16.1.0/24 and 172.16.2.0/24) for redundancy.

Compute: EC2 instances (represented by the stack icon) running within the public subnets.

Load Balancing: An Application Load Balancer (ALB) to distribute incoming traffic.

Networking: An Internet Gateway (IGW) to allow communication between the VPC and the internet.

Storage: An Amazon S3 bucket for persistent data storage or static assets.

# Working with Source Systems: Troubleshooting Database Connectivity on AWS

This project focuses on **troubleshooting and resolving connectivity issues** in complex AWS network environments, specifically when connecting to RDS databases from EC2 instances or local environments.

## Project Overview

The project provides a hands-on approach to diagnosing and fixing common AWS networking and security misconfigurations, including:
- **Security Group Rules**: Analyzing inbound/outbound rules preventing database access.
- **VPC & Networking**: Troubleshooting subnets, routing tables, and internet gateways.
- **SSH Connectivity**: Using Bastion hosts to gain access to private network resources.
- **Database Connection Tests**: Utilizing tools (e.g., ping, telnet, database clients) to isolate connectivity failures.

## Key Concepts Demonstrated

- **Cloud Security**: Implementing the principle of least privilege while ensuring necessary connectivity.
- **Network Diagnostics**: Identifying failures in multi-layered network architectures.
- **RDS Connectivity**: Managing network ACLs and security group ingress for PostgreSQL/MySQL.

## Repository Structure

- `sql/`: Contains diagnostic SQL queries.
- `scripts/`: Python/Shell scripts used for connectivity testing.

## Setup Instructions

1. **Prerequisites**: Access to an AWS account with VPC, RDS, and EC2 resources.
2. **Environment**: Ensure you have proper AWS CLI permissions to modify Security Groups and Network ACLs for testing.
3. **Execution**: Follow the diagnostic steps outlined in the provided scripts to isolate and fix connectivity issues.

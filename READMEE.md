# OPENTOFU-VPC

OpenTofu is an open-source Infrastructure as Code (IaC) tool used to create
and manage cloud infrastructure using code. In this project, OpenTofu is used 
to create an AWS VPC with a public subnet, Internet Gateway, and Route Table.

## How to Create

The AWS infrastructure is defined using `.tf` configuration files.
OpenTofu reads these files and creates the required AWS resources
using commands like `tofu init`, `tofu plan`, and `tofu apply`.

## Resources Created

- VPC
- Public Subnet
- Internet Gateway
- Route Table
- Route Table Association

## Benefits

- Automation of infrastructure
- Consistent infrastructure setup
- Easy version control with Git/GitHub
- Reusable configuration
- Easy resource management
- Reduces manual configuration
- Supports Infrastructure as Code (IaC)

## created by
jaweriya mahin

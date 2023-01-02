## Description

This is a Terraform Module Demo Project. In this project, we are demonstrating the usage of Terraform registry modules to create AWS instances within a VPC.

## Usage

- Execute the command `terraform init` to setup the project workspace.
- Execute the command `terraform apply` to provision the infrastructure. This will create a VPC with Private and Public Subnets, a NAT Gateway and three EC2 instances. 
- Execute the command `terraform destroy` to destroy the infrastructure.

## Note

The resources created in this example may incur cost. So please take care to destroy the infrastructure if you don't need it.
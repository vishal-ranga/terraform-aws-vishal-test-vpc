Overview
This Terraform module creates an AWS VPC with a given CIDR block. It also creates multiple subnets (public and private), and for public subnets, it sets up an Internet Gateway (IGW) and appropriate route tables.

Features
Creates a VPC with a specified CIDR block
Creates public and private subnets
Creates an Internet Gateway (IGW) for public subnets
Sets up route tables for public subnets
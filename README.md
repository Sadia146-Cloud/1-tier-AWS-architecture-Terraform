🌐 One-Tier AWS Architecture with Terraform


This repository provisions a simple one-tier AWS architecture using Terraform. It deploys an EC2 instance running Apache, inside a public subnet, behind a security group, using user-data for web server bootstrapping.

🧱 Components
AWS VPC

Public Subnet

Internet Gateway

Route Table

Security Group (allows SSH and HTTP)

EC2 Instance (Ubuntu with Apache)

Terraform Provisioning


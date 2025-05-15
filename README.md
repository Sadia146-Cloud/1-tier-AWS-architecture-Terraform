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

📁 Project Structure


.
├── main.tf          # Main infrastructure config

├── variables.tf     # Variable definitions

├── outputs.tf       # Output values

└── README.md        # Project documentation


Commands used:

1.terraform init

2.terraform plan

3.terraform apply

Access the Web Server

http://<public-ip>

You should see:

Hello from Terraform EC2

Clean up:

terraform destroy



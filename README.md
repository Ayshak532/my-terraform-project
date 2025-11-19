📘 Terraform AWS VPC Project

This project contains a simple Terraform configuration that creates basic AWS networking resources.
It is based on the YouTube tutorial used to build this project.

✅ Resources Created

VPC

Public Subnet

Internet Gateway

Route Table

Route Table Association

🗂 Project Files
main.tf   → main Terraform configuration file
README.md → project documentation

▶️ How to Run This Project

Install Terraform on your system

Configure your AWS CLI:

aws configure


Initialize Terraform:

terraform init


View the execution plan:

terraform plan


Apply the configuration:

terraform apply

📝 Notes

Make sure your AWS IAM user has correct permissions (EC2, VPC, Networking).

This is a beginner-friendly project created for learning Terraform with AWS.

You can expand this project later with variables, outputs, modules, etc.

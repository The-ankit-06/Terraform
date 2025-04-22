🌐 Terraform AWS VPC Setup

This Terraform project provisions a custom VPC in AWS, along with its essential networking components.
📦 What It Creates

    A VPC

    One or more subnets

    An Internet Gateway

    A Route Table + Route Table Associations

    A Security Group (with customizable rules)





🚀 Terraform EC2 + Apache2 Setup

This Terraform project provisions an AWS EC2 instance with Apache2 web server installed and running.
📦 What it does

    Creates a security group that allows:

        Port 22 (SSH)

        Port 80 (HTTP - Apache2)

    Launches an Ubuntu EC2 instance

    Installs and starts Apache2 using a user_data script

    Outputs the public IP to access the web server

# Provisioning a Highly Available Web-Application using Infrastructure as Code(IaC)-- Cloud Formation

## About
- In this project I set up a highly available web application situated in a private subnet behind a load balancer which can spin more instances of the web app when demand rises.

### Infrastructure Diagram
![alt text](https://github.com/belisky/iac-highly_available_webapp/blob/main/finalproj%20architecture.jpg?raw=true)

### Some Resources provisioned using cloudformation.yaml file is :
- VPC
- Subnets (Both Public and Private)
- NAT Gateway
- Internet Gateway
- Load Balancer
- Security Groups
- Route Tables
- Auto Scaling Groups
- AWS - EC2 Instances with different AZ's

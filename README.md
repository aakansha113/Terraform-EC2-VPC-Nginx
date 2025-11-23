# AWS VPC + EC2 + Nginx Deployment

This project demonstrates how to create a custom **VPC** in AWS, launch an EC2 instance, and configure Nginx as a web server.  
It’s a simple hands-on exercise to understand AWS networking and compute basics.

## 📌 Architecture

**Flow:**
1. User accesses website in browser.
2. Request goes to EC2 instance running inside a VPC.
3. Nginx on EC2 serves the webpage.

## 🚀 Prerequisites

Before starting, ensure you have:

- An **AWS Account**
- **AWS CLI** installed & configured
  
## 📥 Clone This Repository
### To clone this portfolio on your local system, run:
```
https://github.com/aakansha113/Terraform-EC2-VPC-Nginx.git
```

### STEP 1:
#### Initialize Terraform
```
terraform init
```

### STEP 2:
#### Validate and Plan:
```
terraform validate
terraform plan
```
### STEP 3:
#### Apply the configuration
```
terraform apply -auto-approve
```
### Copy the Public IP of EC2 from terminal and paste it to the browser.

### ⭐ Show Your Support
#### If you like this portfolio, feel free to ⭐ star the repo!

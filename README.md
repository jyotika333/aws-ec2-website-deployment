# AWS EC2 Website Deployment

## Project Overview
This project demonstrates the deployment of a live website on AWS EC2 using Amazon Linux 2, with a static Elastic IP, Apache web server, CloudWatch monitoring, and IAM security configuration.

## Steps Performed
1. Launch EC2 instance with Amazon Linux 2 (t2.micro)
2. Connect to EC2 via SSH using key pair
3. Install Apache web server and deploy HTML page
4. Allocate and associate Elastic IP
5. Configure Security Groups and IAM roles
6. Monitor EC2 metrics with CloudWatch

## Project Screenshots
![EC2 Instance with Elastic IP](screenshots/ec2-elastic-ip.png)
![Live Website](screenshots/live-website.png)
![IAM Security](screenshots/iam-security.png)

## Outcome
- Live website accessible via Elastic IP
- CPU and network metrics visible in CloudWatch
- Secure IAM role for EC2 monitoring


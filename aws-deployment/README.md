# AWS Deployment – CDEC StudentApp

## Project Overview

This project demonstrates the AWS cloud deployment architecture for the CDEC StudentApp.

## AWS Services

- Amazon VPC
- Public and Private Subnets
- Internet Gateway and NAT Gateway
- Amazon EC2
- Application Load Balancer
- Auto Scaling Group
- Amazon RDS (MariaDB)
- Amazon S3
- Amazon CloudFront
- Amazon Route 53
- AWS IAM and Security Groups

## Technology Stack

- Frontend: React.js and Vite
- Backend: Java and Spring Boot
- Database: MariaDB
- Cloud Platform: AWS

## Deployment Steps

1. Configure the VPC and subnets.
2. Deploy the backend application on EC2.
3. Connect the backend to Amazon RDS.
4. Configure the Application Load Balancer and health checks.
5. Host frontend files in S3.
6. Configure CloudFront and Route 53.
7. Test the application and API endpoints.

## Security

- Do not upload `.env` files containing secrets.
- Never publish AWS access keys or database passwords.
- Apply appropriate IAM permissions and security group rules.

## Author

Amruta More

GitHub: https://github.com/amruta6966

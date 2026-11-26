# AWS EC2 Project – Host a Dynamic Website

## Project Overview

This project demonstrates the deployment and hosting of a website on Amazon Web Services (AWS) using an Amazon EC2 Linux instance.

The objective is to configure a Linux-based web server, install Apache HTTP Server, deploy website files, and make the website accessible over the internet.

## Project Objectives

- Provision an Amazon EC2 instance.
- Configure and connect to a Linux server using SSH.
- Install and configure Apache HTTP Server.
- Deploy website files on the EC2 instance.
- Configure AWS Security Groups.
- Access the deployed website through the EC2 Public IP address.

## AWS Architecture

User / Web Browser  
↓  
AWS Cloud  
↓  
Amazon EC2 Instance  
↓  
Amazon Linux  
↓  
Apache HTTP Server  
↓  
Hosted Website

## Technologies Used

| Technology | Purpose |
|---|---|
| Amazon EC2 | Cloud server hosting |
| Amazon Linux | Operating system |
| Apache HTTP Server | Web server |
| Linux | Server administration |
| SSH | Remote server connection |
| AWS Security Groups | Network access control |

## Implementation Steps

1. Launched an Amazon EC2 instance.
2. Connected to the instance using SSH.
3. Updated Linux packages.
4. Installed Apache HTTP Server.
5. Started and enabled the Apache service.
6. Created and deployed website files.
7. Configured inbound Security Group rules.
8. Accessed the website using the EC2 Public IP address.

## Security Group Configuration

| Type | Port | Purpose |
|---|---|---|
| SSH | 22 | Remote server administration |
| HTTP | 80 | Website access |

## Project Screenshots

Screenshots of the EC2 instance, Apache service, Security Group configuration, website deployment, and browser output will be added here.

## Project Outcome

Successfully deployed and hosted a website using Amazon EC2 and Apache HTTP Server, gaining practical experience in AWS cloud infrastructure and Linux server administration.

## Author

**Harikaran L**

GitHub: https://github.com/harikaran-cloud


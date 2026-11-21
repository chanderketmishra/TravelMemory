# TravelMemory – AWS Deployment Project

## Project Overview
A MERN stack TravelMemory application deployed on AWS using Terraform and Ansible.

## Technologies
- React.js
- Node.js and Express.js
- MongoDB
- Nginx
- PM2
- Terraform
- Ansible

## AWS Infrastructure
- VPC: 10.0.0.0/16
- Public subnet: 10.0.1.0/24
- Private subnet: 10.0.2.0/24
- Internet Gateway
- NAT Gateway
- Public and Private EC2 instances
- Security Groups and IAM Role

## Application URL
http://13.127.168.139

## Repository Structure
- terraform/ – Infrastructure configuration
- ansible/ – Deployment playbooks
- frontend/ – React application
- backend/ – Node.js backend

## Deployment
Terraform provisions AWS infrastructure.
Ansible configures MongoDB and deploys the application.
Nginx serves the frontend and PM2 manages the backend.

## Verification
- Frontend accessible through public IP
- MongoDB connection successful
- Trips successfully fetched and saved
- Ansible playbook executed successfully
- PM2 process online

## Security
Do not commit passwords, .env files, SSH private keys or Terraform state files.

## Author
Chanderket Mishra

GitHub: https://github.com/chanderketmishra/TravelMemory

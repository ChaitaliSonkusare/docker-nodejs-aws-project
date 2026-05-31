# Dockerized 2-Tier Node.js Application on AWS


## Project Overview

This project demonstrate deployment of 2-tier Node.js web app using Docker Containerization on AWS EC2 Linux instances.The project includes Application Load Balancer (ALB), Auto Scaling Group (ASG), Docker deployment, and AWS Security Group configuration for scalability and high availability.


## Technologies Used

- AWS EC2
- Ubuntu Linux
- Docker
- Node.js
- Application Load Balancer(ALB)
- Auto Scaling Group(ASG)
- Git & GitHub

## Auto Scaling Configuration:

- Minimum Instances: 2
- Desired Instances: 2
- Maximum Instances: 4

## Load Balancer:

- Application Load Balancer (ALB)
- Listener Port: 80
- Target Group Port: 3000 

## Application Output:

2-Tier Docker App Running on AWS

## Deployment Steps:

1. Launch Ubuntu EC2 Instance
2. Install Docker on Linux
3. Create Dockerfile
4. Build Docker Image
5. Run Docker Container
6. Configure Security Groups
7. Create AMI
8. Configure Load balancer
9. Configure Auto Scaling Group

## Learning Outcomes:

- Docker containerization
- AWS EC2 deployment
- Linux server management
- Load balancing
- Auto Scaling
- GitHub project management
- Cloud infrastructure basics



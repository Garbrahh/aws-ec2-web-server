# aws-ec2-web-server
First cloud project: EC2 web server with Nginx

# AWS EC2 Web Server

## Overview
Deployed a web server using AWS EC2 and Nginx.

## Architecture
Internet → Elastic IP → EC2 → Nginx

## Technologies
- AWS EC2
- Elastic IP
- Ubuntu Linux
- Nginx

## Commands Used
sudo apt update
sudo apt install nginx -y

## Challenges & Fixes
- SSH permission denied → fixed key permissions
- Page not loading → opened port 80 in security group

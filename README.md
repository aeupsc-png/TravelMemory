# Travel Memory - AWS Deployment

## Project By
Maheshwari

## GitHub Repository
https://github.com/aeupsc-png/TravelMemory

## Live Website
https://travelmemoryb17.xyz

## Project Overview
Travel Memory is a MERN Stack application that allows users to share and manage travel experiences.

## Technologies Used

- React
- Node.js
- Express.js
- MongoDB
- Nginx
- AWS EC2
- AWS Application Load Balancer
- AWS Auto Scaling Group
- AWS Certificate Manager (ACM)
- Cloudflare

## Deployment Steps

### Backend
- Cloned the repository.
- Configured the `.env` file.
- Started the backend using PM2.
- Configured Nginx as a reverse proxy.

### Frontend
- Updated the frontend API URL.
- Built the React application.
- Served the frontend through Nginx.

### Load Balancer
- Created an Application Load Balancer.
- Created a Target Group.
- Registered EC2 instances.
- Configured health checks.

### Auto Scaling
- Created a Launch Template.
- Created an Auto Scaling Group.
- Attached the Auto Scaling Group to the Load Balancer.

### Cloudflare
- Connected the custom domain.
- Added A and CNAME DNS records.
- Configured SSL/TLS.
- Enabled HTTPS.

## Features

- EC2 Deployment
- Reverse Proxy using Nginx
- Load Balancing
- Auto Scaling
- HTTPS Enabled
- Custom Domain
- Cloudflare Integration

## Author

Maheshwari

GitHub: https://github.com/aeupsc-png

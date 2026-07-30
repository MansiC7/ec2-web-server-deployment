# AWS EC2 Web Server Deployment

## Project Overview

This project demonstrates deploying a static website on an Amazon EC2 virtual machine using Ubuntu Linux and Nginx web server.

The website was hosted on an EC2 instance and made publicly accessible using AWS networking and security configurations.

---

## Architecture
User
|
Internet
|
AWS EC2 Instance
|
Ubuntu Linux
|
Nginx Web Server
|
HTML / CSS / JavaScript Files



---

## AWS Services Used

### Amazon EC2
- Created an Ubuntu EC2 virtual machine
- Configured instance networking
- Connected using SSH

### Security Groups
- Configured inbound rules
- Allowed SSH access from my IP
- Allowed HTTP traffic for website access

### Nginx
- Installed Nginx web server
- Configured website hosting directory
- Served static website files

---

## Technologies

- AWS EC2
- Ubuntu Linux
- Nginx
- HTML
- CSS
- JavaScript
- SSH
- Git & GitHub

---

## Deployment Steps

1. Created an EC2 instance using Ubuntu Server
2. Generated and configured SSH key pair
3. Connected to the server using SSH
4. Updated Ubuntu packages
5. Installed Nginx
6. Uploaded website files to `/var/www/html`
7. Configured security group rules
8. Accessed the website using the EC2 public IP address

---

## Outcome

Successfully deployed a static website on an AWS EC2 Ubuntu server using Nginx.

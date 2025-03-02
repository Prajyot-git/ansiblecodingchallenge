
Challenge: Infrastructure Provisioning with Ansible
Problem:
You are tasked with provisioning cloud resources using Ansible to set up a basic web application
infrastructure. Your infrastructure should consist of the following components:
1. An AWS EC2 instance running a basic web server.
2. An AWS RDS MySQL database for storing application data.
Write Ansible script to provision this infrastructure.
Requirements:
Create an EC2 instance with the following specifications:
1. Instance Type: t2.micro
2. AMI: Ubuntu Server 20.04 LTS
3. Security Group: Allow incoming HTTP (port 80) and SSH (port 22) traffic.
Create an RDS MySQL instance with the following specifications:
1. Instance Class: db.t2.micro
2. Engine: MySQL
3. Allow incoming traffic on port 3306 from the EC2 instance&#39;s security group.



NOTE : I Used t3.micro db instance instead of t2.micro bcoz of AWS RDS not provide mysql db with t2.micro latest for mysql version.
      

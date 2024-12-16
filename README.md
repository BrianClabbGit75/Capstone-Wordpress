# Capstone-Wordpress Site on AWS
Capstone WordPress site on AWS


**Project**

In this project I will be enhancing the online Presence of a digital marketing agency called DigitalBoost. A WordPress based website for their clients.

<ins>Task1 a - Define IP address range for VPC</ins>

Please see following CIDR Block & Subnets

VPC CIDR block: 10.0.0.0/16

•	Public subnet 1: 10.0.0.0/24 (web servers)

•	Public subnet 2: 10.0.1.0/24 (load balancer)

•	Private subnet 1: 10.0.2.0/24 (database servers)

•	Private subnet 2: 10.0.3.0/24 (additional resources)

<ins>Task1 b - Create a VPC with public and private Subnet</ins>

Please see VPC in AWS Console

![Screenshot 1](images/screenshot1.png)


...additionally see created Public & Private Subnets

![Screenshot 1](images/screenshot2.png)

<ins>Task1 c - Configure route tables for each subnet </ins>

Now that the VPC and Subnets are created, I create Route Tables for both Public and Private subnets - please see route table:
![Screenshot 1](images/screenshot3.png)


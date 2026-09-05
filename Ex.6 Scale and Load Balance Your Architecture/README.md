# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture
Author :KISHORE KUMAR B   
Reg no : 212225240073
yours   Date : 05-09-26

---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)
1.Created a launch template with the required EC2 instance configuration, AMI, instance type, and security group.

2.Created an Auto Scaling Group and configured the minimum, maximum, and desired number of EC2 instances.

3.Created an Application Load Balancer with a target group and attached the Auto Scaling Group to distribute incoming traffic.

4.Configured CloudWatch-based scaling policies and tested load balancing and automatic scaling by generating traffic.

## Output Screenshots 
<img width="1920" height="1200" alt="EX6 1" src="https://github.com/user-attachments/assets/bd8b575e-a691-48b4-b1ad-ffcc7093d050" />
<img width="1920" height="1200" alt="EX6 2" src="https://github.com/user-attachments/assets/87e8c2da-b317-4cdd-a138-061e7af21c10" />
<img width="1920" height="1200" alt="EX6 3" src="https://github.com/user-attachments/assets/3c306a5a-b048-413a-8ab7-3a9d6cc0aae7" />
<img width="1920" height="1200" alt="EX6 4" src="https://github.com/user-attachments/assets/1bb4b210-e412-457d-a8ea-1e05681538f5" />
<img width="1920" height="1200" alt="EX6 5" src="https://github.com/user-attachments/assets/4393c536-ef59-48c6-bcf0-aba0c45f4fac" />



---


## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.

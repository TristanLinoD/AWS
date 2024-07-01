## Assigning Static IPs to NLBs with ALB Target Groups

### Hands-on Lab

We are going to deploy an internet-facing Network Load Balancer (NLB) with a static Elastic IP Address (EIP) assigned to it. The NLB will then front a private Application Load Balancer (ALB) as a Target Group, and the ALB will be fronting an Auto Scaling Group of internal web servers.

This allows you to statically reference the internet-facing NLB while still leveraging the ALB and its capabilities!

### Objectives

- Create Target Group
- Create Elastic IP Addresses (EIPs)
- Create Network Load Balancer and Listener

### Architecture
![alt text](https://github.com/TristanLinoD/AWS/blob/main/StaticIPtoNLBwithALB/Architectures/StaticIPtoNLBwithALB.png)

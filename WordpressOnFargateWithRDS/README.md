## Hosting a Wordpress Application on ECS Fargate with RDS, Parameter Store, and Secrets Manager

### Hands-on Lab

We will to deploy a WordPress application using several AWS services, including: Amazon RDS, AWS Systems Manager, Parameter Store, Amazon ECS, Amazon ECR, and Application Load Balancers.

### Objectives

- Create the Amazon RDS Instance
- Create the Parameter Store Parameters and Verify Secrets Manager Secret
- Create the Private ECR Repository
- Create the Amazon ECS Task Definition
- Create the Amazon ECS Cluster
- Verify Resources and Create Database Subnet Group
- Update the RDS Security Group Rules
- Create IAM User Access Keys
- Push Image to ECR Repo from Cloud9
- Configure AWS Cloud9
- Create the Amazon ECS Service
- Test the Application

### Architecture
![alt text](https://github.com/TristanLinoD/AWS/blob/main/WordpressOnFargateWithRDS/Architectures/WordpressOnFargateWithRDS.png)

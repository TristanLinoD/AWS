## Using Secrets Manager to Authenticate with an RDS Database Using Lambda

### Hands-on Lab

AWS Secrets Manager helps you protect secrets needed to access your applications, services, and IT resources. The service enables you to easily rotate, manage, and retrieve database credentials, API keys, and other secrets throughout their lifecycle. We are goign to connect to a MySQL RDS database from an AWS Lambda function using a username and password, and then we hand over credential management to the AWS Secrets Manager service. We then use the Secrets Manager API to connect to the database instead of hard-coding credentials in our Lambda function.

### Objectives

- Create a Lambda Function
- Create the MySQL Layer, and Copy Your Code to the Lambda Function
- Create a Secret in Secrets Manager
- Test Connectivity from Lambda to RDS Using Credentials from AWS Secrets Manager
- Create Table in the RDS Database Using Lambda to Check Connectivity
- Modify the Lambda IAM Role


### Architecture
![alt text](https://github.com/TristanLinoD/AWS/blob/main/SecretManagerWithRDS/Architectures/SecretManagerWithRDS.png)

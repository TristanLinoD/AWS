## Standing Up an Apache Web Server EC2 Instance and Sending Logs to Amazon CloudWatch

### Hands-on Lab

During this hands-on lab project, we are going to work on configuring an Amazon EC2 instance to push some custom log files to Amazon CloudWatch using the CloudWatch agent. Once the log files are correctly configured to be sent to Amazon CloudWatch, we will then implement a simple alerting system to catch some specific warnings and error messages using Metric Filters and Amazon SNS notifications.

### Objectives

- Install and Configure the Amazon CloudWatch Agent
- Create a Metric Filter for 404 Status Codes
- Create SNS Topic and CloudWatch Alarm

### Architecture
![alt text](https://github.com/TristanLinoD/AWS/blob/main/CloudTrailAndEventBridgeAlertConsoleSign-Ins/Architectures/StandingUpAnApacheWebServer.png)

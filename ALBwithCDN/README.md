## Using an ALB behind Amazon CloudFront and Using a Custom HTTP Header to Control Access

### Hands-on Lab

We will work on implementing a more secure web application architecture by leveraging the following AWS services to further restrict public access: Amazon CloudFront, Application Load Balancer (ALB), and Amazon EC2.

We will work with the above services in order to implement a new CDN in front of an internet-facing ALB to improve performance. You will also leverage the ability to pass custom headers to the origin server (the ALB) to restrict access to the hosted web application. The ALB will only allow traffic that contains the secret HTTP header value, which allows you to drop all traffic that is sent directly to the ALB itself.


### Objectives

- Create the CloudFront Distribution
- Update the CloudFront Distribution to Contain the HTTP Header
- Update the ALB Listener Rules

### Architecture
![alt text](https://github.com/TristanLinoD/AWS/blob/main/ALBwithCDN/Architectures/ALBwithCDN.png)

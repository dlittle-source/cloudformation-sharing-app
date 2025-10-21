**Project: This project demonstrates the automation of a website deployment using AWS CloudFormation**

**Overview:** This project demonstrates the deployment of a dynamic recipe-sharing application using an AWS CloudFormation template. 

1. **AWS CloudFormation:** 
   - Used Infrastructure as Code (IaC) with YAML templates to automate and manage AWS resource deployment.

2. **Amazon S3** 
   - Created an S3 bucket to securely store and manage application files.

3. **Route 53:** 
   - Registered a custom domain name and configured DNS records for routing traffic.

4. **CloudFront:**
   - Implemented a content delivery network (CDN) to distribute web content efficiently to end users worldwide.

5. **AWS Certificate Manager (ACM):**
   - Secured application communications with SSL/TLS certificates.

6. **Application Load Balancer (ALB):**
   - Configured an ALB and target group to evenly distribute web traffic across an Auto Scaling Group of EC2 instances in multiple Availability Zones.

7. **Web Servers (EC2 Instances):**
   - Provisioned EC2 instances within private subnets to enhance security and host the web application.

8. **Security Groups:**
   - Defined Security Groups to act as virtual firewalls controlling inbound and outbound traffic to EC2 instances.

9. **Virtual Private Cloud (VPC):**
   - Set up a VPC with public and private subnets across two Availability Zones for improved reliability, scalability, and fault tolerance.

10. **Amazon DynamoDB:**
   - Implemented a NoSQL database to store recipes as single document-based items for high performance and flexibility.

# aws-highly-available-webserver

Overview

This project demonstrates how I designed and deployed a resilient, secure, and cost-efficient web server environment on AWS.
It helped me strengthen my hands-on cloud engineering skills and deepen my understanding of AWS architecture design.

Architecture Summary

EC2 web server running Apache with a custom HTML landing page

EBS for persistent storage and EFS for shared storage between instances

Custom AMIs and automated snapshots for recovery and consistency

Placement Groups for network performance optimization

Elastic IP for consistent public access

IAM roles, encryption, and tight security groups for a secure setup

Auto Scaling and Spot Instances for cost optimization

Outcome

=> Highly available
=> Secure
=> Scalable
=> Cost-optimized

Future Improvements

Add a Load Balancer and Multi-AZ setup

Integrate Route53 and CloudFront for better availability

Automate deployment using Terraform or CloudFormation

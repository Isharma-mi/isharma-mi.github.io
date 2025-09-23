---
title: "Portfolio"
author_profile: true
classes: wide
layout: single
permalink: /portfolio/
---

The following GitHub repositories showcase projects representing my professional skills and experiences.

## [S3 Event Driven Pipeline](https://github.com/Isharma-mi/s3-event-driven-pipeline){:target="_blank"}
*Description*: A Terraform project where an EventBridge rule monitors an S3 bucket for object creation events to push data into a DynamoDB table and publish to a SNS topic.

*Tech Stack*:
- AWS: CloudWatch, DynamoDB, EC2, IAM, Lambda, S3, SNS
- Python: boto3 library to perform actions with DDB and SNS-related API
- Terraform (HCL): Infrastructure as Code to automate AWS deployments with modularization


## [AWS Terraform EC2 CW Agent Project](https://github.com/Isharma-mi/aws-terra-ec2-cw-agent){:target="_blank"}
*Description*: A Terraform project provisioning an AWS EC2 instance with the CloudWatch Agent automatically installed and configured to push custom metrics in a dedicated namespace. 

*Tech Stack*:
- AWS: EC2, IAM, CloudWatch
- Bash: Utilize user data for setting up instance on startup
- JSON: Configure the CloudWatch Agent with a custom infrastructure.json
- Terraform (HCL): Infrastructure as Code to automate AWS deployments with modularization
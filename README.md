Project Overview

This project automatically processes images when they are uploaded to an S3 bucket.

Workflow:

Plain Text
1
User Upload
2
↓
3
S3 Input Bucket
4
↓
5
S3 Event Trigger
6
↓
7
AWS Lambda
8
↓
9
Image Processing
10
↓
11
S3 Output Bucket
12
↓
13
CloudWatch Monitoring
Show more lines
🔧 AWS Services Used
Amazon S3
AWS Lambda
IAM Roles & Policies
Amazon CloudWatch
💡 What I Learned

✅ Event-driven architecture

✅ Serverless computing with AWS Lambda

✅ Configuring S3 triggers

✅ IAM permission management

✅ Monitoring and troubleshooting using CloudWatch Logs

✅ Debugging deployment and dependency issues

🎯 Challenges Faced

Throughout the project, I encountered and resolved several real-world issues:

Lambda deployment package errors
Python syntax and indentation issues
IAM permission configuration
Image processing library compatibility
CloudWatch log analysis and troubleshooting

These challenges provided valuable experience in diagnosing and fixing cloud application issues.

✅ Outcome

Successfully built a serverless workflow where:

Images uploaded to S3 automatically trigger Lambda
Processed files are stored in a separate S3 bucket
Application activity is monitored through CloudWatch logs# AWS-Serverless-Image-Processing-Pipeline
AWS Serverless Image Processing Pipeline Built my first end-to-end serverless application on AWS using Amazon S3, AWS Lambda, IAM, and CloudWatch.

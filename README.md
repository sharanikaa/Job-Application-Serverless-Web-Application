# Job Application Serverless Web Application

## Overview
This project is a serverless web application for job applications built using AWS cloud services. 
Applicants can submit their details and upload resumes, and recruiters can view applications and access resumes through a web portal.

## Technologies Used
- HTML
- CSS
- JavaScript
- AWS S3
- AWS Lambda (Python)
- API Gateway
- DynamoDB

## Features
- Job application form submission
- Resume upload and storage in S3
- Application data stored in DynamoDB
- Recruiter portal to view applications
- Serverless architecture
- Scalable and cost-efficient system

## Architecture
The frontend is hosted on Amazon S3 static website hosting.  
API Gateway connects the frontend to AWS Lambda functions.  
Lambda functions process the requests and store application data in DynamoDB and resumes in S3.

## Deployment Steps
1. Create an S3 bucket for static website hosting
2. Upload frontend files to S3
3. Create DynamoDB table for application data
4. Create S3 bucket for resume storage
5. Create Lambda functions (Python)
6. Create API Gateway endpoints and connect to Lambda
7. Enable CORS in API Gateway
8. Update API endpoints in frontend JavaScript
   
## Architecture Diagram
![Architecture Diagram](Desktop/architecture.png)

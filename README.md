AWS S3 Static Website Hosting
This project demonstrates how to deploy a public-facing website on Amazon S3 and manage secure content delivery using Bucket Policies.

🛠️ Implementation Details
Service: Amazon S3 (Simple Storage Service)

Hosting: Static Website Hosting enabled.

Security: Configured Bucket Policies to allow public s3:GetObject access.

Bucket Name: public-facing-websit-wwmk

📄 Bucket Policy
JSON:
{
    "Version": "2012-10-17",
    "Statement": [
        { 
          "Sid": "PublicReadGetObject",
          "Effect": "Allow",
          "Principal":"*"
          "Action": "s3:GetObject",
          "Resource":"arn:aws:s3:::public-facing-websit-wwmk/*"
        }
      ]

  }

Proof of Deployment
Note: Resources deleted post-deployment to manage costs.

1. Hosting Setup

2. Access Policy

3. Live Site

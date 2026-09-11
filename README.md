# MediaHub – Serverless Contact Workflow

A production-style serverless contact form workflow built on AWS, designed to demonstrate practical **Cloud Support, troubleshooting, monitoring, IAM, and incident-resolution skills**.

The project processes customer contact submissions through API Gateway and Lambda, stores the data in DynamoDB, and sends email notifications through SNS.

---

## Architecture

```text
Customer
   │
   V
API Gateway
   │
   V
AWS Lambda
   |_______________-> DynamoDB
   │                │
   │                |_____-> Contact Submission
   │
   |_______________-> SNS
                    │
                    |-> Email Notification

CloudWatch Logs
        ^
        │
      Lambda

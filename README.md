# MediaHub – Serverless Contact Workflow

A hands-on AWS serverless project demonstrating **API development, cloud integration, troubleshooting, and incident resolution**.

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

```


## AWS Services

* AWS Lambda
* Amazon API Gateway
* Amazon DynamoDB
* Amazon SNS
* IAM
* CloudWatch

## What I Implemented

* Built a serverless contact submission workflow
* Stored contact requests in DynamoDB
* Configured SNS email notifications
* Connected services using IAM permissions
* Tested the API using Postman
* Validated successful data storage and email delivery

## Cloud Support Troubleshooting

Investigated and resolved realistic application incidents:

| Incident                    | Troubleshooting Focus    |
| --------------------------- | ------------------------ |
| IAM AccessDenied            | IAM / Permissions        |
| Invalid SNS Topic ARN       | Configuration / API      |
| Invalid DynamoDB Table Name | Configuration / Database |
| Invalid Request Payload     | API / Input Validation   |

## Support Workflow

**Customer Issue -> Investigation -> Root Cause -> Fix -> Validation**

## Key Skills Demonstrated

**AWS, Lambda, API Gateway, DynamoDB, SNS, IAM, CloudWatch, API Troubleshooting, Configuration Troubleshooting, Log Analysis , Incident Resolution**

## Project Outcome

Built and validated a serverless application while demonstrating the ability to **troubleshoot AWS service integrations, resolve configuration and permission issues, and verify end-to-end recovery**.

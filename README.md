# Export CloudWatch Logs to S3 Bucket using Lambda Function and CloudWatch Role

## Project Overview
This AWS project demonstrates how to export CloudWatch logs to an Amazon S3 bucket using an AWS Lambda function and IAM/CloudWatch role permissions.

The Lambda function reads logs from CloudWatch and stores them into an S3 bucket automatically.

---

## AWS Services Used
- AWS Lambda
- Amazon CloudWatch Logs
- Amazon S3
- AWS IAM Role



## Project Workflow

1. CloudWatch generates logs.
2. Lambda function is triggered.
3. Lambda reads CloudWatch logs.
4. IAM Role provides permissions.
5. Logs are exported to S3 bucket.

---

## Files Included

| File Name | Description |
|---|---|
| lambda_function.py | Lambda function code |
| s3bucketpolicy.json | S3 bucket policy |
| architecture.png | Project architecture diagram |
| screenshots/ | Project screenshots |

---

## Screenshots

### Lambda Function
![Lambda](screenshots/1-lambda-function.png)

### CloudWatch Log Group
![CloudWatch](screenshots/2-cloudwatch-log-group.png)

### S3 Bucket
![S3](screenshots/3-s3-bucket.png)

### IAM Role Permissions
![IAM](screenshots/4-iam-role.png)

### Exported Logs in S3
![Logs](screenshots/5-exported-logs-in-s3.png)

---

## Lambda Function Features
- Reads CloudWatch logs
- Exports logs to S3
- Uses IAM role permissions
- Automated serverless workflow

---

## Outcome
Successfully exported CloudWatch logs into an Amazon S3 bucket using AWS Lambda and IAM Role permissions.

---

## Author
Kedarling Ashok Kanade

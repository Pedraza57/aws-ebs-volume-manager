
# AWS EBS Volume Manager ☁️

**Overview**:

The AWS EBS Volume Manager is a simple project designed to automate the management of Amazon Elastic Block Store (EBS) volumes in the AWS cloud. This project utilizes AWS services such as CloudWatch and Lambda to trigger actions when a new EBS volume is created.

## Features

1. **Automated Volume Type Upgrade**:
- When a new EBS volume is created, CloudWatch triggers a Lambda function.
- The Lambda function checks if the EBS volume is of type GP2.
- If the volume is GP2, the Lambda function automatically modifies it to GP3.
- Cross platform

2. **Serverless Architecture**: 
- The project leverages AWS Lambda for serverless execution, ensuring cost-effectiveness and scalability.

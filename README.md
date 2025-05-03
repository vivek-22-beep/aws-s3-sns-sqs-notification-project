# AWS Notification Project (S3 + SNS + SQS)

## 🎯 Objective
To demonstrate how AWS services like **S3**, **SNS**, and **SQS** can work together to send notifications when a file is uploaded to a bucket.

## 📌 Scope
This project simulates an event-driven architecture where:
- A file is uploaded to an S3 bucket
- The event triggers an SNS topic
- The SNS sends a message to an SQS queue

## 🧰 AWS Services Used
- Amazon S3
- Amazon SNS
- Amazon SQS
- IAM Roles/Policies

## 📸 Screenshots
Refer to the attached PowerPoint (`Project 1-Configuring S3 Event Notifications with SNS.pptx`) for architecture diagrams and working steps.

## 📂 Files Included
- `Project 1-Configuring S3 Event Notifications with SNS.pptx`: Full explanation of the project with screenshots

## 🚀 Future Scope
- Add AWS Lambda to auto-process files
- Store logs in CloudWatch
- Trigger email or SMS using Amazon SES

---


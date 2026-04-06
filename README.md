S3-to-DynamoDB-via-Lambda 

This project demonstrates an event-driven architecture using AWS Lambda to automate data entry. When a file is 
uploaded to an Amazon S3 bucket,a Lambda function is triggered to extract the object's metadata (Name, Key, and Size) 
and store it in an Amazon DynamoDB table.

**🚀 Features

Automated Workflow: Real-time data processing upon S3 uploads.

Serverless Architecture: Built entirely on AWS managed services.

Metadata Tracking: Captures bucket name, file key, and object size.

🛠️ Tech Stack

Language: Python 3.x

AWS Services: Lambda, S3, DynamoDB, IAM

SDK: Boto3 (AWS SDK for Python)

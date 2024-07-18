# Welcome to Cloud Project!

This Project is to learn cloud computing. With 3 repos ; web applications, infrastructure automation, and serverless architectures, leveraging cutting-edge technologies to enhance efficiency and scalability.

## Repositories

### 🌐 WebApp
This repository hosts a Node.js-based Product Management System that facilitates product creation, update, and deletion with robust user authentication and data handling.
- **Technologies Used**: Node.js, Express, Sequelize, AWS SDK.
- **Features**:
  - RESTful API endpoints for product and account management.
  - Integration with AWS SNS for product updates.
  - Comprehensive logging with Winston.

### 🏗️ Infrastructure
Our Infrastructure repository contains CloudFormation templates for setting up AWS resources, making it seamless to deploy and manage cloud environments with high reliability.
- **Components**:
  - VPCs, Subnets, Internet Gateways.
  - EC2 instances, Security Groups.
  - Automated resource deployment scripts.
- **Quick Start**:
  ```bash
  aws cloudformation create-stack --stack-name your-stack-name --template-body file://template.yml --parameters ParameterKey=ParamName,ParameterValue=Value

### ⚡ Serverless

Our Serverless repository is dedicated to harnessing the power of serverless architecture to build scalable, efficient, and cost-effective applications using AWS Lambda and related AWS services.

#### Key Features:
- **Lambda Functions**: Efficient execution of backend processes.
- **Event-Driven Architecture**: Responsive to cloud events, integrating seamlessly with S3, DynamoDB, and API Gateway.
- **Cost Optimization**: Reduced operational costs due to on-demand resource utilization.

#### Technologies Used:
- AWS Lambda, AWS API Gateway
- Amazon S3, Amazon DynamoDB
- AWS CloudWatch for logging and monitoring

#### Example Usage:
- Deploy a Lambda function:
  ```bash
  aws lambda create-function --function-name myFunction \
  --zip-file fileb://function.zip --handler index.handler --runtime nodejs12.x \
  --role arn:aws:iam::123456789012:role/lambda-ex


# AWS Certified Solutions Architect - Professional SAP-C02

## AWS Organizations
 - Service Control Policies (SCP)
    - SCPs are used to manage permissions in AWS Organizations

- Account Factory for terraform 
    - **To enable the Enterprise Support option, set the following feature flag to True** in your AFT deployment input configuration.
        - *`aft_feature_enterprise_support=true`*

 - Service Control Policies:
    - Service Control Policies (SCPs) are a type of policy that can be used to manage permissions across multiple AWS accounts in an organization.
    - Choose SCP if you want to apply some permissions at at the account level
    - Attach at the AWS account level from the Organization account, can have ALLOW/DENY permissions

## AWS IAM
 - IAM permission boundaries : provide maximum permission a role can have , does not have DENY option

## Lambda
 - Reserved concurrency Vs Provisioned Concurrency ?

    | Feature               | Reserved Concurrency  | Provisioned Concurrency |
    |-----------------------|-----------------------|-------------------------|
    | Description           | Allows setting a concurrency limit for a specific function, ensuring that the specified number of invocations will run concurrently. | Pre-warms a specified number of instances of a function to handle traffic immediately, without cold starts. |
    |     Invocation        | Ensures that only the specified number of invocations of that function can run concurrently, regardless of the overall concurrency limits for the account. | Ensures consistent performance and low latency for functions that require it. |
    |    Use Case        | Useful for controlling the resource usage and performance of critical functions. | Helpful for applications with sudden or high spikes in traffic. |


 - **Lambda function concurrency limit** : This is the overall limit on the number of concurrent executions across all functions in your account. By default, this limit is 1000, but it can be increased by contacting AWS Support.


## Amazon DynamoDB
 - DynamoDB global table, will replicate the DynamoDB data across multiple Regions, ensuring fast, local access to data.

## Amazon SQS 
 - *`ApproximateAgeOfOldestMessage`*
 - *`NumberOfMessagesSent`*

## AWS DevOps

## CodeCommit


## CodeBuild
 - `buildspec.yml` file is used to define **build commands and related settings**


## CodeDeploy


## CodePipeline



## AWS Elastic Beanstalk
 - Blue/Green deployments


## Amazon EvenBridge

## Amazon Systems Manager

## Encryption 

## AWS Config
 - AWS Config can be used to meet your organization compliance requirements like resource tagging etc etc
 - Use managed rules where ever applicable
 - AWS Config allows you to develop custom rules using AWS Lambda. 
    - Example: You can create a custom rule that checks the last rotation date of each AWS KMS key and publishes a message to an Amazon SNS topic if a key has not been rotated in the last 90 days
 - AWS Config **`conformance packs`** are designed to **manage a set of AWS Config rules and remediation actions in a standardized way across multiple accounts**

## AWS Trusted Advisor
 - Check AWS Service limits

## AWS GuardDuty
 - Amazon GuardDuty is a **threat detection service** that **continuously monitors for malicious activity and unauthorized behavior**
 - malicious activity
    - compromised EC2 instances
    - suspicious network activity, port scanning
    - unusual API activity in AWS accounts

## Amazon Inspector 
 - Amazon Inspector is a **security assessment service** that helps **identify vulnerabilities in EC2 instances.** 
 - By using Amazon Inspector, the company can be **notified of new vulnerabilities**
 - helps improve the security and compliance of **applications deployed on EC2**


## AWS WAF

## AWS FireWall Manager
 - AWS Firewall Manager allows you to **centrally configure and manage AWS WAF rules across your accounts and applications in AWS Organizations**.

## AWS Service Catalog
 - create approved CloudFormation templates.

## NAT Gateway
 - **NAT gateways CANNOT span multiple Availability Zones**. 
 - **Each NAT gateway is created in a specific Availability Zone** and implemented with redundancy in that zone.

## CloudFront
 - Add a custom error response by configuring a CloudFront custom error page


 ## Analytics
- Amazon Athena
- AWS Data Exchange
- AWS Data Pipeline
- Amazon EMR
- AWS Glue
- Amazon Kinesis Data Analytics
- Amazon Kinesis Data Firehose
- Amazon Kinesis Data Streams
- AWS Lake Formation
- Amazon Managed Streaming for Apache Kafka (Amazon MSK)
- Amazon OpenSearch Service
- Amazon QuickSight

## Application Integration
- Amazon AppFlow
- AWS AppSync
- Amazon EventBridge
- Amazon MQ
- Amazon Simple Notification Service (Amazon SNS)
- Amazon Simple Queue Service (Amazon SQS)
- AWS Step Functions

## Blockchain
- Amazon Managed Blockchain

## Business Applications
- Alexa for Business
- Amazon Simple Email Service (Amazon SES)

## Cloud Financial Management
- AWS Budgets
- AWS Cost and Usage Report
- AWS Cost Explorer
- Savings Plans

## Compute
- AWS App Runner
- AWS Auto Scaling
- AWS Batch
- Amazon EC2
- Amazon EC2 Auto Scaling
- AWS Elastic Beanstalk
- AWS Fargate
- AWS Lambda
- Amazon Lightsail
- AWS Outposts
- AWS Wavelength

## Containers
- Amazon Elastic Container Registry (Amazon ECR)
- Amazon Elastic Container Service (Amazon ECS)
- Amazon ECS Anywhere
- Amazon Elastic Kubernetes Service (Amazon EKS)
- Amazon EKS Anywhere
- Amazon EKS Distro

## Database
- Amazon Aurora
- Amazon Aurora Serverless
- Amazon DocumentDB (with MongoDB compatibility)
- Amazon DynamoDB
- Amazon ElastiCache
- Amazon Keyspaces (for Apache Cassandra)
- Amazon Neptune
- Amazon RDS
- Amazon Redshift
- Amazon Timestream

## Developer Tools
- AWS Cloud9
- AWS CodeArtifact
- AWS CodeBuild
- AWS CodeCommit
- AWS CodeDeploy
- Amazon CodeGuru
- AWS CodePipeline
- AWS CodeStar
- AWS X-Ray

## End User Computing
- Amazon AppStream 2.0
- Amazon WorkSpaces

## Frontend Web and Mobile
- AWS Amplify
- Amazon API Gateway
- AWS Device Farm
- Amazon Pinpoint

## Internet of Things (IoT)
- AWS IoT Analytics
- AWS IoT Core
- AWS IoT Device Defender
- AWS IoT Device Management
- AWS IoT Events
- AWS IoT Greengrass
- AWS IoT SiteWise
- AWS IoT Things Graph
- AWS IoT 1-Click

## Machine Learning
- Amazon Comprehend
- Amazon Forecast
- Amazon Fraud Detector
- Amazon Kendra
- Amazon Lex
- Amazon Personalize
- Amazon Polly
- Amazon Rekognition
- Amazon SageMaker
- Amazon Textract
- Amazon Transcribe
- Amazon Translate

## Management and Governance
- AWS CLI
- AWS CloudFormation
- AWS CloudTrail
- Amazon CloudWatch
- Amazon CloudWatch Logs
- AWS Compute Optimizer
- AWS Config
- AWS Control Tower
- AWS Health Dashboard
- AWS License Manager
- Amazon Managed Grafana
- Amazon Managed Service for Prometheus
- AWS Management Console
- AWS Organizations
- AWS Proton
- AWS Service Catalog
- Service Quotas
- AWS Systems Manager
- AWS Trusted Advisor
- AWS Well-Architected Tool

## Media Services
- Amazon Elastic Transcoder
- Amazon Kinesis Video Streams

## Migration and Transfer
- AWS Application Discovery Service
- AWS Application Migration Service
- AWS Database Migration Service (AWS DMS)
- AWS DataSync
- AWS Migration Hub
- AWS Schema Conversion Tool (AWS SCT)
- AWS Snow Family
- AWS Transfer Family

## Networking and Content Delivery
- Amazon CloudFront
- AWS Direct Connect
- Elastic Load Balancing (ELB)
- AWS Global Accelerator
- AWS PrivateLink
- Amazon Route 53
- AWS Transit Gateway
- Amazon VPC
- AWS VPN

## Security, Identity, and Compliance
- AWS Artifact
- AWS Audit Manager
- AWS Certificate Manager (ACM)
- AWS CloudHSM
- Amazon Cognito
- Amazon Detective
- AWS Directory Service
- AWS Firewall Manager
- Amazon GuardDuty
- AWS IAM Identity Center (AWS Single Sign-On)
- AWS Identity and Access Management (IAM)
- Amazon Inspector
- AWS Key Management Service (AWS KMS)
- Amazon Macie
- AWS Network Firewall
- AWS Resource Access Manager (AWS RAM)
- AWS Secrets Manager
- AWS Security Hub
- AWS Security Token Service (AWS STS)
- AWS Shield
- AWS WAF

## Storage
- AWS Backup
- Amazon Elastic Block Store (Amazon EBS)
- AWS Elastic Disaster Recovery
- Amazon Elastic File System (Amazon EFS)
- Amazon FSx (for all types)
- Amazon S3
- Amazon S3 Glacier
- AWS Storage Gateway
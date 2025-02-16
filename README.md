## Analytics
- ### Amazon Athena
- ### AWS Data Exchange
- ### AWS Data Pipeline
- ### Amazon EMR
- ### AWS Glue
    - Convert to JSON transformation support
    - Highly scalable
    - AWS Glue is serverless and automatically scales
    - Native support for data masking
    - Maintains data encryption throughout process
- ### Amazon Kinesis Data Analytics
- ### Amazon Kinesis Data Firehose
    - fully managed service, minimal operational overhead
- ### Amazon Kinesis Data Streams
    - more management than Kinesis Data Firehose
    - 
- ### AWS Lake Formation
- ### Amazon Managed Streaming for Apache Kafka (Amazon MSK)
- ### Amazon OpenSearch (ElasticSearch) Service
    -  Support for **semi-structured JSON data** and dynamic schemas

- ### Amazon QuickSight

## Application Integration
- ### Amazon AppFlow
- ### AWS AppSync
- ### Amazon EventBridge
- ### Amazon MQ
- ### Amazon Simple Notification Service (Amazon SNS)
- ### Amazon Simple Queue Service (Amazon SQS)
- ### AWS Step Functions

## Blockchain
- ### Amazon Managed Blockchain

## Business Applications
- ### Alexa for Business
- ### Amazon Simple Email Service (Amazon SES)

## Cloud Financial Management
- ### AWS Budgets
- ### AWS Cost and Usage Report
- ### AWS Cost Explorer
- ### Savings Plans

## Compute
- ### AWS App Runner
- ### AWS Auto Scaling
- ### AWS Batch
- ### Amazon EC2
- ### Amazon EC2 Auto Scaling
- ### AWS Elastic Beanstalk
- ### AWS Fargate
- ### AWS Lambda
    - **Lambda function aliases** allow you to **create a pointer to a specific function version**. 
        - The **alias can then be used by the client application instead of a specific function version ARN**. When a new version is ready, you can update the alias to point to the new version without changing the client application, minimizing disruptions to users.  
        - This approach reduces operational overhead by decoupling the client application from specific function versions.
- ### AWS Outposts
- ### Amazon Lightsail
- ### AWS Outposts
- ### AWS Wavelength

## Containers
- ### Amazon Elastic Container Registry (Amazon ECR)
- ### Amazon Elastic Container Service (Amazon ECS)
- ### Amazon ECS Anywhere
- ### Amazon Elastic Kubernetes Service (Amazon EKS)
- ### Amazon EKS Anywhere
- ### Amazon EKS Distro

## Database
- ### Amazon Aurora
- ### Amazon Aurora Serverless
- ### Amazon DocumentDB (with MongoDB compatibility)
- ### Amazon DynamoDB
    - **DynamoDB Accelerator (DAX**) is a **fully managed, highly available in-memory cache** for DynamoDB that significantly reduces read latency from milliseconds to microseconds
- ### Amazon ElastiCache
- ### Amazon Keyspaces (for Apache Cassandra)
- ### Amazon Neptune
    - graph database
- ### Amazon RDS
- ### Amazon Redshift
- ### Amazon Timestream

## Developer Tools
- ### AWS Cloud9
- ### AWS CodeArtifact
- ### AWS CodeBuild
- ### AWS CodeCommit
- ### AWS CodeDeploy
- ### Amazon CodeGuru
- ### AWS CodePipeline
- ### AWS CodeStar
- ### AWS X-Ray

## End User Computing
- ### Amazon AppStream 2.0
- ### Amazon WorkSpaces

## Frontend Web and Mobile
- ### AWS Amplify
- ### Amazon API Gateway
- ### AWS Device Farm
- ### Amazon Pinpoint

## Internet of Things (IoT)
- ### AWS IoT Analytics
- ### AWS IoT Core
- ### AWS IoT Device Defender
- ### AWS IoT Device Management
- ### AWS IoT Events
- ### AWS IoT Greengrass
- ### AWS IoT SiteWise
- ### AWS IoT Things Graph
- ### AWS IoT 1-Click

## Machine Learning
- ### Amazon Comprehend
- ### Amazon Forecast
- ### Amazon Fraud Detector
- ### Amazon Kendra
- ### Amazon Lex
- ### Amazon Personalize
- ### Amazon Polly
- ### Amazon Rekognition
- ### Amazon SageMaker
- ### Amazon Textract
- ### Amazon Transcribe
- ### Amazon Translate

## Management and Governance
- ### AWS CLI
- ### AWS CloudFormation
- ### AWS CloudTrail
- ### Amazon CloudWatch
- ### Amazon CloudWatch Logs
- ### AWS Compute Optimizer
- ### AWS Config
    - Can identify resources missing tags
    - Can be used to meet compliance requirements
    - Config aggregator
        - Can be used to aggregate config data from multiple accounts
        - Provides organization-wide view
- ### AWS Control Tower
- ### AWS Health Dashboard
- ### AWS License Manager
- ### Amazon Managed Grafana
- ### Amazon Managed Service for Prometheus
- ### AWS Management Console
- ### AWS Organizations
- ### AWS Proton
- ### AWS Service Catalog
- ### Service Quotas
- ### AWS Systems Manager
- ### AWS Trusted Advisor
- ### AWS Well-Architected Tool

## Media Services
- ### Amazon Elastic Transcoder
- ### Amazon Kinesis Video Streams

## Migration and Transfer
- ### AWS Application Discovery Service
- ### AWS Application Migration Service
- ### AWS Database Migration Service (AWS DMS)
- ### AWS DataSync
- ### AWS Migration Hub
- ### AWS Schema Conversion Tool (AWS SCT)
- ### AWS Snow Family
- ### AWS Transfer Family

## Networking and Content Delivery
- ### Amazon CloudFront
- ### AWS Direct Connect
- ### Elastic Load Balancing (ELB)
- ### AWS Global Accelerator
- ### AWS PrivateLink
- ### Amazon Route 53
    - CNAME records cannot be used for apex/root domains
- ### AWS Transit Gateway
- ### Amazon VPC
- ### AWS VPN

## Security, Identity, and Compliance
- ### AWS Artifact
- ### AWS Audit Manager
- ### AWS Certificate Manager (ACM)
- ### AWS CloudHSM
- ### Amazon Cognito
- ### Amazon Detective
- ### AWS Directory Service
- ### AWS Firewall Manager
    - Purpose-built for **managing WAF rules across accounts**
    - Centralized management through security policies
    - Native integration with Organizations
    - Parameter Store + EventBridge automation is efficient
    - Minimal operational overhead
- ### Amazon GuardDuty
- ### AWS IAM Identity Center (AWS Single Sign-On)
- ### AWS Identity and Access Management (IAM)
- ### Amazon Inspector
    - Security vulnerability assessment
- ### AWS Key Management Service (AWS KMS)
- ### Amazon Macie
- ### AWS Network Firewall
- ### AWS Resource Access Manager (AWS RAM)
- ### AWS Secrets Manager
- ### AWS Security Hub
    - security findings
    - security controls

- ### AWS Security Token Service (AWS STS)
- ### AWS Shield
    - Protection from DDoS attacks
    - Protection from SQL injection attacks
    - Protection from RCE attacks
    - Protection from bot attacks
    - Protection from web attacks, including application-layer attacks, 
    - offers advanced features like automated mitigation, anomaly detection, and cost protection.
    - It integrates seamlessly with AWS WAF and works with the ALB to reduce operational overhead.
- ### AWS WAF

## Storage
- ### AWS Backup
- ### Amazon Elastic Block Store (Amazon EBS)
- ### AWS Elastic Disaster Recovery
- ### Amazon Elastic File System (Amazon EFS)
    - Amazon EFS does not support Windows ACLs
- ### Amazon FSx (for all types)
    - Amazon FSx for Windows File Server offering native support for Windows ACLs, Active Directory integration, and shared file systems.
- ### Amazon S3
- ### Amazon S3 Glacier
- ### AWS Storage Gateway
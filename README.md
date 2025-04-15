# Azure vs AWS vs Google Cloud: A Practical Guide to the Cloud

## AZURE Services Summary

### 0. Azure Infrastructure(Availability Zones, Regions, Datacenters, etc)

### 1. Identity & Access Management

•	Microsoft Entra ID (Azure AD):

o	Users, Groups, App Registration

o	RBAC (Role-Based Access Control)

o	Conditional Access, MFA

•	Microsoft Entra Permissions Management: Governance across multi-cloud.

•	Azure AD B2C / B2B: Identity for external users.

### 2. Networking

•	Virtual Networks (VNets), Subnets, Route Tables

•	NSGs (Network Security Groups)

•	Service Endpoints & Private Endpoints

•	Application Gateway: Web traffic load balancer with WAF.

•	Azure Firewall: Stateful firewall as a service.

•	VPN Gateway / ExpressRoute: Site-to-site and private connectivity.

•	Azure Front Door: Global load balancing and edge security.

•	Traffic Manager: DNS-based load distribution.

### 3. Storage

•	Blob, File, Queue, Table Storage

•	Storage Tiers: Hot, Cool, Archive

•	Azure Data Lake Storage: Scalable big data storage.

•	Lifecycle Management

•	Shared Access Signatures (SAS)

•	Encryption, Firewall Rules, Private Endpoints

### 4. App Development & Hosting

•	App Service / Web Apps

o	Deployment Slots, Custom Domains, SSL

•	App Service Environments (ASE): Isolated, high-scale environment.

•	Azure Static Web Apps: Static site hosting + serverless APIs.

•	Azure Logic Apps: Workflow automation.

•	Azure Functions: Serverless compute.

•	Azure API Management: Secure and publish APIs.

### 5. Containers & Microservices

•	Azure Kubernetes Service (AKS): Managed Kubernetes.

•	Azure Container Instances (ACI): Lightweight containers.

•	Azure Container Registry (ACR): Private image repository.

•	Dapr: Distributed application runtime for microservices.

### 6. Databases & Analytics

•	Azure SQL Database / SQL Managed Instance

•	Cosmos DB: Globally distributed NoSQL database

•	Azure Database for PostgreSQL, MySQL, MariaDB

•	Azure Synapse Analytics: Data warehouse + big data.

•	Azure Data Factory: Data integration & pipelines.

•	Azure Databricks: Apache Spark analytics.

•	Azure Purview: Data governance and catalog.

### 7. Artificial Intelligence & Machine Learning

•	Azure OpenAI Service: GPT models (chat, text, image)

•	Azure Cognitive Services: Vision, Speech, Language, Search

•	Azure Machine Learning: MLOps, training, and deployment

•	MCP (Model Context Protocol): Prompt orchestration and memory

•	Microsoft.SemanticKernel & Extensions.AI

### 8. Security & Governance

•	Microsoft Defender for Cloud: Threat detection and protection

•	Azure Key Vault: Secrets, keys, certificates

•	Azure Policy: Enforce organizational standards

•	Azure Blueprints: Define and repeat compliant environments

•	Azure Monitor: Performance monitoring and alerts

•	Azure Security Center: Posture management

### 9. DevOps & CI/CD

•	Azure DevOps Services:

o	Repos, Pipelines, Boards, Artifacts

•	GitHub Actions for Azure: CI/CD with GitHub

•	Azure Test Plans: Manual and exploratory testing

### 10. Management & Automation

•	Azure Resource Manager (ARM) & ARM templates

•	Azure Bicep: Simplified IaC language

•	Azure Automation: Runbooks and update management

•	Azure Arc: Manage hybrid and multi-cloud resources

•	Azure Lighthouse: Multi-tenant management for service providers

•	Azure Cost Management + Billing

### 11. Monitoring, Logging & Diagnostics

•	Azure Monitor: End-to-end observability

•	Log Analytics: Query and analyze logs (Kusto)

•	Application Insights: App performance monitoring

•	Azure Advisor: Recommendations for best practices

### 12. Hybrid & Edge

•	Azure Stack: On-premise Azure services

•	Azure Arc: Extend Azure management to any infrastructure

•	Azure IoT Hub: Connect and manage IoT devices

•	Azure Sphere: Secure edge devices

## AWS Services Summary

### 0. AWS Infrastructure & Compute

•	Regions & Availability Zones (AZs): Physical locations with isolated datacenters for high availability.

•	Local Zones / Wavelength Zones: Low-latency access near end-users/devices.

•	Amazon EC2 (Elastic Compute Cloud): Scalable virtual machines.

o	AMIs (Amazon Machine Images), Elastic IPs, Key Pairs

•	Auto Scaling Groups: Automatic VM scaling.

•	AWS Outposts / Dedicated Hosts: On-prem and dedicated infrastructure.

________________________________________

### 1. Identity & Access Management

•	AWS IAM:

o	Users, Groups, Roles, Policies

o	Access Keys, MFA, Identity Federation

•	AWS Organizations: Multi-account governance.

•	AWS SSO / IAM Identity Center: Centralized access management.
________________________________________

### 2. Networking

•	Amazon VPC (Virtual Private Cloud): Isolated network environments.

•	Subnets, Route Tables, Internet/NAT Gateways

•	Security Groups & Network ACLs: Traffic filtering.

•	VPC Endpoints (Interface & Gateway): Private access to AWS services.

•	Elastic Load Balancers (ELB): ALB, NLB, GLB.

•	AWS Direct Connect: Dedicated on-prem to AWS connection.

•	Amazon Route 53: Scalable DNS service.
________________________________________

### 3. Storage

•	Amazon S3 (Simple Storage Service): Object storage with lifecycle policies and versioning.

•	S3 Glacier / Glacier Deep Archive: Cold storage tiers.

•	Amazon EBS (Elastic Block Store): Block storage for EC2.

•	Amazon EFS (Elastic File System): NFS-based file storage.

•	AWS Backup: Centralized backup solution.

________________________________________

### 4. App Development & Hosting

•	AWS Elastic Beanstalk: Platform-as-a-service for web apps.

•	Amazon Lightsail: Simple app hosting with containers and VMs.

•	AWS Amplify: Frontend & mobile app development.

•	AWS App Runner: Deploy web apps from code or containers.

•	API Gateway: Publish, manage, and secure APIs.

•	AWS Lambda: Serverless functions.

________________________________________

### 5. Containers & Orchestration

•	Amazon ECS (Elastic Container Service): Container orchestration.

•	Amazon EKS (Elastic Kubernetes Service): Managed Kubernetes.

•	AWS Fargate: Serverless containers.

•	Amazon ECR (Elastic Container Registry): Private Docker registry.
________________________________________

### 6. Databases & Analytics

•	Amazon RDS: Managed relational DBs (MySQL, PostgreSQL, Oracle, SQL Server, Aurora).

•	Amazon DynamoDB: NoSQL key-value store.

•	Amazon Redshift: Scalable data warehouse.

•	Amazon ElastiCache: Redis/Memcached caching.

•	Amazon DocumentDB: MongoDB-compatible database.

•	Amazon Timestream / QLDB: Time series / ledger databases.

•	AWS Glue: ETL and data catalog.

•	Amazon Athena: SQL queries on S3 data.

•	Amazon Kinesis: Real-time data streaming.
________________________________________

### 7. Artificial Intelligence & Machine Learning

•	Amazon SageMaker: Build, train, and deploy ML models.

•	Amazon Bedrock: Access foundation models (Anthropic, AI21, etc.).

•	Amazon Comprehend: NLP service.

•	Amazon Rekognition: Image and video analysis.

•	Amazon Transcribe / Polly / Translate: Speech and language services.

•	AWS Lex: Conversational interfaces (chatbots).
________________________________________

### 8. Security & Governance

•	AWS KMS (Key Management Service): Manage cryptographic keys.

•	AWS Secrets Manager / Parameter Store: Securely store secrets/configs.

•	AWS Shield & WAF: DDoS protection and web firewall.

•	Amazon Macie: Discover sensitive data.

•	AWS Config: Track resource configurations.

•	AWS Control Tower: Govern multi-account environments.

•	AWS Security Hub: Centralized security posture management.
________________________________________

### 9. DevOps & CI/CD

•	AWS CodeCommit: Git-based repositories.

•	AWS CodeBuild: Build and test code.

•	AWS CodeDeploy: Automated deployments.

•	AWS CodePipeline: CI/CD orchestration.

•	AWS Cloud9: Web-based IDE.
________________________________________

### 10. Management & Automation

•	AWS CloudFormation: Infrastructure as code.

•	AWS CDK (Cloud Development Kit): Code-first IaC.

•	AWS Systems Manager: Manage VMs and configurations.

•	AWS CloudTrail: User and API activity logging.

•	AWS CloudWatch: Metrics, logs, alarms, dashboards.

•	AWS Trusted Advisor: Best practice recommendations.

•	Cost Explorer & Budgets: Track and optimize spending.
________________________________________

### 11. Monitoring, Logging & Diagnostics

•	Amazon CloudWatch: Performance metrics and alerting.

•	CloudWatch Logs & Insights: Log aggregation and analysis.

•	AWS X-Ray: Distributed tracing for applications.

•	AWS Health Dashboard: Personal service health notifications.
________________________________________

### 12. Hybrid & Edge

•	AWS Outposts: Run AWS services on-prem.

•	AWS Snow Family: Edge computing and data transfer devices.

•	AWS Local Zones: Low-latency compute near users.

•	AWS Wavelength: 5G edge computing with telecom providers.

•	AWS IoT Core: Connect and manage IoT devices.

________________________________________

## Google Cloud Services

________________________________________

### 0. GCP Infrastructure & Compute

•	Regions & Zones: Global infrastructure of datacenters.

•	Google Compute Engine (GCE): Virtual machines with custom and predefined machine types.

•	Instance Groups: Managed (auto-scaling) and unmanaged VM groups.

•	Live Migration & Preemptible VMs

•	Google Cloud VMware Engine: VMware workloads on GCP.

•	Bare Metal Solution: Bare metal servers for legacy apps.

________________________________________

### 1. Identity & Access Management

•	Cloud IAM: Role-based access control for GCP resources.

o	Users, Service Accounts, Roles (Primitive, Predefined, Custom)

•	Cloud Identity: Central identity management.

•	Workforce Identity Federation: External identity provider integration.

•	Identity-Aware Proxy (IAP): Context-aware access to apps and VMs.

•	BeyondCorp Enterprise: Zero-trust access model.
________________________________________

### 2. Networking

•	VPC (Virtual Private Cloud): Global network with subnets, routing.

•	Firewall Rules, Routes, NAT Gateway

•	Private Google Access: Connect to Google APIs via internal IPs.

•	Cloud Load Balancing: Global and regional load balancers (HTTP(S), TCP/UDP, SSL).

•	Cloud CDN: Content delivery network.

•	Cloud Interconnect & VPN: Hybrid connectivity.

•	Cloud DNS: Scalable domain name system service.

•	Network Intelligence Center: Network monitoring and insights.

________________________________________

### 3. Storage

•	Cloud Storage: Scalable object storage (Standard, Nearline, Coldline, Archive).

•	Persistent Disks: Block storage for VMs.

•	Filestore: Managed NFS-based file storage.

•	Local SSD: High-speed ephemeral disks.

•	Transfer Appliance / Storage Transfer Service: Data migration tools.

•	Backup and DR: Centralized backup and disaster recovery.
________________________________________

### 4. App Development & Hosting

•	App Engine: Fully managed PaaS for app hosting (Standard & Flexible).

•	Cloud Run: Serverless container execution.

•	Cloud Functions: Event-driven serverless functions.

•	Cloud Endpoints: API management for GCP services.

•	Firebase Hosting: Fast and secure web app hosting for mobile & web.

•	Google Domains / Custom Domain Mapping
________________________________________

### 5. Containers & Orchestration

•	Google Kubernetes Engine (GKE): Managed Kubernetes service.

•	Cloud Run: Serverless containers with scale-to-zero.

•	Artifact Registry: Secure container image and language package storage.

•	GKE Autopilot: Fully managed Kubernetes with less ops overhead.

•	Container Registry: (legacy) Docker image storage.
________________________________________

### 6. Databases & Analytics

•	Cloud SQL: Managed MySQL, PostgreSQL, SQL Server.

•	Cloud Spanner: Global, horizontally scalable relational DB.

•	BigQuery: Serverless data warehouse with SQL and ML support.

•	Firestore / Firebase Realtime DB: NoSQL document databases.

•	Cloud Bigtable: Wide-column NoSQL DB for big data.

•	Datastream: Change data capture and replication.

•	Looker (BI): Business intelligence and data visualization.
________________________________________

### 7. Artificial Intelligence & Machine Learning

•	Vertex AI: End-to-end ML platform (training, deployment, monitoring).

•	AutoML: No-code model training for vision, text, and tables.

•	Dialogflow: Conversational AI / chatbot platform.

•	Cloud Vision, Natural Language, Speech-to-Text, Translate, Text-to-Speech

•	Generative AI Studio: Large language model-based prompt development.

•	PaLM 2 / Gemini: Foundation models via Vertex AI.
________________________________________

### 8. Security & Governance

•	Cloud Key Management (KMS): Create and manage encryption keys.

•	Secret Manager: Store and access secrets securely.

•	Cloud Armor: DDoS protection and WAF.

•	Security Command Center: Threat detection and posture management.

•	Access Transparency / Access Approval: Visibility and control of Google admin actions.

•	Policy Intelligence: Insights into IAM policies.

________________________________________

### 9. DevOps & CI/CD

•	Cloud Build: CI/CD pipeline for building, testing, and deploying.

•	Cloud Deploy: GKE and Cloud Run deployment automation.

•	Artifact Registry: Store and manage build artifacts.

•	Cloud Source Repositories: Private Git repositories.

•	Skaffold, Tekton, and GitHub Actions for GCP

•	Error Reporting & Debugger
________________________________________

### 10. Management & Automation

•	Cloud Deployment Manager: Infrastructure as code (YAML-based).

•	Terraform on GCP: IaC with community and official modules.

•	Cloud Scheduler: Cron job scheduling.

•	Cloud Tasks: Asynchronous task execution.

•	Workflows: Orchestration of services using YAML-based workflows.

•	Activity Logs & Audit Logs
________________________________________

### 11. Monitoring, Logging & Diagnostics

•	Cloud Monitoring (formerly Stackdriver): System and app metrics.

•	Cloud Logging: Centralized log collection and querying.

•	Error Reporting, Trace, Debugger, Profiler

•	Operations Suite Dashboards

•	Uptime Checks & Alerting Policies
________________________________________

### 12. Hybrid & Edge

•	Anthos: Hybrid and multi-cloud Kubernetes management.

•	Google Distributed Cloud (GDC): Edge and on-prem GCP services.

•	Cloud Interconnect: Dedicated network connection.

•	Edge TPU: AI inferencing on edge devices.

•	IoT Core (deprecated, alternatives available via 3rd party or Anthos)

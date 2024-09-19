# Introduction to Cloud Computing and AWS - Important Concepts

## Key Concepts

### Cloud Computing and Virtualization

- **Virtualization:**
  - Enables multiple virtual machines (VMs) to run on a single physical server.
  - Each VM operates with its own OS, memory, storage, and network access.
  - **Benefits:** Flexibility, efficient resource utilization, rapid provisioning.

### Cloud Computing Architecture

- **Resource Pooling:**
  - Combining compute, storage, and network resources across physical servers.
  - Allows for on-demand, self-service access to resources.
- **Metered Billing:**
  - Pay-as-you-go model based on resource consumption.
  - Precise billing, sometimes to fractions of a penny.

### Cloud Computing Optimization

- **Scalability:**
  - Ability to handle increasing workloads by adding resources.
  - AWS Auto Scaling can automatically add EC2 instances to meet demand.
- **Elasticity:**
  - Automatically reduces resources when demand decreases.
  - Helps control costs by running resources only when needed.
- **Cost Management:**
  - Transition from Capital Expenditure (CapEx) to Operational Expenditure (OpEx).
  - Use of AWS Pricing Calculator for cost comparisons.

### The AWS Cloud

- **Core Service Categories:**
  - **Compute:** EC2, Lambda, Auto Scaling, Elastic Beanstalk.
  - **Networking:** VPC, Direct Connect, Route 53, CloudFront.
  - **Storage:** S3, S3 Glacier, EBS, Storage Gateway.
  - **Database:** RDS, DynamoDB.
  - **Application Management:** CloudWatch, CloudFormation, CloudTrail, Config.
  - **Security and Identity:** IAM, KMS, Directory Service.
  - **Application Integration:** SNS, SWF, SQS, API Gateway.

### AWS Platform Architecture

- **Regions:**
  - Geographical areas containing multiple Availability Zones.
  - 24 public regions globally (excluding GovCloud and China regions).
- **Availability Zones (AZs):**
  - Isolated locations within a region.
  - Each AZ consists of one or more data centers.
- **Endpoints:**
  - URLs used to access AWS services programmatically.
  - Format example: `ec2.us-east-1.amazonaws.com`.

### AWS Reliability and Compliance

- **Compliance Standards:**
  - AWS complies with ISO 9001, FedRAMP, NIST, GDPR, etc.
- **AWS Shared Responsibility Model:**
  - **AWS Responsibility:** Security of the cloud infrastructure.
  - **Customer Responsibility:** Security in the cloud (OS, applications, data).

### The AWS Service Level Agreement (SLA)

- **Service Uptime Guarantees:**
  - EC2 SLA: 99.99% uptime.
  - AWS provides service credits if SLAs are not met.

### Working with AWS

- **AWS Management Tools:**
  - **AWS Management Console:** Web-based interface for managing services.
  - **AWS CLI:** Command-line interface for automation and scripting.
  - **AWS SDKs:** Integrate AWS services into application code.

### AWS Organizations

- **Purpose:**
  - Consolidate and manage multiple AWS accounts.
- **Features:**
  - Unified billing, centralized management, policy enforcement.

### AWS Control Tower

- **Purpose:**
  - Simplifies the setup and governance of multi-account AWS environments.
- **Features:**
  - Landing zones, automated policy enforcement, centralized monitoring.

### AWS Service Catalog

- **Purpose:**
  - Create and manage catalogs of approved IT services.
- **Features:**
  - Customizable templates, access control, compliance enforcement.

### AWS License Manager

- **Purpose:**
  - Manage software licenses across AWS and on-premises environments.
- **Features:**
  - Track usage, enforce compliance, manage licensing rules.

### AWS Artifact

- **Purpose:**
  - Access compliance-related information and AWS security reports.
- **Features:**
  - Download compliance reports (SOC, PCI DSS, ISO certifications).

### The AWS CLI

- **Purpose:**
  - Manage AWS services from the command line.
- **Features:**
  - Automate tasks, integrate with scripts, supports Windows, macOS, Linux.

### AWS SDKs

- **Purpose:**
  - Programmatically interact with AWS services using various programming languages.
- **Supported Languages:**
  - Java, .NET, Python, JavaScript, Ruby, Go, PHP, C++, Mobile SDKs.

### Technical Support and Online Resources

- **Support Plans:**
  - **Basic:** Free, access to documentation and forums.
  - **Developer:** Starting at $29/month, business hours email support.
  - **Business:** Starting at $100/month, 24/7 phone, email, chat support.
  - **Enterprise:** Starting at $15,000/month, Technical Account Manager (TAM), fastest response times.
- **Additional Resources:**
  - AWS re:Post, documentation, whitepapers, AWS Well-Architected Framework.

### Migrating Existing Resources to AWS

- **AWS Migration Hub:**
  - Central dashboard to track migration projects.
- **AWS Application Migration Service:**
  - Automates the migration of on-premises servers to AWS.
- **AWS Database Migration Service (DMS):**
  - Migrates databases to AWS with minimal downtime.
- **AWS Application Discovery Service:**
  - Discovers on-premises applications and dependencies to plan migrations.

---


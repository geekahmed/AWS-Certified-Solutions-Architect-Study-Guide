# Introduction to Cloud Computing and AWS - Notes

## Detailed Notes

### Cloud Computing and Virtualization

- **Virtualization Technology:**
  - Allows partitioning of physical servers into multiple VMs.
  - Each VM can run its own OS and applications independently.
  - **Hypervisor:** Software layer managing hardware resources for VMs.

- **Benefits of Virtualization:**
  - Rapid provisioning and decommissioning of resources.
  - Improved hardware utilization.
  - Isolation between different workloads.

### Cloud Computing Architecture

- **Data Centers and Resource Pooling:**
  - Large-scale server farms with thousands of servers and storage devices.
  - Resources like compute cycles, storage, and network bandwidth are pooled.
  - Efficient allocation based on demand.

- **On-Demand Self-Service:**
  - Users can provision resources without human intervention.
  - Accessed via web interfaces or APIs.

- **Metered Billing:**
  - Usage-based billing models.
  - Precise billing down to fractions of a penny.

### Cloud Computing Optimization

- **Scalability:**
  - **Vertical Scaling:** Adding more resources to an existing instance.
  - **Horizontal Scaling:** Adding more instances to handle increased load.
  - AWS Auto Scaling can automatically adjust the number of instances.

- **Elasticity:**
  - Resources can scale up or down automatically based on demand.
  - Helps in cost savings by reducing unused resources.

- **Cost Management:**
  - Shift from CapEx to OpEx.
  - No upfront costs for hardware.
  - Pay only for what you use.
  - **AWS Pricing Calculator:** Tool to estimate costs.

### The AWS Cloud

- **AWS Core Services:**

  - **Compute Services:**
    - **EC2 (Elastic Compute Cloud):**
      - Virtual servers with configurable CPU, memory, storage, and networking.
      - Supports various instance types and pricing models.

    - **Lambda:**
      - Serverless computing.
      - Run code in response to events without managing servers.

    - **Auto Scaling:**
      - Automatically adjusts the number of EC2 instances.

  - **Networking Services:**
    - **VPC (Virtual Private Cloud):**
      - Virtual network for AWS resources.
      - Control over IP addresses, subnets, route tables, and gateways.

    - **Direct Connect:**
      - Dedicated network connection from on-premises to AWS.

    - **Route 53:**
      - DNS web service.
      - Domain registration and traffic routing.

    - **CloudFront:**
      - Content Delivery Network (CDN).
      - Delivers content with low latency.

  - **Storage Services:**
    - **S3 (Simple Storage Service):**
      - Object storage with high durability and scalability.
      - Used for data storage and backups.

    - **S3 Glacier:**
      - Low-cost storage for archiving and long-term backup.

    - **EBS (Elastic Block Store):**
      - Block storage volumes for use with EC2 instances.

    - **Storage Gateway:**
      - Hybrid storage service connecting on-premises software appliances with cloud-based storage.

  - **Database Services:**
    - **RDS (Relational Database Service):**
      - Managed relational database service.
      - Supports MySQL, PostgreSQL, Oracle, SQL Server, and Aurora.

    - **DynamoDB:**
      - Managed NoSQL database service.
      - High performance and scalability.

### AWS Platform Architecture

- **Regions and Availability Zones:**
  - **Regions:**
    - Separate geographic areas.
    - Each region is isolated to reduce the impact of outages.

  - **Availability Zones (AZs):**
    - Distinct locations within a region.
    - Designed for fault isolation.
    - Connected with low-latency networking.

- **Edge Locations:**
  - Used by CloudFront to cache content closer to users.
  - Improves performance and reduces latency.

- **Endpoints:**
  - URLs used to interact with AWS services.
  - Service-specific endpoints per region.

### AWS Reliability and Compliance

- **Service Level Agreements (SLAs):**
  - AWS commitment to uptime and availability.
  - EC2 SLA: 99.99% availability.

- **Compliance Programs:**
  - AWS adheres to various compliance standards.
  - Helps customers meet regulatory requirements.

### The AWS Shared Responsibility Model

- **AWS Responsibility:**
  - Security **of** the cloud.
  - Physical infrastructure, networking, virtualization layer.

- **Customer Responsibility:**
  - Security **in** the cloud.
  - Operating systems, applications, data, IAM configurations.

### Working with AWS

- **AWS Management Console:**
  - Web-based interface.
  - Access and manage AWS services visually.

- **AWS CLI:**
  - Command-line tool for managing AWS services.
  - Supports automation and scripting.

- **AWS SDKs:**
  - Language-specific APIs.
  - Integrate AWS services into applications.

- **Installation of AWS CLI:**
  - Available for Windows, macOS, Linux.
  - Configure using `aws configure` command.

### AWS Organizations and Control Tower

- **AWS Organizations:**
  - Centralized management of multiple AWS accounts.
  - Hierarchical grouping using Organizational Units (OUs).
  - Apply Service Control Policies (SCPs) for governance.

- **AWS Control Tower:**
  - Automates setup of multi-account environments.
  - Enforces policies and compliance.
  - Provides pre-configured landing zones.

### AWS Service Catalog and License Manager

- **AWS Service Catalog:**
  - Create and manage catalogs of approved products.
  - Ensures consistent governance.

- **AWS License Manager:**
  - Track and manage software licenses.
  - Enforce licensing rules.

### AWS Artifact

- **Purpose:**
  - Central resource for compliance-related information.
  - Access AWS SOC reports, PCI reports, ISO certifications.

### AWS Migration Services

- **AWS Migration Hub:**
  - Track migration tasks across multiple AWS tools.

- **AWS Application Migration Service:**
  - Lift-and-shift migration of on-premises servers.

- **AWS Database Migration Service (DMS):**
  - Migrate databases with minimal downtime.
  - Supports homogeneous and heterogeneous migrations.

- **AWS Application Discovery Service:**
  - Discovers on-premises applications and dependencies.
  - Assists in migration planning.

### Technical Support and Resources

- **Support Plans:**
  - Choose based on business needs and budget.
  - Enterprise plan offers Technical Account Manager (TAM).

- **Self-Service Support:**
  - AWS re:Post community forums.
  - Extensive documentation and whitepapers.

---


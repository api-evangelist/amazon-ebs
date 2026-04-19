# Amazon EBS (amazon-ebs)
Amazon Elastic Block Store (EBS) provides persistent block storage volumes for use with Amazon EC2 instances. EBS volumes are highly available and reliable storage volumes that can be attached to any running instance in the same Availability Zone, offering consistent and low-latency performance for workloads that require persistent storage.

**URL:** [Visit APIs.json URL](https://aws.amazon.com/ebs/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Amazon Web Services, AWS, Block Storage, EBS, EC2, Snapshots, Storage, Volumes

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon EBS API
API for managing Amazon EBS volumes, snapshots, and related resources through the EC2 API.

**Human URL:** [https://aws.amazon.com/ebs/](https://aws.amazon.com/ebs/)

#### Properties

- [Documentation](https://docs.aws.amazon.com/ebs/latest/userguide/)
- [OpenAPI](openapi/amazon-ebs-openapi.yml)
- [JSONSchema](json-schema/amazon-ebs-volume-schema.json)
- [JSONLD](json-ld/amazon-ebs-context.jsonld)
- [Pricing](https://aws.amazon.com/ebs/pricing/)
- [GettingStarted](https://aws.amazon.com/ebs/getting-started/)
- [FAQ](https://aws.amazon.com/ebs/faqs/)
- [Documentation](https://docs.aws.amazon.com/ebs/latest/userguide/)
- [APIReference](https://docs.aws.amazon.com/AWSEC2/latest/APIReference/)
- [Documentation](https://docs.aws.amazon.com/cli/latest/reference/ec2/)
- [Security](https://docs.aws.amazon.com/ebs/latest/userguide/security.html)
- [JSONStructure](json-structure/amazon-ebs-volume-structure.json)
- [Example](examples/amazon-ebs-volume-example.json)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [DeveloperPortal](https://aws.amazon.com/)
- [Documentation](https://docs.aws.amazon.com/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/support/)
- [Blog](https://aws.amazon.com/blogs/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://status.aws.amazon.com/)
- [KnowledgeCenter](https://repost.aws/knowledge-center)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/amazon-web-services)
- [Contact](https://aws.amazon.com/contact-us/)
- [Security](https://aws.amazon.com/security/)
- [Compliance](https://aws.amazon.com/compliance/)
- [SpectralRules](rules/amazon-ebs-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-ebs-vocabulary.yaml)
- [NaftikoCapability](capabilities/ebs-management.yaml)

## Features

| Name | Description |
|------|-------------|
| Multiple Volume Types | Choose from gp3, gp2, io2, io1, st1, sc1, and io2 Block Express volumes optimized for different workloads. |
| EBS Snapshots | Point-in-time backups stored in Amazon S3 for disaster recovery, migration, and data sharing. |
| Encryption | AES-256 encryption at rest and in transit using AWS KMS customer-managed or AWS-managed keys. |
| Elastic Volumes | Dynamically modify volume size, performance, and type without detaching from instances. |
| Data Lifecycle Manager | Automate snapshot creation, retention, deletion, and cross-account sharing with policy-based management. |
| Multi-Attach | Attach a single io2 volume to up to 16 EC2 instances simultaneously for high availability. |

## Use Cases

| Name | Description |
|------|-------------|
| Relational Databases | High-performance persistent storage for MySQL, PostgreSQL, Oracle, and SQL Server databases. |
| NoSQL Databases | Low-latency block storage for MongoDB, Cassandra, and other NoSQL workloads. |
| Enterprise Applications | SAN workload migration for I/O-intensive SAP, Oracle, and other enterprise applications. |
| Big Data Analytics | Resizable storage for Hadoop, Spark, and other big data cluster deployments. |
| Boot Volumes | OS and application boot volumes for all EC2 instance types. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon EC2 | Attach EBS volumes to EC2 instances in the same Availability Zone for persistent storage. |
| Amazon Data Lifecycle Manager | Automate snapshot management and cross-account data sharing policies. |
| AWS Backup | Centralized backup management for EBS volumes with configurable retention and compliance. |
| AWS Key Management Service | Manage encryption keys for EBS volumes and snapshots. |
| Amazon CloudWatch | Monitor EBS volume performance metrics including IOPS, throughput, and latency. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon Ebs](openapi/amazon-ebs-openapi.yml)

### JSON Schema

- [Amazon Ebs Volume](json-schema/amazon-ebs-volume-schema.json)
- [Ebs Openapi Describe Volumes Result](json-schema/ebs-openapi-describe-volumes-result-schema.json)
- [Ebs Openapi Volume](json-schema/ebs-openapi-volume-schema.json)

### JSON Structure

- [Amazon Ebs Volume](json-structure/amazon-ebs-volume-structure.json)
- [Ebs Openapi Describe Volumes Result](json-structure/ebs-openapi-describe-volumes-result-structure.json)
- [Ebs Openapi Volume](json-structure/ebs-openapi-volume-structure.json)

### JSON-LD

- [Amazon Ebs](json-ld/amazon-ebs-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Ebs](capabilities/shared/ebs.yaml) — 38 operations

### Workflow Capabilities

| Workflow | Tools | Persona |
|----------|-------|---------|
| [Ebs Management](capabilities/ebs-management.yaml) | 7 | managing EBS volumes, snapshots, and encryption for cloud storage administrators |

## Vocabulary

- [Amazon EBS Vocabulary](vocabulary/amazon-ebs-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 5 actions, 1 workflows, and 1 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon Ebs Spectral Rules](rules/amazon-ebs-spectral-rules.yml) — 28 rules enforcing Amazon EBS API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
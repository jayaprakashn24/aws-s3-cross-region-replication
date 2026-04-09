# Cross Region Backup Project (S3)

**AWS S3 Cross-Region Replication (CRR)** is a feature that automatically replicates data from one Amazon S3 bucket to another in a different AWS region. It ensures higher data durability, improved availability, and helps with disaster recovery, compliance, and reduced latency for global users.

## Key Features:
- **Automated Replication**: Replicates new objects to the destination region automatically.
- **Support for Encryption**: Works with encrypted and unencrypted objects.
- **Metadata Preservation**: Includes tags, versioning, and storage class.
- **Versioning**: Replicates all object versions.
- **Replication Filters**: Based on object prefixes or tags.
- **Replication Time Control (RTC)**: Guarantees replication within set SLAs.
- **Monitoring**: CloudWatch metrics for replication status.

## Benefits:
- **Disaster Recovery**: Replicates data to ensure business continuity.
- **Data Redundancy**: Enhances data durability and availability.
- **Compliance**: Meets regulatory data residency requirements.
- **Reduced Latency**: Improves content delivery to global users.

## Example Use Case:
An e-commerce company with global customers sets up CRR to replicate product images from the U.S. to Europe and Asia. This ensures:
- **Fast Image Loading**: Customers in Europe and Asia can quickly access product images.
- **Data Redundancy**: Even if the U.S. region goes down, data remains accessible in other regions.
- **Compliance**: Product images from European customers are stored in compliance with regulations like GDPR.

**Real-Time Small-Scale Mart Application Architecture**

***Overview***

Designed an architecture for a real-time mart application using AWS services to manage and manipulate large datasets efficiently.

***Key AWS Services***

VPC: Create isolated networks for resources.
EC2: Launch instances with AMI for data management.

S3: Store and version data across zones.

Lambda: Trigger actions based on S3 events.

DynamoDB: Store de-duplicated data in a serverless NoSQL database.

RDS: Provide high availability and query data.

SNS: Alert subscribers when data thresholds are exceeded.

CloudWatch: Monitor metrics and set up alerts.

Glue: ETL tasks to move data from S3 to RDS.

***Architecture Highlights***

Data Flow: Data stored in S3, de-duplicated and moved to DynamoDB, then transferred to RDS for querying.

Alerts: SNS used to notify subscribers on key data thresholds.

Flexibility: Architecture supports high availability and efficient data management.

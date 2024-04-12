# Title: Application will use data pipeline in Azure

## Status

DRAFT

## Context

We wanted to choose a suitable cloud based AI/ML data pipeline implementation for efficient processing of FishWatch data received from Fish farms.

## Decision

* Two major cloud services vendors, Amazon Web Services (AWS) and Microsoft Azure, offers end-to-end AI/ML data pipeline.
* Our team is experienced on Microsoft Azure
* Very good learning center and support system from Microsft Azure
* Hence we decided to go with Microsoft Azure to implement AI/ML data pipeline

![](https://media.licdn.com/dms/image/D4D12AQGqJBsL1cyuiQ/article-cover_image-shrink_720_1280/0/1690974328345?e=2147483647&v=beta&t=jOlUpmtgG3y4uoKYMTS23FKSh_EQbBJqFdVHzPD9ZyY)

## Consequences

#### Positive
* Prooven track record of Microsoft Azure that has empowered data engineers to create robust, scalable, and efficient data pipelines.
* Scalability and Elasticity: Leverage Azure's scalability by using services like Azure Databricks or Azure Synapse Analytics to handle varying data workloads.
* Modularity: Design pipelines as modular components to facilitate reusability and easier maintenance. This also helps in debugging and troubleshooting.
* Monitoring and Logging: Implement robust monitoring and logging using Azure Monitor and Azure Log Analytics to track pipeline performance and identify issues.
* Data Partitioning: When dealing with large datasets, use partitioning strategies to optimize data storage and retrieval efficiency.
* Backup and Disaster Recovery: Ensure data integrity and availability by implementing backup and disaster recovery solutions provided by Azure.

#### Negative
* Costs are quite high due to unused compute time, etc.
* Microsoft Azure certified engineers are required to maintain and implement AI/ML data pipeline

## Conclusion:

With the help of a rich ecosystem on cloud services, we can create data pipelines that provide accurate, timely, and actionable insights on fish farm data to make important decisions or course correction.

[Home Page](../README.md) | [ADR Home Page](../Architecture_Decision_Reports)

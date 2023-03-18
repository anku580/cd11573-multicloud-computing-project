# Reason for choosing AWS Dynamo DB over Azure Cosmo DB

### Some of the features offered by Amazon DynamoDB are:

- Automated Storage Scaling – There is no limit to the amount of data you can store in a DynamoDB table, and the service automatically allocates more storage, as you store more data using the DynamoDB write APIs.
- Provisioned Throughput – When creating a table, simply specify how much request capacity you require.
- Fully Distributed, Shared Nothing Architecture – Amazon DynamoDB scales horizontally and can seamlessly scale a single table over hundreds of servers.

### Azure Cosmos DB provides the following key features:

- Fully managed with 99.99% Availability SLA
- Elastically and highly scalable (both throughput and storage)
- Predictable low latency: <10ms @ P99 reads and <15ms @ P99 fully-indexed writes

"Predictable performance and cost" is the top reason why we chose Amazon dynamo DB as it is cheaper than the cosmo DB.

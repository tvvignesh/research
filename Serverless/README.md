AWS lambda
--------------
Supported languages: Java, Node.js, C#, Go or Python
Max duration: 300 seconds/request
Max temp space: 512 MB
Memory Limits: Minimum = 128 MB / Maximum = 3008 MB (with 64 MB increments). If the maximum memory use is exceeded, function invocation will be terminated.
Payload size Limit - synchronous: 6 MB
Payload size Limit - asynchronous: 128 KB

Pricing: https://aws.amazon.com/lambda/pricing/

More info here: https://docs.aws.amazon.com/lambda/latest/dg/limits.html

Azure functions
--------------
Supported languages: 

https://docs.microsoft.com/en-us/azure/azure-functions/supported-languages

Max duration: 10 minutes (5 min by default), increase more than that requires a dedicated VM in Azure App Service plan

Max temp space: 500 MB (https://stackoverflow.com/questions/43682887/what-is-the-maximum-limit-of-temp-directory-in-azure-functions-on-a-consumption)

Memory Limits: 1.5GB for function apps (multiple functions together)

Pricing: https://azure.microsoft.com/en-in/pricing/details/functions/  (Separate pricing for storage & networking)

More info here: https://docs.microsoft.com/en-us/azure/azure-functions/functions-scale

Creating an azure function: https://docs.microsoft.com/en-us/azure/azure-functions/functions-create-first-azure-function

Google Cloud functions
--------------

Language supported: Node.js
Pricing & General Info: https://cloud.google.com/functions/

Limit info: https://cloud.google.com/functions/quotas


<hr>

Storage
--------

Cosmos & Stored Procedures
---------------
Supported language: Javascript

Supported API: SQL,MongoDB,Graph,Table,Cassandra

Storage Limit: Supports unlimited storage but needs to be 10GB/Partition Key

Max size for a document: 2 MB

Max size for blobs: 2 GB/account

Execution Limits: Limited by Throughput (Throughput is expressed in terms of a normalized unit of CPU, memory and IO consumption called request units or RUs. )

Time Limit: 5 seconds (No clear indication in official documentation but limit is available at https://stackoverflow.com/questions/34656072/what-happens-when-5-second-execution-time-limit-exceeds-in-azure-documentdb-stor)

Pricing: https://azure.microsoft.com/en-us/pricing/details/cosmos-db/

More info here: https://docs.microsoft.com/en-us/azure/cosmos-db/programming  and  https://docs.microsoft.com/en-us/azure/cosmos-db/faq

Reference video: https://azure.microsoft.com/en-in/resources/videos/documentdb-stored-procedures-best-practices/

Azure Table Storage
--------------
NoSQL Table Storage, recommended for non-relational use - https://docs.microsoft.com/en-us/azure/cosmos-db/table-storage-overview

Max size of single table: 500 TiB

Max size of a table entity: 1 MiB

Max number of properties in a table entity: 252

Max number of stored access policies per table: 5

Maximum request rate per storage account: 20,000 transactions per second (assuming 1 KiB entity size)

Target throughput for single table partition (1 KiB entities): Up to 2000 entities per second

Pricing: https://azure.microsoft.com/en-in/pricing/details/storage/tables/

Limit info here: https://docs.microsoft.com/en-us/azure/azure-subscription-service-limits

More info here: https://docs.microsoft.com/en-in/azure/cosmos-db/table-storage-how-to-use-dotnet

Azure SQL
---------------

Dynamically scale up/down: https://azure.microsoft.com/en-in/resources/videos/azure-sql-database-dynamically-scale-up-or-scale-down/

Limit info here: https://docs.microsoft.com/en-us/azure/sql-database/sql-database-resource-limits

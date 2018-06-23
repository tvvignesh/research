## Elasticsearch, Logstash & Kibana

### Outline

Search Engine based on Apache Lucene

### Underlying technology

Java

### Reference Links

https://www.elastic.co/guide/index.html

https://www.tutorialspoint.com/elasticsearch/index.htm

### Samples

https://dzone.com/articles/23-useful-elasticsearch-example-queries

### Videos

https://www.youtube.com/watch?v=ksTTlXNLick

https://www.elastic.co/webinars/getting-started-elasticsearch

### Pros

1. All queries available as REST endpoints
2. Superfast queries with different tokenizers
3. Detailed query logs and stats available
4. Distributed, scalable, can be clustered, sharded
5. Client SDKs available in multiple languages (optional)
6. Good support in the Cloud
7. Document oriented, with full text support, schema free
8. Persistence available
9. Open Source, Enterprise support available
10. Powerful Devtools, Insights, Dashboards made available via Kibana
11. Logstash supports various ETL operations, with various input-output sources, custom scripts can be written to facilitate ETL

### Cons

1. Not a reliable datastore, data loss can occur
2. Some useful plugins are paid
3. Bulk upload of data into elastic seems a bit odd where we have to give line breaks between each and every JSON record (not a standard)

### Licence

Apache 2.0 & Elastic License
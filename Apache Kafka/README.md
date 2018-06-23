## Apache Kafka

### Outline

A Distributed Scalable Event Store

### Underlying technology

Scala

### Reference Links

https://kafka.apache.org

https://www.tutorialspoint.com/apache_kafka/index.htm

https://docs.confluent.io/current/tutorials/index.html

https://www.confluent.io/blog/building-a-microservices-ecosystem-with-kafka-streams-and-ksql/

https://www.confluent.io/blog/stream-data-platform-1/

### Samples

https://github.com/SOHU-Co/kafka-node/tree/master/example

### Videos

https://www.youtube.com/watch?v=gg-VwXSRnmg&list=PLkz1SCf5iB4enAR00Z46JwY9GGkaS2NON

https://www.youtube.com/watch?v=hyJZP-rgooc&list=PL9ooVrP1hQOG7-vTVK-hgiPwKJT6XOfO_

https://www.pluralsight.com/courses/apache-kafka-getting-started

### Pros

1. Battle tested, and production ready by LinkedIn, Uber, Netflix, Confluent, etc.
2. Highly scalable, distributed, with partitions, persistence and high throughput
3. Allows back-pressure when receiving message (Pull based)
4. Good tooling built by LinkedIn and Confluent on top to enable monitoring, management, etc.
5. SDK available in multiple languages
6. Comes with Zookeeper configured and also with helpers like Mirrormaker to enable quick iteration
7. Page cache can be used to avoid too much disk I/O

### Cons

1. High degree of learning curve to get things production ready
2. Complete set of monitoring tools are not built in. You have to use or buy other tools to do it for you
3. Incorporation of Kafka (or any event queue system) for microservices require a complete change in the Architecture of the application
4. Snapshots needs to be done in patch to improve performance
5. Eventually consistent, hence doing transactions in Kafka will be relatively difficult.

### Licence

Apache 2.0
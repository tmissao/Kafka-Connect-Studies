# Kafka Connect - Studies

This project intends to summarize all the knowledge earned during my studies of Kafka Connect

It can be divided into the following sections:

- [Introduction](./00-Introduction.md)
- [Kafka Connect Source](./01-KafkaConnectSource.md)
- [Extracting data from Database with Debezium](./02-KafkaConnectSourceDebezium.md)
- [Moving data to ElasticSearch](./03-KafkaConnectSinkElasticsearch.md)
- [Moving data to MongoDB](./04-KafkaConnectSinkMongoDB.md)
- [Monving data to Postgres Using JDBC Connector](/05-KafkaConnectSinkJDBC.md)
- [Monving data to Azure Blob Connector](/06-KafkaConnectSinkAzureBlob.md)
- [Kafka Connect with Azure Eventhub](./07-KafkaConnectAzureEventhub.md)
- [MSK + Kafka Connect on K8s](./08-MSKKafkaConnectKubernetes.md)

## Results
The goal of this study is to extract data from a datasource using kafka source connector, moving it to kafka, and then push this data to another datasource using kafka sink connector

![Goal](./artifacts/pictures/00-Goal.png)


## References

- [Kafka Connect Course](https://www.udemy.com/course/kafka-connect)
- [Confluent Connectors](https://www.confluent.io/hub/)
- [Configuring Connectors](https://kafka.apache.org/documentation.html#connect_configuring)
- [Landoop Include Connectors](https://github.com/lensesio/fast-data-dev#enable-additional-connectors)
- [Kafka Converters and Serialization](https://www.confluent.io/blog/kafka-connect-deep-dive-converters-serialization-explained/#json-schemas)
- [Kafka Transformation](https://www.confluent.io/blog/kafka-connect-single-message-transformation-tutorial-with-examples/)
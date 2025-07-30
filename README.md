# Kafka Examples

This repository contains small examples demonstrating Producer/Consumer API and Kafka Streams features.

## Producer API

### Producer

* `ProducingSimpleRecord` : Demonstrates how to use the Java Producer API to send record into Kafka.
* `ProducingRecordWithHeader` : Demonstrates how to add header to a record before sending it into Kafka. 

### Producer-Advanced

Complete example demonstrating how to implement a failover mechanism using the Callback interface in order to don't loss any record even in case of cluster failure.

### Producer-Interceptor

* `ProducerWithInterceptor` : Demonstrates how to implement a custom producer interceptor in order to track all records being sent.

### Producer Transactional

* `ProducerWithInterceptor` : Demonstrates how to implement a transactional producer.

## Consumer API

### Consumer-Interceptor

* `ConsumerWithInterceptor` : Demonstrates how to implement a custom consumer interceptor in order to track all records being fetched.

## Kafka Stream 

Work in progress!



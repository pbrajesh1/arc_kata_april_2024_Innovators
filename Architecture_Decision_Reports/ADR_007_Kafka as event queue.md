# Title: Use Kafka as event queue

## Status

APPROVED

## Context

We are developing an event-driven Microservice that requires high-throughput, low-latency, and reliable event processing. We need to choose a technology that can support these requirements and facilitate the communication between different components of our system.


## Decision

* We decide to use Kafka as an event queue for our system. 
* Kafka is a distributed streaming platform that enables us to publish, store, and consume events (or messages) in a scalable and fault-tolerant way. 
* Kafka uses a log-structured approach to store events in topics, which are partitioned and replicated across multiple brokers (or servers).


## Consequences

By using Kafka as an event queue for our system, we can expect to achieve several benefits, such as:
* We can handle large volumes of events with high throughput and low latency by leveraging the sequential and distributed nature of Kafka’s log. We can also tune the performance of our system by adjusting the configuration parameters of Kafka, such as batch size, compression, retention, etc.
* We can ensure the reliability and availability of our system by taking advantage of Kafka’s replication and fault tolerance features.
However, we also need to be aware of some challenges or trade-offs that we may face by using Kafka as an event queue for our system, such as: 
* We need to have a good understanding of the concepts, principles, patterns, and best practices of event-driven architecture and streaming platforms. 
* We also need to be familiar with the various components, dependencies, configurations, and conventions of Kafka and the libraries we use. 
* We need to implement proper security and governance mechanisms for our system and data sources.

[Home Page](../README.md) | [ADR Home Page](../Architecture_Decision_Reports)
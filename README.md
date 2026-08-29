# Awesome-Streaming-Data-Platform

## Top Streaming Data Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Event Streaming, Kafka-Compatible Brokers, Real-Time Data Pipelines, Pub/Sub & Stream Processing Foundations*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Streaming Data Platforms**. These systems provide durable, high-throughput event streaming used for real-time analytics, microservices communication, change-data-capture, and data pipelines.



**Examples** include Confluent Cloud, Redpanda, Aiven for Kafka, WarpStream, StreamNative, Amazon MSK, Azure Event Hubs, Google Pub/Sub, Estuary, Upsolver, AutoMQ, Memphis.dev, and related offerings (the category leaders).



**Open-source emphasis**: Streaming is one of the strongest open-source domains. **Apache Kafka** remains the industry standard, with high-performance alternatives such as **Redpanda**, **Apache Pulsar**, and **NATS**. This section is heavily expanded with every major active project.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Confluent Cloud](https://www.confluent.io/)**  

  Fully managed data streaming platform built by the original creators of Apache Kafka, with cloud-native architecture, rich connectors, and enterprise features.



- **[Redpanda Cloud / Serverless](https://www.redpanda.com/)**  

  High-performance, Kafka-compatible streaming platform written in C++, known for simpler operations, low latency, and strong price-performance.



- **[Aiven for Apache Kafka](https://aiven.io/)**  

  Fully managed Kafka service with additional Aiven platform capabilities and multi-cloud support.



- **[WarpStream](https://www.warpstream.com/)**  

  Diskless, Kafka-protocol-compatible streaming platform built on object storage (S3, etc.), designed for lower cloud costs and simpler operations.



- **[StreamNative](https://streamnative.io/)**  

  Managed Apache Pulsar and Kafka-compatible offerings, including lakehouse-native streaming options.



- **[Amazon MSK (Managed Streaming for Apache Kafka)](https://aws.amazon.com/msk/)**  

  AWS-managed Kafka service with provisioned and serverless options tightly integrated into the AWS ecosystem.



- **[Azure Event Hubs](https://azure.microsoft.com/en-us/products/event-hubs)**  

  Fully managed, real-time data ingestion service with Kafka protocol support for Azure workloads.



- **[Google Cloud Pub/Sub](https://cloud.google.com/pubsub)**  

  Global, managed messaging and event ingestion service from Google Cloud.



- **[AutoMQ, Memphis.dev, Estuary, Upsolver, and others](https://www.automq.com/)**  

  Additional managed or specialized streaming platforms focusing on cost efficiency, simplicity, or specific integration patterns.



- **[Other managed Kafka & streaming services](https://www.confluent.io/)**  

  Offerings from Instaclustr, Upstash, Kafkaesque, and hyperscaler or specialist providers.



## Open-Source GitHub Projects



- **[Apache Kafka](https://github.com/apache/kafka)**  

  The foundational open-source distributed event streaming platform. Widely adopted for high-throughput, durable, ordered log-based messaging and the basis of most Kafka-compatible systems.



- **[Redpanda](https://github.com/redpanda-data/redpanda)**  

  Kafka-compatible streaming platform rewritten in C++ for higher performance and simpler operations. Source-available / open-source core with commercial offerings.



- **[Apache Pulsar](https://github.com/apache/pulsar)**  

  Cloud-native, multi-tenant distributed messaging and streaming platform with strong geo-replication, tiered storage, and compute (Functions) capabilities.



- **[NATS](https://github.com/nats-io/nats-server)**  

  High-performance, cloud-native messaging system (CNCF) excellent for microservices, edge, and simpler pub/sub or request-reply patterns. Supports JetStream for persistence.



- **[Strimzi](https://github.com/strimzi/strimzi-kafka-operator)**  

  Kubernetes operator that makes running Apache Kafka on Kubernetes straightforward, including topic and user management.



- **[AutoMQ and other Kafka forks / S3-native projects](https://github.com/search?q=kafka+S3+OR+diskless)**  

  Emerging open-source efforts exploring diskless or object-storage-native Kafka-compatible architectures.



### Additional Strong Open-Source Options



- **Kafka ecosystem**: Kafka Connect, Kafka Streams, MirrorMaker, Schema Registry alternatives, and the broader connector ecosystem.

- **Stream processing**: Apache Flink, Apache Spark Structured Streaming, Kafka Streams, and related engines that consume from streaming platforms.

- **Schema & governance**: Apicurio Registry, Confluent Schema Registry (open parts), and OpenAPI/AsyncAPI tools.

- **Observability**: Kafka UI projects, Cruise Control, and monitoring exporters for brokers and consumers.

- **Lightweight messaging**: Redis Streams, RabbitMQ, and other systems sometimes used alongside or instead of full streaming platforms.

- Kubernetes operators and Helm charts that simplify deployment of the above systems.



**Frameworks for building custom systems**:  

Most organizations start with **Apache Kafka** (self-managed or via Strimzi on Kubernetes) or a Kafka-compatible alternative such as **Redpanda**.  

Choose **Apache Pulsar** when multi-tenancy, geo-replication, or tiered storage are primary requirements.  

Use **NATS** for lighter-weight, cloud-native messaging and edge scenarios.  

Managed services (Confluent Cloud, Redpanda Cloud, MSK, Aiven, WarpStream, etc.) remove operational burden and often provide better elasticity and cost models for production workloads.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Streaming platforms are foundational infrastructure. Correct configuration of retention, replication, security (TLS, ACLs, encryption), and capacity planning is critical for reliability and cost control.

- Self-hosted open-source deployments require significant operational expertise, especially at scale. Managed services shift that responsibility to the provider.



---



**Made for data engineers, platform teams, and architects building real-time systems.**  

Let's keep the streaming ecosystem open, high-performance, and accessible.

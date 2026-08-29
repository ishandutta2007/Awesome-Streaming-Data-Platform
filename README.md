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

| Platform | Description | Starting Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Confluent Cloud](https://www.confluent.io/)** | Fully managed data streaming platform built by Kafka creators, featuring managed Flink, Schema Registry, and enterprise connectors. | **$0.14 / eCKU-hr** (Basic tier; 1st eCKU free) + $0.05/GB data in/out + $0.08/GB-mo storage | **30-Day Free Trial** with **$400 in free credits** across clusters, connectors, and Schema Registry (no credit card required) |
| **[Redpanda Cloud](https://www.redpanda.com/)** | High-performance, C++ Kafka-compatible engine with sub-millisecond latency, zero-JVM footprint, and built-in Data Transforms. | **$0.10 / cluster-hr** + **$0.045 / GB** ingress + **$0.04 / GB** egress + $0.09/GB-mo storage ($0.0015/partition-hr) | **30-Day Free Trial** with **$100 in free credits** ($300 credits via AWS Marketplace; no credit card required) |
| **[Aiven for Apache Kafka](https://aiven.io/)** | Fully managed Apache Kafka service across AWS, GCP, and Azure with Karapace Schema Registry, REST proxy, and built-in monitoring. | **$35 / month** ($0.048/hr) for Developer plan; **$75 / month** ($0.10/hr) for Startup plan | **Free Forever Plan**: 1 Kafka service, 250 KiB/s ingress & egress, up to 5 topics (max 2 partitions/topic), 3-day data retention; plus **30-Day Trial** with **$300 credits** |
| **[WarpStream](https://www.warpstream.com/)** | Diskless, Kafka-protocol streaming engine built directly on cloud object storage (S3/GCS/Azure Blob) to minimize cloud networking and disk costs. | **$0.010 / GiB** logical write throughput (first 50 TiB, steps down to $0.003/GiB); $0 cluster base fee | **$400 non-expiring trial credits** on sign-up (no credit card required; pay only underlying cloud S3/compute costs) |
| **[StreamNative Cloud](https://streamnative.io/)** | Enterprise cloud-native messaging and streaming powered by Apache Pulsar with native Kafka protocol compatibility (KoP) and Lakehouse streaming. | **$73 / month** (~$0.10/hr) for Serverless tier + $0.06/GB ingress/egress; BYOC plans from **$365 / month** | **30-Day Free Trial** with **$200 in free credits** for Serverless and BYOC testing (no credit card required) |
| **[Amazon MSK](https://aws.amazon.com/msk/)** | AWS-managed Kafka offering provisioned EC2-backed brokers or serverless autoscaling integrated deeply into AWS IAM and CloudWatch. | **$0.0456 / broker-hr** (`kafka.t3.small`, min 3 brokers = **$0.1368/hr** / ~$98.50/mo) + $0.10/GB-mo storage; Serverless at **$0.75 / cluster-hr** + $0.10/GB in + $0.05/GB out | **30-Day Free Trial via AWS Free Account**: **$200 in AWS credits** for new accounts (no standalone MSK free tier) |
| **[Azure Event Hubs](https://azure.microsoft.com/en-us/products/event-hubs)** | Fully managed, real-time data ingestion service supporting Kafka 1.0+ producer/consumer APIs and AMQP protocols. | **$0.015 / hour per Throughput Unit (TU)** (1 MB/s in, 2 MB/s out) + **$0.028 per million ingress events** (Basic); Standard tier at **$0.030 / hour / TU** | **100 free concurrent AMQP connections** per namespace; plus **30-Day Free Trial** with **$200 Azure credits** via Azure Free Account |
| **[Google Cloud Pub/Sub](https://cloud.google.com/pubsub)** | Global, fully managed messaging and stream ingestion service featuring automatic horizontal scaling and multi-zone durability. | **$40 per TiB** (~$0.04/GB) for throughput exceeding 10 GB; snapshot & retained message storage at **$0.27 / GB-month** (free first 24h) | **Free Forever Plan**: **10 GB message throughput per month** at $0 + 24-hour message retention storage; plus **90-Day Trial** with **$300 credits** on GCP |
| **[Upstash Kafka](https://upstash.com/)** | Serverless per-request Kafka service that scales to zero with pay-per-message billing, REST APIs, and Kafka wire protocol support. | **$0.20 per 100K messages** (single-zone) / **$0.60 per 100K messages** (multi-zone) + **$0.25 / GB storage** (pay-as-you-go cap at $360/mo) | **Free Forever Plan**: Up to **10,000 messages / day** and **256 MB max storage retention** (no credit card required) |
| **[Estuary Flow](https://estuary.dev/)** | Real-time streaming ETL and CDC pipeline platform with built-in real-time storage engine and managed connector ecosystem. | **$0.50 / GB** data moved + **$100 / month** per active connector (after initial connector allowance) | **Free Forever Plan**: Up to **10 GB / month data transfer** and **2 active connector instances**; plus **30-Day Free Trial** for Cloud plan |
| **[AutoMQ](https://www.automq.com/)** | Cloud-first Kafka alternative replacing local broker storage with S3/EBS to eliminate cross-AZ replication network costs. | **~$0.411 / hour** cluster fee + **$0.008–$0.02 / GiB** ingress + **$0.00275–$0.0067 / GiB** egress + S3 storage ($0.005–$0.01/GiB-mo) | **30-Day Free Trial** with full cluster quota on AutoMQ Cloud / AWS Marketplace (no credit card required) |
| **[Instaclustr for Apache Kafka](https://www.instaclustr.com/)** | Enterprise managed Apache Kafka service with SOC 2 compliance, automated operations, and SLA guarantees on AWS, GCP, and Azure. | **~$0.09 / node-hour** (~$65/node/month) management fee + underlying cloud provider compute and storage costs | **30-Day Free Trial** with full cluster management access on AWS/GCP/Azure |



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

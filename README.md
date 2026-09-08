# Awesome-Stream-Processing-Platform

## Top Stream Processing Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Real-Time Stream Processing, Streaming SQL, Event-Driven Pipelines, Materialized Views & Continuous Analytics*  

**Last updated: September 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Stream Processing**. These systems continuously ingest, transform, enrich, and serve data in motion — powering real-time analytics, event-driven applications, streaming ETL, and low-latency materialized views.



**Examples** include Confluent Cloud, Flink Cloud by Ververica, Decodable, Aiven for Apache Flink, Upsolver, RisingWave Cloud, Tinybird, Materialize Cloud, Estuary, and DeltaStream (the category leaders).



**Open-source emphasis**: Stream processing has one of the strongest open-source ecosystems in data infrastructure. **Apache Flink**, **Apache Kafka** (with Kafka Streams / ksqlDB), **RisingWave**, **Apache Pulsar**, and related projects form the foundation of most modern streaming architectures. This section is heavily expanded with every major active project.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Confluent Cloud](https://www.confluent.io/)**  

  Fully managed Apache Kafka platform with stream processing capabilities (including Flink and ksqlDB), connectors, governance, and enterprise features from the creators of Kafka.



- **[Flink Cloud by Ververica](https://www.ververica.com/)**  

  Managed Apache Flink service from the original Flink company, focused on production-grade stream processing and stateful computations.



- **[Decodable](https://www.decodable.co/)**  

  Modern managed Apache Flink platform emphasizing SQL-first development, simplicity, and pay-per-use compute for stream pipelines.



- **[Aiven for Apache Flink](https://aiven.io/)**  

  Managed Flink (and Kafka/Pulsar) offering from Aiven, providing open-source-compatible streaming infrastructure with operational simplicity.



- **[Upsolver](https://www.upsolver.com/)**  

  Cloud platform for building and managing streaming data pipelines and lakehouse-oriented transformations with a low-code/SQL approach.



- **[RisingWave Cloud](https://risingwave.com/)**  

  Managed service for the RisingWave streaming database, offering PostgreSQL-compatible streaming SQL and real-time materialized views.



- **[Tinybird](https://www.tinybird.co/)**  

  Real-time analytics platform built on ClickHouse that supports streaming ingestion and low-latency SQL over event data.



- **[Materialize Cloud](https://materialize.com/)**  

  Managed streaming database that maintains incrementally updated materialized views with strong consistency and PostgreSQL compatibility.



- **[Estuary, DeltaStream](https://estuary.dev/)**  

  Additional streaming and real-time data platforms focused on change data capture, continuous pipelines, and streaming SQL.



- **[Other managed streaming services](https://www.confluent.io/)**  

  Cloud offerings from AWS (Managed Flink / Kinesis), Google, Azure, and specialized vendors that provide hosted stream processing and event streaming.



## Open-Source GitHub Projects



- **[Apache Flink](https://github.com/apache/flink)**  

  The dominant open-source stream processing engine. Supports high-throughput, low-latency, stateful computations, complex event processing, and Flink SQL. Foundation of most commercial Flink services.



- **[Apache Kafka](https://github.com/apache/kafka)**  

  Foundational distributed event streaming platform. Combined with Kafka Streams or ksqlDB it enables powerful stream processing directly on Kafka topics.



- **[ksqlDB / Kafka Streams](https://github.com/confluentinc/ksql)**  

  Stream processing layer for Kafka that lets you build real-time applications and materialized views using SQL (ksqlDB) or the Kafka Streams library.



- **[RisingWave](https://github.com/risingwavelabs/risingwave)**  

  Fully open-source (Apache 2.0) streaming database written in Rust. PostgreSQL wire-compatible, designed for streaming SQL, real-time materialized views, and elastic scaling.



- **[Apache Pulsar](https://github.com/apache/pulsar)**  

  Cloud-native distributed messaging and streaming platform with strong multi-tenancy, geo-replication, and stream processing capabilities (via Pulsar Functions and related engines).



- **[Materialize](https://github.com/MaterializeInc/materialize)**  

  Source-available streaming database focused on incrementally maintained materialized views and strong consistency (Business Source License with eventual open-source conversion).



- **[Apache Spark Structured Streaming](https://github.com/apache/spark)**  

  Mature micro-batch and continuous processing engine within the Spark ecosystem, ideal when batch and streaming workloads share the same infrastructure.



- **[Redpanda](https://github.com/redpanda-data/redpanda)**  

  Kafka-compatible, high-performance streaming platform written in C++ that eliminates JVM overhead while remaining API-compatible with Kafka clients.



- **[Other streaming engines & SQL layers](https://github.com/search?q=stream+processing+OR+streaming+SQL+OR+Flink+OR+RisingWave)**  

  Projects such as Arroyo and community streaming SQL or CEP engines that complement the major platforms.



### Additional Strong Open-Source Options



- **Connectors & CDC**: Debezium, Kafka Connect, and native CDC implementations for databases.

- **State stores & checkpointing**: RocksDB-based and object-storage-backed state backends used by Flink and similar engines.

- **Observability**: Open-source metrics, tracing, and logging stacks tailored for streaming jobs.

- **Stream SQL & query layers**: Emerging projects that provide SQL interfaces over Kafka, Pulsar, or custom streams.

- **Lakehouse integration**: Tools that continuously write streaming results into Apache Iceberg, Delta Lake, or Hudi tables.

- Coordination and cluster management tools used to operate large Flink or Kafka deployments.



**Frameworks for building custom systems**:  

For general-purpose, large-scale stream processing, start with **Apache Flink**.  

For event streaming + lightweight processing, **Apache Kafka** + Kafka Streams / ksqlDB remains the industry standard.  

For SQL-first streaming databases with materialized views, evaluate **RisingWave** (fully open-source) or **Materialize**.  

**Apache Pulsar** and **Redpanda** offer strong alternatives or complements to Kafka.  

Managed services (Confluent, Ververica, Decodable, RisingWave Cloud, Materialize Cloud, etc.) reduce operational burden while building on these same open-source foundations. Many production architectures combine self-managed open-source engines with selective use of commercial cloud offerings.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Stream processing systems are often mission-critical for real-time applications and data products. Correctness, exactly-once semantics, state management, and failure recovery require careful design and testing.

- Open-source engines provide exceptional power and flexibility but demand operational expertise (cluster management, checkpointing, scaling, monitoring). Managed services trade some control for reduced operational load.



---



**Made for data engineers, streaming architects, real-time analytics teams, and platform builders.**  

Let's keep stream processing open, interoperable, and developer-friendly through strong open-source engines and standards.

<div align="center">  
  <a href="https://awesome.re"><img src="https://awesome.re/badge-flat.svg" alt="Awesome"></a>
  <h1> Edge Computing & Internet Of Things 🛜 </h1>
  <i> A qualitative compilation of production-ready edge computing projects with a focus on Edge-2-Cloud Data Engineering </i>
</div>

## _Table of Contents_

- [_Major IoT Clouds_](#iot-on-hyperscalers)
- [_Major Edge OSS Projects_](#major-edge-oss-projects)
- [_Edge Messaging_](#edge-messaging)
    - [Brokerless](#brokerless)
    - [Websockets](#websockets)
    - [MQTT](#mqtt)
    - [Industrial](#industrial)
- [_Message Serialization_](#message-serialization)
- [_Messaging & Data Streaming_](#messaging-and-data-streaming)
    - [Cloud Managed](#cloud-managed)
    - [On-Prem](#on-prem)
- [_Stream Processing_](#stream-processing)
    - [Cloud Managed](#cloud-managed-1)
    - [On-Prem](#on-prem-1)
- [_Databases_](#databases)
    - [Cloud Managed](#cloud-managed-2)
    - [Time Series Database](#time-series-database)
    - [Document Database (NoSQL)](#document-database-nosql)
    - [Persistent Key Value DB](#persistent-kv-db)
    - [Relational Database](#relational-database)
    - [In Memory Database](#in-memory-database)
- [_Batch Processing / Analytics_](#batch-processing--analytics)
- [_Industrial IoT with Kubernetes_](#industrial-iot-with-kubernetes)
    - [Kubernetes Distributions for Lightweight Edge](#kubernetes-distributions-for-edge)
    - [Kubernetes Networking](#kubernetes-networking)
    - [Multi-Cluster Networking](#multi-cluster-networking)
    - [Service Mesh](#service-mesh)
    - [Distributed Orchestration](#distributed-orchestration)
    - [Microservice Frameworks](#microservice-frameworks)
    - [Distributed Filesystem](#distributed-filesystem)
    - [FaaS](#faas)
---

### _Projects in the curated list are filtered based on the following conditions:_
* High Quality 
* Production Ready
* Well Documented
* Well Maintained
* Cloud Ready
* Scalable

---

# _IoT on Hyperscalers_
* [AWS IoT](https://aws.amazon.com/iot/) - Unlock your IoT data and accelerate business growth
* [Azure IoT Operations](https://azure.microsoft.com/en-us/products/iot-operations) - Build interoperable IoT solutions that transform physical operations at scale.

# _Major Edge OSS Projects_
* [Eclipse Ditto](https://github.com/eclipse/ditto) - the open-source project of Eclipse IoT that provides a ready-to-use functionality to manage the state of Digital Twins
* [Eclipse Hono](https://github.com/eclipse-hono/hono) - provides uniform (remote) service interfaces for connecting large numbers of IoT devices to a (cloud) back end. 
* [Akri](https://docs.akri.sh/) - Akri is a Kubernetes Resource Interface that lets you easily expose heterogeneous leaf devices
* [Akraino](https://www.lfedge.org/projects/akraino) - LF Edge is an umbrella organization that establishes an open, interoperable framework for edge computing
* [Shifu](https://shifu.dev/docs/guides/cases/connect-opcua/) - Shifu provides users with a transparent framework for full-scene device hosting and integrated software development




# _Edge Messaging_

### MQTT
* [HiveMQ](https://github.com/hivemq) - Enterprise MQTT Platform
* [Nats.io](https://nats.io/) - Connective Technology for Adaptive Edge & Distributed Systems
* [Mosquitto](https://github.com/eclipse/mosquitto) - An Open Source MQTT v3.1/v3.1.1 Broker.
* [VerneMQ](https://github.com/erlio/vernemq) - A distributed MQTT message broker.
* [Waterstream](https://waterstream.io/) - MQTT broker leveraging Apache Kafka as its own storage and distribution engine.
* [NanoMQ](https://github.com/nanomq/nanomq) - A light-weight and Blazing-fast MQTT Broker for IoT Edge platform.

### Industrial
* [Node CoAP](https://github.com/mcollina/node-coap) - A client and server library for CoAP modeled after the http module.
* [Rust CoAP](https://github.com/covertness/coap-rs) - A Constrained Application Protocol (CoAP) library implemented in Rust.
* [OPC-UA](https://opcfoundation.org/) - Interoperability standard for the secure and reliable exchange of data
* [ModBus](https://modbus.org/) - A data communications protocol for use with Modicon PLC's

### Brokerless
* [ZeroMQ Overview](https://zeromq.org/get-started/) - An open-source universal messaging library
* [NanoMSG](https://nanomsg.org/index.html) - a simple high-performance implementation of several "scalability protocols"
* [NNG](https://nng.nanomsg.org/) - nanomsg-next-generation -- light-weight brokerless messaging

### Websockets
* [uws](https://github.com/uNetworking/uWebSockets.js) - Tiny WebSockets (access to the C++ library, µWebSockets, via Node.js)
* [uWebsockets](https://github.com/uNetworking/uWebSockets.js) - is a lightweight and efficient MQTT broker designed to raise the bar for pub/sub performance.
* [Tungstenite WS](https://github.com/snapview/tungstenite-rs) - Lightweight stream-based WebSocket implementation for Rust.
* [Python Websockets](https://websockets.readthedocs.io/en/stable/) - A library for building WebSocket servers and clients in Python
* [Autobahn.ws](https://crossbar.io/autobahn/) - Open-source real-time framework for Web, Mobile & Internet of Things.
* [socket.io](https://socket.io/) - Bidirectional and low-latency communication for every platform


# _Message Serialization_
* [Apache Avro](https://avro.apache.org/docs/current/) - Apache Avro™ is a data serialization system
* [Apache Thrift](https://thrift.apache.org/) - scalable cross-language services development
* [CapNProto](https://capnproto.org/) - Apache Avro™ is a data serialization system.
* [JSON](https://www.json.org/json-en.html) - is a lightweight data-interchange format.
* [MessagePack](https://msgpack.org/index.html) - MessagePack is an efficient binary serialization format. 
* [CBOR](https://cbor.io/) - RFC 8949 Concise Binary Object Representation
* [FlatBuffers](https://google.github.io/flatbuffers/) - an efficient cross platform serialization library
* [Protocol Buffer](https://developers.google.com/protocol-buffers) - a language-neutral, platform-neutral extensible mechanism for serializing structured data



# _Messaging and Data Streaming_

### Cloud Managed
* [Azure Event Hub](https://azure.microsoft.com/en-us/products/event-hubs) - a fully managed, real-time data ingestion service that’s simple, trusted, and scalable
* [Azure Managed Kafka](https://azure.microsoft.com/en-us/products/hdinsight/) - Azure HDInsight, a customizable, enterprise-grade service for open-source analytics. 
* [Azure Queue Storage](https://azure.microsoft.com/nl-nl/products/storage/queues) -  a service for storing large numbers of messages
* [Azure Event Grid](https://learn.microsoft.com/en-us/azure/event-grid/overview) - a highly scalable, serverless event broker that you can use to integrate applications using events.
* [Confluent Cloud](https://www.confluent.io/confluent-cloud/) - Apache Kafka as a Service
* [AWS MSK](https://aws.amazon.com/msk/) - Securely stream data with a fully managed, highly available Apache Kafka service
* [AWS SQS](https://aws.amazon.com/sqs/) - Fully managed message queuing for microservices, distributed systems, and serverless applications
* [AWS Kinesis](https://aws.amazon.com/kinesis/data-streams/) - Easily stream data at any scale

### On-Prem
* [Strimzi](https://strimzi.io/) - Cloud Native Apache Kafka
* [Apache Pulsar](https://github.com/apache/pulsar) - a distributed pub-sub messaging platform with a very flexible messaging model and an intuitive client API.
* [Apache Kafka](http://kafka.apache.org/) - distributed publish-subscribe messaging system.
* [Apache NiFi](https://nifi.apache.org/) - Apache NiFi is an integrated data logistics platform for automating the movement of data between disparate systems.
* [redpanda](https://vectorized.io/redpanda) - A Kafka® replacement for mission critical systems; 10x faster. Written in C++.
* [Fluentd](http://www.fluentd.org) - tool to collect events and logs.
* [Kestrel](https://github.com/papertrail/kestrel) - distributed message queue system.
* [Apache ActiveMQ Artemis](https://activemq.apache.org/components/artemis/) - The Next Generation Message Broker by ActiveMQ, AMQP 1.0 is a natively supported protocol.
* [Apache Qpid Java Broker](http://qpid.apache.org/components/java-broker/) - A pure-Java AMQP message broker.
* [Solace](http://dev.solace.com/tech/amqp/) - Messaging Platform that supports AMQP 1.0
* [RabbitMQ](https://www.rabbitmq.com) with [AMQP 1.0 plugin](https://github.com/rabbitmq/rabbitmq-amqp1.0).



# _Stream Processing_

### Cloud Managed
* [AWS Kinesis Data Analytics](https://aws.amazon.com/kinesis/data-analytics/) - Gain actionable insights from streaming data with serverless, fully managed Apache Flink
* [Azure Stream Analytics](https://azure.microsoft.com/en-us/services/stream-analytics/) - Serverless real-time analytics, from the cloud to the edge
* [KSQL DB](https://ksqldb.io/) - KSQL DB on Confluent Cloud

### On-Prem
* [Faust](https://github.com/robinhood/faust) - stream processing and event processing in Python
* [Siddhi](https://github.com/siddhi-io/siddhi) - stream Processing and Complex Event Processing Engine
* [KSQL](https://github.com/confluentinc/ksql) - The database purpose-built for stream processing applications.
* [Benthos](https://github.com/Jeffail/benthos) - Declarative stream processing for mundane tasks and data engineering
* [Go Streams](https://github.com/reugn/go-streams) - A lightweight stream processing library for Go
* [Flogo](https://github.com/project-flogo/stream) - Elegant stream processing pipeline written entirely in Golang
* [Apache Heron](https://github.com/apache/incubator-heron) - A realtime, distributed, fault-tolerant stream processing engine
* [Apache Beam](https://beam.apache.org/) - Implement batch and streaming data processing jobs that run on any execution engine.
* [Apache Flink](https://flink.apache.org/) - Stateful Computations over Data Streams
* [Apache Samza](https://samza.apache.org/) - A distributed stream processing framework

# _Batch Processing / Analytics_
* [Databricks](https://databricks.com/) - All your data, analytics and AI on one Lakehouse platform
* [Apache Mahout](https://mahout.apache.org/) - For Creating Scalable Performant Machine Learning Applications
* [H2O](https://www.h2o.ai/products/h2o/) - The #1 open-source machine learning platform for the enterprise
* [Apache Drill](https://drill.apache.org/) - Schema-free SQL Query Engine for Hadoop, NoSQL and Cloud Storage.
* [Apache Spark](https://spark.apache.org/) - Apache Spark™ is a unified analytics engine for large-scale data processing.



# _Databases_

## Cloud Managed
* [Azure SQL](https://azure.microsoft.com/en-us/products/azure-sql/database/) - Build apps that scale with managed and intelligent SQL in the cloud
* [Azure CosmosDB](https://azure.microsoft.com/en-us/services/cosmos-db/) - Fast NoSQL / Graph / Relational database with open APIs for planet scale
* [Azure PostgreSQL](https://azure.microsoft.com/en-us/services/postgresql/) - Fully managed, intelligent, and scalable PostgreSQL
* [Azure Data Explorer](https://azure.microsoft.com/en-us/products/data-explorer/) - Fast and highly scalable data exploration service.
* [AWS Aurora]() - AWS Relational DB
* [AWS DynamoDB]() -  fast, flexible, and serverless NoSQL database for any scale
* [AWS DocumentDB]() - Scale JSON workloads with ease using a MongoDB-compatible document database
* [AWS Keyspaces]() - Run your Apache Cassandra workloads on a scalable, highly available, and managed wide column database service.
* [AWS Neptune]() - Build applications that work with highly connected datasets using a fast, reliable graph database service.
* [AWS Ledger]() - Provide transparent, immutable, cryptographically verifiable transaction logs with a fully managed ledger database service.
* [AWS Timestream]() - Provide transparent, immutable, cryptographically verifiable transaction logs with a fully managed ledger database service.

## On-Prem

### Time Series Database
* [InfluxDB](https://github.com/influxdata/influxdb) - Scalable datastore for metrics, events, and real-time analytics
* [TimescaleDB](http://www.timescale.com/) - An open-source time-series database optimized for fast ingest and complex queries
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) - fast, cost-effective monitoring solution and time series database
* [Cortex](https://github.com/cortexproject/cortex) - A horizontally scalable, highly available, multi-tenant, long term Prometheus.

### Document Database (NoSQL)
* [Crate Data](https://crate.io/) - is an open source massively scalable data store. It requires zero administration.
* [MongoDB](https://www.mongodb.com/) - Document-oriented database system.
* [RavenDB](https://ravendb.net/) - A transactional, open-source Document Database.
* [RethinkDB](https://rethinkdb.com/) - document database that supports queries like table joins and group by.
* [Couchbase](https://www.couchbase.com/) - The Modern Database for Enterprise Applications
* [Apache Cassandra](https://cassandra.apache.org/_/index.html) - Manage massive amounts of data, fast, without losing sleep

### Persistent KV DB
* [TiKV](https://tikv.org/) - a highly scalable, low latency, and easy to use key-value database.
* [BadgerDB](https://dgraph.io/blog/post/badger/) - an embeddable, persistent and fast key-value (KV) database written in pure Go
* [FoundationDB](https://foundationdb.com/) - scalable distributed database
* [RocksDB](http://rocksdb.org/) - embeddable persistent key-value store for fast storage based on LevelDB.

### Relational Database
* [Citus](https://github.com/citusdata/citus) - Distributed PostgreSQL
* [Cockroach](https://github.com/cockroachdb/cockroach) - Scalable, Geo-Replicated, Transactional Datastore.
* [TiDB](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database
* [yugabyteDB](https://github.com/YugaByte/yugabyte-db) - open source, high-performance, distributed SQL database compatible with PostgreSQL
* [MariaDB](https://mariadb.org/) - enhanced, drop-in replacement for MySQL
* [Apache Calcite](https://calcite.apache.org/) - the foundation for your next high-performance database
* [Vitess](https://vitess.io/) - A database clustering system for horizontal scaling of MySQL

### In Memory Database
* [VoltDB](https://www.voltdb.com/) - claims to be fastest in-memory database.
* [BerkeleyDB](https://www.oracle.com/database/berkeley-db/index.html) - a software library that provides a high-performance embedded database for key/value data.
* [LevelDB](https://github.com/google/leveldb) - a fast key-value storage library written at Google that provides an ordered mapping from string keys to string values.
* [Memcached](https://www.memcached.org/) - high-performance, distributed memory object caching system


# _Industrial IoT with Kubernetes_

### Kubernetes Hybrid
* [Azure Arc](https://learn.microsoft.com/en-us/azure/azure-arc/overview) - Azure Arc simplifies governance and management by delivering a consistent multicloud and on-premises management platform.
* [EKS Anywhere](https://aws.amazon.com/eks/eks-anywhere/) - Create and operate Kubernetes clusters on your own infrastructure

### Kubernetes Distributions for Edge
* [AKS Edge](https://github.com/Azure/AKS-Edge) - AKS Edge Essentials is an on-premises Kubernetes implementation running containers at scale
* [K3s](https://k3s.io/) - The certified Kubernetes distribution built for IoT & Edge computing
* [microk8s](https://microk8s.io/) - The best Kubernetes experience for developers, DevOps, cloud and edge

### Kubernetes Networking
* [Cilium](https://cilium.io/) - eBPF-based Networking, Observability, and Security
* [Calico](https://www.tigera.io/project-calico/) - most widely adopted solution for Kubernetes networking and security
* [Flannel](https://github.com/flannel-io/flannel#flannel) - Flannel is a simple and easy way to configure a layer 3 network fabric
* [Antrea](https://github.com/antrea-io/antrea) - Kubernetes networking based on Open vSwitch
* [KubeEdge](https://kubeedge.io/en/) - An open platform to enable Edge computing
* [Kube Router](https://www.kube-router.io/) - networking solution built for operational simplicity and performance.

### Multi-Cluster Networking
* [Liqo](https://liqo.io/) - P2P, Seamless, Dynamic and Secure Resource Sharing
* [Admiralty](https://admiralty.io/) - The simplest way to deploy applications to multiple Kubernetes clusters.
* [Submariner](https://submariner.io/) - direct networking between Pods and Services in different Kubernetes clusters
* [Skupper](https://skupper.io/) - Skupper Multicloud communication for Kubernetes

### Service Mesh
* [Istio](https://istio.io/latest/) - the leading multi-cluster service mesh
* [Linkerd](https://linkerd.io/) - multi-cluster services with security, observability, and reliability
* [Consul](https://www.consul.io/) - Service Mesh for any runtime or cloud
* [Traefik Mesh](https://traefik.io/traefik-mesh/) - Traefik Mesh is a straight-forward, easy to configure, and non-invasive service mesh
* [Kuma](https://kuma.io/) - The universal Envoy service mesh for distributed service connectivity
* [Istio](https://istio.io/latest/) - the leading service mesh

### Distributed Orchestration
* [Serf](https://www.serf.io/) - decentralized solution for service discovery and orchestration
* [etcd](https://etcd.io/) - a distributed, reliable key-value store for the most critical data of a distributed system

### Microservice Frameworks
* [Lightbend Akka](http://akka.io/) - runtime for distributed, and fault tolerant event-driven applications on the JVM.
* [Lightbend Lagom](https://www.lagomframework.com/) -  opinionated microservices framework
* [GoKit](https://gokit.io/) - A toolkit for microservices
* [Goa](https://goa.design/) - Goa provides a holistic approach for developing remote APIs and microservices in Go.
* [Micro](https://micro.mu/) - Micro is a cloud platform for API development
* [Dapr](https://dapr.io/) - Dapr is a portable, event-driven, runtime for building distributed applications across cloud and edge.

### Distributed Filesystem
* [Rook](https://rook.io/) - Open-Source, Cloud-Native Storage for Kubernetes
* [Minio](https://min.io/) - Object Storage for the Era of the Hybrid Cloud
* [Longhorn](https://longhorn.io/) - Cloud native distributed block storage for Kubernetes
* [OpenEBS](https://openebs.io/) - OpenEBS builds on Kubernetes to enable Stateful applications to easily access Persistent Volumes

### FaaS
* [Serverless](https://www.serverless.com/) - zero-friction serverless development
* [Apache Camel](https://camel.apache.org/) - easily integrate various systems consuming or producing data.
* [Apache Openwhisk](https://openwhisk.apache.org/) - Open Source Serverless Cloud Platform
* [Fission](https://fission.io/) - Open source, Kubernetes-native Serverless Framework
* [KNative](https://github.com/knative/docs/) - Serverless Kubernetes functions
* [Kubeless](https://kubeless.io/) - The Kubernetes Native Serverless Framework
* [Kyma](https://kyma-project.io/) - Extend your applications with Kubernetes
* [Nuclio](https://nuclio.io/) - High-Performance Serverless event and data processing platform

<div align="center">  
  <a href="https://awesome.re"><img src="https://awesome.re/badge-flat.svg" alt="Awesome"></a>
  <h1> Edge Computing & Internet Of Things </h1>
  <i> A qualitative compilation of production-ready edge computing projects with a focus on IoT based Data Engineering </i>
</div>

## _Table of Contents_

- [_High-Level Programming Languages_](#high-level-programming-languages)
- [_Major IoT Clouds_](#major-iot-clouds)
- [_Major Edge Projects_](#major-edge-projects)
- [_Provisioning_](#provisioning)
    - [Infrastructure](#infrastructure)
    - [Kubernetes Networking](#kubernetes-networking)
    - [Multi-Cluster Networking](#multi-cluster-networking)
    - [Service Mesh](#service-mesh)
    - [Kubernetes Distributions](#kubernetes-distributions)
    - [Job Scheduling](#job-scheduling)
    - [Serverless Functions](#serverless-functions)
- [_Messaging Protocols_](#messaging-protocols)
    - [Brokerless](#brokerless)
    - [Websockets](#websockets)
    - [MQTT](#mqtt)
    - [CoAP](#coap)
    - [Other](#other)
- [_Message Serialization_](#message-serialization)
- [_Messaging Brokers_](#messaging-brokers)
    - [Cloud](#cloud)
    - [On-Prem](#on-prem)
- [_Data Storage_](#data-storage)
    - [Distributed Filesystems (Object Store)](#distributed-filesystems-object-store)
    - [Time Series Database](#time-series-database)
    - [Document Database (NoSQL)](#document-database-nosql)
    - [Persistent Key Value Storage](#persistent-kv-storage)
    - [Relational Database](#relational-database)
    - [In Memory Database](#in-memory-database)
    - [Cloud (Native) Database](#cloud-native-database)
- [_Stream Processing_](#stream-processing)
    - [Cloud](#cloud-1)
    - [On-Prem](#on-prem-1)
- [_Batch Processing / Analytics_](#batch-processing--analytics)
- [_Microservices_](#microservices)
    - [Frameworks](#frameworks)
    - [Distributed Orchestration](#distributed-orchestration)

---

### _Projects in the curated list are filtered based on the following conditions:_
* High Quality 
* Production Ready
* Well Documented
* Well Maintained
* Cloud Ready
* Scalable


---

# _High-Level Programming Languages_
<div align="center">  
  <a href="https://www.python.org" target="_blank"><img align="center" alt="Python" height ="80px" src="https://github.com/yarncraft/yarncraft/raw/main/python.svg"></a>
  <a href="https://www.typescriptlang.org/" target="_blank"><img align="center" alt="Typescript" height ="80px" src="https://github.com/yarncraft/yarncraft/raw/main/typescript.svg"></a>
    <a href="https://www.javascript.com/" target="_blank"><img align="center" alt="Javascript" height ="80px" src="https://github.com/yarncraft/yarncraft/raw/main/javascript.svg"></a>
  <a href="https://www.rust-lang.org/" target="_blank"><img align="center" alt="Rust" width ="80px" src="https://github.com/yarncraft/yarncraft/raw/main/Rust.svg"></a>
   <a href="https://golang.org/" target="_blank"><img align="center" alt="Golang" height ="80px" src="https://github.com/yarncraft/yarncraft/raw/main/go.svg"></a>
   <a href="https://www.scala-lang.org/" target="_blank"><img align="center" alt="Scala" height ="80px" src="https://github.com/yarncraft/yarncraft/raw/main/scala.svg"></a>
</div>

# _Major IoT Clouds_
* [Google Cloud IoT](https://cloud.google.com/solutions/iot/) - Google Cloud Platform IoT solutions.
* [IBM Watson](http://www.ibm.com/watson/) - IBM cloud for the IoT.
* [AWS IoT](https://aws.amazon.com/iot/) - Amazon cloud for the IoT.
* [Oracle IoT Cloud](https://cloud.oracle.com/iot) - ORACLE Cloud for the Internet of Things.
* [Azure IoT Hub](https://azure.microsoft.com/en-us/services/iot-hub/) - Microsoft cloud for the IoT.
* [Bosch IoT Suite](https://developer.bosch-iot-suite.com/capabilities-bosch-iot-suite/) - Highly scalable cloud infrastructure based on Cloud Foundry.
* [SAP HANA](https://saphanajourney.com/) - SAP cloud for the Internet of Things.

# _Major Edge Projects_
* [Akraino](https://www.lfedge.org/projects/akraino) - a set of open infrastructures and application blueprints for the edge
* [Edge Foundry](https://www.lfedge.org/projects/edgexfoundry/) - The Preferred Edge PnP IoT Platform
* [Eve OS](https://www.lfedge.org/projects/eve/) - a universal, open Linux-based operating system for distributed edge computing
* [Fledge](https://www.lfedge.org/projects/fledge/) - industrial manufacturing solutions to accelerate Industrial 4.0 adoption.
* [Open Horizon](https://open-horizon.github.io/) - secure and robust containerized application management for IoT
* [Baetyl](https://baetyl.io/en/) - Baetyl, extend cloud computing, data and service seamlessly to edge devices
* [Secure Device Onboard](https://www.lfedge.org/projects/securedeviceonboard/) - An Automated “Zero-Touch” Onboarding Service
* [Eclipse Ditto](https://github.com/eclipse/ditto) is the open-source project of Eclipse IoT that provides a ready-to-use functionality to manage the state of Digital Twins.

# _Provisioning_

### Infrastructure
* [Kubernetes](https://kubernetes.io/) - a system for automating deployment, scaling, and management of containerized applications.
* [Hashicorp Nomad](https://www.nomadproject.io/) - Workload Orchestration made easy

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

### Kubernetes Distributions
* [K3s](https://k3s.io/) - The certified Kubernetes distribution built for IoT & Edge computing
* [K3OS](https://k3os.io/) - k3OS is purpose-built to simplify Kubernetes operations in low-resource computing environments
* [MicroK8s](https://microk8s.io/) - Low-ops, minimal production Kubernetes, for devs, cloud, clusters, workstations, Edge and IoT.
* [RKE](https://rancher.com/products/rke/) - RKE is a CNCF-certified Kubernetes distribution that runs entirely within Docker containers
* [Lokomotive](https://kinvolk.io/lokomotive-kubernetes/) - A self-hosted, security-centric and composable Kubernetes distribution
* [Kubesphere](https://kubesphere.io/) - The Kubernetes platform tailored for hybrid multicloud
* [K0S](https://k0sproject.io/) - k0s is a single binary all-inclusive Kubernetes distribution
* [openSUSE Kubic](https://kubic.opensuse.org/) - Certified Kubernetes distribution & container-related technologies built by the openSUSE community

### Job Scheduling
* [Apache Airflow](https://github.com/apache/incubator-airflow) - a platform to programmatically author, schedule and monitor workflows.
* [Armada](https://armadaproject.io/) - Armada is an application to achieve high throughput of run-to-completion jobs

### Serverless Functions
* [Serverless](https://www.serverless.com/) - zero-friction serverless development
* [Apache Camel](https://camel.apache.org/) - easily integrate various systems consuming or producing data.
* [Apache Openwhisk](https://openwhisk.apache.org/) - Open Source Serverless Cloud Platform
* [Fission](https://fission.io/) - Open source, Kubernetes-native Serverless Framework
* [KNative](https://github.com/knative/docs/) - Serverless Kubernetes functions
* [Kubeless](https://kubeless.io/) - The Kubernetes Native Serverless Framework
* [Kyma](https://kyma-project.io/) - Extend your applications with Kubernetes
* [Nuclio](https://nuclio.io/) - High-Performance Serverless event and data processing platform

# _Edge Messaging Protocols_

### Brokerless
* [ZeroMQ Overview](https://zeromq.org/get-started/) - An open-source universal messaging library
* [NanoMSG](https://nanomsg.org/index.html) - a simple high-performance implementation of several "scalability protocols"
* [NNG](https://nng.nanomsg.org/) - nanomsg-next-generation -- light-weight brokerless messaging
* [Mangos](https://github.com/nanomsg/mangos) - nanomsg-next-generation implemented in pure Go

### Websockets
* [Gorilla Websocket](https://github.com/gorilla/websocket) - WebSocket implementation for Go.
* [gotify/server](https://gotify.net/) - A simple server for sending and receiving messages in real-time per web socket.
* [Centrifuge](https://github.com/centrifugal/centrifuge) - Real-time messaging library for Go with scalability in mind.
* [deepstream.io](https://deepstream.io/) - Open realtime server a fast, secure and scalable realtime server for mobile, web & iot.
* [uws](https://github.com/uNetworking/uWebSockets.js) - Tiny WebSockets (access to the C++ library, µWebSockets, via Node.js)
* [netflux](https://coast-team.github.io/netflux/) - JavaScript client and server side transport API based on WebRTC & WebSocket
* [uWebsockets](https://github.com/uNetworking/uWebSockets.js) - is a lightweight and efficient MQTT broker designed to raise the bar for pub/sub performance.
* [Tungstenite WS](https://github.com/snapview/tungstenite-rs) - Lightweight stream-based WebSocket implementation for Rust.
* [Python Websockets](https://websockets.readthedocs.io/en/stable/) - A library for building WebSocket servers and clients in Python with a focus on correctness and simplicity.
* [Autobahn.ws](http://autobahn.ws) - Open-source real-time framework for Web, Mobile & Internet of Things.

### MQTT
* [Mosquitto](https://github.com/eclipse/mosquitto) - An Open Source MQTT v3.1/v3.1.1 Broker.
* [VerneMQ](https://github.com/erlio/vernemq) - A distributed MQTT message broker.
* [Waterstream](https://waterstream.io/) - MQTT broker leveraging Apache Kafka as its own storage and distribution engine.
* [NanoMQ](https://github.com/nanomq/nanomq) - A light-weight and Blazing-fast MQTT Broker for IoT Edge platform.

### CoAP
* [Node CoAP](https://github.com/mcollina/node-coap) - A client and server library for CoAP modeled after the http module.
* [Rust CoAP](https://github.com/covertness/coap-rs) - A Constrained Application Protocol (CoAP) library implemented in Rust.

### AMQP
* [Apache ActiveMQ Artemis](https://activemq.apache.org/components/artemis/) - The Next Generation Message Broker by ActiveMQ, AMQP 1.0 is a natively supported protocol.
* [Apache Qpid Java Broker](http://qpid.apache.org/components/java-broker/) - A pure-Java AMQP message broker.
* [Solace](http://dev.solace.com/tech/amqp/) - Messaging Platform that supports AMQP 1.0
* [RabbitMQ](https://www.rabbitmq.com) with [AMQP 1.0 plugin](https://github.com/rabbitmq/rabbitmq-amqp1.0).

### Other
* [OPC-UA](https://opcfoundation.org/) - Interoperability standard for the secure and reliable exchange of data
* [ModBus](https://modbus.org/) - A data communications protocol for use with Modicon PLC's
* [Matrix](https://matrix.org/) - An open network for secure, decentralized communication

# _Message Serialization_
* [Apache Avro](https://avro.apache.org/docs/current/) - Apache Avro™ is a data serialization system
* [Apache Thrift](https://thrift.apache.org/) - scalable cross-language services development
* [CapNProto](https://capnproto.org/) - Apache Avro™ is a data serialization system.
* [JSON](https://www.json.org/json-en.html) - is a lightweight data-interchange format.
* [MessagePack](https://msgpack.org/index.html) - MessagePack is an efficient binary serialization format. 
* [CBOR](https://cbor.io/) - RFC 8949 Concise Binary Object Representation
* [FlatBuffers](https://google.github.io/flatbuffers/) - an efficient cross platform serialization library
* [Protocol Buffer](https://developers.google.com/protocol-buffers) - a language-neutral, platform-neutral extensible mechanism for serializing structured data

# _Messaging Brokers_

### Cloud
* [Confluent Cloud](https://www.confluent.io/confluent-cloud/) - Apache Kafka as a Service
* [EMQ X Cloud](https://cloud.emqx.io/) - IoT MQTT 5.0 cloud service for rapid deployment, easy management, and on-demand expansion.
* [Pubnub](https://www.pubnub.com/) - Data stream network

### On-Prem
* [Strimzi](https://strimzi.io/) - Cloud Native Apache Kafka
* [Apache Pulsar](https://github.com/apache/pulsar) - a distributed pub-sub messaging platform with a very flexible messaging model and an intuitive client API.
* [Apache Kafka](http://kafka.apache.org/) - distributed publish-subscribe messaging system.
* [Apache NiFi](https://nifi.apache.org/) - Apache NiFi is an integrated data logistics platform for automating the movement of data between disparate systems.
* [redpanda](https://vectorized.io/redpanda) - A Kafka® replacement for mission critical systems; 10x faster. Written in C++.
* [Fluentd](http://www.fluentd.org) - tool to collect events and logs.
* [Kestrel](https://github.com/papertrail/kestrel) - distributed message queue system.

# _Data Storage_

### Distributed Filesystems (Object Store)
* [Rook](https://rook.io/) - Open-Source, Cloud-Native Storage for Kubernetes
* [Minio](https://min.io/) - Object Storage for the Era of the Hybrid Cloud
* [Longhorn](https://longhorn.io/) - Cloud native distributed block storage for Kubernetes
* [OpenEBS](https://openebs.io/) - OpenEBS builds on Kubernetes to enable Stateful applications to easily access Persistent Volumes

### Time Series Database
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) - fast, cost-effective monitoring solution and time series database
* [Warp10](https://github.com/senx/warp10-platform) - The Most Advanced Time Series Platform
* [M3](https://github.com/m3db/m3) - Distributed TSDB, Aggregator and Query Engine, Prometheus Sidecar, Graphite Compatible, Metrics Platform
* [Thanos](https://github.com/thanos-io/thanos) - Highly available Prometheus setup with long term storage capabilities
* [Apache Pinot](https://github.com/apache/pinot) - A realtime distributed OLAP datastore
* [InfluxDB](https://github.com/influxdata/influxdb) - Scalable datastore for metrics, events, and real-time analytics
* [LinDB](https://github.com/lindb/lindb) - A scalable, high performance, high availability distributed time series database.
* [Clickhouse](https://github.com/ClickHouse/ClickHouse) - A column-oriented database management system that allows generating analytical data reports in real time.
* [Cortex](https://github.com/cortexproject/cortex) - A horizontally scalable, highly available, multi-tenant, long term Prometheus.
* [Timely](https://code.nsa.gov/timely/) - A secure time series database based on Accumulo and Grafana
* [Druid](https://github.com/druid-io/druid/) Column oriented distributed data store ideal for powering interactive applications
* [TimescaleDB](http://www.timescale.com/) - An open-source time-series database optimized for fast ingest and complex queries

### Document Database (NoSQL)
* [Crate Data](https://crate.io/) - is an open source massively scalable data store. It requires zero administration.
* [MongoDB](https://www.mongodb.com/) - Document-oriented database system.
* [RavenDB](https://ravendb.net/) - A transactional, open-source Document Database.
* [RethinkDB](https://rethinkdb.com/) - document database that supports queries like table joins and group by.
* [Couchbase](https://www.couchbase.com/) - The Modern Database for Enterprise Applications
* [Apache Cassandra](https://cassandra.apache.org/_/index.html) - Manage massive amounts of data, fast, without losing sleep

### Persistent KV Storage
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

### Cloud Managed Database
* [Google Spanner](https://research.google.com/archive/spanner.html) - globally distributed semi-relational database.
* [Google BigQuery](https://research.google.com/pubs/pub36632.html) - framework for interactive analysis, implementation of Dremel
* [Google Cloud SQL](https://cloud.google.com/sql/docs/) - MySQL databases in Google's cloud
* [Azure SQL](https://azure.microsoft.com/en-us/products/azure-sql/database/) - Build apps that scale with managed and intelligent SQL in the cloud
* [Azure CosmosDB](https://azure.microsoft.com/en-us/services/cosmos-db/) - Fast NoSQL database with open APIs for any scale
* [Azure PostgreSQL](https://azure.microsoft.com/en-us/services/postgresql/) - Fully managed, intelligent, and scalable PostgreSQL

# _Stream Processing_

### Cloud
* []() -
* []() -
* []() -
* []() -
* []() -
* []() -
* []() -
* []() -
* []() -


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
* [Firebolt](https://github.com/digitalocean/firebolt) -  streaming ETL, observability data pipeline, and event processing apps
* [eKuiper](https://github.com/lf-edge/ekuiper) - A lightweight IoT edge analytics software

# _Batch Processing / Analytics_
* [GCP DataProc](https://cloud.google.com/dataproc/) - Dataproc for data lake modernization, ETL, and secure data science, at planet scale
* [Databricks](https://databricks.com/) - All your data, analytics and AI on one Lakehouse platform
* [Apache Mahout](https://mahout.apache.org/) - For Creating Scalable Performant Machine Learning Applications
* [H2O](https://www.h2o.ai/products/h2o/) - The #1 open-source machine learning platform for the enterprise
* [Apache Drill](https://drill.apache.org/) - Schema-free SQL Query Engine for Hadoop, NoSQL and Cloud Storage.
* [Apache Spark](https://spark.apache.org/) - Apache Spark™ is a unified analytics engine for large-scale data processing.

# _Microservices_

### Frameworks
* [Lightbend Akka](http://akka.io/) - runtime for distributed, and fault tolerant event-driven applications on the JVM.
* [Lightbend Lagom](https://www.lagomframework.com/) -  opinionated microservices framework
* [GoKit](https://gokit.io/) - A toolkit for microservices
* [Goa](https://goa.design/) - Goa provides a holistic approach for developing remote APIs and microservices in Go.
* [Garden](https://garden.io/) - Garden is an automation platform for Kubernetes development and testing
* [Micro](https://micro.mu/) - Micro is a cloud platform for API development
* [Dapr](https://dapr.io/) - Dapr is a portable, event-driven, runtime for building distributed applications across cloud and edge.

### Distributed Orchestration
* [Serf](https://www.serf.io/) - decentralized solution for service discovery and orchestration
* [etcd](https://etcd.io/) - a distributed, reliable key-value store for the most critical data of a distributed system


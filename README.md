# awesome-kafka

This list is for anyone wishing to learn about [Apache Kafka](http://kafka.apache.org/), but do not have a starting point.

You can help by sending Pull Requests to add more information.

If you're not inclined to make PRs, you can tweet me at `@infoslack`

# Table of Contents

- [Articles](#articles)
- [Books](#books)
- [Online Courses](#courses)
- [Papers](#papers)
- [Presentations](#presentations)
- [Talks](#talks)
- [Tools](#tools)
- [Docker Compose](#docker-compose)

## Articles

- [http://blog.cloudera.com/blog/2014/09/apache-kafka-for-beginners/](https://web.archive.org/web/20190212174120/https://blog.cloudera.com/blog/2014/09/apache-kafka-for-beginners/) - Apache Kafka for Beginners
- http://sysadvent.blogspot.com.br/2014/12/day-4-introduction-to-kafka.html - Introduction to Kafka
- https://medium.com/@ruurtjan/understanding-kafka-with-factorio-74e8fc9bf181 - Understanding Kafka with Factorio
- http://www.confluent.io/blog/introducing-kafka-streams-stream-processing-made-simple - Introducing Kafka Streams: Stream Processing Made Simple
- https://medium.com/swlh/apache-kafka-in-a-nutshell-5782b01d9ffb - Apache Kafka in a Nutshell
- http://www.confluent.io/blog/apache-kafka-samza-and-the-unix-philosophy-of-distributed-data - Apache Kafka, Samza, and the Unix Philosophy of Distributed Data
- http://www.confluent.io/blog/using-logs-to-build-a-solid-data-infrastructure-or-why-dual-writes-are-a-bad-idea/ - Using logs to build a solid data infrastructure (or: why dual writes are a bad idea)
- http://www.confluent.io/blog/bottled-water-real-time-integration-of-postgresql-and-kafka/ - Bottled Water: Real-time integration of PostgreSQL and Kafka
- http://www.confluent.io/blog/deploying-apache-kafka-on-aws-elastic-block-store-ebs - Deploying Apache Kafka on AWS Elastic Block Store (EBS)
- http://www.confluent.io/blog/how-we-monitor-and-run-kafka-at-scale-signalfx - How We Monitor and Run Kafka At Scale
- https://www.datadoghq.com/blog/monitoring-kafka-performance-metrics/ - Monitoring Kafka performance metrics
- http://oobaloo.co.uk/kafka-for-uswitchs-event-pipeline - Kafka for uSwitch's Event Pipeline
- [http://blog.infochimps.com/2012/10/30/next-gen-real-time-streaming-storm-kafka-integration/](https://web.archive.org/web/20160321163106/http://blog.infochimps.com/2012/10/30/next-gen-real-time-streaming-storm-kafka-integration/) - Next Gen Real-time Streaming with Storm-Kafka Integration
- https://medium.com/netflix-techblog/search?q=kafka - all netflix tech blog kafka tagged articles
- https://engineering.linkedin.com/blog/topic/kafka - all linked in tech blog kafka tagged articlesEEEEE
- https://medium.com/@stephane.maarek/how-to-use-apache-kafka-to-transform-a-batch-pipeline-into-a-real-time-one-831b48a6ad85 - How to use Apache Kafka to transform a batch pipeline into a real-time one
- https://dev.to/barryosull/event-sourcing-what-it-is-and-why-its-awesome - Event Sourcing: What it is and why it's awesome
- https://www.confluent.io/blog/getting-started-with-rust-and-kafka - Using Kafka with Rust
- https://medium.com/@gayathrisiva8608/apache-kafka-is-a-distributed-streaming-system-that-can-publish-and-subscribe-a-stream-of-records-12af92e2d491 - Apache Kafka-Intro
- https://www.loginradius.com/engineering/blog/stream-processing-using-kafka/ - Introduction to Stream Processing using Kafka Streams
- https://jaehyeon.me/blog/2022-03-07-schema-registry-part1/ - Use External Schema Registry With MSK Connect – Part 1 Local Development
- https://jaehyeon.me/blog/2022-04-03-schema-registry-part2/ - Use External Schema Registry With MSK Connect – Part 2 MSK Deployment
- https://jaehyeon.me/blog/2023-01-10-kafka-consumer-seek-offsets/ - How to Configure Kafka Consumers to Seek Offsets by Timestamp
- https://jaehyeon.me/blog/2023-02-08-simplify-streaming-ingestion-redshift/ - Simplify Streaming Ingestion on AWS – Part 1 MSK and Redshift
- https://jaehyeon.me/blog/2023-03-14-simplify-streaming-ingestion-athena/ - Simplify Streaming Ingestion on AWS – Part 2 MSK and Athena
- https://jaehyeon.me/blog/2023-04-12-integrate-glue-schema-registry/ - Integrate Glue Schema Registry With Your Python Kafka App
- https://jaehyeon.me/blog/2021-12-05-datalake-demo-part1/ - Data Lake Demo Using Change Data Capture (CDC) on AWS – Part 1 Local Development
- https://jaehyeon.me/blog/2021-12-12-datalake-demo-part2/ - Data Lake Demo Using Change Data Capture (CDC) on AWS – Part 2 Implement CDC
- https://jaehyeon.me/blog/2021-12-19-datalake-demo-part3/ - Data Lake Demo Using Change Data Capture (CDC) on AWS – Part 3 Implement Data Lake
- <details>
    <summary>https://jaehyeon.me/blog/2023-05-04-kafka-development-with-docker-part-1 - Kafka Development with Docker Series</summary>
  
    * https://jaehyeon.me/blog/2023-05-04-kafka-development-with-docker-part-1/ - Part 1 Cluster Setup
    * https://jaehyeon.me/blog/2023-05-18-kafka-development-with-docker-part-2/ - Part 2 Management App
    * https://jaehyeon.me/blog/2023-05-25-kafka-development-with-docker-part-3/ - Part 3 Kafka Connect
    * https://jaehyeon.me/blog/2023-06-01-kafka-development-with-docker-part-4/ - Part 4 Producer and Consumer
    * https://jaehyeon.me/blog/2023-06-08-kafka-development-with-docker-part-5/ - Part 5 Glue Schema Registry
    * https://jaehyeon.me/blog/2023-06-15-kafka-development-with-docker-part-6/ - Part 6 Kafka Connect with Glue Schema Registry
    * https://jaehyeon.me/blog/2023-06-22-kafka-development-with-docker-part-7/ - Part 7 Producer and Consumer with Glue Schema Registry
    * https://jaehyeon.me/blog/2023-06-29-kafka-development-with-docker-part-8/ - Part 8 SSL Encryption
    * https://jaehyeon.me/blog/2023-07-06-kafka-development-with-docker-part-9/ - Part 9 SSL Authentication
    * https://jaehyeon.me/blog/2023-07-13-kafka-development-with-docker-part-10/ - Part 10 SASL Authentication
    * https://jaehyeon.me/blog/2023-07-20-kafka-development-with-docker-part-11/ - Part 11 Kafka Authorization

  </details>

## Books

- http://www.confluent.io/making-sense-of-stream-processing-ebook - Making sense of stream processing
- http://shop.oreilly.com/product/0636920032175.do - Designing Data-Intensive Applications
- http://apachekafkabook.com/ - Effective Kafka - A Hands-On Guide to Building Robust and Scalable Event-Driven Applications
- https://www.confluent.io/wp-content/uploads/confluent-kafka-definitive-guide-complete.pdf - Kafka: The Definitive Guide
- https://www.manning.com/books/kafka-in-action - A fast-paced introduction to every aspect of working with Kafka you need to really reap its benefits.
- https://www.manning.com/books/kafka-streams-in-action - By the end of the book, you'll be ready to use Kafka Streams in your projects to reap the benefits of the insight your data holds quickly and easily.
- https://www.manning.com/books/kafka-streams-in-action-second-edition - The book that teaches you to implement stream processing within the Kafka platform.
- https://www.manning.com/books/streaming-data-pipelines-with-kafka - A book about building reliable data pipelines that can deliver real-time insights from your data.

## Courses

- [Udemy Apache Kafka Series - Learning Apache Kafka for Beginners](https://goo.gl/GaCKQN) - All Level
- [Udemy Apache Kafka Series - Kafka Connect Hands-on Learning](https://goo.gl/wLLLY9) - Intermediate
- [Udemy Apache Kafka Series - Kafka Streams for Data Processing](https://goo.gl/bro314) - Intermediate
- [Udemy Apache Kafka Series - Kafka Cluster Setup & Administration](https://goo.gl/1uYAuU) - Expert
- [Udemy Apache Kafka Series - Confluent Schema Registry & REST Proxy](https://goo.gl/XgWcVz) - Intermediate

## Papers

- http://www.vldb.org/pvldb/vol8/p1654-wang.pdf - Building a Replicated Logging System with Apache Kafka
- http://research.microsoft.com/en-us/um/people/srikanth/netdb11/netdb11papers/netdb11-final12.pdf - Kafka: a Distributed Messaging System for Log Processing
- http://sites.computer.org/debull/A12june/pipeline.pdf - Building LinkedIn’s Real-time Activity Data Pipeline
- https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying - The Log: What every software engineer should know about real-time data's unifying abstraction

## Presentations

- http://www.slideshare.net/charmalloc/developing-with-the-go-client-for-apache-kafka - Developing with the Go client for Apache Kafka
- http://www.slideshare.net/miguno/apache-kafka-08-basic-training-verisign - Apache Kafka 0.8 basic training - Verisign
- http://www.slideshare.net/charmalloc/developingwithapachekafka-29910685 - Developing Real-Time Data Pipelines with Apache Kafka
- http://www.slideshare.net/AmazonWebServices/infrastructure-at-scale-apache-kafka-twitter-storm-elastic-search-arc303-aws-reinvent-2013 - Infrastructure at Scale: Apache Kafka, Twitter Storm & Elastic Search (ARC303) | AWS re:Invent 2013
- http://www.slideshare.net/charmalloc/real-timestreamingdata-pipelinesapachekafka - Real-time streaming and data pipelines with Apache Kafka
- http://www.slideshare.net/Hadoop_Summit/building-a-realtime-data-pipeline-apache-kafka-at-linkedin - Building a Real-time Data Pipeline: Apache Kafka at LinkedIn
- http://www.slideshare.net/junrao/kafka-replication-apachecon2013 - Kafka replication apachecon_2013
- http://www.slideshare.net/mumrah/kafka-talk-tri-hug - Introduction and Overview of Apache Kafka

## Talks

- https://www.youtube.com/watch?v=qc33qMUvR7c - Introduction to Apache Kafka by Joe Stein
- https://www.youtube.com/watch?v=9RMOc0SwRro - Apache Kafka and the Next 700 Stream Processing Systems by Jay Kreps
- https://martin.kleppmann.com/2015/05/27/logs-for-data-infrastructure.html - Transcript of Martin Kleppmann (Linkedin) - Using Logs To Build a Solid Data Infrastructure
- https://www.youtube.com/watch?v=aJuo_bLSW6s - I ♥ Logs: Apache Kafka and Real-Time Data Integration
- https://www.youtube.com/watch?v=InAKDEk7H0M - Apache Kafka: Real-time Streaming and Data Pipelines with Apache Kafka by Joe Stein
- https://vimeo.com/63040812 - AJUG - Apache Kafka - Chris Curtin
- https://www.youtube.com/playlist?list=PLkz1SCf5iB4enAR00Z46JwY9GGkaS2NON - Getting started guide on Apache Kafka by Learning Journal
- https://youtu.be/qoeuufklgUE - the basics of what a KStream, KTable, and GlobalKTable

## Tools
- [Firehose](https://github.com/odpf/firehose) - Firehose is an extensible, no-code, and cloud-native service to load real-time streaming data from Kafka to data stores, data lakes, and analytical storage systems.
- [Dagger](https://github.com/odpf/dagger) - Dagger is an easy-to-use, SQL framework to process built on top of Apache Flink for stateful processing of Kafka data.
- [Raccoon](https://github.com/odpf/raccoon) - Raccoon is a high-throughput, low-latency service to collect events in real-time from your web, mobile apps, and services using multiple network protocols and publish to Kafka.
- [Stencil](https://github.com/odpf/stencil) - Stencil is a Protobuf schema registry for Kafka that enables you to create, maintain and consume protobuf messages and APIs dynamically, efficiently, and reliably.
- [Meteor](https://github.com/odpf/meteor) - Meteor is a scalable, easy-to-use, extensible metadata collection framework from the different cloud providers and on-prem sources and publish to Kafka.
- [Logit.io](https://logit.io/sources/configure/kafka) - Logit.io allows you to send logs and metrics from Kafka for centralised monitoring, alerting and analysis.
- [Zilla](https://github.com/aklivity/zilla) - An API gateway built for event-driven architectures and streaming that supports standard protocols such as HTTP, SSE, gRPC, MQTT, and the native Kafka protocol.

- https://github.com/Microsoft/Availability-Monitor-for-Kafka
- https://github.com/linkedin/Burrow
- https://github.com/splee/burrower
- https://github.com/yahoo/kafka-manager
- https://github.com/tchiotludo/kafkahq
- https://github.com/SourceLabOrg/kafka-webview
- http://www.kafkatool.com/
- https://github.com/kafka-ops/kafka-topology-builder Gitops and Automation for Apache Kafka
- [Strimzi](https://github.com/strimzi/strimzi-kafka-operator) Operator for deploying and running Apache Kafka on Kubernetes and OpenShift
- [kafkacat](https://github.com/edenhill/kafkacat) Generic CLI non-JVM Apache Kafka producer and consumer
- [connectctl](https://github.com/90poe/connectctl) Manage kafka connect connectors easily
- [Kafdrop](https://github.com/obsidiandynamics/kafdrop) Web UI for browsing Kafka topics and consumer groups
- [Kokpit](https://github.com/daneshzaki/kokpit) Basic Kafka client that does publish subscribe and runs as a Windows application
- [Strimzi Kafka CLI](https://github.com/systemcraftsman/strimzi-kafka-cli) A CLI for Strimzi Kafka Operator
- [Kowl](https://github.com/cloudhut/kowl) A modern Kafka WebUI written in Go & React
- [UI for Apache Kafka](https://github.com/provectus/kafka-ui) A modern Kafka WebUI written in Java & React
- [Franz](https://franz.defn.io) A native macOS GUI client for Kafka
- [TypeStream](https://github.com/typestreamio/typestream) Open Source streaming platform. Write and run typed data pipelines with a minimal, familiar syntax. 

## Docker Compose
- [Kafka Cluster Kraft Mode - DockerCompose](https://github.com/minhhungit/kafka-kraft-cluster-docker-compose) - Workable kafka cluster with kraft mode using docker-compose

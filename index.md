---
layout: default
---

## About

Staff Software Engineer and Tech Lead Manager at Uber, specializing in distributed systems and messaging platforms. Currently leading Uber's trip-critical Kafka Messaging platform, responsible for reliability, on-call outcomes, and roadmap execution. Passionate about building scalable infrastructure that powers mission-critical services.

Based in Belmont, CA | [find.qichao@gmail.com](mailto:find.qichao@gmail.com)

## Experience

**Staff Software Engineer, Tech Lead Manager (TLM)** | Uber, Kafka - Platform Engineering
*Dec 2020 - Present | Sunnyvale, CA*

Led Uber's trip-critical Kafka Messaging platform (Kafka Consumer Proxy/uForwarder, Kafka REST Proxy, uReplicator), accountable for reliability, on-call outcomes, and roadmap execution.

- Drove platform architecture: replication re-architecture, Flink-based ingestion, and AutoMQ/RBS adoption to improve durability and operational simplicity
- Cut consumer incident mitigation from ~3 hours to ~30 minutes by designing freshness-restore + automated failover/backfill workflows across KCP and replication pipelines
- Implemented and supporting: native/proxy clients, retryQ/DLQ, context propagation, zone isolation, workload rebalance, metadata storage (Zookeeper) and much more
- Owned uGroup (Kafka consumer monitoring) end-to-end
- ex-TLM of Kafka Control Plane, enhanced internal Kafka metadata management with cloud-like experience. Strengthened cross-region reliability through source-of-truth re-architecture

**Knowledge Platform Founding Member** | Uber
*Supporting Online Data AI transformation*

- Built efficient CPU-based embedding generation service for large-scale near realtime ingestion
- Built knowledge data intake (WebSocket push, API fetch, etc) service featuring OpenSearch indexing, LanceDB persistence, and taxonomy/ontology extraction

**Active Uber Ring0 First Responder**
Global incident responder / incident commander: coordinated cross-team mitigations including lockdowns and failovers during SEVs.

**Tech Lead** | Uber, Money - Core Services
*Nov 2018 - Dec 2020 | Amsterdam, The Netherlands*

Tech Lead of Collections & Cashouts team, moving money in and out of Uber for the areas of arrears collection and driver cashout, in a secure, efficient and scalable way.

- Led 3DS/SCA project, worked with 10+ teams and 10+ European banks to enable two-factor auth for credit card payment across 60+ payment flows in European Economic Area
- Integrated UberPay in arrears collection, instantly unlocking more payment service providers in different regions without repeated integration

**Software Engineer** | Uber, Identity - Security Engineering
*Jan 2018 - Nov 2018 | San Francisco, CA*

- Maintained Uber's 3rd party customer identity platform for OAuth and external provider integrations
- Implemented both backend and frontend changes for new Alipay-Uber integration
- Enabled Uber in Google Maps with new JWT-based 3rd-party integration

**Member of Technical Staff III** | VMware, Network & Security Business Unit
*Feb 2016 - Jan 2018 | Palo Alto, CA*

- Implemented CDO mode IPS mode cluster level API
- Enhanced NSX-V product security for FIPS certification, including upstream (Python) patches
- Implemented CLI and daemon to support Java profiling on NSX-T/V Controllers

**Software Engineer Intern** | Alibaba Group, Data Technology & Product Division
*May 2015 - Jul 2015 | Hangzhou, China*

- Built an Apache Storm and Apache Kafka based large scale realtime crawler, with peak performance of 10M pages/day

## Publications

1. [Introducing uGroup: Uber's Consumer Management Platform](https://uber.com/blog/introducing-ugroup-ubers-consumer-management-framework) - Uber Engineering Blog
2. [Kafka Async Queuing with Consumer Proxy](https://www.uber.com/blog/kafka-async-queuing-with-consumer-proxy/) - Uber Engineering Blog

## Education

**Master of Science in Electrical & Computer Engineering** | Georgia Institute of Technology
*Aug 2014 - Dec 2015 | Atlanta, GA*
GPA: 3.81/4

Research Assistant, Contributed to DoE ARPA-E with data collection application CommuteWarrior

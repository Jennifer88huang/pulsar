---
id: ecosystem-overview
title: Pulsar Ecosystem
sidebar_label: Pulsar Ecosystem
---

Apache Pulsar supports 
continues to evolve and is adopted by a broader user base, we noted the need for more integrations to facilitate the building of better streaming data pipelines and event-driven applications. We introduced the StreamNative Hub to provide a single experience for finding, downloading, using, storing, and sharing Pulsar related extensions, getting involved in data processing, logging, monitoring, authentication, deployment, and offering a broad spectrum of Pulsar integrations. Let’s take a look at some of the StreamNative Hub’s key components:

Connector: allows you to move streaming data in and out of Pulsar, which simplifies integration for enterprises bringing Pulsar into their existing infrastructure. All Pulsar built-in connectors are shipped in the StreamNative Hub.

Offloader: allows you to offload the majority of the data from BookKeeper to external remote storage, which provides a cheaper form of storage that readily scales with the volume of data. Pulsar is able to retain both historic and real-time data and provides a unified view as infinite event streams, which can be easily reprocessed or backloaded into new systems. Companies can integrate Pulsar with a unified data processing engine (such as Flink or Spark) to unlock new use cases stemming from infinite data retention. AWS S3, GCS, and filesystem offloaders are supported.

Protocol handler: allows you to support other messaging protocols natively and dynamically in Pulsar brokers on runtime, which streamlines operations with Pulsar’s enterprise-grade features without modifying code. Kafka, AMQP, and MQTT are supported.

With StreamNative Hub, whether you have already run on Pulsar and just want to use several plugins, or you are eager to try plugins that are out of the Pulsar community, you can use pre-built plugins directly and quickly and do not need to build plugins from sources. Additionally, by simplifying the installation process and reducing deployment time, the StreamNative Hub allows you to focus on how to maximize business value from living data in a more efficient manner. Now, you can get started in just a few clicks with intuitive website design and complete user guides.

plugins and integrations around the Pulsar ecosystem

We should highlight for StreamNative Hub is a centralized place for hosting third-part adapters and integrations. People can find third-party adapters in StreamNative Hub.


I’d suggest adding a “Protocol Handler” section to include KoP, AoP, and MoP documentation as well.

Add a Apache Flink in the “Adaptors” page. You can add the documentation for streamnative/pulsar-flink connector (highlighted that is the one being contributed to upstream Flink).
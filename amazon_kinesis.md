# Amazon Kinesis

## AWS Kinesis Overview

* Kinesis is a managed alternative to Apache Kafka.
* Great for applicaiton logs, metrics, Iot, clickstreams.
* Great for 'real-time' big data.
* Great for streaming processing frameworks (Spark, NiFi, etc)
* Data is automatically replicated synchronously to 3 AZ.
* Kinesis Streams: Low latency streaming ingest at scale
* Kinasys Analytics: Perform real-time analytics on streams using SQL.

_PUT_KINESIS_SLIDE_HERE_

## Kinesis Streams Overview

* Streams are didvided into ordered Shard / Partitions

_Image_Goes_Here_

* Data retention is 24 hours by defaults. Can go up to 7 days.
* Ability ti reprocess / replay data.
* Multiple applications can consume the same stream.
* Real-Time processing with scale of throughput.
* Once data is inserted in Kinesis, it cannot be deleted (immutability).

## Kinesis Streams Shards

## Kinesis Streams Records

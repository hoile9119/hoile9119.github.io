---
layout: default
title: Home
description: Streaming, Spark, and lakehouse notes from six years in fintech data engineering
---

# Data Engineering Notes

Working notes from building streaming and lakehouse systems in fintech — Flink and
Spark in production, Iceberg on object storage, and the platform work around them.

Written for my own recall first. Published because the good version of a note is
the one you had to make legible to someone else.

## Sections

| Section | What's in it |
|---|---|
| [Streaming]({{ site.baseurl }}/streaming/) | Flink on Kubernetes, latency engineering, Kafka, Structured Streaming |
| [Spark]({{ site.baseurl }}/spark/) | The engine — execution model, shuffle, memory, tuning. Batch *and* streaming. |
| [Lakehouse]({{ site.baseurl }}/lakehouse/) | Storage, table formats, catalogs, query engines |
| [Databricks]({{ site.baseurl }}/databricks/) | Notes from the Data Engineer Professional certification track |
| [Architecture]({{ site.baseurl }}/architecture/) | Patterns, feature stores, MLOps |
| [Platform]({{ site.baseurl }}/platform/) | Containers, Kubernetes, local LLMs, MCP servers |
| [Tools]({{ site.baseurl }}/tools/) | A spark-submit command generator |
| [About]({{ site.baseurl }}/about) | Who writes this |

## Start here

- [Table Formats]({{ site.baseurl }}/lakehouse/table-formats) — Iceberg internals end to end
- [PySpark Function Reference]({{ site.baseurl }}/spark/pyspark-functions) — the built-ins that replace a UDF
- [Spark Submit Generator]({{ site.baseurl }}/tools/spark-submit-generator/) — build a command from a form

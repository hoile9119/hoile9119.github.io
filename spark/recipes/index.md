---
layout: default
title: Recipes
description: Runnable PySpark snippets — helpers pulled out of production jobs
---

[← Spark]({{ site.baseurl }}/spark/)

# Recipes

Runnable snippets rather than conceptual notes — small helpers lifted out of
production jobs and stripped down to something reusable.

- [HDFS Helper]({{ site.baseurl }}/spark/recipes/hdfs) — a wrapper over the Hadoop `FileSystem` API
- [Impala Client]({{ site.baseurl }}/spark/recipes/impala) — querying Impala from a Spark job
- [JSON Flattener]({{ site.baseurl }}/spark/recipes/json) — flatten nested JSON, infer a schema from a string column
- [Nested XML with XSD]({{ site.baseurl }}/spark/recipes/xml) — parsing deeply nested XML against a schema
- [Write Table]({{ site.baseurl }}/spark/recipes/write) — partitioning, overwrite modes, compaction
- [Webhook Sender]({{ site.baseurl }}/spark/recipes/webhook) — notifications out of a cluster job

For HDFS as a *storage layer*, see [Lakehouse]({{ site.baseurl }}/lakehouse/);
the HDFS helper here is a PySpark wrapper over the FileSystem API.

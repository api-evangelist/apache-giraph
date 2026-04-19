# Apache Giraph (apache-giraph)
Apache Giraph is an iterative graph processing system built for high scalability on Apache Hadoop. It is modeled after Google's Pregel and provides a simple yet flexible Java API for graph algorithms at massive scale using the Bulk Synchronous Parallel (BSP) model. Note - Apache Giraph has been retired as of 2024.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-giraph/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Apache, Big Data, BSP, Graph Processing, Hadoop, Open Source, Retired

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Giraph Job Monitoring API
Monitoring API for Apache Giraph graph processing jobs via the YARN ResourceManager REST API, providing job status, progress tracking, and cluster capacity metrics.

**Human URL:** [https://giraph.apache.org/quick_start.html](https://giraph.apache.org/quick_start.html)

#### Tags:

 - BSP, Graph, Hadoop, Job Management, YARN

#### Properties

- [Documentation](https://giraph.apache.org/quick_start.html)
- [OpenAPI](openapi/apache-giraph-job-openapi.yml)
- [JSONSchema](json-schema/giraph-job-application-info-schema.json)
- [JSON-LD](json-ld/apache-giraph-job-context.jsonld)

### Apache Giraph Java API
Java API based on the Bulk Synchronous Parallel (BSP) model for implementing graph algorithms, with Vertex, Edge, and Master compute APIs for distributed graph processing on Hadoop.

**Human URL:** [https://giraph.apache.org/apidocs/](https://giraph.apache.org/apidocs/)

#### Tags:

 - BSP, Graph, Java, SDK

#### Properties

- [Documentation](https://giraph.apache.org/apidocs/)
- [Java SDK (Maven Central)](https://search.maven.org/artifact/org.apache.giraph/giraph-core)

## Common Properties

- [Documentation](https://giraph.apache.org/)
- [GettingStarted](https://giraph.apache.org/quick_start.html)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/giraph)

## Features

| Name | Description |
|------|-------------|
| Bulk Synchronous Parallel (BSP) Model | Google Pregel-inspired BSP computation model where vertices communicate through supersteps. |
| Vertex-Centric Programming | Write graph algorithms by defining per-vertex compute functions that exchange messages with neighbors. |
| Master Compute API | Global coordination API for aggregating results and controlling algorithm termination across supersteps. |
| Aggregators | Sharded aggregators for collecting global statistics across all vertices during computation. |
| Edge-Oriented Input | Flexible input formats for loading graphs from HDFS, Hive, Gora, and Rexster sources. |
| Out-of-Core Computation | Spill graph data to disk for processing graphs larger than available memory. |
| Hadoop Integration | Runs as a MapReduce job on Apache Hadoop YARN for resource management and fault tolerance. |
| Fault Tolerance | Checkpoint-based recovery for fault tolerance across superstep boundaries. |

## Use Cases

| Name | Description |
|------|-------------|
| Social Graph Analysis | Analyze social network connections, communities, and influence at billions-of-vertices scale (as used at Facebook). |
| PageRank Computation | Compute web page or entity rankings using iterative link analysis algorithms. |
| Shortest Path Computation | Find shortest paths between vertices for network routing and recommendation problems. |
| Connected Components | Identify clusters and connected components in large graphs for community detection. |
| Graph Machine Learning Features | Generate graph-structural features for machine learning models at scale. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Hadoop | Runs on Hadoop YARN as a MapReduce application for cluster resource management. |
| Apache Hive | Hive I/O module for loading graph data from Hive tables. |
| Apache Gora | Gora I/O module for loading graph data from various NoSQL data stores. |
| Rexster | Rexster graph server I/O module for loading data from TinkerPop graph databases. |
| Apache HBase | HBase integration for storing and loading vertex and edge data. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Giraph Job Monitoring API](openapi/apache-giraph-job-openapi.yml)

### JSON Schema

- 4 schema files in [json-schema/](json-schema/)

### JSON Structure

- 4 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Apache Giraph Job Context](json-ld/apache-giraph-job-context.jsonld)

### Examples

- 4 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache Giraph Job Monitoring API](capabilities/shared/giraph-job.yaml) — 3 operations for job monitoring

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache Giraph Graph Processing](capabilities/giraph-graph-processing.yaml) | giraph-job | 3 | Data Engineer |

## Vocabulary

- [Apache Giraph Vocabulary](vocabulary/apache-giraph-vocabulary.yaml) — Unified taxonomy mapping 2 resources, 2 actions, 1 workflow, and 1 persona across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Apache Giraph Spectral Rules](rules/apache-giraph-spectral-rules.yml) — 7 rules across 4 categories enforcing Apache Giraph API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com

# Apache Giraph (apache-giraph)

Apache Giraph is an iterative graph processing system built for high scalability on Apache Hadoop. It is modeled after Google's Pregel and provides a simple yet flexible Java API for graph algorithms at massive scale using the Bulk Synchronous Parallel (BSP) model. Note - Apache Giraph has been retired as of 2024.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-giraph/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-giraph/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Apache
- Big Data
- BSP
- Graph Processing
- Hadoop
- Open Source
- Retired

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Apache Giraph Job Monitoring API

Monitoring API for Apache Giraph graph processing jobs via the YARN ResourceManager REST API, providing job status, progress tracking, and cluster capacity metrics.

- **Human URL:** [https://giraph.apache.org/quick_start.html](https://giraph.apache.org/quick_start.html)
- **Base URL:** `http://localhost:8088`

#### Tags

- BSP
- Graph
- Hadoop
- Job Management
- YARN

#### Properties

- [Documentation](https://giraph.apache.org/quick_start.html)
- [OpenAPI](openapi/apache-giraph-job-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apache-giraph-job.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-giraph-job.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/giraph-job-application-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/apache-giraph-job-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Apache Giraph Java API

Java API based on the Bulk Synchronous Parallel (BSP) model for implementing graph algorithms, with Vertex, Edge, and Master compute APIs for distributed graph processing on Hadoop.

- **Human URL:** [https://giraph.apache.org/apidocs/](https://giraph.apache.org/apidocs/)

#### Tags

- BSP
- Graph
- Java
- SDK

#### Properties

- [Documentation](https://giraph.apache.org/apidocs/)
- [SDK](https://search.maven.org/artifact/org.apache.giraph/giraph-core)
- [Postman Collection](collections/apache-giraph-job.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-giraph-job.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Documentation](https://giraph.apache.org/)
- [Getting Started](https://giraph.apache.org/quick_start.html)
- [GitHub Organization](https://github.com/apache)
- [GitHub Repository](https://github.com/apache/giraph)
- [Spectral Rules](rules/apache-giraph-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-giraph-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com

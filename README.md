# Apache Giraph (apache-giraph)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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

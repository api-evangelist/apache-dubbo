# Apache Dubbo (apache-dubbo)

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

Apache Dubbo is a high-performance, Java-based open-source RPC framework that provides service discovery, traffic management, and observability capabilities for building enterprise-level microservices. It supports multiple protocols including Triple (gRPC-compatible), Dubbo, and REST, with SDKs for Java, Go, Node.js, Python, Rust, and Erlang.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-dubbo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-dubbo/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Apache
- Go
- Java
- Microservices
- Open Source
- RPC
- Service Discovery
- Service Mesh

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Apache Dubbo Admin API

The Dubbo Admin REST API provides service governance operations for managing services, instances, traffic rules, load balancing, route policies, and dynamic configuration in a Dubbo microservices cluster.

- **Human URL:** [https://github.com/apache/dubbo-admin](https://github.com/apache/dubbo-admin)

#### Tags

- Admin
- Governance
- REST
- Service Management

#### Properties

- [Documentation](https://dubbo.apache.org/en/overview/reference/admin/)
- [OpenAPI](openapi/apache-dubbo-admin-openapi-original.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apache-dubbo-admin-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-dubbo-admin-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub Repository](https://github.com/apache/dubbo-admin)

### Apache Dubbo Java SDK

The core Apache Dubbo Java framework providing RPC service definition, publishing, invocation, and service governance APIs for building enterprise microservices in Java and Spring Boot.

- **Human URL:** [https://dubbo.apache.org/en/overview/mannual/java-sdk/](https://dubbo.apache.org/en/overview/mannual/java-sdk/)

#### Tags

- Java
- RPC
- SDK
- Spring Boot

#### Properties

- [Documentation](https://dubbo.apache.org/en/overview/mannual/java-sdk/)
- [SDK](https://search.maven.org/artifact/org.apache.dubbo/dubbo)
- [GitHub Repository](https://github.com/apache/dubbo)
- [Postman Collection](collections/apache-dubbo-admin-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-dubbo-admin-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache Dubbo Go SDK

The Go implementation of Apache Dubbo, providing the same RPC framework capabilities including service discovery, traffic management, and Triple protocol support for Go-based microservices.

- **Human URL:** [https://dubbo.apache.org/en/overview/mannual/golang-sdk/](https://dubbo.apache.org/en/overview/mannual/golang-sdk/)

#### Tags

- Go
- Golang
- RPC
- SDK

#### Properties

- [Documentation](https://dubbo.apache.org/en/overview/mannual/golang-sdk/)
- [GitHub Repository](https://github.com/apache/dubbo-go)
- [Postman Collection](collections/apache-dubbo-admin-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-dubbo-admin-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/apache)
- [GitHub Repository](https://github.com/apache/dubbo)
- [GitHub Repository](https://github.com/apache/dubbo-go)
- [GitHub Repository](https://github.com/apache/dubbo-admin)
- [GitHub Repository](https://github.com/apache/dubbo-kubernetes)
- [Documentation](https://dubbo.apache.org/en/overview/)
- [Getting Started](https://dubbo.apache.org/en/overview/quickstart/)
- [Blog](https://dubbo.apache.org/en/blog/)
- [Release Notes](https://github.com/apache/dubbo/releases)
- [Spectral Rules](rules/apache-dubbo-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-dubbo-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com

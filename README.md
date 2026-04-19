# Apache Dubbo (apache-dubbo)
Apache Dubbo is a high-performance, Java-based open-source RPC framework that provides service discovery, traffic management, and observability capabilities for building enterprise-level microservices. It supports multiple protocols including Triple (gRPC-compatible), Dubbo, and REST, with SDKs for Java, Go, Node.js, Python, Rust, and Erlang.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-dubbo/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Apache, Go, Java, Microservices, Open Source, RPC, Service Discovery, Service Mesh

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Dubbo Admin API
The Dubbo Admin REST API provides service governance operations for managing services, instances, traffic rules, load balancing, route policies, and dynamic configuration in a Dubbo microservices cluster.

**Human URL:** [https://github.com/apache/dubbo-admin](https://github.com/apache/dubbo-admin)

#### Tags:

 - Admin, Governance, REST, Service Management

#### Properties

- [Documentation](https://dubbo.apache.org/en/overview/reference/admin/)
- [OpenAPI](openapi/apache-dubbo-admin-openapi-original.json)
- [GitHubRepository](https://github.com/apache/dubbo-admin)

### Apache Dubbo Java SDK
The core Apache Dubbo Java framework providing RPC service definition, publishing, invocation, and service governance APIs for building enterprise microservices in Java and Spring Boot.

**Human URL:** [https://dubbo.apache.org/en/overview/mannual/java-sdk/](https://dubbo.apache.org/en/overview/mannual/java-sdk/)

#### Tags:

 - Java, RPC, SDK, Spring Boot

#### Properties

- [Documentation](https://dubbo.apache.org/en/overview/mannual/java-sdk/)
- [SDK](https://search.maven.org/artifact/org.apache.dubbo/dubbo)
- [GitHubRepository](https://github.com/apache/dubbo)

### Apache Dubbo Go SDK
The Go implementation of Apache Dubbo, providing the same RPC framework capabilities including service discovery, traffic management, and Triple protocol support for Go-based microservices.

**Human URL:** [https://dubbo.apache.org/en/overview/mannual/golang-sdk/](https://dubbo.apache.org/en/overview/mannual/golang-sdk/)

#### Tags:

 - Go, Golang, RPC, SDK

#### Properties

- [Documentation](https://dubbo.apache.org/en/overview/mannual/golang-sdk/)
- [GitHubRepository](https://github.com/apache/dubbo-go)

## Common Properties

- [Apache GitHub Organization](https://github.com/apache)
- [Apache Dubbo Java (Main Repo)](https://github.com/apache/dubbo)
- [Apache Dubbo Go](https://github.com/apache/dubbo-go)
- [Apache Dubbo Admin](https://github.com/apache/dubbo-admin)
- [Apache Dubbo Kubernetes](https://github.com/apache/dubbo-kubernetes)
- [Documentation](https://dubbo.apache.org/en/overview/)
- [GettingStarted](https://dubbo.apache.org/en/overview/quickstart/)
- [Blog](https://dubbo.apache.org/en/blog/)
- [ReleaseNotes](https://github.com/apache/dubbo/releases)

## Features

| Name | Description |
|------|-------------|
| Triple Protocol (gRPC Compatible) | HTTP/2-based RPC protocol fully compatible with gRPC, supporting streaming communication and cross-language interoperability. |
| Service Discovery | High-performance application-level service discovery supporting Nacos, Zookeeper, Kubernetes, Consul, Etcd, and Redis registries. |
| Traffic Management | Advanced traffic control with conditional routing, tag routing, gray releases, and percentage-based traffic splitting. |
| Load Balancing | Multiple load balancing strategies including weighted random, round-robin, least active, and consistent hashing. |
| Rate Limiting and Circuit Breaking | Built-in rate limiting, circuit breaker, and service degradation capabilities for resilient microservices. |
| Observability | Full-link tracing via OpenTelemetry, Prometheus metrics, Grafana dashboards, Zipkin, and SkyWalking integration. |
| Multi-Language SDK Support | Official SDKs for Java, Go, Node.js, Python, Rust, and Erlang enabling polyglot microservices architectures. |
| Service Mesh Integration | Native Istio integration with xDS protocol support for deploying Dubbo services in service mesh environments. |
| Dubbo Admin Console | Visual cluster management UI for service governance, traffic rules, configuration, and monitoring. |
| Pixiu Gateway | HTTP/gRPC gateway (Pixiu) enabling REST HTTP clients to access Dubbo backend services. |

## Use Cases

| Name | Description |
|------|-------------|
| Enterprise Microservices | Build high-performance Java or Go microservices with RPC communication, service discovery, and traffic governance. |
| gRPC Migration | Adopt the Triple protocol as a drop-in gRPC-compatible alternative with richer governance capabilities. |
| Cross-Language Service Communication | Enable polyglot microservices with Java, Go, Node.js, Python, Rust, and Erlang services communicating via Dubbo protocols. |
| Service Mesh Deployment | Run Dubbo services in Istio-managed service meshes using xDS protocol for sidecar-free or sidecar-based deployments. |
| Cloud-Native Kubernetes Deployment | Deploy and manage Dubbo services on Kubernetes using the Dubbo Kubernetes operator and control plane. |
| API Gateway Integration | Expose internal Dubbo RPC services as REST HTTP endpoints through the Pixiu API gateway. |

## Integrations

| Name | Description |
|------|-------------|
| Nacos | Service registry and configuration center integration for service discovery and dynamic configuration. |
| Zookeeper | Apache Zookeeper integration for service registry and coordination. |
| Kubernetes | Native Kubernetes service discovery and deployment orchestration support. |
| Istio | Service mesh integration with Istio using xDS protocol for traffic management. |
| Prometheus | Metrics export to Prometheus for monitoring Dubbo service performance. |
| Grafana | Pre-built Grafana dashboards for visualizing Dubbo service metrics. |
| OpenTelemetry | Distributed tracing via OpenTelemetry standard for end-to-end request tracking. |
| Zipkin | Distributed tracing integration with Zipkin for request flow visualization. |
| SkyWalking | Apache SkyWalking APM integration for distributed tracing and service performance monitoring. |
| Seata | Apache Seata integration for distributed transaction management across Dubbo services. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Dubbo Admin API](openapi/apache-dubbo-admin-openapi-original.json)

### JSON Schema

- 32 schema files in [json-schema/](json-schema/)

### JSON Structure

- 32 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Apache Dubbo Admin Context](json-ld/apache-dubbo-admin-context.jsonld)

### Examples

- 32 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache Dubbo Admin API](capabilities/shared/dubbo-admin.yaml) — 4 operations for service governance

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache Dubbo Service Governance](capabilities/dubbo-service-governance.yaml) | dubbo-admin | 5 | Platform Engineer, SRE |

## Vocabulary

- [Apache Dubbo Vocabulary](vocabulary/apache-dubbo-vocabulary.yaml) — Unified taxonomy mapping 8 resources, 6 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Apache Dubbo Spectral Rules](rules/apache-dubbo-spectral-rules.yml) — 15 rules across 6 categories enforcing Apache Dubbo API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com

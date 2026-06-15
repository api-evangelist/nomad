# HashiCorp Nomad (nomad)

HashiCorp Nomad is a flexible workload orchestrator that enables organizations to deploy and manage containers, legacy applications, and batch jobs across any infrastructure. The Nomad developer platform provides a comprehensive HTTP API, official SDKs, and tooling for automating job scheduling, cluster management, and service orchestration at scale.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nomad/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nomad/refs/heads/main/apis.yml)

## Tags

- Workload Orchestration
- Container Orchestration
- Scheduling
- Infrastructure
- DevOps

## Timestamps

- **Created:** 2026-03-20
- **Modified:** 2026-05-19

## APIs

### HashiCorp Nomad HTTP API

The HashiCorp Nomad HTTP API provides programmatic access to all Nomad functionality including job scheduling, allocation management, node operations, deployments, services, evaluations, namespaces, ACL policies, and cluster status. All API routes are prefixed with /v1/ and the default port is 4646. The API is RESTful, responds to standard HTTP verbs, and supports ACL token authentication via the X-Nomad-Token header or Bearer scheme. Developers can use this API to submit and manage workloads, monitor cluster health, query allocation status, and integrate Nomad orchestration into their infrastructure automation workflows.

- **Human URL:** [https://developer.hashicorp.com/nomad/api-docs](https://developer.hashicorp.com/nomad/api-docs)
- **Base URL:** `http://localhost:4646`

#### Tags

- Workload Orchestration
- Container Orchestration
- Scheduling
- Infrastructure
- DevOps
- Cloud

#### Properties

- [Documentation](https://developer.hashicorp.com/nomad/api-docs)
- [OpenAPI](openapi/nomad-http-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nomad-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomad-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/nomad-event-stream-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/nomad-job-schema.json) — [JSON Schema](https://json-schema.org/specification)

### HashiCorp Nomad Go SDK

The HashiCorp Nomad Go SDK is the official Go client library for interacting with the Nomad HTTP API. It provides a high-level, idiomatic Go interface for managing jobs, allocations, nodes, deployments, evaluations, and other Nomad resources. The SDK is maintained by HashiCorp as part of the main Nomad repository and is used internally by the Nomad CLI itself, making it the most comprehensive and up-to-date client available.

- **Human URL:** [https://pkg.go.dev/github.com/hashicorp/nomad/api](https://pkg.go.dev/github.com/hashicorp/nomad/api)

#### Tags

- Workload Orchestration
- Go
- SDK
- DevOps

#### Properties

- [Documentation](https://pkg.go.dev/github.com/hashicorp/nomad/api)
- [Postman Collection](collections/nomad-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomad-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HashiCorp Nomad Python SDK

The python-nomad library is a Python client for the HashiCorp Nomad HTTP API. It provides Pythonic access to Nomad resources including jobs, nodes, allocations, deployments, evaluations, namespaces, and ACL management. The library supports configuration via environment variables such as NOMAD_ADDR, NOMAD_TOKEN, and NOMAD_NAMESPACE for consistency with the Nomad CLI and other ecosystem tools.

- **Human URL:** [https://github.com/jrxFive/python-nomad](https://github.com/jrxFive/python-nomad)

#### Tags

- Workload Orchestration
- Python
- SDK
- DevOps

#### Properties

- [Documentation](https://github.com/jrxFive/python-nomad)
- [Postman Collection](collections/nomad-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomad-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HashiCorp Nomad Java SDK

The Nomad Java SDK is an official Java client library for the HashiCorp Nomad HTTP API. It enables Java and JVM-based applications to interact with Nomad clusters for submitting jobs, querying allocations, managing nodes, and performing other orchestration operations. The SDK provides a typed Java interface over the Nomad REST API, making it suitable for enterprise applications and microservice architectures running on the JVM.

- **Human URL:** [https://developer.hashicorp.com/nomad/api-docs/libraries-and-sdks](https://developer.hashicorp.com/nomad/api-docs/libraries-and-sdks)

#### Tags

- Workload Orchestration
- Java
- SDK
- DevOps

#### Properties

- [Documentation](https://developer.hashicorp.com/nomad/api-docs/libraries-and-sdks)
- [Postman Collection](collections/nomad-http-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomad-http-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/hashicorp)
- [Portal](https://developer.hashicorp.com/nomad)
- [Documentation](https://developer.hashicorp.com/nomad/docs)
- [Website](https://www.nomadproject.io/)
- [Privacy Policy](https://www.hashicorp.com/privacy)
- [Terms of Service](https://www.hashicorp.com/terms-of-service)
- [Support](https://support.hashicorp.com/)
- [Blog](https://www.hashicorp.com/blog)
- [Login](https://portal.cloud.hashicorp.com/sign-in)
- [JSON-LD](json-ld/nomad-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com

# HashiCorp Nomad (nomad)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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

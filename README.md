# HashiCorp Nomad

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

**Areas:** Workload Orchestration · Container Orchestration · Scheduling · Infrastructure · DevOps

## HashiCorp Nomad on APIs.io

Everything profiled for HashiCorp Nomad is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/nomad/](https://apis.io/providers/nomad/)** — or go straight to one of the APIs or properties below.

### APIs (22)

- [HashiCorp Nomad Go SDK](https://apis.io/apis/nomad/go-sdk/) — The HashiCorp Nomad Go SDK is the official Go client library for interacting with the Nomad HTTP API. It provides a high-level, idiomatic Go interface for…
- [HashiCorp Nomad Python SDK](https://apis.io/apis/nomad/python-sdk/) — The python-nomad library is a Python client for the HashiCorp Nomad HTTP API. It provides Pythonic access to Nomad resources including jobs, nodes,…
- [HashiCorp Nomad Java SDK](https://apis.io/apis/nomad/java-sdk/) — The Nomad Java SDK is an official Java client library for the HashiCorp Nomad HTTP API. It enables Java and JVM-based applications to interact with Nomad…
- [HashiCorp Nomad ACL API](https://apis.io/apis/nomad/nomad-acl-api/) — Endpoints for managing Access Control List policies, tokens, and authentication methods.
- [HashiCorp Nomad Agent API](https://apis.io/apis/nomad/nomad-agent-api/) — Endpoints for interacting with the local Nomad agent, including health checks, member listing, and server management.
- [HashiCorp Nomad Allocations API](https://apis.io/apis/nomad/nomad-allocations-api/) — Endpoints for querying allocations. An allocation declares that a set of tasks in a job should be run on a particular node.
- [HashiCorp Nomad Deployments API](https://apis.io/apis/nomad/nomad-deployments-api/) — Endpoints for querying and managing deployments. Deployments track the rolling update of allocations between two versions of a job.
- [HashiCorp Nomad Evaluations API](https://apis.io/apis/nomad/nomad-evaluations-api/) — Endpoints for querying evaluations. Evaluations are the mechanism by which Nomad makes scheduling decisions.
- [HashiCorp Nomad Jobs API](https://apis.io/apis/nomad/nomad-jobs-api/) — Endpoints for listing, creating, reading, updating, and deleting jobs. Jobs are the primary unit of work in Nomad.
- [HashiCorp Nomad Namespaces API](https://apis.io/apis/nomad/nomad-namespaces-api/) — Endpoints for managing namespaces, which segment jobs and their associated objects.
- [HashiCorp Nomad Node Pools API](https://apis.io/apis/nomad/nomad-node-pools-api/) — Endpoints for managing node pools, which group nodes for scheduling constraints.
- [HashiCorp Nomad Nodes API](https://apis.io/apis/nomad/nomad-nodes-api/) — Endpoints for querying and managing client nodes registered with the Nomad cluster.
- [HashiCorp Nomad Operator API](https://apis.io/apis/nomad/nomad-operator-api/) — Endpoints for cluster-level operations such as Raft peer management and autopilot configuration.
- [HashiCorp Nomad Regions API](https://apis.io/apis/nomad/nomad-regions-api/) — Endpoints for listing known regions in the Nomad cluster.
- [HashiCorp Nomad Scaling API](https://apis.io/apis/nomad/nomad-scaling-api/) — Endpoints for querying scaling policies and their status.
- [HashiCorp Nomad Search API](https://apis.io/apis/nomad/nomad-search-api/) — Endpoints for searching across Nomad objects by prefix or fuzzy match.
- [HashiCorp Nomad Service API](https://apis.io/apis/nomad/nomad-service-api/) — The Service API from HashiCorp Nomad — 1 operation(s) for service.
- [HashiCorp Nomad Services API](https://apis.io/apis/nomad/nomad-services-api/) — The Services API from HashiCorp Nomad — 1 operation(s) for services.
- [HashiCorp Nomad Status API](https://apis.io/apis/nomad/nomad-status-api/) — Endpoints for querying the status of the Nomad cluster including leader and peer information.
- [HashiCorp Nomad System API](https://apis.io/apis/nomad/nomad-system-api/) — Endpoints for system maintenance operations such as garbage collection and reconciliation.
- [HashiCorp Nomad Variables API](https://apis.io/apis/nomad/nomad-variables-api/) — Endpoints for managing Nomad variables, which store encrypted key-value data.
- [HashiCorp Nomad Volumes API](https://apis.io/apis/nomad/nomad-volumes-api/) — Endpoints for managing CSI and host volumes attached to Nomad allocations.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [HashiCorp Nomad Event Stream](https://apis.io/asyncapis/nomad/nomad-event-stream-asyncapi/)

#### Event channels (8)

Individual events and webhooks the provider emits.

- [/event/stream?topic=*](https://apis.io/channels/nomad/event-stream-topic/)
- [/event/stream?topic=Allocation](https://apis.io/channels/nomad/event-stream-topic-allocation/)
- [/event/stream?topic=Deployment](https://apis.io/channels/nomad/event-stream-topic-deployment/)
- [/event/stream?topic=Evaluation](https://apis.io/channels/nomad/event-stream-topic-evaluation/)
- [/event/stream?topic=Job](https://apis.io/channels/nomad/event-stream-topic-job/)
- [/event/stream?topic=Node](https://apis.io/channels/nomad/event-stream-topic-node/)
- [/event/stream?topic=NodePool](https://apis.io/channels/nomad/event-stream-topic-nodepool/)
- [/event/stream?topic=Service](https://apis.io/channels/nomad/event-stream-topic-service/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Nomad Agentic Access](https://apis.io/agentic-access/nomad/nomad-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [HashiCorp Nomad Job](https://apis.io/schemas/nomad/nomad-job/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Nomad Context](https://apis.io/jsonld/nomad/nomad-context/)

#### Collections (39)

Postman and Open Collection request collections.

- [HashiCorp Nomad HTTP ACL API](https://apis.io/collections/nomad/open-nomad-acl-api/)
- [HashiCorp Nomad HTTP ACL Agent API](https://apis.io/collections/nomad/open-nomad-agent-api/)
- [HashiCorp Nomad HTTP ACL Allocations API](https://apis.io/collections/nomad/open-nomad-allocations-api/)
- [HashiCorp Nomad HTTP ACL Deployments API](https://apis.io/collections/nomad/open-nomad-deployments-api/)
- [HashiCorp Nomad HTTP ACL Evaluations API](https://apis.io/collections/nomad/open-nomad-evaluations-api/)
- [HashiCorp Nomad HTTP API](https://apis.io/collections/nomad/open-nomad-http-api/)
- [HashiCorp Nomad HTTP ACL Jobs API](https://apis.io/collections/nomad/open-nomad-jobs-api/)
- [HashiCorp Nomad HTTP ACL Namespaces API](https://apis.io/collections/nomad/open-nomad-namespaces-api/)
- [HashiCorp Nomad HTTP ACL Node Pools API](https://apis.io/collections/nomad/open-nomad-node-pools-api/)
- [HashiCorp Nomad HTTP ACL Nodes API](https://apis.io/collections/nomad/open-nomad-nodes-api/)
- [HashiCorp Nomad HTTP ACL Operator API](https://apis.io/collections/nomad/open-nomad-operator-api/)
- [HashiCorp Nomad HTTP ACL Regions API](https://apis.io/collections/nomad/open-nomad-regions-api/)
- [HashiCorp Nomad HTTP ACL Scaling API](https://apis.io/collections/nomad/open-nomad-scaling-api/)
- [HashiCorp Nomad HTTP ACL Search API](https://apis.io/collections/nomad/open-nomad-search-api/)
- [HashiCorp Nomad HTTP ACL Service API](https://apis.io/collections/nomad/open-nomad-service-api/)
- [HashiCorp Nomad HTTP ACL Services API](https://apis.io/collections/nomad/open-nomad-services-api/)
- [HashiCorp Nomad HTTP ACL Status API](https://apis.io/collections/nomad/open-nomad-status-api/)
- [HashiCorp Nomad HTTP ACL System API](https://apis.io/collections/nomad/open-nomad-system-api/)
- [HashiCorp Nomad HTTP ACL Variables API](https://apis.io/collections/nomad/open-nomad-variables-api/)
- [HashiCorp Nomad HTTP ACL Volumes API](https://apis.io/collections/nomad/open-nomad-volumes-api/)
- [HashiCorp Nomad HTTP ACL API](https://apis.io/collections/nomad/postman-nomad-acl-api/)
- [HashiCorp Nomad HTTP ACL Agent API](https://apis.io/collections/nomad/postman-nomad-agent-api/)
- [HashiCorp Nomad HTTP ACL Allocations API](https://apis.io/collections/nomad/postman-nomad-allocations-api/)
- [HashiCorp Nomad HTTP ACL Deployments API](https://apis.io/collections/nomad/postman-nomad-deployments-api/)
- [HashiCorp Nomad HTTP ACL Evaluations API](https://apis.io/collections/nomad/postman-nomad-evaluations-api/)
- …and 14 more published on APIs.io

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [HashiCorp Nomad — asyncapi rules](https://apis.io/rules/nomad/nomad-asyncapi-spectral-rules/)
- [HashiCorp Nomad — jsonschema rules](https://apis.io/rules/nomad/nomad-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Nomad Authentication](https://apis.io/security/nomad/nomad-authentication/)
- [Nomad Domain Security](https://apis.io/security/nomad/nomad-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Nomad Plans Pricing](https://apis.io/plans/nomad/nomad-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Nomad Rate Limits](https://apis.io/rate-limits/nomad/nomad-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Nomad Finops](https://apis.io/finops/nomad/nomad-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.nomadproject.io/)
- [Documentation](https://developer.hashicorp.com/nomad/docs)
- [Support](https://support.hashicorp.com/)
- [Blog](https://www.hashicorp.com/blog)
- [Terms of service](https://www.hashicorp.com/terms-of-service)
- [Privacy policy](https://www.hashicorp.com/privacy)

## API Evangelist rating

**Kin Score 39.1** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 62.9 |
| Contract governance | 13.6 |
| Operational transparency | 7.9 |
| Developer ergonomics | 38.1 |
| Access clarity | 25.0 |

**Agent readiness 19.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 20.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/nomad/](https://apis.io/providers/nomad/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for HashiCorp Nomad: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/nomad/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).

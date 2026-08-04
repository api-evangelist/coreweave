# CoreWeave (coreweave)

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

CoreWeave is a specialized GPU cloud purpose-built for AI workloads, offering managed Kubernetes (CKS), Slurm-on-Kubernetes (SUNK), dedicated and serverless inference, AI Object Storage, distributed VAST file storage, HPC InfiniBand interconnect, and a Sandbox product. CoreWeave's control plane is Kubernetes-native and exposes APIs for CKS clusters, Inference deployments and gateways, VPCs, Object Storage, and Sandbox control.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/coreweave/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/coreweave/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producer
- **Access:** 3rd-Party

## Tags

- AI
- Cloud
- GPU
- HPC
- Inference
- Kubernetes
- Machine Learning
- Storage

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### CoreWeave Kubernetes Service API

The CKS API provisions and manages CoreWeave Kubernetes Service clusters and node pools on bare-metal GPU and CPU hardware. It exposes operations for cluster lifecycle, node pool configuration, and hardware-aware scheduling for training, inference, and HPC workloads.

- **Human URL:** [https://docs.coreweave.com/products/cks/reference/cks-api](https://docs.coreweave.com/products/cks/reference/cks-api)

#### Tags

- Bare Metal
- Clusters
- GPU
- Kubernetes
- Node Pools

#### Properties

- [Documentation](https://docs.coreweave.com/products/cks/reference/cks-api)
- [Reference](https://docs.coreweave.com/products/cks/reference/node-pool)
- [Postman Collection](collections/coreweave.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coreweave.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CoreWeave Inference API

The CoreWeave Inference API manages Deployments, Gateways, and Capacity Claims for serverless and dedicated AI inference. It is used to create, update, and route to managed model deployments backed by CoreWeave's GPU fleet.

- **Human URL:** [https://docs.coreweave.com/products/inference/reference/api-overview](https://docs.coreweave.com/products/inference/reference/api-overview)

#### Tags

- AI
- Deployments
- Gateways
- Inference
- Models

#### Properties

- [Documentation](https://docs.coreweave.com/products/inference/reference/api-overview)
- [Reference](https://docs.coreweave.com/products/inference/reference/deploymentservice/create-deployment)
- [Reference](https://docs.coreweave.com/products/inference/reference/gatewayservice/create-gateway)
- [Reference](https://docs.coreweave.com/products/inference/reference/capacityclaimservice/create-capacity-claim)
- [Postman Collection](collections/coreweave.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coreweave.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CoreWeave VPC API

The VPC API creates and manages Virtual Private Clouds on CoreWeave, including network configuration, routing, and isolation for CKS clusters and other compute resources.

- **Human URL:** [https://docs.coreweave.com/products/networking/vpc/vpc-api](https://docs.coreweave.com/products/networking/vpc/vpc-api)

#### Tags

- Networking
- Routing
- VPC

#### Properties

- [Documentation](https://docs.coreweave.com/products/networking/vpc/vpc-api)
- [Reference](https://docs.coreweave.com/products/networking/vpc/vpc-api/vpcservice/create-vpc)
- [Postman Collection](collections/coreweave.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coreweave.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CoreWeave AI Object Storage API

CoreWeave AI Object Storage (CAIOS) is an S3-compatible object storage service optimized for AI dataset and model storage. It supports standard S3 operations alongside CoreWeave-specific bucket and access controls.

- **Human URL:** [https://docs.coreweave.com/products/storage/object-storage/reference/object-storage-api-ref](https://docs.coreweave.com/products/storage/object-storage/reference/object-storage-api-ref)

#### Tags

- AI
- Buckets
- Datasets
- Object Storage
- S3

#### Properties

- [Documentation](https://docs.coreweave.com/products/storage/object-storage/reference/object-storage-api-ref)
- [Reference](https://docs.coreweave.com/products/storage/object-storage/reference/object-storage-s3)
- [Postman Collection](collections/coreweave.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coreweave.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CoreWeave Sandbox Control Plane API

The Sandbox Control Plane API provisions ephemeral compute sandboxes for short-lived, isolated workloads on CoreWeave infrastructure.

- **Human URL:** [https://docs.coreweave.com/products/sandboxes/reference/control-plane-api](https://docs.coreweave.com/products/sandboxes/reference/control-plane-api)

#### Tags

- Compute
- Ephemeral
- Sandbox

#### Properties

- [Documentation](https://docs.coreweave.com/products/sandboxes/reference/control-plane-api)
- [Postman Collection](collections/coreweave.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coreweave.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.coreweave.com)
- [Developer](https://docs.coreweave.com)
- [Documentation](https://docs.coreweave.com)
- [Portal](https://cloud.coreweave.com)
- [Pricing](https://www.coreweave.com/pricing)
- [Blog](https://www.coreweave.com/blog)
- [GitHub Organization](https://github.com/coreweave)
- [Status Page](https://status.coreweave.com)
- [Terms of Service](https://www.coreweave.com/legal/terms-of-use)
- [Privacy Policy](https://www.coreweave.com/legal/privacy-policy)
- [Support](https://www.coreweave.com/contact)
- [LinkedIn](https://www.linkedin.com/company/coreweave)
- [Terraform](https://docs.coreweave.com/platform/terraform)
- [SDK](https://github.com/coreweave/tensorizer)
- [Samples](https://github.com/coreweave/kubernetes-cloud)
- [Features](undefined)
- [Integrations](undefined)
- [L L Ms Txt](https://docs.coreweave.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com

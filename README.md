# CoreWeave (coreweave)

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

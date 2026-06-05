# Google Cloud Binary Authorization (google-cloud-binary-authorization)

Google Cloud Binary Authorization is a deploy-time security control that ensures only trusted container images are deployed on Google Kubernetes Engine (GKE), Cloud Run, and Anthos clusters. It uses attestation-based policies to validate that container images have been signed by trusted authorities before allowing deployment, helping enforce software supply chain security.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/google-cloud-binary-authorization/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/google-cloud-binary-authorization/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Attestation
- Container Security
- DevSecOps
- Kubernetes
- Policy Enforcement
- Supply Chain Security

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-05-19

## APIs

### Binary Authorization API

The Binary Authorization API provides programmatic access to manage deploy-time security policies for container images. Developers can use the API to create and manage attestors, attestations, and policies that control which container images are allowed to be deployed. The API integrates with GKE, Cloud Run, and Anthos to enforce that only verified and trusted container images are deployed to production environments.

- **Human URL:** [https://cloud.google.com/binary-authorization/docs](https://cloud.google.com/binary-authorization/docs)
- **Base URL:** `https://binaryauthorization.googleapis.com`

#### Tags

- Attestations
- Attestors
- Container Images
- Policies

#### Properties

- [Documentation](https://cloud.google.com/binary-authorization/docs/reference/rest)
- [OpenAPI](openapi/binary-authorization-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/binary-authorization-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/binary-authorization-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://cloud.google.com/binary-authorization/docs/reference/rest#authentication)
- [JSON Schema](json-schema/google-cloud-binary-authorization-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Common Properties

- [GitHub Organization](https://github.com/GoogleCloudPlatform)
- [Portal](https://cloud.google.com/binary-authorization)
- [Getting Started](https://cloud.google.com/binary-authorization/docs/getting-started-cli)
- [Documentation](https://cloud.google.com/binary-authorization/docs)
- [Authentication](https://cloud.google.com/binary-authorization/docs/reference/rest#authentication)
- [Pricing](https://cloud.google.com/binary-authorization/pricing)
- [Terms of Service](https://cloud.google.com/terms)
- [Privacy Policy](https://policies.google.com/privacy)
- [Status Page](https://status.cloud.google.com)
- [Support](https://cloud.google.com/binary-authorization/docs/support)
- [JSON-LD](json-ld/google-cloud-binary-authorization-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Integrations](https://cloud.google.com/marketplace)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

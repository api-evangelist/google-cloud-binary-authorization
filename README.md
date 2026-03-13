# Google Cloud Binary Authorization (google-cloud-binary-authorization)
Google Cloud Binary Authorization is a deploy-time security control that ensures only trusted container images are deployed on Google Kubernetes Engine (GKE), Cloud Run, and Anthos clusters. It uses attestation-based policies to validate that container images have been signed by trusted authorities before allowing deployment, helping enforce software supply chain security through its API.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/google-cloud-binary-authorization/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Container Security, Kubernetes, Supply Chain Security, Attestation, Policy Enforcement, DevSecOps

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-03-13

## APIs

### Binary Authorization API
The Binary Authorization API provides programmatic access to manage deploy-time security policies for container images. Developers can use the API to create and manage attestors, attestations, and policies that control which container images are allowed to be deployed. The API integrates with GKE, Cloud Run, and Anthos to enforce that only verified and trusted container images are deployed to production environments.

**Human URL:** [https://cloud.google.com/binary-authorization/docs](https://cloud.google.com/binary-authorization/docs)


#### Tags:

 - Attestors, Attestations, Policies, Container Images

#### Properties

- [Documentation](https://cloud.google.com/binary-authorization/docs/reference/rest)
- [OpenAPI](openapi/binary-authorization-api-openapi.yml)
- [JSONSchema](json-schema/google-cloud-binary-authorization-policy-schema.json)

## Common Properties

- [GettingStarted](https://cloud.google.com/binary-authorization/docs/getting-started-cli)
- [Pricing](https://cloud.google.com/binary-authorization/pricing)
- [Authentication](https://cloud.google.com/binary-authorization/docs/reference/rest#authentication)
- [Support](https://cloud.google.com/binary-authorization/docs/support)
- [Status](https://status.cloud.google.com)
- [JSON-LD](json-ld/google-cloud-binary-authorization-context.jsonld)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com

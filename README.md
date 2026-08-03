# Amazon Cloud WAN (amazon-cloud-wan)

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

Amazon Cloud WAN is a managed wide area networking service that simplifies building, managing, and monitoring global WANs by connecting branch offices, data centers, and Amazon VPCs through a central dashboard with network policy automation and unified monitoring.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-cloud-wan/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Cloud WAN, Networking, Wide Area Network, SD-WAN

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon Cloud WAN API
API for building and managing global wide area networks, connecting branch offices, data centers, and VPCs with centralized control, monitoring, and network policy automation.

**Human URL:** [https://aws.amazon.com/cloud-wan/](https://aws.amazon.com/cloud-wan/)

#### Tags:

 - AWS, Cloud WAN, Networking

#### Properties

- [Documentation](https://docs.aws.amazon.com/network-manager/latest/cloudwan/)

- [APIReference](https://docs.aws.amazon.com/network-manager/latest/cloudwan/)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/cloud-wan/)
- [SpectralRules](rules/amazon-cloud-wan-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-cloud-wan-vocabulary.yaml)
- [NaftikoCapability](capabilities/wan-management.yaml)

## Features

| Name | Description |
|------|-------------|
| Centralized WAN Management | Build and manage global wide area networks through a single centralized dashboard. |
| Network Policy Automation | Automate management and security tasks across your entire WAN infrastructure. |
| Unified Monitoring | Monitor on-premises and AWS network health and performance from one view. |
| Network Segmentation | Isolate sensitive traffic from standard data flows with segmentation policies. |
| Global Connectivity | Connect branch offices, data centers, and VPCs with minimal configuration globally. |

## Use Cases

| Name | Description |
|------|-------------|
| Global Enterprise WAN | Build globally distributed corporate WANs using AWS infrastructure. |
| Hybrid Network Extension | Extend on-premises corporate WANs into AWS cloud environments seamlessly. |
| Network Centralization | Centralize network configuration, monitoring, and automation across all locations. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Transit Gateway | Connect VPCs and on-premises networks through Transit Gateway attachments. |
| AWS Direct Connect | Dedicated network connections from on-premises to AWS. |
| Amazon VPC | Connect VPCs across regions into the global WAN. |
| AWS IAM | Control access to Cloud WAN resources with IAM policies. |

## Artifacts

### JSON Schema

- No schemas generated

### JSON-LD

- [Amazon Cloud WAN Context](json-ld/amazon-cloud-wan-context.jsonld)

## Capabilities

### Shared Per-API Definitions

- [Amazon Cloud WAN](capabilities/shared/cloud-wan.yaml) — 6 operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [WAN Management](capabilities/wan-management.yaml) | Amazon Cloud WAN | 6 | Network Engineer |

## Vocabulary

- [Amazon Cloud WAN Vocabulary](vocabulary/amazon-cloud-wan-vocabulary.yaml) — Unified taxonomy covering operations, workflows, and personas

## Rules

- [Amazon Cloud WAN Spectral Rules](rules/amazon-cloud-wan-spectral-rules.yml) — 19 rules enforcing Amazon Cloud WAN API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

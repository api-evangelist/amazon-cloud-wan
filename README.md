# Amazon Cloud WAN (amazon-cloud-wan)
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

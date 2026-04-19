# Amnic (amnic)
Amnic is a cloud cost observability platform providing real-time cost monitoring, anomaly detection, and optimization for cloud and Kubernetes environments. Powered by context-aware AI agents, Amnic helps FinOps practitioners, engineering leads, and finance teams gain visibility into AWS, GCP, Azure, and Kubernetes costs through automated reporting, anomaly detection, budget governance, and programmatic API access.

**URL:** [https://amnic.com](https://amnic.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Cloud Cost Observability, FinOps, Cloud Cost Management, Cost Optimization, Kubernetes, AWS, Azure, Google Cloud

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-04-19

## APIs

### Amnic Cloud Cost Observability API
The Amnic API provides programmatic access to cloud cost data from saved Cost Analyzer charts, enabling automation of reporting and integration with other FinOps tools. Authenticate with an API key header to retrieve chart filters and cost data with custom filter parameters.

**Human URL:** [https://amnic.com/](https://amnic.com/)

#### Tags:

 - Cloud Cost Observability, FinOps, Cost Analytics

#### Properties

- [Documentation](https://docs.amnic.com/)
- [GettingStarted](https://docs.amnic.com/)
- [OpenAPI](openapi/amnic-openapi.yml)
- [JSONSchema](json-schema/amnic-api-filter-schema.json)
- [JSONSchema](json-schema/amnic-api-filter-list-schema.json)
- [JSONSchema](json-schema/amnic-api-filter-request-schema.json)
- [JSONSchema](json-schema/amnic-api-chart-data-schema.json)
- [JSONStructure](json-structure/amnic-api-filter-structure.json)
- [JSONStructure](json-structure/amnic-api-filter-list-structure.json)
- [JSONStructure](json-structure/amnic-api-filter-request-structure.json)
- [JSONStructure](json-structure/amnic-api-chart-data-structure.json)
- [Example](examples/amnic-api-filter-example.json)
- [Example](examples/amnic-api-filter-list-example.json)
- [Example](examples/amnic-api-filter-request-example.json)
- [Example](examples/amnic-api-chart-data-example.json)

## Common Properties

- [Website](https://amnic.com/)
- [Documentation](https://docs.amnic.com/)
- [Pricing](https://amnic.com/pricing)
- [Blog](https://amnic.com/blog)
- [LinkedIn](https://www.linkedin.com/company/amnic)
- [SpectralRules](rules/amnic-spectral-rules.yml)
- [NaftikoCapability](capabilities/shared/amnic-api.yaml)
- [NaftikoCapability](capabilities/cloud-cost-observability.yaml)
- [JSONLD](json-ld/amnic-api-context.jsonld)
- [Vocabulary](vocabulary/amnic-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| X-Ray Agent | AI agent that provides cloud cost health assessments in 30 seconds, surfacing anomalies and optimization opportunities across AWS, GCP, Azure, and Kubernetes. |
| Insights Agent | Delivers audience-specific cloud cost insights through natural language queries tailored for finance, engineering, and leadership teams. |
| Governance Agent | Detects cost anomalies, manages budgets, and enforces tag hygiene across cloud environments for compliance and cost control. |
| Reporting Agent | Generates customized cost reports for different stakeholder audiences with automated scheduling and delivery. |
| Cost Anomaly Detection | Real-time detection of unexpected cost spikes and anomalies with alerts to reduce mean time to resolution by 90%. |
| Cost Allocation | Allocate cloud costs across teams, projects, and business units using tags and custom allocation rules. |
| Unit Economics | Measure cost efficiency metrics and unit economics to understand cost per customer, feature, or business unit. |
| Budget Management | Set budgets, track spending against targets, and receive alerts when budgets are approached or exceeded. |
| Spending Forecasting | Predict future cloud costs based on historical usage patterns and growth trends. |
| Programmatic API Access | REST API for automating reporting, retrieving saved chart data with custom filters, and integrating Amnic with other FinOps tools. |

## Use Cases

| Name | Description |
|------|-------------|
| Automated Cost Reporting | Programmatically retrieve cloud cost data from saved charts and integrate into internal dashboards, data warehouses, or BI tools. |
| Cost Anomaly Investigation | Detect and investigate unexpected cloud cost spikes using AI agents and real-time cost monitoring to reduce debugging time by 90%. |
| FinOps Workflow Automation | Automate FinOps workflows including cost allocation, chargeback reporting, and budget variance analysis across engineering teams. |
| Multi-Cloud Cost Visibility | Gain unified cost visibility across AWS, GCP, Azure, and Kubernetes environments in a single observability platform. |
| AI-Assisted Cost Optimization | Use natural language queries and AI agents to identify cost optimization opportunities and implement recommendations. |
| Stakeholder Reporting | Generate and deliver customized cost reports for finance, engineering, and executive stakeholders with relevant metrics and insights. |

## Integrations

| Name | Description |
|------|-------------|
| AWS | Connect AWS accounts to ingest billing and usage data for cost monitoring, anomaly detection, and optimization recommendations. |
| Google Cloud Platform | Integrate GCP projects for unified cloud cost visibility and optimization across Google Cloud services. |
| Microsoft Azure | Connect Azure subscriptions for real-time cost monitoring and FinOps automation across Azure services. |
| Kubernetes | Native Kubernetes cost observability for container workloads, namespace cost allocation, and cluster efficiency optimization. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amnic Cloud Cost Observability API](openapi/amnic-openapi.yml)

### JSON Schema

- [Filter](json-schema/amnic-api-filter-schema.json)
- [Filter List](json-schema/amnic-api-filter-list-schema.json)
- [Filter Request](json-schema/amnic-api-filter-request-schema.json)
- [Chart Data](json-schema/amnic-api-chart-data-schema.json)

### JSON Structure

- [Filter](json-structure/amnic-api-filter-structure.json)
- [Filter List](json-structure/amnic-api-filter-list-structure.json)
- [Filter Request](json-structure/amnic-api-filter-request-structure.json)
- [Chart Data](json-structure/amnic-api-chart-data-structure.json)

### JSON-LD

- [Amnic API Context](json-ld/amnic-api-context.jsonld)

### Examples

- [Filter](examples/amnic-api-filter-example.json)
- [Filter List](examples/amnic-api-filter-list-example.json)
- [Filter Request](examples/amnic-api-filter-request-example.json)
- [Chart Data](examples/amnic-api-chart-data-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amnic Cloud Cost Observability API](capabilities/shared/amnic-api.yaml) — 2 operations for cloud cost data retrieval

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Cloud Cost Observability](capabilities/cloud-cost-observability.yaml) | Amnic API | 2 | FinOps Practitioner, Engineering Lead, Finance Team |

## Vocabulary

- [Amnic Vocabulary](vocabulary/amnic-vocabulary.yaml) — Unified taxonomy mapping 1 resource, 2 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amnic Spectral Rules](rules/amnic-spectral-rules.yml) — 27 rules across 13 categories enforcing Amnic API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

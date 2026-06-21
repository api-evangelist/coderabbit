# CodeRabbit (coderabbit)

CodeRabbit is an AI-powered code review platform that installs as a Git app (GitHub, GitLab, Bitbucket, Azure DevOps) to deliver line-by-line, context-aware reviews and summaries on pull requests, plus IDE and CLI reviews. It exposes a REST API for on-demand developer activity report generation and is configured per-repository with a .coderabbit.yaml file.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/coderabbit/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/coderabbit/refs/heads/main/apis.yml)

## Tags

- AI
- Code Review
- Developer Tools
- Pull Requests
- DevOps

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### CodeRabbit Reports API

REST API for generating developer activity reports over a date range, authenticated with the x-coderabbitai-api-key header. The POST /report.generate endpoint returns an on-demand report and supports prompt templates, grouping, and parameter filters.

- **Human URL:** [https://docs.coderabbit.ai/api-reference/report-generate](https://docs.coderabbit.ai/api-reference/report-generate)
- **Base URL:** `https://api.coderabbit.ai/api/v1`

#### Tags

- Reports
- Analytics
- Developer Activity

#### Properties

- [Documentation](https://docs.coderabbit.ai/api-reference/report-generate)
- [API Reference](https://docs.coderabbit.ai/api-reference/report-generate)
- [OpenAPI](openapi/coderabbit-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/coderabbit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coderabbit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CodeRabbit Git App Integration

CodeRabbit installs as a Git application on GitHub, GitLab, Bitbucket, and Azure DevOps, subscribing to pull/merge request events to post AI reviews, summaries, and chat replies. Integration is event-driven rather than a public REST surface.

- **Human URL:** [https://docs.coderabbit.ai/platforms/](https://docs.coderabbit.ai/platforms/)
- **Base URL:** `https://app.coderabbit.ai`

#### Tags

- Git App
- Pull Requests
- Webhooks

#### Properties

- [Documentation](https://docs.coderabbit.ai/platforms/)
- [Getting Started](https://docs.coderabbit.ai/getting-started/quickstart)

### CodeRabbit Configuration

Per-repository behavior is configured with a .coderabbit.yaml file (validated against a published JSON schema) controlling review tone, path filters, enabled tools/linters, auto-review, and chat behavior.

- **Human URL:** [https://docs.coderabbit.ai/getting-started/configure-coderabbit](https://docs.coderabbit.ai/getting-started/configure-coderabbit)
- **Base URL:** `https://docs.coderabbit.ai`

#### Tags

- Configuration
- YAML
- Repository Settings

#### Properties

- [Documentation](https://docs.coderabbit.ai/getting-started/configure-coderabbit)
- [Reference](https://docs.coderabbit.ai/reference/configuration)

## Common Properties

- [GitHub Organization](https://github.com/coderabbitai)
- [LinkedIn](https://www.linkedin.com/company/coderabbitai)
- [Website](https://www.coderabbit.ai)
- [Documentation](https://docs.coderabbit.ai)
- [Plans](plans/coderabbit-plans-pricing.yml)
- [Rate Limits](rate-limits/coderabbit-rate-limits.yml)
- [Fin Ops](finops/coderabbit-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

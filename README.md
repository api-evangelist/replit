# Replit (replit)

Replit is a cloud-based development platform that lets you create, run, and deploy software directly from your browser. It provides instant, containerized environments for many programming languages, real-time multiplayer collaboration, an integrated editor and terminal, built-in package management, version control, and AI coding assistance. Whether you're learning to code or building production applications, Replit lets you go from idea to running prototype with no local setup required.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/replit/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

- Code
- Compiling
- Development Environment
- Programming Languages
- Version Control

## Timestamps

- **Created:** 2026-01-02
- **Modified:** 2026-05-02

## APIs

### Replit

Replit is a cloud-based development platform that lets you create, run, and deploy software directly from your browser. The Replit API provides programmatic access to manage Repls (coding environments), deployments, and user profiles.

**Human URL:** [https://replit.com/](https://replit.com/)

#### Tags:

- Code
- Development Environment
- Deployments
- Programming Languages
- Repls
- Users
- Version Control

#### Properties

- [Documentation](https://docs.replit.com/api)
- [OpenAPI](openapi/replit-openapi.yml)
- [Spectral Ruleset](rules/replit-rules.yml)
- [Capability: Development Workflow](capabilities/development-workflow.yaml)
- [Vocabulary](vocabulary/replit-vocabulary.yml)

## Common Properties

- [Website](https://replit.com)
- [Documentation](https://docs.replit.com)
- [API Documentation](https://docs.replit.com/api)
- [Pricing](https://replit.com/pricing)
- [Blog](https://blog.replit.com)
- [TermsOfService](https://replit.com/site/terms)
- [PrivacyPolicy](https://replit.com/site/privacy)
- [SignUp](https://replit.com/signup)
- [Login](https://replit.com/login)
- [GitHub Organization](https://github.com/replit)
- [Python SDK](https://github.com/replit/replit-py)
- [Discord](https://discord.gg/replit)
- [Status](https://status.replit.com)

## Artifacts

### OpenAPI Specifications

- [replit-openapi.yml](openapi/replit-openapi.yml) — Replit REST API covering Repls, deployments, and users (11 operations)

### Spectral Rulesets

- [replit-rules.yml](rules/replit-rules.yml) — Spectral rules enforcing Replit API conventions (dot-notation operationIds, Bearer auth, cursor pagination)

### Naftiko Capabilities

#### Shared Definitions

- [shared/replit.yaml](capabilities/shared/replit.yaml) — Complete Replit API consumed definition

#### Workflow Capabilities

- [development-workflow.yaml](capabilities/development-workflow.yaml) — Create Repls, deploy to production, manage users (9 tools)

### JSON Schemas

- [replit-repl-schema.json](json-schema/replit-repl-schema.json) — Schema for Replit Repl objects

### JSON Structures

- [replit-repl-structure.json](json-structure/replit-repl-structure.json) — Field-level documentation for Repl objects

### JSON-LD Contexts

- [replit-context.jsonld](json-ld/replit-context.jsonld) — Linked data context mapping Replit terms to schema.org vocabulary

### Examples

- [replit-create-repl-example.json](examples/replit-create-repl-example.json) — Create a new Python Repl

### Vocabulary

- [replit-vocabulary.yml](vocabulary/replit-vocabulary.yml) — Domain vocabulary covering Repls, deployments, collaboration, and hosting

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

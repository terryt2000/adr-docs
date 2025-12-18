# ADR 0003: Introduce Schema Registry

## Context
With Azure Event Hubs in place, we needed a way to manage and validate event schemas to prevent contract drift between producers and consumers.

## Decision
We adopted the **Azure Event Hubs Schema Registry** to store and validate event schemas.

## Consequences
- ✅ Enforced schema compatibility across services.
- ✅ Provided a single source of truth for event contracts.
- ⚠️ Required integration with CI/CD pipelines for automated validation.
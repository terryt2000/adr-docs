# ADR 0004: Enforce Schema Validation in CI/CD

## Context
Manual schema validation was error-prone and inconsistent. We needed automation to ensure schema compatibility before deployment.

## Decision
We integrated **schema validation checks into our CI/CD pipelines** to catch issues early in the development lifecycle.

## Consequences
- ✅ Prevented incompatible schemas from being deployed.
- ✅ Increased confidence in event-driven integrations.
- ⚠️ Required teams to follow schema registration and validation guidelines.
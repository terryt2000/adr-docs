# ADR 0001: Adopt Event-Driven Architecture

## Context
Our monolithic system was becoming increasingly difficult to scale and maintain. Services were tightly coupled, and performance degraded under load.

## Decision
We decided to adopt an **event-driven architecture** to decouple services and enable asynchronous communication.

## Consequences
- ✅ Improved scalability and resilience.
- ✅ Services can evolve independently.
- ⚠️ Introduced the need for a central event backbone and governance for event contracts.
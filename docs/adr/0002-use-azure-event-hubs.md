# ADR 0002: Use Azure Event Hubs

## Context
Following ADR 1, we needed a reliable event backbone. We evaluated several options including Kafka and Azure Event Hubs.

## Decision
We selected **Azure Event Hubs** as our event backbone due to its managed nature and seamless integration with our Azure infrastructure.

## Consequences
- ✅ Reduced operational overhead.
- ✅ Easy integration with existing Azure services.
- ⚠️ Introduced the need for schema governance to manage event contracts.
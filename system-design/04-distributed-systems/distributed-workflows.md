# Distributed Workflows

## Learn
- Why a database transaction usually cannot atomically cover multiple services.
- Sagas, compensating actions, and orchestration versus choreography.
- Transactional outbox and reliable event publication.
- Duplicate requests, idempotency keys, and workflow state tracking.

## Practice
Design a purchase flow spanning order, payment, and inventory services. Define each state transition and compensation for failures.

## Ready when
Every intermediate state and recovery action is explicit, including timeout and duplicate-message behavior.
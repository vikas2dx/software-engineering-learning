# Project 4: Reliability and Observability

## Goal
Make service behavior diagnosable and predictable when dependencies or clients fail.

## Work
- Add request IDs, structured logs, metrics, and readiness/liveness checks.
- Set request and database timeouts and define retry behavior where safe.
- Make retried writes idempotent when the use case requires it.
- Add tests for dependency failure, duplicate requests, and graceful error responses.
- Run a small load test and capture a baseline.

## Exit criteria
A failure can be traced from request to dependency, and the service remains within agreed limits under the test workload.
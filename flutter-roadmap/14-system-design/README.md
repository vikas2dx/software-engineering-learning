# Flutter System Design

Design the client and its backend contract together. A mobile client runs on unreliable networks, is updated independently, and may keep data offline.

## Learn
- Define product requirements, latency expectations, supported platforms, and offline needs.
- Separate presentation, application state, repositories, remote services, and local storage where useful.
- Design API contracts for pagination, versioning, errors, authentication, and idempotent writes.
- Plan cache policy, synchronization, conflict handling, and stale-data presentation.
- Account for security boundaries, privacy, accessibility, observability, and release compatibility.
- Draw request and synchronization flows; identify failure cases and recovery behavior.

## Practice
Design a mobile feed or messaging client. Document screens, state transitions, API shapes, local schema, offline behavior, security assumptions, and backend dependencies.

## Ready when
The design explains normal and failure flows end to end and identifies which decisions belong to the client, backend, and platform.
# Offline-First Design

## Learn
- Local source of truth, synchronization, and cache freshness.
- Pending writes, retries, idempotency, and conflict resolution.
- Connectivity is a hint, not proof that a service is reachable.
- Communicating stale, pending, and failed states to users.

## Practice
Allow edits offline, queue changes, and synchronize after reconnect. Test duplicate delivery and a conflicting server update.

## Ready when
Users can predict what is saved locally, what is synchronized, and how conflicts or failures are resolved.
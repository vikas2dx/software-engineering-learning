# WebSockets

## Learn
- Persistent, bidirectional connections and connection lifecycle.
- Reconnection with backoff, heartbeat, and foreground/background behavior.
- Message ordering, duplicates, delivery guarantees, and authentication renewal.
- When server-sent events, polling, or push notifications fit better.

## Practice
Build a live update screen with reconnect status and deduplicate messages using stable event identifiers.

## Ready when
The UI remains understandable during disconnects and reconnects, and the client does not assume every event arrives exactly once.
# Chat Service Exercise

## Requirements to clarify
- One-to-one and group messaging, history, read receipts, and attachment needs.
- Ordering scope, offline behavior, retention, and privacy requirements.

## Design questions
- How are messages persisted and delivered to online devices?
- How are reconnects, duplicate delivery, and missed messages handled?
- How are conversations partitioned and large groups represented?
- Which features need strong ordering and which tolerate eventual consistency?

## Practice output
Document send, persistence, fan-out, reconnect, and history-read flows, including consistency choices and failure recovery.
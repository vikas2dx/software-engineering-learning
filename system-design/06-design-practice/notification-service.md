# Notification Service Exercise

## Requirements to clarify
- Supported channels, user preferences, priorities, and delivery deadlines.
- Retry and duplicate tolerance, quiet hours, and delivery status visibility.

## Design questions
- How are notifications queued and prioritized?
- How do provider failures and rate limits affect delivery?
- What keys make retries idempotent?
- How are preferences, templates, and delivery outcomes stored?

## Practice output
Design the API, queueing and worker flow, idempotency strategy, provider adapter boundary, and operational metrics.
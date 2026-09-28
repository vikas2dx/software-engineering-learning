# URL Shortener Exercise

## Requirements to clarify
- Link creation, redirects, custom aliases, expiration, and analytics expectations.
- Public versus private links, abuse reporting, and deletion behavior.

## Design questions
- How are identifiers generated and collisions avoided?
- What redirect latency and availability are needed?
- Which data should be cached, and how does expiration propagate?
- How are hot links, abuse, and analytics ingestion handled?

## Practice output
Write a design using the template. Include a rough read/write estimate, schema, redirect flow, cache policy, and abuse controls.
# System Design Roadmap

Learn to turn requirements into a design that can be reasoned about, operated, and changed. Progress from fundamentals to distributed systems, then practice by writing concise design documents.

## Stages

1. [Foundations and requirements](01-foundations/README.md)
2. [Data and storage](02-data-storage/README.md)
3. [Scalability patterns](03-scalability-patterns/README.md)
4. [Distributed systems](04-distributed-systems/README.md)
5. [Reliability and security](05-reliability-security/README.md)
6. [Design practice](06-design-practice/README.md)

## Design Workflow

1. Clarify users, core use cases, constraints, and quality goals.
2. Estimate scale with stated assumptions; refine estimates as requirements change.
3. Define APIs and data ownership before selecting infrastructure.
4. Sketch components and trace the important read and write paths.
5. Analyze bottlenecks, failure modes, security boundaries, and operational costs.
6. Record tradeoffs and revisit the design when assumptions change.

**Completion exercise:** Design a notification or messaging service from requirements through operations. Include estimates, API, data model, architecture, failure behavior, security, and unresolved tradeoffs.
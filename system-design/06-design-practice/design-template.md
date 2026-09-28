# A Repeatable Design Template

Use this outline for each design exercise:

1. **Requirements:** users, use cases, constraints, and out-of-scope work.
2. **Quality goals:** measurable latency, availability, durability, privacy, and consistency needs.
3. **Estimates:** traffic, storage, bandwidth, peaks, and assumptions.
4. **API and data:** contracts, ownership, schema, indexes, and retention.
5. **Architecture:** components and important read/write flows.
6. **Failure behavior:** timeouts, retries, duplicates, overload, and recovery.
7. **Security and operations:** trust boundaries, observability, deployment, and cost.
8. **Tradeoffs:** alternatives considered and the assumptions that would change the choice.

Keep diagrams and text focused on decisions. Update the design when a new constraint invalidates an assumption.
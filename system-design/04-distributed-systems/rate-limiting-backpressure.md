# Rate Limiting and Backpressure

## Learn
- Token bucket and leaky bucket concepts and limit scope.
- Per-user, per-tenant, and global limits.
- Queue bounds, load shedding, concurrency limits, and retry amplification.
- Clear limit responses and client retry guidance.

## Practice
Protect an expensive endpoint with tenant-aware limits. Model burst allowance, distributed enforcement, and overload response.

## Ready when
Overload is controlled before it cascades and clients can distinguish a rate limit from a transient server failure.
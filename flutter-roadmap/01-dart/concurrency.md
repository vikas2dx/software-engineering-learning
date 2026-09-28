# Asynchronous Dart and Concurrency

## Learn
- `Future`, `async`/`await`, error propagation, and cancellation limitations.
- `Stream`, subscriptions, broadcast streams, and subscription cleanup.
- Isolates for CPU-heavy work and message passing between isolates.
- Structured lifetimes: do not start asynchronous work whose owner has ended.

## Practice
Fetch several independent values concurrently, handle partial failure, and stream updates into a small consumer. Try moving an expensive calculation to an isolate.

## Ready when
You can select a Future or Stream API, handle errors, and explain who owns the lifetime of the asynchronous operation.
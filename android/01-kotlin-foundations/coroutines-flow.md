# Coroutines and Flow

## Learn
- Suspending functions, coroutine scopes, dispatchers, and structured concurrency.
- Cancellation propagation and why cancellation should not be swallowed.
- `Flow`, cold versus hot streams, and state/event stream use cases.
- `StateFlow`, `SharedFlow`, exception handling, and lifecycle-aware collection.

## Practice
Load data through a repository, expose loading/data/error states, and cancel work when its owner is cleared. Test with controlled coroutine dispatchers.

## Ready when
Every coroutine has an intentional owner, cancellation works, and stream collection respects the UI lifecycle.
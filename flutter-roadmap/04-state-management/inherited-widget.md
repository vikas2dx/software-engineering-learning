# InheritedWidget

## Learn
- How inherited data is exposed down a widget subtree.
- Dependency registration and dependent rebuild behavior.
- The role of `InheritedNotifier` and `InheritedModel`.
- When a direct implementation is useful for understanding or a small abstraction.

## Practice
Implement a tiny immutable settings scope and read it from a descendant. Change the value and observe which dependents rebuild.

## Ready when
You understand the mechanism behind many dependency and state libraries, even if you choose a higher-level API for production.
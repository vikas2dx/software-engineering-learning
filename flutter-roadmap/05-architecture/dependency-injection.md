# Dependency Injection

## Learn
- Constructor injection and explicit dependency ownership.
- Composition roots and lifetimes for app-, feature-, and request-scoped objects.
- Fakes and overrides for tests.
- When a service locator hides dependencies and makes lifecycle behavior unclear.

## Practice
Inject a repository into a feature controller and supply a fake repository in tests. Keep platform and networking construction near the app composition root.

## Ready when
Dependencies are visible, replaceable in tests, and created and disposed at a deliberate scope.
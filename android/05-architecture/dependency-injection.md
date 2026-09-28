# Dependency Injection

## Learn
- Constructor injection and explicit dependency graphs.
- Hilt or another DI framework: modules, scopes, and component lifetimes.
- ViewModel and worker construction and scope boundaries.
- Test replacements and avoiding hidden global dependencies.

## Practice
Inject a repository into a ViewModel and replace it with a fake in tests. Confirm scoped instances are not kept longer than intended.

## Ready when
Dependencies are visible at construction, replaceable in tests, and have deliberate lifetimes.
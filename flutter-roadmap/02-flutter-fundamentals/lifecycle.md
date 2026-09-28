# Widget Lifecycle

## Learn
- Stateless and stateful widget configuration and `State` ownership.
- `initState`, `didChangeDependencies`, `didUpdateWidget`, and `dispose`.
- Subscriptions, controllers, and other resources that require cleanup.
- Why `BuildContext` must not be used after its owning element is unmounted.

## Practice
Create a stateful screen that listens to a stream and owns a controller. Handle widget updates and verify every resource is cleaned up.

## Ready when
You can place initialization, update, and cleanup logic in the correct lifecycle method.
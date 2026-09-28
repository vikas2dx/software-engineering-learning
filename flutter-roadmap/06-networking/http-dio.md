# HTTP Clients and Dio

## Learn
- HTTP methods, headers, status codes, timeouts, and TLS basics.
- Centralized client configuration, interceptors, and safe request logging.
- Cancellation, retry policy, authentication refresh, and idempotent operations.
- Distinguish transport, server, and domain errors.

## Practice
Wrap a REST API client behind a repository. Test success, timeout, unauthorized response, malformed response, and retry behavior with a mock adapter.

## Ready when
Request policy is consistent and errors are converted into useful app-level outcomes without leaking secrets into logs.
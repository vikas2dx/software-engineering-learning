# Security

Treat the client as an untrusted environment: secrets embedded in an app can be extracted, and authorization must be enforced by the server.

## Learn
- Authentication versus authorization, least privilege, and secure session handling.
- Secure storage for credentials and platform-backed protection where appropriate.
- TLS, certificate validation, input validation, and safe WebView configuration.
- Avoid logging tokens or sensitive personal data; minimize retained data.
- Threat modeling, dependency updates, and reporting security issues.

## Practice
Threat-model one data flow from sign-in to API request. Verify access controls on the server and inspect logs and crash reports for sensitive values.

## Ready when
You can identify trust boundaries and explain which protections belong in the app, operating system, and backend.
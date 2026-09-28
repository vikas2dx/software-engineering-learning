# Firebase

Use Firebase services when their managed capabilities fit the product and operational constraints.

## Learn
- Configure separate Firebase projects for development, staging, and production.
- Choose among Authentication, Cloud Firestore, Realtime Database, Storage, and Cloud Messaging.
- Design security rules alongside data access; client-side checks are not authorization.
- Use the Emulator Suite for local development and rule testing.
- Understand quotas, pricing, offline behavior, and vendor-specific data models.

## Practice
Build a small authenticated feature using the emulator. Test allowed and denied reads and writes, and document the production project setup.

## Ready when
Data access is protected by tested server-enforced rules and environment configuration cannot accidentally target production during local work.
# Persistence and Transactions

## Learn
- Spring Data/JPA or JDBC repository boundaries and query behavior.
- Entity lifecycle, lazy loading, N+1 queries, and DTO mapping.
- Transaction boundaries, isolation, and rollback behavior.
- Database migrations with Flyway or Liquibase and integration testing.

## Practice
Persist an aggregate with related records. Add a migration and test transaction rollback and query counts for a list endpoint.

## Ready when
Transaction scope is intentional and database access does not surprise callers with hidden queries.
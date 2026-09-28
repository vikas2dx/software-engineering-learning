# Null Safety

## Learn
- Nullable types (`T?`), non-nullable types, and null-aware operators.
- Promotion after checks, null assertions, and why `!` should be rare.
- `late` initialization and the risks of accessing an uninitialized value.
- Modeling absent, loading, invalid, and present values explicitly.

## Practice
Refactor a data parser to handle missing fields deliberately. Test absent keys, explicit nulls, valid values, and invalid values.

## Ready when
You can tell from a type whether a value may be absent and handle that case without relying on unchecked assertions.
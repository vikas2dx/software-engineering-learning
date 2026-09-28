# Serialization

## Learn
- JSON primitives, nested objects, lists, and date/time representation.
- Mapping transport DTOs to domain models when their lifetimes or meanings differ.
- Generated serializers, code generation, and handling schema evolution.
- Validation and tolerant parsing for optional or unknown fields.

## Practice
Parse representative API fixtures, including missing optional fields and unexpected values. Test conversion separately from the live network client.

## Ready when
Malformed or changed payloads fail predictably and transport details do not spread unnecessarily through the UI.
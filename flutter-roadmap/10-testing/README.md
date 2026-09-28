# Testing

Test behavior at the narrowest level that gives confidence, then verify important user flows end to end.

## Learn
- Unit tests for pure logic and service boundaries.
- Widget tests for rendering, interaction, semantics, and state transitions.
- Integration tests for critical end-to-end flows on a device or emulator.
- Fakes, mocks, fixtures, deterministic clocks, and avoiding brittle implementation tests.
- Accessibility checks, golden tests, and CI test selection.

## Practice
Test a feature's domain rules, loading/error/success UI, and one full user flow. Include at least one regression test for a real bug.

## Ready when
The suite catches meaningful regressions, runs reliably, and does not depend on production services or fragile timing.
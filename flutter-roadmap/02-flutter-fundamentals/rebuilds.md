# Rebuilds

## Learn
- `setState` schedules work; it does not immediately draw a frame.
- Rebuilding widgets is different from relaying out and repainting render objects.
- Keep build methods deterministic and inexpensive.
- Use keys and state ownership to preserve the intended identity.

## Practice
Use DevTools to inspect rebuilds in a list-heavy screen. Move state closer to its consumer and compare behavior before adding optimizations.

## Ready when
You can identify what triggered a rebuild and distinguish a real performance issue from harmless widget reconstruction.
# Clean Architecture

## Learn
- Separate policy from implementation details where change or testing warrants it.
- Use domain entities and use cases only when they express meaningful rules.
- Keep UI and infrastructure dependencies pointing toward stable application logic.
- Avoid pass-through layers that only rename or forward calls.

## Practice
Trace one user action through UI, application logic, and a repository. Test the rule without Flutter widgets or a live server.

## Ready when
The boundaries isolate volatile details while leaving ordinary feature changes straightforward.
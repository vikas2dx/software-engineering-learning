# App Architecture

## Learn
- UI, domain, and data responsibilities and when separate layers help.
- ViewModel as a state holder, not a replacement for all application logic.
- Repository boundaries and mapping between network, database, and UI models.
- Unidirectional data flow and explicit loading, success, and failure states.

## Practice
Trace one feature from user action through state holder and repository to persistence or network. Unit-test business decisions outside the UI.

## Ready when
Changes have a clear home and tests can exercise important rules without launching the whole app.
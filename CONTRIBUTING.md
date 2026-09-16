# Contributing to seiri

## Doc comment style

- Use American English spelling throughout (e.g., "color", "honor", "analyze").
- Limit em-dashes (—); prefer commas or parentheses.
- Keep doc comments concise: describe **what** an item does, not **why** or **how**.
- Do not include implementation details, examples, file paths, or algorithm internals in doc comments — move those to `CLAUDE.md`, inline comments, or test names.
- Avoid "Test T0XX:" or "Regression test for issue #XXX:" prefixes; the test name should be self-explanatory.
- Doc comments are for public API documentation. Private helper functions and tests may use brief inline comments instead.

## Terminology

- **Defect** — incorrect code. **Infection** — incorrect program state caused by a defect. **Failure** — the observable incorrect behavior (also called an "issue"/"problem"). When bug-hunting, contributors are asked to follow TRAFFIC: Track, Reproduce, Automate, Find origins, Focus, Isolate, Correct.

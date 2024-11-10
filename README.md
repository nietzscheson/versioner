# Commit Types and Release Generation
## Commit Types That Trigger a Version Release:
- feat: Generates a minor version release (e.g., 1.1.0).
- fix: Generates a patch version release (e.g., 1.0.1).
- perf: Generates a patch version release (e.g., 1.0.1).
- BREAKING CHANGE: Generates a major version release (e.g., 2.0.0).
## Commit Types That Do NOT Trigger a Version Release:
- chore: For minor changes, maintenance, or updates that do not affect production code (e.g., dependency updates).
- docs: For documentation updates.
- style: For code formatting or style changes that do not affect functionality (e.g., code linting, whitespace changes).
- refactor: For code refactoring without functional changes.
- test: For adding or updating tests.
- ci: For changes to CI/CD configuration.

By following these commit conventions, you can ensure that releases are created only when meaningful changes are made to the codebase.
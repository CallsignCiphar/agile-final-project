# Development workflow

This is a solo project, but it follows a real branching and review workflow so the git history reflects Agile practice.

## Branching

- `main` is always deployable.
- Work happens on feature branches named `feature/<issue-number>-short-description`, e.g. `feature/3-create-project`.

## Commits

- Small, focused commits.
- Reference the issue number in the commit message, e.g. `Add project creation form (#3)`.

## Pull requests

- Open a PR from the feature branch into `main` when a story is ready for review.
- PR description links the GitHub Issue and lists what was done against the acceptance criteria.
- Self-review against the [Definition of Done](docs/DEFINITION_OF_DONE.md) before merging.

## Issues

- Every backlog item from [docs/PRODUCT_BACKLOG.md](docs/PRODUCT_BACKLOG.md) is tracked as a GitHub Issue with acceptance criteria and a story-point label.
- Issues move across the [Project board](../../projects) columns (Backlog, To Do, In Progress, In Review, Done) as work progresses.

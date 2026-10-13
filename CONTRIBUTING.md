# Contributing

## Workflow

1. Open or pick an issue. Use the bug or feature request form.
2. Create a branch from an up-to-date `main`: `<type>/<issue#>-<short-description>`, for example `feat/42-user-login`.
3. Commit using [Conventional Commits](https://www.conventionalcommits.org/): `type(scope): summary`.
4. Open a pull request that fills in the template and includes `Closes #<issue>`.
5. CI must pass and review threads must be resolved before merge.
6. PRs are squash merged; the PR title becomes the commit on `main`. The branch is deleted after merge.

Types for branches and commits: `build`, `chore`, `ci`, `docs`, `feat`, `fix`, `perf`, `refactor`, `revert`, `style`, `test`.

## Development setup

TODO: how to install dependencies, run the project and run the tests locally.
If the repo uses pre-commit hooks, run `pre-commit install` after cloning.

## Pull request guidelines

- One concern per PR; keep it small enough to review in one sitting.
- Add or update tests for behavior changes.
- Update documentation when behavior or configuration changes.
- Commits are signed off / signed only where this file says so: TODO (DCO required: yes/no; signed commits required: yes/no).

## Reporting security issues

See [SECURITY.md](SECURITY.md). Do not open public issues for vulnerabilities.

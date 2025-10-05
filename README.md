# GITHUB

## Security Settings as priority

network restriction

Every Repo should be private

Fork should be disabled on every repo

disable ssh key

commit signing

rebase to main before pr

Artifact Attestations or signing

Docker Attestations or signing

## Default Files and Folders for all repos

- README.md
- LICENSE.md
- CONTRIBUTING.md
- CODE_OF_CONDUCT.md
- .github/workflows
- .gitignore

## Pull Requests

- Template for all repos
- Status Checks before merging PR
  - Linting
  - Code and secrets scanning
  - Rebase test
  - Unit Tests
  - Only Squash Merge is allowed
  - Atleast one approval from another developer is required
  - Labels to PRs

## Access

- should be configured using teams on repository level

## TAGS

- After every Production Deployment a version tag should be created automatically.

## Actions

- Only verified actions should be used from marketplace.

## Devops Repository

- .github repository provides access to all projects for shared actions

# WinningAtLife

A repository with automated task assignment for better project management.

## Features

### Auto-Assign Tasks

This repository includes a GitHub Actions workflow that automatically assigns
newly created issues and pull requests to `@TheNewAuntyEmm`. This ensures that
all tasks are immediately assigned and tracked.

The auto-assignment happens automatically when:
- A new issue is opened
- A new pull request is opened

To modify the assignee, edit the `.github/workflows/auto-assign.yml` file and
update the `assignees` array.

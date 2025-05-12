## Introduction

This is a template repository for go projects.

## Setup

Execute the following commands to install [git hooks](https://git-scm.com/docs/githooks):

1. `ln -s ../../githooks/pre-commit .git/hooks/`: Run checks and tests before committing.
2. `ln -s ../../githooks/commit-msg .git/hooks/`: Check whether the commit message conforms to [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/).

The pre-commit hook requires the following tools to be installed:

1. [mockgen](https://github.com/uber-go/mock): Generate mock files.
2. [wire](https://github.com/google/wire): Generate dependency injection files.
3. [golangci-lint](https://golangci-lint.run/welcome/install/): Linters.

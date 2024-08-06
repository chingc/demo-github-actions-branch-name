# Demo

This demo shows how to get the branch name in GitHub Actions.

It's simple, but there are quirks depending on how the workflow is triggered.

## Overview

- Shows various `github` context properties that may or may not be the branch name
- Sets correct branch name to the top level `env` scope accessible by the entire workflow

## References

- [GitHub Docs: GitHub Actions](https://docs.github.com/en/actions)
- [GitHub Docs: github context](https://docs.github.com/en/actions/writing-workflows/choosing-what-your-workflow-does/contexts#github-context)
- [Stack Overflow: How to get the current branch within Github Actions?](https://stackoverflow.com/q/58033366/808678)

# Demo

This demo shows how to get the branch name in GitHub Actions.

It's simple, but there are quirks depending on how the workflow is triggered.

Edge case (more quirks): If your commit is tagged this method will return the tag. See SO link below.

## Overview

- Shows various `github` context properties that may or may not be the branch name
- Sets branch name to the top level `env` so it can be accessed by the entire workflow

## References

- [GitHub Docs: GitHub Actions](https://docs.github.com/en/actions)
- [GitHub Docs: github context](https://docs.github.com/en/actions/writing-workflows/choosing-what-your-workflow-does/contexts#github-context)
- [GitHub Docs: Events that trigger workflows](https://docs.github.com/en/actions/writing-workflows/choosing-when-your-workflow-runs/events-that-trigger-workflows)
- [Stack Overflow: How to get the current branch within Github Actions?](https://stackoverflow.com/q/58033366/808678)
- [Stack Overflow: How to get a branch name on GitHub action when push on a tag?](https://stackoverflow.com/q/63745613)

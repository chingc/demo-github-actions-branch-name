# Demo

Getting the branch name is a common CI operation. Surprisingly, there's no pre-defined way to get it in GitHub Actions.

There are several ways to do it. This demo shows the simplest way without using 3rd party actions or invoking various tools.

It works in most cases, but there are some quirks.

For example, if your commit is tagged this method will return the tag instead of the branch name. See SO link below.

## Overview

- Shows various `github` context properties that may or may not contain the branch name
- Sets branch name to the top level `env` so it can be accessed by the entire workflow

## References

- [GitHub Docs: GitHub Actions](https://docs.github.com/en/actions)
- [GitHub Docs: github context](https://docs.github.com/en/actions/writing-workflows/choosing-what-your-workflow-does/contexts#github-context)
- [GitHub Docs: Events that trigger workflows](https://docs.github.com/en/actions/writing-workflows/choosing-when-your-workflow-runs/events-that-trigger-workflows)
- [Stack Overflow: How to get the current branch within Github Actions?](https://stackoverflow.com/q/58033366/808678)
- [Stack Overflow: How to get a branch name on GitHub action when push on a tag?](https://stackoverflow.com/q/63745613)

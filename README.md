# repository-template
Template for GitHub repositories

[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://github.com/pre-commit/pre-commit)

# Contributing


### Commit Hooks
[ Install `pre-commit`](https://pre-commit.com/#install) and install the GitHub hook scripts
```bash
pre-commit install
pre-commit install -t commit-msg
```

This repository uses [pre-commit](https://pre-commit.com) and [commitlint](https://github.com/conventional-changelog/commitlint#what-is-commitlint) to ensure that code committed to this repository follows our formatting standards and is accompanied by a commit message that meets the [conventional commit format](https://www.conventionalcommits.org/en/v1.0.0/)

If you would like to use JIRA task IDs for your commit messages instead of the conventional format, following the instruction in [.commitlintrc.yaml](./.commitlintrc.yaml).


### Release Management
This repository uses [semantic-release](https://github.com/semantic-release/semantic-release) to manage the release process. Sematic-release runs on each merge to the master branch and will automatically generate a changelog and release.

For options on customizing the GitHub release process see the documentation for [semantic-release/github](https://github.com/semantic-release/github)

# How to review

This document outlines the steps to review a pull request in a GitHub authored Learning Lab course repository. You can find pull requests awaiting review in the "Needs review" column of the [Learning Lab maintenance project board](https://github.com/orgs/githubtraining/projects/1).

Guidelines for review are based on the type of changes in the pull request:

#### Minor markdown changes

If a pull request is only editing minor markdown responses, (like correcting a spelling error or broken URL,) then going through the entire course to review is not necessary. These pull requests can be reviewed simply by viewing and reading the files changed. If this is the case, consider the context of the course as well as the original issue reporting a bug or requesting a change.

#### Moderate to significant markdown changes

If a pull request introduces moderate to significant changes to markdown, a manual review of the course is necessary. Examples of moderate to significant changes could be:

- Changing the instructions of a step in a way that would cause the learner to do something different
- Changing responses that include liquid syntax or other variables outside of [GitHub flavored markdown](https://github.github.com/gfm/)

#### `config.yml` changes

If a pull request changes the `config.yml` file, a manual review is always required.

### Manual testing

Only members with specific permission are currently able to manually review the versions of courses that are deployed from pull requests. If you are a regular contributor and would like this access, please contact @githubtraining/programs.

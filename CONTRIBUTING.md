# Contributing Guide

Thanks for taking the time to contribute to a course on GitHub Learning Lab! :robot: :heart: :balloon: 

Every Learning Lab consists of two repositories:
- **a course repository** containing the bot code and responses 
- **a template repository** containing the starter code for the hands-on project

Most community contributions begin in the course repository.

### Ways to contribute

We love contributions from the community. Here are just a few of the ways you can contribute:

- **Report bugs:** if you find a bug while taking a Learning Lab course, you may want to do a quick check of past issues in the course repository to see if you can find any help there. Otherwise, create a new bug issue in the course repository using the provided template. 
- **Answer questions:** check out the open issues in the course repository to see if you can help answer learner questions. Learners also ask questions in the [GitHub community forum](https://github.community/t5/GitHub-Learning-Lab/bd-p/learn)
- **Suggest changes:** this could come in the form of a new learning outcome, updates to the content, updates to the bot responses, or the logic of the course. If you'd like, you can fork the course and suggest the change that way, but most people like to talk about it first in an issue.
- **Tackle an issue:** if you see an issue you would like to resolve, please feel free to fork the course and submit a PR (check out the instructions below).
- **Translate a course:** if you have the ability to translate a course, we'd love to see it. Please fork the course and submit a PR. We'll need a second native speaker to confirm the translation so if you have anyone in mind, please @ mention them in your PR for a review.

### What should I know before I get started?

You'll want to learn more about how Learning Lab works and courses are structured. To get up to speed, use the following resources:
- take the course: [_Write a Learning Lab course_](https://lab.github.com/github/write-a-learning-lab-course)
- read the [documentation on writing a course](https://lab.github.com/docs/writing-quickstart)
- watch the [video on how a Learning Lab course works](https://www.youtube.com/watch?v=xaLSVcwFkiI&list=PLg7s6cbtAD147DXcVp899Fk6SegoLY9gL&index=4)
- watch the [video on the `config.yml`](https://www.youtube.com/watch?v=HL8MdBsFaF4&list=PLg7s6cbtAD147DXcVp899Fk6SegoLY9gL&index=2)

### Finding open issues

The [course maintenance project board](https://github.com/orgs/githubtraining/projects/1) is the place to go if you want to contribute but aren't sure _what_ to do. The project board is the unifying place to find bug reports, fixes, and course enhancements across all of the GitHub authored Learning Lab courses. It may be used in several ways:

#### A new issue is opened

When a new issue is opened in any of the course or template repositories for GitHub authored Learning Lab courses, they should be moved to the `Triage` column. This creates visibility for the issue.

#### Triaging existing issues

Maintainers of Learning Lab courses may use this board to triage existing issues. When triaging, maintainers evaluate the issue and fit it into the column that is most appropriate. The columns are sorted via priority, with highest priority issues at the top, but currently the system for determining priority is fluid.

#### Finding somewhere to contribute

If you want to contribute, but aren't sure how or where to start, the project board is a perfect place. You can see all of the open issues in one place. Aside from opening an issue, the main ways of contributing are to [replicate bug reports](how_to_replicate.md), [open pull requests](CONTRIBUTING.md) addressing open issues, or [reviewing open pull requests](how_to_review.md).

### How to Contribute

1. Fork the course repository AND the template repository.
1. In order to test your changes, you'll need to create your own draft version of the course on Learning Lab. You'll need to:
   - Install Learning Lab on both the course repository and the template repository
   - Go to `https://lab.github.com/{{ your-username }}/new` and provide the slug for the course repository
   - This will create a **draft** course. You can do all of the testing while in draft, you won't need to publish the course
1. Once you've created the draft version, you can use the Course Builder to make changes. For more information on how to make changes, check out the [documentation](https://lab.github.com/docs/writing-quickstart) 
1. Commit your changes to your branch
1. Open a pull request in the parent repository with:
    - base branch: the default branch of the course repository, usually `main`
    - compare branch: the branch containing your commits in your fork
    - Note: If a pull request is created from a fork, then Learning Lab will not deploy a version of that course. Please ping a member of @githubtraining/programs for help. They will merge the pull request into a different branch (_not the default or original target branch_) and open a new pull request that will trigger a build of the course that can be manually tested.
1. Request a review from the Learning Lab team (this should be automatically requested)

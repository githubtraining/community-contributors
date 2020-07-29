# Updating template repositories

Updating template repositories is particularly tricky, because there is distinct history on each branch plotted intentionally to be ready for the pull requests that a learner may interact with. For this reason, contributions to the template repository should be managed by the @githubtraining/programs team in most cases.

## Syncing the course repository

In any case where a course repository is updated, a member of @githubtraining/programs will need to manually sync the template repository to the course via Learning Lab stafftools.

## Updates not affecting activities

If you need to make a change to a template repository that does not affect the branches or activities, please commit directly to master.

## Updates affecting activities

Changes on branches affecting activities can be complex and difficult. Template repositories cannot be synced to some versions of a course, and not others. **In these cases, it may be useful to create a fork of template repository to test separately and completely.** 

1. If you do this, update the link to the template repository from the course repository's `config.yml` file.
2. Then, you can test the course from a branch with a separate template repository. Make any necessary changes to the _forked_ version of the template repository, and test.
3. Once things work as expected, force push all branches from the fork to the upstream repository.
4. **Important**: update the reference in the course repository's `config.yml` file back to the original template repository.
5. Delete the fork of the template repository.
6. Test again from the branch deployment.
7. After merging the pull request, test once more from the published and public version of the course.
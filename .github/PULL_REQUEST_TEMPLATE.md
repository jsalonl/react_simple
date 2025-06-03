# Pull Request Summary

## Description

As developer, describe in a clear and concise way your changes here.

## Task Review

Link ticket: [#1]()

## Release Manager

### Dependencies before deploy
<!-- To be filled by the developer -->

- [ ] Database migration.
- [ ] Configs.
- [ ] Secrets.
- [ ] Environment variables.

### Impact
<!-- To be filled by the developer -->
More info: [Semantic Versioning](https://semver.org/lang/es/)

- [ ] Major (Incompatible API changes).
    - [ ] Big feature.
    - [ ] Redesign with domain impact (> 50%).
    - [ ] New version for API (> 50%).
- [ ] Minor (Add functionality in a backwards-compatible manner).
    - [ ] Feature.
-[ ] Patch (Backwards-compatible bug fixes).
    - [ ] Refactor.
    - [ ] Optimization.
    - [ ] Bug Fix.
    - [ ] Documentation Update.

#### Merge Convention

| Branch from     | Branch to | Merge commit | Squash and Merge |
|-----------------|-----------|--------------|------------------|
| feature/        | develop   | ❌            | ✅               |
| fix/            | develop   | ❌            | ✅               |
| bugfix/         | develop   | ❌            | ✅               |
| enhancement/    | develop   | ❌            | ✅               |
| backport/       | develop   | ✅            | ❌               |
| hotfix/         | master    | ✅            | ❌               |
| release/        | master    | ✅            | ❌               |
| migration/      | master    | ✅            | ❌               |

## PR Review

### Compliance
<!-- As developer, first create the pull request as DRAFT, then go over all the following points, and replace ⁠ [ ] ⁠ with ⁠ [x] ⁠ in all the boxes that apply -->
<!-- When you are done, set the pull request as ready for review -->

- [ ] I follow as well as possible the guidelines indicated in [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit).
- [ ] I have updated the Swagger.
- [ ] I have updated the Postman Collections.
- [ ] I have updated the Changelog.
- [ ] I will squash intermediate commits when this PR is Merged.

### QA
<!-- To be completed by the developer and/or reviewer -->

- [ ] I run ⁠ make all ⁠. <!-- Developer & Reviewer -->
- [ ] I have added necessary tests, not only coverage <!-- Developer, verified by the Reviewer -->
- [ ] I have tested in Local environment. <!-- Developer -->
- [ ] We have tested in STG environment. <!-- Developer -->

### Code Quality
<!-- To be filled by the reviewer -->

- [ ] Follow the conventions indicated in [Java Conventions](https://www.oracle.com/technetwork/java/codeconventions-150003.pdf)
- [ ] Does not introduce any vulnerabilities.
- [ ] The readability is promoted.
- [ ] Cyclomatic complexity is maintained at a level equal or less than 20
- [ ] There are no useless functions
- [ ] There are no dead code
- [ ] There are no logic or code duplications
- [ ] Appropriate comments have been made (comprehensive, relevant and up-to-date)
- [ ] Low coupling and high cohesion are promoted
- [ ] Does not introduce any anti-patterns
- [ ] [The implementation aligns with the basic design concepts that were agreed upon.](https://wiki)

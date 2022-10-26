# git-slice-tools-test-cases

## slice-main branch

In each test case, we create a new branch from this branch via Github GraphQL API (ex: `slice-main-<unique-key>`) then use that branch in tests instead of using this branch directly.

In this branch, we prepare files which are needed for testing overriding behavior in `git-slice-tools` `pull` jobs. For other test cases, we recommend to create new `slice-main-<unique-key>` from `sliced-main` branch, so we don't need to perform `pull` job before performing test cases.

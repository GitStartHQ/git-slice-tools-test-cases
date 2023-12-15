# git-slice-tools-test-cases - Test push 

## upstream-main branch

In this branch, we will add all cases of source code files which are needed to increase coverage in `git-slice-tools` unit tests (like normal files, lfs files, synlink files, .gitsliceignore files...)

In each test case, we create a new branch from this branch via Github GraphQL API (ex: `upstream-main-<unique-key>` or `slice-main-<unique-key>`) then use that branch in tests instead of using this branch directly

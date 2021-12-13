# dummy-action

A dummy action to build deterministic testing of a git-ref to commit-sha resolver.

GitHub Actions allows for multiple ways to define the `uses:` part of a step.

The documentation says:

> **Using the commit SHA of a released action version is the safest for stability and security.**
> 
> _Source: [GitHub Documentation]_

[GitHub Documentation]: https://docs.github.com/en/actions/learn-github-actions/workflow-syntax-for-github-actions#jobsjob_idstepsuses

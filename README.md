# dummy-action

A dummy action to build deterministic testing of a git-ref to commit-sha resolver.

GitHub Actions allows for multiple ways to define the `uses:` part of a step:

```yaml
# Reference a specific commit with a comment at the end of the line
    - uses: actions/checkout@a81bbbf8298c0fa03ea29cdc473d45769f953675 # v2.4.0
# Reference a specific commit
    - uses: actions/checkout@a81bbbf8298c0fa03ea29cdc473d45769f953675
# Reference the major version of a release
    - uses: actions/checkout@v2
# Reference a specific version
    - uses: actions/checkout@v2.2.0
# Reference a branch
    - uses: actions/checkout@main
```

The documentation says:

> **Using the commit SHA of a released action version is the safest for stability and security.**
> 
> _Source: [GitHub Documentation]_

[GitHub Documentation]: https://docs.github.com/en/actions/learn-github-actions/workflow-syntax-for-github-actions#jobsjob_idstepsuses

# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test codebase-memory-mcp https://github.com/shaolang/asdf-codebase-memory-mcp.git "codebase-memory-mcp --version"
```

Tests are automatically run in GitHub Actions on push and PR.

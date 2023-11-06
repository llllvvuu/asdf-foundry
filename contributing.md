# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test foundry https://github.com/llllvvuu/asdf-foundry.git "forge --help"
```

Tests are automatically run in GitHub Actions on push and PR.

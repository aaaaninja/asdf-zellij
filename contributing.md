# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test zellij https://github.com/aaaaninja/asdf-zellij.git "zellij --help"
```

Tests are automatically run in GitHub Actions on push and PR.

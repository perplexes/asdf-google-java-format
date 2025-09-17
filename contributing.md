# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test google-java-format https://github.com/perplexes/asdf-google-java-format.git "google-java-format --help"
```

Tests are automatically run in GitHub Actions on push and PR.

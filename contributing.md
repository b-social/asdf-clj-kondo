# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test cljkondo https://github.com/ssorc3/asdf-cljkondo.git "clj-kondo"
```

Tests are automatically run in GitHub Actions on push and PR.

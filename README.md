<div align="center">

# asdf-cljkondo [![Build](https://github.com/ssorc3/asdf-cljkondo/actions/workflows/build.yml/badge.svg)](https://github.com/ssorc3/asdf-cljkondo/actions/workflows/build.yml) [![Lint](https://github.com/ssorc3/asdf-cljkondo/actions/workflows/lint.yml/badge.svg)](https://github.com/ssorc3/asdf-cljkondo/actions/workflows/lint.yml)

[cljkondo](https://github.com/b-social/asdf-cljkondo) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add cljkondo
# or
asdf plugin add cljkondo https://github.com/ssorc3/asdf-cljkondo.git
```

cljkondo:

```shell
# Show all installable versions
asdf list-all cljkondo

# Install specific version
asdf install cljkondo latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cljkondo latest

# Now cljkondo commands are available
clj-kondo
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ssorc3/asdf-cljkondo/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ben Cross](https://github.com/ssorc3/)

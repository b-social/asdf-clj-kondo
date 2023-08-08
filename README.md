# asdf-cljkondo

[clj-kondo](https://github.com/clj-kondo/clj-kondo) plugin for the [asdf version manager](https://asdf-vm.com).

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
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
asdf plugin add cljkondo https://github.com/b-social/asdf-cljkondo.git
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

# License

See [LICENSE](LICENSE) © [Kroo](https://github.com/b-social/)

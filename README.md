# asdf-clj-kondo

[clj-kondo](https://github.com/clj-kondo/clj-kondo) plugin for the [asdf version manager](https://asdf-vm.com).

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Legal](#legal)

# Dependencies

- `bash`, `curl`, `unzip`

# Install

Plugin:

```shell
asdf plugin add clj-kondo
# or
asdf plugin add clj-kondo https://github.com/b-social/asdf-clj-kondo.git
```

clj-kondo:

```shell
# Show all installable versions
asdf list-all clj-kondo

# Install specific version
asdf install clj-kondo latest

# Set a version globally (on your ~/.tool-versions file)
asdf global clj-kondo latest

# Now clj-kondo commands are available
clj-kondo
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

## Legal

Copyright © 2023 Kroo Bank Ltd.

This library and source code are available under the terms of the MIT licence.  A full copy of the licence file is provided in the `LICENCE` file of the source code.

<div align="center">

# asdf-nats [![Build](https://github.com/richjddavis/asdf-nats/actions/workflows/build.yml/badge.svg)](https://github.com/richjddavis/asdf-nats/actions/workflows/build.yml) [![Lint](https://github.com/richjddavis/asdf-nats/actions/workflows/lint.yml/badge.svg)](https://github.com/richjddavis/asdf-nats/actions/workflows/lint.yml)


[nats](https://docs.nats.io) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `unzip`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add nats https://github.com/richjddavis/asdf-nats.git
```

nats:

```shell
# Show all installable versions
asdf list-all nats

# Install specific version
asdf install nats latest

# Set a version globally (on your ~/.tool-versions file)
asdf global nats latest


# Version >= 2: the nats-server command is available
nats-server --help

# Version < 2: the gnatsd command is available
gnatsd --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/richjddavis/asdf-nats/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Rich Davis](https://github.com/richjddavis/)

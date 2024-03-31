> [!IMPORTANT]
> Foundry [only keeps the earliest release of each month](https://github.com/foundry-rs/foundry/blob/d94e3c631e2da7756af46c70f8f58b75563b7013/.github/scripts/prune-prereleases.js#L38). So I don't recommend pinning to any other release.

> [!TIP]
> I use and recommend [`mise`](https://github.com/jdx/mise), a drop-in replacement for `asdf` written in Rust.

<div align="center">

# asdf-foundry [![Build](https://github.com/llllvvuu/asdf-foundry/actions/workflows/build.yml/badge.svg)](https://github.com/llllvvuu/asdf-foundry/actions/workflows/build.yml) [![Lint](https://github.com/llllvvuu/asdf-foundry/actions/workflows/lint.yml/badge.svg)](https://github.com/llllvvuu/asdf-foundry/actions/workflows/lint.yml)

[foundry](https://github.com/foundry-rs/foundry) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `sed`, `grep`, `awk`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add foundry https://github.com/llllvvuu/asdf-foundry.git
```

foundry:

```shell
# Show all installable versions
asdf list-all foundry

# Install specific version
asdf install foundry latest

# Set a version globally (on your ~/.tool-versions file)
asdf global foundry latest

# Now foundry commands are available
forge --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/llllvvuu/asdf-foundry/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [llllvvuu](https://github.com/llllvvuu/)

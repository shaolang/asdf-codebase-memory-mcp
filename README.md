<div align="center">

# asdf-codebase-memory-mcp [![Build](https://github.com/shaolang/asdf-codebase-memory-mcp/actions/workflows/build.yml/badge.svg)](https://github.com/shaolang/asdf-codebase-memory-mcp/actions/workflows/build.yml) [![Lint](https://github.com/shaolang/asdf-codebase-memory-mcp/actions/workflows/lint.yml/badge.svg)](https://github.com/shaolang/asdf-codebase-memory-mcp/actions/workflows/lint.yml)

[codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add codebase-memory-mcp https://github.com/shaolang/asdf-codebase-memory-mcp.git
```

codebase-memory-mcp:

```shell
# Show all installable versions
asdf list-all codebase-memory-mcp

# Install specific version
asdf install codebase-memory-mcp latest

# Set a version globally (on your ~/.tool-versions file)
asdf global codebase-memory-mcp latest

# Now codebase-memory-mcp commands are available
codebase-memory-mcp --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

After setting the version, run `codebase-memory-mcp install`.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/shaolang/asdf-codebase-memory-mcp/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Shaolang Ai](https://github.com/shaolang/)

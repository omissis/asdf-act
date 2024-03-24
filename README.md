<div align="center">

# asdf-act [![Build](https://github.com/omissis/asdf-act/actions/workflows/build.yml/badge.svg)](https://github.com/omissis/asdf-act/actions/workflows/build.yml) [![Lint](https://github.com/omissis/asdf-act/actions/workflows/lint.yml/badge.svg)](https://github.com/omissis/asdf-act/actions/workflows/lint.yml)

[act](https://nektosact.com) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add act
# or
asdf plugin add act https://github.com/omissis/asdf-act.git
```

act:

```shell
# Show all installable versions
asdf list-all act

# Install specific version
asdf install act latest

# Set a version globally (on your ~/.tool-versions file)
asdf global act latest

# Now act commands are available
act --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/omissis/asdf-act/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Claudio Beatrice](https://github.com/omissis/)

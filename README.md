<div align="center">

# asdf-mockolo [![Build](https://github.com/MontakOleg/asdf-mockolo/actions/workflows/build.yml/badge.svg)](https://github.com/MontakOleg/asdf-mockolo/actions/workflows/build.yml) [![Lint](https://github.com/MontakOleg/asdf-mockolo/actions/workflows/lint.yml/badge.svg)](https://github.com/MontakOleg/asdf-mockolo/actions/workflows/lint.yml)

[mockolo](https://github.com/uber/mockolo) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add mockolo
# or
asdf plugin add mockolo https://github.com/MontakOleg/asdf-mockolo.git
```

mockolo:

```shell
# Show all installable versions
asdf list-all mockolo

# Install specific version
asdf install mockolo latest

# Set a version globally (on your ~/.tool-versions file)
asdf global mockolo latest

# Now mockolo commands are available
mockolo --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/MontakOleg/asdf-mockolo/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Oleg Montak](https://github.com/MontakOleg/)

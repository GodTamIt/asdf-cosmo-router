<div align="center">

# asdf-cosmo-router [![Build](https://github.com/GodTamIt/asdf-cosmo-router/actions/workflows/build.yml/badge.svg)](https://github.com/GodTamIt/asdf-cosmo-router/actions/workflows/build.yml) [![Lint](https://github.com/GodTamIt/asdf-cosmo-router/actions/workflows/lint.yml/badge.svg)](https://github.com/GodTamIt/asdf-cosmo-router/actions/workflows/lint.yml)

[cosmo-router](https://wundergraph.com/router-gateway) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add cosmo-router
# or
asdf plugin add cosmo-router https://github.com/GodTamIt/asdf-cosmo-router.git
```

cosmo-router:

```shell
# Show all installable versions
asdf list-all cosmo-router

# Install specific version
asdf install cosmo-router latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cosmo-router latest

# Now cosmo-router commands are available
router --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/GodTamIt/asdf-cosmo-router/graphs/contributors)!

# License

Licensed under the [Apache License, Version 2.0](LICENSE).

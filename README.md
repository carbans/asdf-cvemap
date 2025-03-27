<div align="center">

# asdf-cvemap [![Build](https://github.com/carbans/asdf-cvemap/actions/workflows/build.yml/badge.svg)](https://github.com/carbans/asdf-cvemap/actions/workflows/build.yml) [![Lint](https://github.com/carbans/asdf-cvemap/actions/workflows/lint.yml/badge.svg)](https://github.com/carbans/asdf-cvemap/actions/workflows/lint.yml)

[cvemap](https://docs.projectdiscovery.io/tools/cvemap/usage) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add cvemap
# or
asdf plugin add cvemap https://github.com/carbans/asdf-cvemap.git
```

cvemap:

```shell
# Show all installable versions
asdf list-all cvemap

# Install specific version
asdf install cvemap latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cvemap latest

# Now cvemap commands are available
cvemap -version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/carbans/asdf-cvemap/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Carlos Latorre](https://github.com/carbans/)

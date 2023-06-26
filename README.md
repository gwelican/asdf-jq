<div align="center">

# asdf-jq [![Build](https://github.com/gwelican/asdf-jq/actions/workflows/build.yml/badge.svg)](https://github.com/gwelican/asdf-jq/actions/workflows/build.yml) [![Lint](https://github.com/gwelican/asdf-jq/actions/workflows/lint.yml/badge.svg)](https://github.com/gwelican/asdf-jq/actions/workflows/lint.yml)

[jq](https://github.com/jqlang/jq) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add jq
# or
asdf plugin add jq https://github.com/gwelican/asdf-jq.git
```

jq:

```shell
# Show all installable versions
asdf list-all jq

# Install specific version
asdf install jq latest

# Set a version globally (on your ~/.tool-versions file)
asdf global jq latest

# Now jq commands are available
jq --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gwelican/asdf-jq/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Peter Varsanyi](https://github.com/gwelican/)

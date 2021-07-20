<div align="center">

# asdf-fzf [![Build](https://github.com/nklmilojevic/asdf-fzf/actions/workflows/build.yml/badge.svg)](https://github.com/nklmilojevic/asdf-fzf/actions/workflows/build.yml) [![Lint](https://github.com/nklmilojevic/asdf-fzf/actions/workflows/lint.yml/badge.svg)](https://github.com/nklmilojevic/asdf-fzf/actions/workflows/lint.yml)


[fzf](https://github.com/junegunn/fzf) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add fzf
# or
asdf plugin add fzf https://github.com/nklmilojevic/asdf-fzf.git
```

fzf:

```shell
# Show all installable versions
asdf list-all fzf

# Install specific version
asdf install fzf latest

# Set a version globally (on your ~/.tool-versions file)
asdf global fzf latest

# Now fzf commands are available
fzf --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/nklmilojevic/asdf-fzf/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Nikola Milojević](https://github.com/nklmilojevic/)

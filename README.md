<div align="center">

# asdf-sass [![Build](https://github.com/vimalloc/asdf-sass/actions/workflows/build.yml/badge.svg)](https://github.com/vimalloc/asdf-sass/actions/workflows/build.yml) [![Lint](https://github.com/vimalloc/asdf-sass/actions/workflows/lint.yml/badge.svg)](https://github.com/vimalloc/asdf-sass/actions/workflows/lint.yml)

[sass](https://github.com/vimalloc/sass) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add sass
# or
asdf plugin add sass https://github.com/vimalloc/asdf-sass.git
```

sass:

```shell
# Show all installable versions
asdf list-all sass

# Install specific version
asdf install sass latest

# Set a version globally (on your ~/.tool-versions file)
asdf global sass latest

# Now sass commands are available
sass --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/vimalloc/asdf-sass/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Lily Acadia Gilbert](https://github.com/vimalloc/)

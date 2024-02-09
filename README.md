<div align="center">

# asdf-cljstyle [![Build](https://github.com/abogoyavlensky/asdf-cljstyle/actions/workflows/build.yml/badge.svg)](https://github.com/abogoyavlensky/asdf-cljstyle/actions/workflows/build.yml) [![Lint](https://github.com/abogoyavlensky/asdf-cljstyle/actions/workflows/lint.yml/badge.svg)](https://github.com/abogoyavlensky/asdf-cljstyle/actions/workflows/lint.yml)

[cljstyle](https://github.com/greglook/cljstyle) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Dependencies

- `bash`, `curl`, `unzip`

# Install

Plugin:

```shell
asdf plugin add cljstyle
# or
asdf plugin add cljstyle https://github.com/abogoyavlensky/asdf-cljstyle.git
```

cljstyle:

```shell
# Show all installable versions
asdf list-all cljstyle

# Install specific version
asdf install cljstyle latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cljstyle latest

# Now cljstyle commands are available
cljstyle version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/abogoyavlensky/asdf-cljstyle/graphs/contributors)!


## License

Copyright © 2024 [Andrey Bogoyavlenskiy](https://github.com/abogoyavlensky/)

Distributed under the MIT License.

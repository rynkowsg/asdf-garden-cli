<div align="center">

# asdf-garden-cli
[![GitHub Actions Test Status][ci-actions-test-badge]][ci-actions-test]
[![GitHub Actions Lint Status][ci-actions-lint-badge]][ci-actions-lint]
[![CircleCI Lint Status][ci-circleci-lint-badge]][ci-circleci-lint]
[![License][license-badge]][license]

[asdf version manager][asdf-website] plugin for [garden-cli][garden-cli-repo], a CLI tool of [application.garden][application.garden-website].

</div>

## Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [License](#license)

## Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

## Install

Install the plugin:

```shell
asdf plugin add garden-cli https://github.com/rynkowsg/asdf-garden-cli.git
```

Install garden-cli:

```shell
# Show all installable versions
asdf list-all garden-cli

# Install specific version
asdf install garden-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global garden-cli latest

# Now garden commands are available
garden --help
```

Check [application.garden docs][application.garden-docs] for more instructions on how to use garden CLI tool.

## License

See [LICENSE](LICENSE) © [Grzegorz Rynkowski][gh-profile-rynkowsg]

[application.garden-docs]: https://docs.apps.garden/
[application.garden-website]: https://application.garden/
[asdf-website]: https://asdf-vm.com
[ci-actions-lint-badge]: https://github.com/rynkowsg/asdf-garden-cli/actions/workflows/lint.yml/badge.svg
[ci-actions-lint]: https://github.com/rynkowsg/asdf-garden-cli/actions/workflows/lint.yml
[ci-actions-test-badge]: https://github.com/rynkowsg/asdf-garden-cli/actions/workflows/test.yml/badge.svg
[ci-actions-test]: https://github.com/rynkowsg/asdf-garden-cli/actions/workflows/test.yml
[ci-circleci-lint-badge]: https://circleci.com/gh/rynkowsg/asdf-garden-cli.svg?style=shield
[ci-circleci-lint]: https://circleci.com/gh/rynkowsg/asdf-garden-cli
[garden-cli-repo]: https://github.com/nextjournal/garden-cli
[gh-profile-rynkowsg]: https://github.com/rynkowsg
[license-badge]: https://img.shields.io/badge/license-MIT-lightgrey.svg
[license]: LICENSE

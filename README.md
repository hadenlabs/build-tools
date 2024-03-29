<!--


  ** DO NOT EDIT THIS FILE
  **
  ** 1) Make all changes to `provision/generator/README.yaml`
  ** 2) Run`task readme` to rebuild this file.
  **
  ** (We maintain HUNDREDS of open source projects. This is how we maintain our sanity.)
  **


  -->

[![Latest Release](https://img.shields.io/github/release/hadenlabs/build-tools)](https://github.com/hadenlabs/build-tools/releases) [![Lint](https://img.shields.io/github/workflow/status/hadenlabs/build-tools/lint-code)](https://github.com/hadenlabs/build-tools/actions?workflow=lint-code) [![CI](https://img.shields.io/github/workflow/status/hadenlabs/build-tools/ci)](https://github.com/hadenlabs/build-tools/actions?workflow=ci) [![Test](https://img.shields.io/github/workflow/status/hadenlabs/build-tools/test)](https://github.com/hadenlabs/build-tools/actions?workflow=test) [![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://github.com/pre-commit/pre-commit) [![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow)](https://conventionalcommits.org) [![KeepAChangelog](https://img.shields.io/badge/changelog-Keep%20a%20Changelog%20v1.0.0-orange)](https://keepachangelog.com)

# build-tools

build-tools for hadenlabs.

## Requirements

This is a list of applications that need to be installed previously to enjoy all the goodies of this configuration:

- [Pyenv](https://github.com/pyenv/pyenv)
- [Docker](https://www.docker.com/)
- [Tfenv](https://github.com/tfutils/tfenv)
- [Terragrunt](https://github.com/gruntwork-io/terragrunt)
- [terraform-docs](https://github.com/segmentio/terraform-docs)

or

- [zsh-pyenv](https://github.com/luismayta/zsh-pyenv)
- [zsh-docker](https://github.com/hadenlabs/zsh-docker)
- [zsh-tfenv](https://github.com/luismayta/zsh-tfenv)

## Usage

# How to use this project

```bash
docker run \
  --rm \
  -v "$(pwd)":/usr/src/app \
  --name build-tools \
  hadenlabs/build-tools:0.2.0
```

## Examples

<!-- Space: Projects -->
<!-- Parent: BuildTools -->
<!-- Title: Examples BuildTools -->
<!-- Label: Examples -->
<!-- Include: ./../disclaimer.md -->
<!-- Include: ac:toc -->

### Common

## Help

**Got a question?**

File a GitHub [issue](https://github.com/hadenlabs/build-tools/issues).

## Contributing

See [Contributing](./docs/contributing.md).

## Module Versioning

This Module follows the principles of [Semantic Versioning (SemVer)](https://semver.org/).

Using the given version number of `MAJOR.MINOR.PATCH`, we apply the following constructs:

1. Use the `MAJOR` version for incompatible changes.
1. Use the `MINOR` version when adding functionality in a backwards compatible manner.
1. Use the `PATCH` version when introducing backwards compatible bug fixes.

### Backwards compatibility in `0.0.z` and `0.y.z` version

- In the context of initial development, backwards compatibility in versions `0.0.z` is **not guaranteed** when `z` is increased. (Initial development)
- In the context of pre-release, backwards compatibility in versions `0.y.z` is **not guaranteed** when `y` is increased. (Pre-release)

## Copyright

Copyright © 2018-2022 [Hadenlabs](https://hadenlabs.com)

## Trademarks

All other trademarks referenced herein are the property of their respective owners.

## License

The code and styles are licensed under the LGPL-3.0 license [See project license.](LICENSE).

## Don't forget to 🌟 Star 🌟 the repo if you like build-tools

[Your feedback is appreciated](https://github.com/hadenlabs/build-tools/issues)

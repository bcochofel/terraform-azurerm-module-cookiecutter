# terraform-azurerm-module-cookiecutter

[![pre-commit badge][pre-commit-badge]][pre-commit] [![Conventional commits badge][conventional-commits-badge]][conventional-commits] [![Keep a Changelog v1.1.0 badge][keep-a-changelog-badge]][keep-a-changelog] [![MIT License Badge][license-badge]][license]

## Usage

Use this repository to create a Terraform module for AzureRM.
The `name` should be:

`terraform-azurerm-<resource>`

```bash
pip install cookiecutter
cookiecutter gh:bcochofel/terraform-azurerm-module-cookiecutter
```

This repository initializes git and pre-commit using post hook.
Check [here](hooks/post_gen_project.sh) for more info.

## pre-commit hooks

Read the [pre-commit hooks](docs/pre-commit-hooks.md) document for more info.

[pre-commit]: https://github.com/pre-commit/pre-commit
[pre-commit-badge]: https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white
[conventional-commits-badge]: https://img.shields.io/badge/Conventional%20Commits-1.0.0-green.svg
[conventional-commits]: https://conventionalcommits.org
[keep-a-changelog-badge]: https://img.shields.io/badge/changelog-Keep%20a%20Changelog%20v1.1.0-%23E05735
[keep-a-changelog]: https://keepachangelog.com/en/1.0.0/
[license]: ./LICENSE
[license-badge]: https://img.shields.io/badge/license-MIT-green.svg
[changelog]: ./CHANGELOG.md
[changelog-badge]: https://img.shields.io/badge/changelog-Keep%20a%20Changelog%20v1.1.0-%23E05735

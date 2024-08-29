# {{ cookiecutter.name }}

{{ cookiecutter.description }}

## Usage

```hcl
```

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Run tests

```bash
cd test/
go test -v
```

## pre-commit hooks

This repository uses [pre-commit](https://pre-commit.com/).

To install execute:

```bash
pre-commit install
pre-commit install --install-hooks -t commit-msg
```

To run the hooks you need to install:

* [terraform](https://github.com/hashicorp/terraform)
* [terraform-docs](https://github.com/terraform-docs/terraform-docs)
* [TFLint](https://github.com/terraform-linters/tflint)
* [TFSec](https://github.com/tfsec/tfsec)
* [checkov](https://github.com/bridgecrewio/checkov)
* [goimports](https://pkg.go.dev/golang.org/x/tools/cmd/goimports)
* [golint](https://pkg.go.dev/golang.org/x/lint/golint)

## References

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

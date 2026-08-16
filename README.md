# python-package-template

Opinionated template for creating modern python packages

## Usage

```shell
copier copy gh:asynq-io/python-package-template [DESTINATION_FOLDER]
```

## Features

- `uv` for dependency management and `uv_build` build backend
- Dependency groups (`dev`, `test`, `lint`, `docs`)
- Pre-configured linters & checkers (ruff with `ALL` rules, mypy, bandit)
- Pytest setup with coverage, sugar, repeat and timeout plugins
- `py.typed` marker and typed package layout
- pre-commit config
- Dependabot for automatic updates of Github Actions and python dependencies
- Pull request pipeline with all the checks and coverage report
- Publish to PyPi workflow on release

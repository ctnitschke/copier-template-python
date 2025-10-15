# My personal Python cookiecutter

## Structure

```
├── README.md        <-- The top-level README for users
├── .gitignore       <-- .gitignore with things I commonly don't want to check in in a Python project
├── pyproject.toml   <-- The project configuration file
└── src
    └── <package_name>   <-- The main package directory
        └── __init__.py  <-- A standard __init__.py file
```

## Baked-in tooling

### pytest with coverage

Testing.

### ruff

Linter and code formatter.

### mypy

Type checker.

### Environment managers

The template supports `poetry` or `uv` as environment managers, or doing things by hand using `venv` and `pip`.

### VCS-based versioning

Versions are derived from version control using either
[`poetry-dynamic-versioning`](https://github.com/mtkennerly/poetry-dynamic-versioning)
when using poetry or [`setuptools-scm`](https://github.com/pypa/setuptools-scm) when not.

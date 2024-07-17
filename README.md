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

Linter.

### black

Code formatter.

### mypy

Type checker.

# pre-commit-pyright

Pre-commit hook for running pyright static type checker

## Usage

Note that this hook is going to honor any configuration files defined in your repository.

### If you use poetry

In your `.pre-commit-config.yaml`:

```yaml
-   repo: https://github.com/zmievsa/pre-commit-pyright
    rev: '1.1.355'
    hooks:
    -   id: poetry
```

### If you use pdm

In your `.pre-commit-config.yaml`:

```yaml
-   repo: https://github.com/zmievsa/pre-commit-pyright
    rev: '1.1.355'
    hooks:
    -   id: pdm
```

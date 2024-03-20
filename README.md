# pre-commit-pyright-poetry

Pre-commit hook for running pyright static type checker with poetry

## Usage:

In your `.pre-commit-config.yaml`:

```yaml
-   repo: https://github.com/zmievsa/pre-commit-pyright-poetry
    rev: '1.1.355'
    hooks:
    -   id: pyright
```

If you have pyright configuration in `pyrightconfiguration.json` or `pyproject.toml`, this hook will honor it.

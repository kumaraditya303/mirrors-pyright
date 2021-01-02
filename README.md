# pyright mirror

Mirror of pyright package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For pyright: see https://github.com/microsoft/pyright

### Using pyright with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/kumaraditya303/mirrors-pyright
  rev: "" # Use the sha / tag you want to point at
  hooks:
    - id: pyright
```

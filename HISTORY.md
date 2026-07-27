# HISTORY

### initialize uv project

```shell
uv init . --python 3.10
uv sync
```

### add pre-commit with default hooks

```shell
uv add --dev pre-commit
uv run pre-commit sample-config > .pre-commit-config.yaml
```

Update the `rev` of [pre-commit-hooks](https://github.com/pre-commit/pre-commit-hooks) from `v3.2.0` to `v6.0.0`.

```shell
uv run pre-commit install
uv run pre-commit run --all-files
```

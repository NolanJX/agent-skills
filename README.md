# python-uv-template

A minimal Python project template powered by uv, with ruff, ty, and pre-commit pre-configured.

## Usage

1. [Create a new repository from this template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template).
2. Replace `python-uv-template` with your project name in `pyproject.toml`.
3. Install dependencies and pre-commit hooks:
    ```shell
    uv sync
    uv run pre-commit install
    ```
4. Rewrite the `README.md` to describe your project.

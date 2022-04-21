# Pre-Commit

Install pre-commit from
[https://pre-commit.com/#install](https://pre-commit.com/#install)

Create a `.pre-commit-config.yaml` file at the root of your repository with the following content:

```yaml
    repos:
      - repo: https://github.com/timcleaver/scc-system-pre-commit-hook
        rev: HEAD
        hooks:
          - id: scc-system
```

Make sure that you have installed [scc](https://github.com/boyter/scc) and it
is available on your \$PATH. On macos you can install via `homebrew`:

```sh
brew install scc
```

# Contributing

## Testing Locally

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test cosmo-router https://github.com/GodTamIt/asdf-cosmo-router.git "router --help"
```

Tests are automatically run in GitHub Actions on push and PR.

## Lint & Format

```shell
./scripts/format.bash
./scripts/lint.bash
```

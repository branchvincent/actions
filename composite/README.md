# Composite

This is an example composite action take from [here](https://docs.github.com/en/actions/creating-actions/creating-a-composite-run-steps-action).

## Usage

```yaml
jobs:
  main:
    runs-on: ubuntu-latest
    steps:
      - uses: branchvincent/actions/composite@main
        with:
          who-to-greet: me!
```

## Limitations

Currently, a composite action cannot reference another action. See <https://github.com/actions/runner/issues/646>.

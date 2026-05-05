# Experiments

Each experiment should have its own folder:

```text
experiments/001_nnunet_v2_acdc/
  config.yaml
  commands.md
  results.md
  failure_cases.md
```

## Experiment Rules

- Record exact commands.
- Record git commit hash when available.
- Record dataset version and split.
- Record hardware and runtime.
- Keep generated predictions out of git.
- Add only small figures or compressed screenshots if they are useful for the report.

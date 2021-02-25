# AWS RDS Restore

## Usage

```yaml
- uses: branchvincent/actions/aws-rds-restore@main
  with:
    source: source_id
    target: target_id
  env:
    AWS_ACCESS_KEY_ID: foo
    AWS_SECRET_ACCESS_KEY: bar
    AWS_DEFAULT_REGION: us-east-1
```

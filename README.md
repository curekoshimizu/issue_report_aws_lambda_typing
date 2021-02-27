# issue_report_aws_lambda_typing
Issue report for aws lambda typing

## How to use

```
poetry install
./lint.bash
aws_lambda/app.py:1: error: Skipping analyzing 'aws_lambda_typing': found module but no type hints or library stubs  [import]
aws_lambda/app.py:1: note: See https://mypy.readthedocs.io/en/latest/running_mypy.html#missing-imports
```

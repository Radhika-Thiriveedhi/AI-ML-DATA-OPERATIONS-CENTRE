# Contributing

## Local checks

Run the following checks before opening a pull request:

```powershell
python -m compileall app services run.py
python -m pytest
```

Keep changes focused, preserve the stateless service contract, and add or update tests when behavior changes.

## Pull requests

Use a short branch name that describes the change. The pull request description should explain the behavior changed, the validation performed, and any operational considerations.
# Testing Guide

The test suite covers the Flask application and service behavior with `pytest`.

Run the full suite with:

```powershell
python -m pytest
```

For a quick source check, compile the application and services:

```powershell
python -m compileall app services run.py
```

When changing a route or service contract, add a focused test in `tests/` and verify both successful and invalid input paths.
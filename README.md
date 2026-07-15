# Common Pipelines

Shared CI for the **SDET-org** microrepositories (automated test projects).

## Files

| File | Purpose |
| --- | --- |
| `.github/workflows/tests-common-python.yml` | Reusable workflow (`on: workflow_call`) with the Python-tests pipeline: mypy + ruff → pytest → build & publish Allure report. Called from a microrepo via `uses:`. |

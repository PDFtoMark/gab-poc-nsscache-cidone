# PoC: workflow_run untrusted artifact -> GITHUB_OUTPUT injection

Mirrors google/nsscache `.github/workflows/ci-done.yml` (workflow_run on "CI",
downloads the "test-results" artifact produced by the untrusted PR run).

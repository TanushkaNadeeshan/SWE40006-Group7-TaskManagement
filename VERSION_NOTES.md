# Phase 5 — CI and deployment preparation (reconstructed)
Expanded full application with GitHub Actions CI (`.github/workflows/ci.yml`) and deployment instructions. The release workflow is withheld for the final checkpoint.

CAUTION: The current CI workflow exercises Docker's optional monitoring profile; its missing Prometheus files in this snapshot mean the workflow needs adapting before it can pass. This is a *review checkpoint*, not a verified deployable release. Run tests and build, and do not deploy until the workflow is corrected and browser testing completed.

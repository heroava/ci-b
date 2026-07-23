# CI Pipeline

Automated CI/CD pipeline for repository maintenance and code quality assurance.

Runs hourly to analyze code, verify dependencies, and generate build artifacts.

## Configuration

Secrets required in repository settings:

| Secret | Purpose |
|---|---|
| `APP_ID` | Application identifier |
| `PRIVATE_KEY` | Authentication key |
| `INSTALLATION_ID` | Installation identifier |
| `PAT_TOKEN` | Access token for pipeline runtime |
| `SCANNER_REPO` | Pipeline runtime repository (org/repo) |

## Output

Build artifacts are published to `ci_artifacts/` on each run.

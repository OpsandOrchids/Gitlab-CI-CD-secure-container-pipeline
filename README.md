# Gitlab-CI-CD-secure-container-pipeline
A reusable GitLab CI/CD pipeline that lints, builds, scans, and publishes container images, then deploys them with Docker Compose. It authenticates to cloud IAM through short-lived OIDC tokens, so no long-lived credentials are stored in CI variables.

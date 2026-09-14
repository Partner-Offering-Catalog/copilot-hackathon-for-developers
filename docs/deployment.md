# Deployment

Describe each environment, the promotion path, approval owners, release
versioning, and rollback procedure. Link to the CI/CD workflow and
infrastructure-as-code once they exist. Do not copy environment credentials,
deployment keys, or production URLs into this document.

## Publishing this knowledge base

Use Hugo or the organization-approved static-site generator with its source in
`docs/`. This template publishes through the `Deploy documentation` GitHub
Actions workflow rather than a branch. In repository **Settings > Pages**,
select **GitHub Actions** as the build and deployment source. The workflow
builds `docs/` with Hugo and deploys the generated artifact. Publish only
non-sensitive documentation, and validate generated links before release.

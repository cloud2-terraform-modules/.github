# Cloud2 Default Organization Configuration

This repository provides default configurations for Cloud2-owned GitHub organizations.

## Default Health Files

- These files automatically apply to any repository within this organization unless overridden by repository-specific files.
- They won’t appear in each repository’s file browser but will still be used automatically when relevant (e.g., opening a PR).
- If a repository needs customized versions, create the required file in the repository’s root directory.

For more details, see [GitHub Docs: Creating a Default Community Health File](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

### Pull Request Template

Our Pull Request template emphasizes security considerations in daily development, covering both software and infrastructure changes.

## GitHub Actions Workflows

We also include GitHub Actions workflows and workflow templates aimed at strengthening security across repositories.

- **Reusable Workflows**: Centrally defined workflows that can be referenced by any repostitory. You can find them in the [`.github/workflows`](.github/workflows) directory.
- **Workflow Templates**: Can be accessed easily from the GitHub UI when creating a new workflow.

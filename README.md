# Default Health Files for Cloud2 GitHub Organizations


This repository provides default health files for all repositories within Cloud2-owned GitHub organizations. These files automatically apply to any repository within this organization unless overridden by repository-specific files.

## How Default Files Work

* These files won’t appear in the file browser of each repository but will be used automatically when relevant (e.g., when opening a PR).
* If a repository needs customized versions, create the required file in the repository’s root directory.
* If an entire organization requires different default files, a separate .github repository can be created in that organization to override these defaults.

For more details, see [GitHub Docs: Creating a Default Community Health File](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

## Pull Request Template

The pull request template is focused on bringing security considerations to be a part of every day work. It covers software development as well as infrastructure development.
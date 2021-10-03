# Azure DevOps Templates and Scripts

This repository contains some of the scripts and templates that I use in Azure Pipelines.

| File                                                                         | Description                                                             |
| ---------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| [tag-sources.yml](./templates/git/tag-sources.yml)                           | Create a git tag and push it                                            |
| [doctl.yml](./templates/tools/doctl.yml)                                     | Install and authenticate [doctl](https://github.com/digitalocean/doctl) |
| [get-package-version.yml](./templates/nuget/get-package-version.yml)         | Get latest package version from NuGet and update SemVer                 |
| [get-updated-package-version.ps1](./scripts/get-updated-package-version.ps1) | Script to get latest package version from NuGet and update SemVer       |

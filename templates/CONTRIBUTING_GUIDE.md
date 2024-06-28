# Contributing

This package is maintained by the [TEAM] team. Ask for help or a review in the [#[TEAM SLACK NAME]]([TEAM SLACK NAME LINK]) Slack channel.

## :gear: Setup

<!-- When applicable, list system requirements to work on the project. -->

The following setup is required to work on this project:

- Prerequisite 1
- Prerequisite 2
- Prerequisite 3

## :memo: Project-specific notes

<!-- Share information about the repository. -->
<!-- What specific knowledge do contributors need? -->

> [!TIP]
> Please update this section with helpful notes for contributors.

## :construction_worker: Develop

> [!NOTE]
> It's highly recommended to discuss your changes with the [TEAM] team before starting.
>
> A short discussion can accelerate your work and ship it faster.

```sh
# Clone and prepare the project.
git clone [REPO SSH ADDRESS]
cd [REPO NAME]
[DEPENDENCY INSTALL COMMAND]

# Create a new branch for your changes (e.g. lh/fix-win32-paths).
git checkout -b <your-initials>/<feature-or-fix-description>

# Start the development server.
# Run this command while you are working on your changes.
[DEV SERVER COMMAND]

# Build the project for production.
# Run this command when you want to see the production version.
[BUILD COMMAND]

# Lint your changes before requesting a review. No errors are allowed.
[LINT COMMAND]

# Format your changes before requesting a review. No errors are allowed.
[FORMAT COMMAND]

# Test your changes before requesting a review.
# All changes should be tested. No failing tests are allowed.
[TEST COMMAND]
```

## :building_construction: Submit a pull request

> [!NOTE]
> Code should be reviewed by the [TEAM] team before merging.
>
> Request a review in the [#[TEAM SLACK NAME]]([TEAM SLACK LINK]) Slack channel.

```sh
# Open a pull request. This example uses the GitHub CLI.
gh pr create

# Perform a review within your team. This review should at least consider
# the PR's general direction, code style, and test coverage.

# Once approved, request a review from the [TEAM] team in #[TEAM SLACK NAME].
# This second review should verify the pull request is not missing crucial
# logic.

# When ready, PRs should be merged using the "Squash and merge" option.
```

<!-- FOR SERVICES: -->
<!-- Delete this section if not applicable. -->

## :rocket: Deploy

Deployments are broken into three stages: development, staging, and production.

#### Development environment

<!-- Describe how to deploy this service to the development environment. -->

#### Staging

<!-- Describe how to deploy this service to the staging environment. -->

#### Production

<!-- Describe how to deploy this service to the production environment. -->

<!-- FOR PACKAGES: -->
<!-- Delete this section if not applicable. -->

## :rocket: Publish

> [!NOTE]
> Ask the [TEAM] team ([#[TEAM SLACK NAME]]([TEAM SLACK NAME LINK])) for [npm](https://www.npmjs.com) publish access before continuing.

```sh
# Checkout the master branch and pull the latest changes.
git checkout master
git pull

# Perform a dry-run and verify the output.
# If it looks good, release a new version.
npm run release:dry
npm run release

# Or release an alpha.
# Perform a dry-run and verify the output.
# If it looks good, release a new alpha version.
npm run release:alpha:dry
npm run release:alpha
```

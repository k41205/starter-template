# starter-template

## Description

I created this handful template to clone as as boilerplate code to quickly set up a new project.

Right now, there it provides just a basic tool called "semantic-release", installed as a dev-dependency and configured to work with GitHub Actions in an already configured CI/CD pipeline.

This template has been thought to work along with GitHub flow strategy. Every time a feature branch is merged to the main branch, it will trigger semantic-release which will update the changelog, update the version in package.json, and handle the creation of a GitHub release of that version.

## Further info

semantic-release documentation: https://semantic-release.gitbook.io/semantic-release/

GitHub flow documentation: https://docs.github.com/en/get-started/using-github/github-flow

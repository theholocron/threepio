# Threepio

This protocol droid contains all protocols (shareable configurations) used within the Galaxy.

## Installation

Please check the README for each configuration within the `packages` directory for specific installation instructions, however the general process is:

```bash
npm install --save-dev @theholocron/<lib>
```

## Table of Contents

- [Usage](#usage)
- [Packages](#the-packages-we-maintain)
- [Documentation](#where-to-find-documentation)
- [Changelog](#how-we-track-changes)
- [Versioning](#how-we-version)
- [Contribution](#how-to-contribute)
- [Support](#where-to-find-suport)
- [Tools](#tools-we-use)
- [Support](#where-to-find-suport)
- [License](#license)

## Usage

Check the README for each configuration within the `packages` directory for specific usage instructions.

## The Packages We Maintain

- [commitlint-config](./packages/commitlint-config#readme) - A CommitLint configuration for writing well-formatted and consistent Git commits.

## Where to Find Documentation

The best way to find out what's available is to dig through source code, as each directory has a README file to describe each feature.

## How We Track Changes [![Keep a Changelog](https://img.shields.io/badge/Keep%20a%20Changelog-1.0.0-orange)](https://keepachangelog.com/en/1.0.0/)

This project uses a CHANGELOG and [GitHub releases](https://help.github.com/en/github/administering-a-repository/about-releases) which contains a curated, chronologically ordered list of notable changes for each version of a project. [Read more about changelogs](https://keepachangelog.com/en/1.0.0/).

## How We Version [![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

We use [SemVer](https://semver.org/) for its versioning providing us an opt-in approach to releases. This means we add a version number according to the spec, as you see below. So rather than force developers to consume the latest and greatest, they can choose which version to consume and test any newer ones before upgrading. Please the read the spec as it goes into further detail.

Given a version number **MAJOR.MINOR.PATCH**, increment the:

- **MAJOR** version when you make incompatible API changes.
- **MINOR** version when you add functionality in a backward-compatible manner.
- **PATCH** version when you make backward-compatible bug fixes.

Additional labels for pre-release and build metadata are available as extensions to the **MAJOR.MINOR.PATCH** format.

## How to Contribute [![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)

Have a bug or a feature request? Looking to contribute to advance the project? Read our [contribution guide](./github/CONTRIBUTING.md) or [maintenance guide](./.github/MAINTAINING.md) first in order to understand how we do things around here. Or you could look at some of our other guides below:

<details>
  <summary><strong>How do I…</strong> (click to expand)</summary>

- [Ask or Say Something?](./.github/SUPPORT.md)
    - [Request Support](./.github/SUPPORT.md#request-support)
    - [Report an Error or Bug](./.github/SUPPORT.md#report-an-error-or-bug)
    - [Request a Feature](./.github/SUPPORT.md#request-a-feature)
- [Make Something?](./.github/CONTRIBUTING.md)
    - [Setup the Project](./.github/CONTRIBUTING.md#get-started)
    - [Create an Issue](./.github/CONTRIBUTING.md#creating-a-good-issue)
    - [Create a Feature Request](./.github/CONTRIBUTING.md#create-a-good-feature-request)
    - [Contribute Documentation](./.github/CONTRIBUTING.md#contribute-to-documentation)
    - [Contribute Code](./.github/CONTRIBUTING.md#create-a-pull-request)
    - [Join the Team](./.github/CONTRIBUTING.md#join-the-team)
- [Manage Something](./.github/MAINTAINING.md)
    - [Provide Support on Issues](./.github/MAINTAINING.md#provide-support-on-issues)
    - [Label Issues](./.github/MAINTAINING.md#label-issues)
    - [Clean Up Issues and PRs](./.github/MAINTAINING.md#clean-up-issues-and-prs)
    - [Create a Pull Request](./.github/MAINTAINING.md#create-a-pull-request)
    - [Review Pull Requests](./.github/MAINTAINING.md#review-pull-requests)
    - [Merge Pull Requests](./.github/MAINTAINING.md#merge-pull-requests)
    - [Tag a Release](./.github/MAINTAINING.md#tag-a-release)
    - [Release a Version](./.github/MAINTAINING.md#release-a-version)

</details>

## Where to Find Support [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](code_of_conduct.md)

Looking to talk to someone or need some help? Please read our [support guidelines](./.github/SUPPORT.md).

## Tools We Use

- [Babel](https://babeljs.io/) - Used to compile JavaScript 
- [Browserslist](https://github.com/browserslist/browserslist) - Used to share to our code which browsers we support
- [CommitLint](https://commitlint.js.org/#/) - Used to ensure our commits follow our standards
- [Conventional Changelog](https://github.com/conventional-changelog/conventional-changelog) - Used to generate our CHANGELOG
- [ESLint](https://eslint.org/) - Used to lint our JavaScript
- [Husky](https://github.com/typicode/husky) - Used for auto-fixing linting errors on each commit
- [Jest](https://jestjs.io/) - Used for testing our JavaScript and (S)CSS
- [MarkdownLint](https://github.com/DavidAnson/markdownlint) - Used to lint our Markdown docs
- [PostCSS](https://postcss.org/) - Used to compile (S)CSS
- [Semantic Release](https://semantic-release.gitbook.io/semantic-release/) - Used for automating and releasing our library
- [StorybookJS](https://storybook.js.org/) - Used for building out our interactive docs
- [StyleLint](https://stylelint.io/) - Used to lint our (S)CSS
- [Webpack](https://webpack.js.org/) - Used to bundle assets
- [@godban's Browser Support Badges](https://godban.github.io/browsers-support-badges) - The tool used to generate the "Which Browsers [sic] We Support" section

## References

- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) - For how we format commit messages
- [Contributor Convenant](https://www.contributor-covenant.org)
- [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) - For building out a quality CHANGELOG
- [Make a README](https://www.makeareadme.com/) - For building out this README
- [SemVer](https://semver.org/) - For versioning this library

## License [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

©2020 GNU General Public License v3. See [LICENSE](./LICENSE.md) for specifics.

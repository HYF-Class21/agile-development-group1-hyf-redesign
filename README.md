# HYF REDESIGN

> Hack Your Future is an IT school which has been founded in 2015 in Amsterdam.
> They aim to empower refugees and migrants by teaching them the necessary
> skills for a career in software development. We will try to redesign their
> website in this project.

## Table of contents

- [HYF Redesign](#name-of-project)
  - [Table of contents](#table-of-contents)
  - [General info](#general-info)
  - [Screenshots](#screenshots)
  - [Technologies](#technologies)
  - [Setup](#setup)
  - [Code Examples](#code-examples)
  - [Features](#features)
  - [Status](#status)
  - [Inspiration](#inspiration)
  - [Contact](#contact)
  - [Instructions for use](#instructions-for-use)
  - [Code Quality Checks](#code-quality-checks)
  - [Continuous Integration (CI)](#continuous-integration-ci)
  - [Repo Setup](#repo-setup)

## General info

> HYF empowers the refugees and newcomers to be a frontend web developer in the
> IT field.

## Screenshots

![Example screenshot](/planning/images/Screenshot-2.png)

![Example screenshot](/planning/images/Screenshot-1.png)

![Example screenshot](/planning/images/Screenshot-3.png)

## Technologies

- Node 14.16.0
- VSC code
- HTML
- CSS
- NPM
- Markdown
- Google Chrome

## Setup

- Fork the project
  [Template](https://github.com/HackYourFutureBelgium/template-html-css) from
  [Tamer Almurshidi](https://github.com/talmurshidi)
- Clone the repository
  > <https://github.com/HYF-Class21/agile-development-group1-hyf-redesign.git>
- Run NPM
  > npm install
- Create branch
  > git branch "branchname"

## Code Examples

-

## Features

To-do list:

- Navbar & Header
- Main Section
  - Info About the Programs
  - Graduation Statistics
  - Core Values & Succes Stories
  - Partners
  - Support Box & Contact
- Footer

Ready:

## Status

Project is: _in progress_

## Inspiration

Website of [HYFBelgium](https://hackyourfuture.be/)

## Contact

- [Mervat](https://github.com/Mervatabuamro)
- [Yun-Hsia](https://github.com/yunhsiaho)
- [Allan](https://github.com/AllanSaku)
- [Ali](https://github.com/alisanlii)

## Instructions for use

<details>
  <summary>Getting Started</summary>

<!-- a guide to using this repository -->

1. `git clone git@github.com:HackYourFutureBelgium/template-markdown.git`
2. `cd template-markdown`
3. `npm install`

## Code Quality Checks

- `npm run format`: Makes sure all the code in this repository is well-formatted
  (looks good).
- `npm run lint:ls`: Checks to make sure all folder and file names match the
  repository conventions.
- `npm run lint:md`: Will lint all of the Markdown files in this repository.
- `npm run lint:css`: Will lint all of the CSS files in this repository.
- `npm run validate:html`: Validates all HTML files in your project.
- `npm run spell-check`: Goes through all the files in this repository looking
  for words it doesn't recognize. Just because it says something is a mistake
  doesn't mean it is! It doesn't know every word in the world. You can add new
  correct words to the [./.cspell.json](./.cspell.json) file so they won't cause
  an error.
- `npm run accessibility -- ./path/to/file.html`: Runs an accessibility analysis
  on all HTML files in the given path and writes the report to
  `/accessibility_report`

## Continuous Integration (CI)

When you open a PR to `main`/`master` in your repository, GitHub will
automatically do a linting check on the code in this repository, you can see
this in the[./.github/workflows/lint.yml](./.github/workflows/lint.yml) file.

If the linting fails, you will not be able to merge the PR. You can double check
that your code will pass before pushing by running the code quality scripts
locally.

## Repo Setup

- Give each member **_write_** access to the repo (if it's a group project)
- Turn on GitHub Pages and put a link to your website in the repo's description
- Turn on GitHub Actions
- In _General_ Section > check **Discussions**
- In the _Branches_ section of your repo's settings make sure the
  `master`/`main` branch must:
  - "_Require a pull request before merging_"
  - "_Require approvals_"
  - "_Dismiss stale pull request approvals when new commits are pushed_"
  - "_Require status checks to pass before merging_"
  - "_Require branches to be up to date before merging_"
  - "_Do not allow bypassing the above settings_"

</details>

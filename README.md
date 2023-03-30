<<<<<<< HEAD

# (project name)

<!-- describe your project -->

## Getting Started

<!-- a guide to using this repository -->

1. `git clone git@github.com:HackYourFutureBelgium/<project-name>.git`
2. `cd project-name`
3. `npm install`

## Code Quality Checks

- `npm run format`: Makes sure all the code in this repository is well-formatted
  (looks good).
- `npm run lint:ls`: Will lint the folder and file names in this repository to
  make sure they match the repo conventions.
- `npm run lint:md`: Will lint all of the Markdown files in this repository and
  let you know if there are any style mistakes to fix.
- `npm run spell-check`: Goes through all the files in this repository looking
  for words it doesn't recognize. Just because it says something is a mistake
  doesn't mean it is! It doesn't know every word in the world. You can add new
  correct words to the [./.cspell.json](./.cspell.json) file so they won't cause
  an error.

## Continuous Integration (CI)

When you open a PR to `main`/`master` in your repository, GitHub will
automatically do a linting check on the code in this repository, you can see
this in the[./.github/workflows/lint.yml](./.github/workflows/lint.yml) file.

If the linting fails, you will not be able to merge the PR. You can double check
that your code will pass before pushing by running `npm run lint:md` locally.

## Repo Setup

- Give each member _write_ access to the repo (if it's a group project)
- Turn on GitHub Pages and put a link to your website in the repo's description
- Turn on GitHub Actions
- in the _Branches_ section of your repo's settings make sure:
  - The repository
    [requires a review](https://github.blog/2018-03-23-require-multiple-reviewers/)
    before pull requests can be merged.
  - The `master`/`main` branch must "_Require status checks to pass before
    merging_"
  - The `master`/`main` branch must "_Require require branches to be up to date
    before merging_" =======

# Group 4 class 20 Intro

## Description

The project we are doing is done by Group4 of class 20 at HYFBE. This project is
about getting to know ourselves in the community of Developers. The group
consists of this members:

![together we can](./Introduction/img/Thank%20you.png)

## Instructions:

Here are the steps we needed to do to complete this project:

- On `Github`:
  - Used `template-markdown` repo as a template for creating.
    `workflows-group4-intro` repo.
  - Protected the `main` branch (Settings -> Branch protection rule).
  - Added team members (Settings -> Collaborators and teams) and assigned all as
    `Admin`.
  - Enabled `Github` pages (Settings -> Pages).
  - Created a `Project` on `Github`.
  - Created `Issues` for the project and linked them to the project.
- On `VSC`:
  - Each team member cloned the repo to his machine, installed npm packages,
    created their own branch and made their own `bio.md` file.
  - Ran all check commands.
  - Added files to the `Staging Area`.
  - Commit the changes with meaningful message.
  - Pushed the changes to `Github` and made `Pull Request`.

---

## What we learnt:

- How to create a new `Repo` from a template one.
- How to add team members, assign their roles in the `repo`.
- How to protect the `repo`'s `master` branch.
- How to create a `Project Board` and use it.
- How to work as a `Team` on the same project.
  > > > > > > > d4ec49e60c33ed739c5fbe5a04244ed258704a58

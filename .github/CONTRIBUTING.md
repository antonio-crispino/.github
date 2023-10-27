# Contributing Guide

This guide covers the prerequisites, setup, and workflow for contributing to this project and repository. It assumes that you already have an understanding of how [Git](https://git-scm.com/doc "Docs"), [GitHub](https://docs.github.com/en "Docs"), and [VS Code](https://code.visualstudio.com/docs "Docs") work. If these topics are unfamiliar to you, there are numerous online learning materials and documentation available.

## Prerequisites & Setup

1. **GitHub**: Ensure that you have a GitHub account. If not, [sign up](https://github.com/ "GitHub") on GitHub's website.

2. **Git**: Ensure that you have **Git installed** on your local machine. If not, you can [download](https://git-scm.com/downloads "Git") it from their website. If you are using Windows, it is recommended to use the Git Bash terminal for all git related operations. Git must be configured with your [`name`](https://docs.github.com/en/get-started/getting-started-with-git/setting-your-username-in-git) and [`email`](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-email-preferences/setting-your-commit-email-address). You must also configure Git to have a `signingkey` for [commit signature verification](https://docs.github.com/en/authentication/managing-commit-signature-verification/about-commit-signature-verification) on GitHub.

3. **Visual Studio Code**: Ensure that you have the Visual Studio Code (VS Code) editor installed on your local machine. If not, you can [download](https://code.visualstudio.com/ "Visual Studio Code (VS Code)") it from their website. In order to collaborate and follow the coding standards of this project, you must use this editor. This project has workspace configuration files for this specific editor within the `.vscode` folder. These files may include [`settings.json`](https://code.visualstudio.com/docs/getstarted/settings), [`extensions.json`](https://code.visualstudio.com/docs/editor/extension-marketplace#_workspace-recommended-extensions), [`tasks.json`](https://code.visualstudio.com/docs/editor/tasks), and [`launch.json`](https://code.visualstudio.com/docs/editor/debugging#_launch-configurations). They configure the VS Code editor's workspace (project) and you must ensure that your user scoped configurations do not override any of them (even user [language-specific settings](https://code.visualstudio.com/docs/getstarted/settings#_language-specific-editor-settings) should not override the default workspace settings that apply to all languages). See VS Code's [settings precedence](https://code.visualstudio.com/docs/getstarted/settings#_settings-precedence) for more information.

   The `extensions.json` file is typically meant to recommend extensions that should be downloaded for the VS Code editor. However, for the purposes of this project, some will be required while others will be optional/recommended. There will be comments within this file to differentiate between the two. All of this will ensure that formatting, linting, schema validation, and many other things are enforced as intended.

4. **Repository**: Ensure that you have [cloned](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) the repository onto your local machine and that it is connected to the remote repository on GitHub.

## Workflow

### 1 - Issues

Before working on this project, an issue regarding the change you would like to make should exist. If it does not exist, create an issue using one of the issue templates available. Be sure to add the relevant labels while filling out the issue template. If applicable, add the project and milestone as well. Once an issue exists, you can assign the issue to yourself, [create a branch](#2---branches), and link the branch to the issue to begin working on the project. If this is not a solo project, you can leave the issue unassigned for someone else to work on, or you can assign it to one or more collaborators best suited to work on the issue.

The following are descriptions of the available **issue templates**:

1. [**Epic**](ISSUE_TEMPLATE/epic-issue-template.md "epic-issue-template.md"): An Epic is a large body of work that is broken down into a number of smaller parts (Stories and Tasks). It is a high-level parent work item that typically involves considerable work to complete. An Epic might encapsulate a new feature, a large enhancement, or any other significant piece of work that is expected to take a long time to complete.

2. [**Story**](ISSUE_TEMPLATE/story-issue-template.md "story-issue-template.md"): A Story (also known as user story) is a work item that represents a requirement or request from the user's perspective, often written from the viewpoint of the end-user. It describes a specific piece of work that needs to be done, usually able to be completed within a single sprint. It is a small, independent piece of work and provides value to the user. Stories are usually part of an Epic to make the work manageable and trackable, but they can be stand-alone. They can be further broken down into child Subtasks.

3. [**Task**](ISSUE_TEMPLATE/task-issue-template.md "task-issue-template.md"): A Task is a work item that needs to be completed but does not fit the narrative style of a Story (user story). It could be any kind of work such as a technical piece of work, conducting a meeting, performing some research, or doing other activities that does not deliver a user-facing feature or fix, but are necessary for the project. Tasks are usually part of an Epic to make the work manageable and trackable, but they can be stand-alone. They can be further broken down into child Subtasks.

4. [**Bug**](ISSUE_TEMPLATE/bug-issue-template.md "bug-issue-template.md"): A Bug is a work item that represents a problem, error, flaw, or fault in the software that needs to be fixed. Bugs can be discovered during testing or reported by users once the software is in use. Bugs are stand-alone. They can be further broken down into child Subtasks.

5. [**Subtask**](ISSUE_TEMPLATE/subtask-issue-template.md "subtask-issue-template.md"): A Subtask is a child work item that is part of a larger Story, Task, or Bug. Subtasks are used to break down the work into smaller, more manageable parts, each of which can be worked on independently. They cannot be further broken down into child Subtasks.

**NOTE:** The current [configuration](.github/ISSUE_TEMPLATE/config.yml "config.yml") does not restrict you from opening blank issues. However, this should be avoided since all issues should fall under one of the provided templates. Regardless, for exceptional circumstances requiring a distinct issue format, this option remains available.

### 2 - Branches

When you create a branch to work on an issue, ensure that the respective issue is linked to the branch. Note that in some cases, a branch can be linked to more than one issue. For example, the changes in a branch can add a feature (issue 1) that in turn fixes a bug (issue 2).

When creating a branch, ensure that you use the following format and naming convention:

```text
<type>/<branch-subject>
```

Where,

1. `<type>` is one of the following (in lowercase):

   - `build` : Changes that affect the build system or external dependencies.
   - `ci` : Changes to CI configuration files and scripts.
   - `docs` : Changes to documentation.
   - `feat` : A new feature.
   - `fix` : A bug fix.
   - `perf` : Changes to code that improves performance.
   - `refactor` : Changes to code that neither fixes a bug nor adds a feature.
   - `revert` : Changes that revert a previous commit.
   - `style` : Changes to code that do not affect its meaning (formatting, etc.).
   - `test` : Changes to existing tests or adding missing tests.
   - `chore` : Changes, additions, configurations, routines, or maintenance tasks that does not fit into any other category. Changes do not modify src or test files.

2. `<branch-subject>` is a short keyword description of what you are working on. All words must be lowercase and separated by hyphens (-). Also, do not add a dot (.) at the end.

**NOTE:** Whenever you create a local branch, make sure to push it to the remote GitHub repository. Additionally, always push any commits you make on that branch to the remote as well. This ensures that the remote repository always has the latest changes and helps prevent potential data loss if something happens to the local environment. Additionally, always ensure that local branches are synchronized with the corresponding branches on the remote repository.

### 3 - Commits

Direct commits to the base branch (main) must never be done. A new branch (head branch) must be made from the base branch, commits must be made to the head branch, then a pull request can be made to merge the head branch into the base branch. Ensure that you make meaningful commits. All commits must have verified signatures. See "[About commit signature verification](https://docs.github.com/en/authentication/managing-commit-signature-verification/about-commit-signature-verification)" to follow the steps to sign commits and have those commits verified on GitHub.

When creating a commit to the head branch, ensure that you use the following format and naming convention:

```text
<type>(#<issue-id-number>): <commit-subject>
```

Where,

1. `<type>` is one of the types mentioned in the "Branches" section (in lowercase).

2. `<issue-id-number>` is the id number given to the specific GitHub issue. Note that in some cases, a commit can be linked to more than one issue. For example, the changes in a commit can add a feature (issue 1) that in turn fixes a bug (issue 2). In this case, add comma separated issue ids within the parentheses. The first id number is the one related to the main change, and the `<type>` (since there can only be one) is related to the first id.

3. `<commit-subject>` is a brief description of the change. Use imperative (command or instruction) and present tense language. For example, use "change", not "changed" nor "changes". Do not capitalize the first letter and do not add a dot (.) at the end.

**NOTE:** As for the merge commit that GitHub auto generates when merging a pull request from the website, leave it as is. All merge commits should use GitHub's auto generated message. As for the first commit in the repository, the commit message may be "Initial commit" which is fine.

### 4 - Pull Requests (PR)

Once all changes are committed to the head branch, you can open a pull request to merge it into the base branch. Fill out the [default general pull request template](pull_request_template.md "pull_request_template.md") to describe the changes and to ensure that guidelines were followed. Add yourself as an assignee if the PR is created for your branch. In certain situations, you might designate additional assignees to share responsibility for the PR. Be aware that assignees are not the same as [reviewers](#5---reviews). Be sure to add the relevant labels while filling out the PR template. If applicable, add the project and milestone as well. Ensure that the related issue(s) is/are linked to the PR. Resolve any merge conflicts that may arise.

### 5 - Reviews

Once the pull request is made, one or more reviewers can approve or request changes. You can add them or they can add themselves as reviewers. For solo projects, the owner should still make a pull request and review it themselves. Regardless, if all is approved, the branch is ready to be merged. If changes have been requested, make the changes with another commit and await approval.

### 6 - Merging

Once the pull request is approved with no conflicts and all checks have passed (if applicable), merge the head branch into the base branch. Do this through the GitHub website and replace the default commit message (see the "[Commits](#3---commits)" section for more information). Squash/Rebase and merge options are not allowed. Close the pull request and issue. Finally, delete the head branch from the remote repository and from your local repository.

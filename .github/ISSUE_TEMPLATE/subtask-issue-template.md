---
name: Subtask Issue Template
about: A Subtask is a smaller component of a larger Story, Task, or Bug, designed to make work more manageable and allow for independent progress. Subtasks cannot be further divided.
title: "[SUBTASK: E###-[S/T]###-ST### or [S/T/B]###-ST###] Subtask Brief Description"
labels: subtask
assignees: ""
---

# Subtask: [E###](https://github.com/<username>/<repository-name>/issues/<issue-id-number> "Grandparent Issue (Epic)")-[[S/T]###](https://github.com/<username>/<repository-name>/issues/<issue-id-number> "Parent Issue (Story/Task/Bug)")-ST### or [[S/T/B]###](https://github.com/<username>/<repository-name>/issues/<issue-id-number> "Parent Issue (Story/Task/Bug)")-ST### <span id="st-subtask">

A brief summary of the Subtask.

## Table of Contents <span id="st-table-of-contents">

1. [Type :label:](#st-type "The type of Subtask.")
2. [Description :memo:](#st-description "A detailed description of the Subtask. This includes any relevant context, requirements, and constraints.")
3. [Priority :exclamation:](#st-priority "The priority of the Subtask (MoSCoW method).")
4. [Subtask Points (STP) :star:](#st-subtask-points-stp "The estimated effort required to complete the Subtask.")
5. [Dependencies :chains:](#st-dependencies "A list of dependencies required for the completion of the Subtask.")
6. [Acceptance Criteria :heavy_check_mark:](#st-acceptance-criteria "A list of conditions that must be met for the Subtask to be considered complete.")
7. [Sub-Subtasks :clipboard:](#st-sub-subtasks "A list of sub-subtasks required to complete the Subtask. These do not have their own Subtask issues.")
8. [Parent Issue (Story/Task/Bug) :link:](#st-parent-issue-storytaskbug "The parent issue (Story/Task/Bug) for this Subtask.")
9. [Grandparent Issue (Epic) :link:](#st-grandparent-issue-epic "The grandparent issue (Epic) for this Subtask, if it has one.")
10. [Resources :books:](#st-resources "A list of useful resources/links for the Subtask.")
11. [Notes :pencil2:](#st-notes "A list of additional information about the Subtask.")

## 1 - Type :label: <span id="st-type">

> _The type of Subtask. Select one of the following types and add it as a label as well:_
>
> 1. :hammer_and_wrench: `build` (build): Changes that affect the build system or external dependencies.
> 2. :gear: `ci` (ci): Changes to CI configuration files and scripts.
> 3. :books: `documentation` (docs): Changes to documentation.
> 4. :sparkles: `feature` (feat): A new feature.
> 5. :bug: `fix` (fix): A bug fix.
> 6. :rocket: `performance` (perf): Changes to code that improves performance.
> 7. :package: `refactor` (refactor): Changes to code that neither fixes a bug nor adds a feature.
> 8. :wastebasket: `revert` (revert): Changes that revert a previous commit.
> 9. :gem: `style` (style): Changes to code that do not affect its meaning (formatting, etc.).
> 10. :rotating_light: `test` (test): Changes to existing tests or adding missing tests.
> 11. _:recycle: `chore` (chore): Changes, additions, configurations, routines, or maintenance tasks that does not fit into any other category. Changes do not modify src or test files._

[`type`]

## 2 - Description :memo: <span id="st-description">

> _A detailed description of the Subtask. This includes any relevant context, requirements, and constraints._

## 3 - Priority :exclamation: <span id="st-priority">

> _The priority of the Subtask (MoSCoW method). Select one of the following priorities:_
>
> 1. :sunny: `must-have`
> 2. :large_orange_diamond: `should-have`
> 3. :large_blue_diamond: `could-have`
> 4. :no_entry: `won't-have`

[`priority`]

## 4 - Subtask Points (STP) :star: <span id="st-subtask-points-stp">

> _The estimated effort required to complete the Subtask. This is estimated using subtask points (STP), which are based on and equivalent to user story points (USP). The number of subtask points allocated is a portion selected from the points (USP, TP, or BP) of the parent issue (Story/Task/Bug)._

[Points] STP

## 5 - Dependencies :chains: <span id="st-dependencies">

> _A list of dependencies required for the completion of the Subtask._

1. **The Subtask** depends on the completion of [other Epic/Story/Task/Bug/Subtask - include link].
2. **The Subtask** cannot start until [other Epic/Story/Task/Bug/Subtask - include link] is completed.
3. **The Subtask** is blocked by [other Epic/Story/Task/Bug/Subtask - include link].

## 6 - Acceptance Criteria :heavy_check_mark: <span id="st-acceptance-criteria">

> _A list of conditions that must be met for the Subtask to be considered complete. This can use the Given-When-Then (GWT) format and/or other statement formats if appropriate._

1. **Given** [Context], **when** [Action], **then** [Expected Result].
2. **Given** [Context], **when** [Action], **then** [Expected Result].
3. Acceptance criteria 3

## 7 - Sub-Subtasks :clipboard: <span id="st-sub-subtasks">

> _A list of sub-subtasks required to complete the Subtask. These do not have their own Subtask issues._

- [ ] 1. Sub-Subtask 1
- [ ] 2. Sub-Subtask 2
- [ ] 3. Sub-Subtask 3

## 8 - Parent Issue (Story/Task/Bug) :link: <span id="st-parent-issue-storytaskbug">

> _The parent issue (Story/Task/Bug) for this Subtask._

[Story/Task/Bug E###-[S/T]### or [S/T/B]###](https://github.com/<username>/<repository-name>/issues/<issue-id-number> "Parent Issue (Story/Task/Bug)"): Story/Task/Bug brief description.

## 9 - Grandparent Issue (Epic) :link: <span id="st-grandparent-issue-epic">

> _The grandparent issue (Epic) for this Subtask, if it has one._

None _or_

[Epic E###](https://github.com/<username>/<repository-name>/issues/<issue-id-number> "Parent Issue (Epic)"): Epic brief description.

## 10 - Resources :books: <span id="st-resources">

> _A list of useful resources/links for the Subtask._

1. [Resource 1](#)
2. [Resource 2](#)
3. [Resource 3](#)

## 11 - Notes :pencil2: <span id="st-notes">

> _A list of additional information about the Subtask._

1. Note 1
2. Note 2
3. Note 3

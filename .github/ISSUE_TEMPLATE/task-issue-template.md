---
name: Task Issue Template
about: A Task is a work item that does not fit the narrative style of a Story (user story). Tasks can be part of a larger Epic and can be divided into Subtasks for easier management and tracking.
title: "[TASK: E###-T### or T###] Task Brief Description"
labels: task
assignees: ""
---

# Task: [E###](https://github.com/<username>/<repository-name>/issues/<issue-id-number> "Parent Issue (Epic)")-T### or T### <span id="t-task">

A brief summary of the Task.

## Table of Contents <span id="t-table-of-contents">

1. [Type :label:](#t-type "The type of Task.")
2. [Description :memo:](#t-description "A detailed description of the Task. This includes any relevant context, requirements, and constraints.")
3. [Priority :exclamation:](#t-priority "The priority of the Task (MoSCoW method).")
4. [Task Points (TP) :star:](#t-task-points-tp "The estimated effort required to complete the Task.")
5. [Dependencies :chains:](#t-dependencies "A list of dependencies required for the completion of the Task.")
6. [Acceptance Criteria :heavy_check_mark:](#t-acceptance-criteria "A list of conditions that must be met for the Task to be considered complete.")
7. [Subtasks :clipboard:](#t-subtasks "A list of subtasks required to complete the Task. These do not need to have their own Subtask issues, but they could.")
8. [Parent Issue (Epic) :link:](#t-parent-issue-epic "The parent issue (Epic) for this Task, if it has one.")
9. [Resources :books:](#t-resources "A list of useful resources/links for the Task.")
10. [Notes :pencil2:](#t-notes "A list of additional information about the Task.")

## 1 - Type :label: <span id="t-type">

> _The type of Task. Select one of the following types and add it as a label as well:_
>
> 1. :hammer_and_wrench: `build` (build): Changes that affect the build system or external dependencies.
> 2. :gear: `ci` (ci): Changes to CI configuration files and scripts.
> 3. :books: `documentation` (docs): Changes to documentation.
> 4. :rocket: `performance` (perf): Changes to code that improves performance.
> 5. :package: `refactor` (refactor): Changes to code that neither fixes a bug nor adds a feature.
> 6. :wastebasket: `revert` (revert): Changes that revert a previous commit.
> 7. :gem: `style` (style): Changes to code that do not affect its meaning (formatting, etc.).
> 8. :rotating_light: `test` (test): Changes to existing tests or adding missing tests.
> 9. _:recycle: `chore` (chore): Changes, additions, configurations, routines, or maintenance tasks that does not fit into any other category. Changes do not modify src or test files._

[`type`]

## 2 - Description :memo: <span id="t-description">

> _A detailed description of the Task. This includes any relevant context, requirements, and constraints._

## 3 - Priority :exclamation: <span id="t-priority">

> _The priority of the Task (MoSCoW method). Select one of the following priorities:_
>
> 1. :sunny: `must-have`
> 2. :large_orange_diamond: `should-have`
> 3. :large_blue_diamond: `could-have`
> 4. :no_entry: `won't-have`

[`priority`]

## 4 - Task Points (TP) :star: <span id="t-task-points-tp">

> _The estimated effort required to complete the Task. This is estimated using task points (TP), which are based on and equivalent to user story points (USP). The number of task points allocated is selected from the following Fibonacci-like sequence: [1, 2, 3, 5, 8, 13, 20, 40, 100]._

[1, 2, 3, 5, 8, 13, 20, 40, 100] TP

## 5 - Dependencies :chains: <span id="t-dependencies">

> _A list of dependencies required for the completion of the Task._

1. **The Task** depends on the completion of [other Epic/Story/Task/Bug/Subtask - include link].
2. **The Task** cannot start until [other Epic/Story/Task/Bug/Subtask - include link] is completed.
3. **The Task** is blocked by [other Epic/Story/Task/Bug/Subtask - include link].

## 6 - Acceptance Criteria :heavy_check_mark: <span id="t-acceptance-criteria">

> _A list of conditions that must be met for the Task to be considered complete._

1. Acceptance criteria 1
2. Acceptance criteria 2
3. Acceptance criteria 3

## 7 - Subtasks :clipboard: <span id="t-subtasks">

> _A list of subtasks required to complete the Task. These do not need to have their own Subtask issues, but they could._

- [ ] 1. Subtask 1
- [ ] 2. Subtask 2
- [ ] 3. [Subtask E###-T###-ST### or T###-ST###](https://github.com/<username>/<repository-name>/issues/<issue-id-number> "Child Issue (Subtask)"): Subtask brief description.

## 8 - Parent Issue (Epic) :link: <span id="t-parent-issue-epic">

> _The parent issue (Epic) for this Task, if it has one._

None _or_

[Epic E###](https://github.com/<username>/<repository-name>/issues/<issue-id-number> "Parent Issue (Epic)"): Epic brief description.

## 9 - Resources :books: <span id="t-resources">

> _A list of useful resources/links for the Task._

1. [Resource 1](#)
2. [Resource 2](#)
3. [Resource 3](#)

## 10 - Notes :pencil2: <span id="t-notes">

> _A list of additional information about the Task._

1. Note 1
2. Note 2
3. Note 3

---
name: Epic Issue Template
about: An Epic is a large body of work that is broken down into a number of smaller parts (Stories and Tasks).
title: "[EPIC: E###] Epic Brief Description"
labels: epic
assignees: ""
---

# Epic: E### <span id="e-epic">

A brief summary of the Epic.

## Table of Contents <span id="e-table-of-contents">

1. [Description :memo:](#e-description "A detailed description of the Epic. This includes the business need, the goals, and the relevant stakeholders.")
2. [Priority :exclamation:](#e-priority "The priority of the Story (MoSCoW method).")
3. [Epic Points (EP) :star:](#e-epic-points-ep "The estimated effort required to complete the Epic.")
4. [Requirements :clipboard:](#e-requirements "A list of the high-level requirements (functional and non-functional) that must be met for the Epic to be considered complete. These will translate to Stories and Tasks.")
   1. [Functional](#e-functional)
   2. [Non-Functional](#e-non-functional)
5. [Constraints :lock:](#e-constraints "The constraints of the Epic.")
   1. [Scope](#e-scope "The scope of the Epic. This defines what is and is not included in the Epic, encompassing any related initiatives, projects, or Epics.")
   2. [Timeline](#e-timeline "The estimated start and end dates (duration) of the Epic.")
   3. [Budget](#e-budget "The estimated budget for the Epic.")
   4. [Other Constraints](#e-other-constraints "A list of any other constraints that the Epic may have.")
6. [Assumptions :question:](#e-assumptions "A list of things that are assumed to be true in the planning and execution of the Epic.")
7. [Risks :warning:](#e-risks "A list of potential risks that may impact the completion of the Epic.")
8. [Dependencies :chains:](#e-dependencies "A list of dependencies required for the completion of the Epic.")
9. [Acceptance Criteria :heavy_check_mark:](#e-acceptance-criteria "A list of conditions that must be met for the Epic to be considered complete. This can use the Given-When-Then (GWT) format and other statement formats if appropriate.")
10. [Child Issues :link:](#e-child-issues "A list of child issues that will contribute to the completion of the Epic.")
    1. [Stories](#e-stories)
    2. [Tasks](#e-tasks)
11. [Resources :books:](#e-resources "A list of useful resources/links for the Epic.")
12. [Notes :pencil2:](#e-notes "A list of additional information about the Epic.")

## 1 - Description :memo: <span id="e-description">

> _A detailed description of the Epic. This includes the business need, the goals, and any relevant stakeholders._

## 2 - Priority :exclamation: <span id="e-priority">

> _The priority of the Epic (MoSCoW method). Select one of the following priorities:_
>
> 1. :sunny: `must-have`
> 2. :large_orange_diamond: `should-have`
> 3. :large_blue_diamond: `could-have`
> 4. :no_entry: `won't-have`

[`priority`]

## 3 - Epic Points (EP) :star: <span id="e-epic-points-ep">

> _The estimated effort required to complete the Epic. This is estimated using epic points (EP), which are based on and equivalent to user story points (USP). The number of epic points allocated represents the sum of the points (USP and TP) from all child issues._

The number of epic points is the sum of the points (USP and TP) from all child issues.

[USP+TP] EP _or_ Do not explicitly show the points.

## 4 - Requirements :clipboard: <span id="e-requirements">

> _A list of the high-level requirements (functional and non-functional) that must be met for the Epic to be considered complete. These will translate to Stories and Tasks._

### Functional <span id="e-functional">

1. Functional Requirement 1
2. Functional Requirement 2
3. Functional Requirement 3

### Non-Functional <span id="e-non-functional">

1. Non-Functional Requirement 1
2. Non-Functional Requirement 2
3. Non-Functional Requirement 3

## 5 - Constraints :lock: <span id="e-constraints">

> _The constraints of the Epic._

### Scope <span id="e-scope">

> _The scope of the Epic. This defines what is and is not included in the Epic, encompassing any related initiatives, projects, or Epics._

### Timeline <span id="e-timeline">

> _The estimated start and end dates (duration) of the Epic._

This is based on the planned sprints (milestones) for the child issues (Stories and Tasks) linked to this Epic. The start date is the start date of the child issue with the earliest sprint, while the end date is the end date of the child issue with the latest sprint.

### Budget <span id="e-budget">

> _The estimated budget for the Epic._

US$ [0.00]

### Other Constraints <span id="e-other-constraints">

> _A list of any other constraints that the Epic may have._

The constraints commonly associated with software development projects are implied. If any other constraints beyond what's ordinarily expected are identified, they will be stated here.

1. Other Constraint 1
2. Other Constraint 2
3. Other Constraint 3

## 6 - Assumptions :question: <span id="e-assumptions">

> _A list of things that are assumed to be true in the planning and execution of the Epic._

The assumptions commonly associated with software development projects are implied. If any other assumptions beyond what's ordinarily expected are identified, they will be stated here.

1. Assumption 1
2. Assumption 2
3. Assumption 3

## 7 - Risks :warning: <span id="e-risks">

> _A list of potential risks that may impact the completion of the Epic. Risk probability and risk impact range from 1 to 5, where 1 is "Very Low" and 5 is "Very High". Therefore, risk score (risk probability x risk impact) ranges from 1 to 25._

The risks commonly associated with software development projects are implied. If any other risks beyond what's ordinarily expected are identified, they will be stated here.

1. **If** [Cause], **then** [Event] **may occur, which will lead to** [Impact]. **The risk probability is** [1-5] **and the risk impact would be** [1-5]. **Therefore, the risk score is** [Risk Probability x Risk Impact].
2. **If** [Cause], **then** [Event] **may occur, which will lead to** [Impact]. **The risk probability is** [1-5] **and the risk impact would be** [1-5]. **Therefore, the risk score is** [Risk Probability x Risk Impact].
3. **If** [Cause], **then** [Event] **may occur, which will lead to** [Impact]. **The risk probability is** [1-5] **and the risk impact would be** [1-5]. **Therefore, the risk score is** [Risk Probability x Risk Impact].

## 8 - Dependencies :chains: <span id="e-dependencies">

> _A list of dependencies required for the completion of the Epic._

1. **The Epic** depends on the completion of [other Epic/Story/Task/Bug/Subtask - include link].
2. **The Epic** cannot start until [other Epic/Story/Task/Bug/Subtask - include link] is completed.
3. **The Epic** is blocked by [other Epic/Story/Task/Bug/Subtask - include link].

## 9 - Acceptance Criteria :heavy_check_mark: <span id="e-acceptance-criteria">

> _A list of conditions that must be met for the Epic to be considered complete. This can use the Given-When-Then (GWT) format and other statement formats if appropriate._

1. **Given** [Context], **when** [Action], **then** [Expected Result].
2. **Given** [Context], **when** [Action], **then** [Expected Result].
3. Acceptance criteria 3

## 10 - Child Issues :link: <span id="e-child-issues">

> _A list of child issues that will contribute to the completion of the Epic._

### Stories <span id="e-stories">

- [ ] 1. [Story E###-S001](https://github.com/<username>/<repository-name>/issues/<issue-id-number> "Child Issue (Story)"): User story statement.
- [ ] 2. [Story E###-S002](https://github.com/<username>/<repository-name>/issues/<issue-id-number> "Child Issue (Story)"): User story statement.
- [ ] 3. [Story E###-S003](https://github.com/<username>/<repository-name>/issues/<issue-id-number> "Child Issue (Story)"): User story statement.

### Tasks <span id="e-tasks">

- [ ] 1. [Task E###-T001](https://github.com/<username>/<repository-name>/issues/<issue-id-number> "Child Issue (Task)"): Task brief description.
- [ ] 2. [Task E###-T002](https://github.com/<username>/<repository-name>/issues/<issue-id-number> "Child Issue (Task)"): Task brief description.
- [ ] 3. [Task E###-T003](https://github.com/<username>/<repository-name>/issues/<issue-id-number> "Child Issue (Task)"): Task brief description.

## 11 - Resources :books: <span id="e-resources">

> _A list of useful resources/links for the Epic._

1. [Resource 1](#)
2. [Resource 2](#)
3. [Resource 3](#)

## 12 - Notes :pencil2: <span id="e-notes">

> _A list of additional information about the Epic._

1. Note 1
2. Note 2
3. Note 3

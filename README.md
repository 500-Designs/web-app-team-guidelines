<div align="center">
  <h1>500 Designs Web App Team - Scrum Guidelines</h1>
</div>

#### Sprint requirements

-   Before a sprint starts or any code is written for it, the following must be set and verified through sprint grooming (SG)
    -   Goals
    -   Requirements
    -   Assignments
    -   Deliverables
    -   Known unkowns
    -   Backlogs
-   Sprints are broken down into epics, each epic is a feature or a major project component to be delivered at the end of the sprint.
-   Each epic will consist of user stories to be assigned as tasks for
-   Each story must a have a well defined acceptance criteria and keep unknowns to a minimal
-   Each story must have a story point estimate to be confirmed by assigned devs or all devs that are capable if not yet assigned.
    - Stories must be estimated through time and 1, 2, 3, 4, 5; with 5 consuming 1 work shift.
    - If a story's estimate won't fit 5 then it will be broken down to smaller stories.
    - Placeholder stories for "known unkowns" must have a max of 5 point estimates.
    - Story point estimation must not be taken lightly, each assigned developer will to assess and confirm during backlog grooming and change if needed before next Sprint Planning ends.
-   Blocking stories must be determined and linked
    -   Sprint grooming and daily scrum is purely technical, a manager may sit-in to observe but not intervene.

#### Walking the board:

-   Daily scrum Lasts only 15 minutes
-   Each story has a corresponding repo branch with format from "[PR Requirements](https://github.com/500-Designs/design-force-portal#repo-pr-requirements)" section of the project repo, after a PR has been approved by lead dev or substitute (if dev lead is on leave) and merged, it will be moved to QA.
-   If QA finds issues, it will be go back to 'rework' state and budget for "known unkowns" will be utilized for story point estimate
-   Any non-moving stories will be set to blocked/rework, blocking details/dependencies should be indicated as comment by the assigned dev
-   Budget for "known unknowns" will be utilized for creating stories that resolved the blocked/rework stories
-   Story point estimates are final when sprint starts, any excess time/effort will be placed on placholder "known unknowns" stories
-   After all devs have gotten their in-progress/rework stories, they will post it to the "WebApp Team" chat space as their daily TO-DOs: with story ID and when the start their next shift.

#### The status meeting with managers / stakeholders:

-   Separate from sprint grooming or daily scrums.
-   It is where we can present to managers or product owners a demo of a feature, or component after a sprint is completed.
-   After a SG has been completed, a clear and concise documentation for the Sprint goals and deliverables will be presented to the managers and product owners before the Sprint starts.
-   Velocity and burn down charts will be used by the manager/scrum master down the road.

### Automated Tests:

-   Automations need to be setup by test engineer (or dev lead) before a sprint starts:
    -   Automated tests for each acceptance criteria through Just
    -   CI pipelines for deployment for each story to be passed for QA/rework status

### Sprint schedules and initial goals

Sprint 0 [Aug 1-5, 2022]:
  - System design

Sprint 1 [Aug 8-19, 2022]:
  - BE design
  - mini UI components

Sprint 2 [Aug 22-Sep 2, 2022]:
  - login
  - client onboarding screens


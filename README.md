<div align="center">
  <h1>500 Designs Web App Team - Scrum Guidelines</h1>
</div>

#### Sprint requirements
- Before a sprint starts or any code is written for it, the following must be set and verified through sprint grooming (SG)
  - Goals
  - Requirements
  - Assignments
  - Deliverables
  - Known unkowns
  - Backlogs
- Sprints are broken down into epics, each epic is a feature or a major project component to be delivered at the end of the sprint.
- Each epic will consist of user stories to be assigned as tasks for
- Each story must a have a well defined acceptance criteria and keep unknowns to a minimal
- Each story must have a story point estimate to be confirmed by assigned devs or all devs that are capable if not yet assigned.
  - Stories must be estimated through time and 0, 0.5, 1, 2, 3, 5, 8, with 8 consuming 1 work shift.
  - Place holder stories for "known unkowns" must have a max of 3 point estimates.
  - If it won't fit then it will be broken down to smaller stories. Estimate values will be .
  - Story point estimataion must not be taken lightly, each developer will have a couple of days to assess and change estimates if needed.
- Blocking stories must be determined and linked
  - Sprint grooming and daily scrum is purely technical, a manager may sit-in to observe but not intervene.
#### Walking the board: 
  - Daily scrum Lasts only 15minutes 
  - Each story has a corresponding repo branch with format from "PR Requirements" section of the project repo, after a PR has been approved by Project Lead and merged, it will be moved to QA
  - Unless Approved by QA, it will be go back to 'rework' state and budget for "known unkowns" will be utilized for story point estimate
  - Any non-moving stories will be set to blocked/rework, blocking details should be indicated as comment 
  - Budget for "known unkowns" will be utilized for creating stories for resolving the blocked or non moving stories
  - After all devs have gotten their in-progress/rework stories, they will post it to the "WebApp Team" chat space as their daily TO-DOs: with story ID and when the start their next shift.

#### The status meeting with managers:
  - Velocity chart and burndown charts will be used by the manager.
  - Separate from sprint grooming or daily scrums.
  - It is where we can present to managers or product owners a demo of a feature, or component after a sprint is completed.
- After a SG has been completed, a clear and concise documentation for the Sprint goals and deliverables will be presented to the managers and product owners before the Sprint starts.
- There will be back burner stories from the backlogs to to assign if devs complete there stories before the sprint ends or the "known unknowns" placeholder stories weren't utilized.

### Design Force Portal specific notes:

- Automations to be setup by lead dev on later sprints:
  - Automated tests for each acceptance criteria through jest and cypress
  - CI pipeless for deployment for each story to be passed for QA/rework

### Sprint schedules and initial goals

Sprint 0 [Aug 1-5, 2022]:
  - System design

Sprint 1 [Aug 8-19, 2022]:
  - BE design
  - mini UI components

Sprint 2 [Aug 22-Sep 2, 2022]:
  - login
  - dashboards


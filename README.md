<div align="center">
  <h1>500 Designs Web App Team - Scrum Guidelines</h1>
</div>

#### Sprint requirements
- Before a sprint starts or any code is written for it, the following must be set and verified through sprint grooming (SG)
  - Requirements
  - Goals
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
- There will be back burner stories from the backlogs to to assign if devs complete there stories before the sprint ends or the "known unknowns" placeholder stories wasn't utilized.

### Design Force Portal specific notes:

- Automations to be setup by lead dev on later sprints:
  - Automated tests to test each acceptance criteria
  - CI pipeless for deployment for each story to be passed for QA/rework
- The first sprint as Sprint 0, since it won't cover the whole full week.
- And it will comprise mostly newly onboarded web app team, getting the hang of the process.

### Intial sprint schedules

Sprint 0 [Aug 1-5, 2022]:

- Lightweight or introductory tasks will be assigned for each dev to work on the remaining days of week until Aug 5.
- The first grooming session will be cover small task assignments for Aug 1-5 period. 
- The second grooming session will be for Sprint 1 that starts Aug 8.
    - so the 2nd grooming session should happen before then.
    - During grooming, each will assess and add more acceptance criteria (AC) to his/her assigned stories as needed
    - Determine if there are dependecies or requirements to achieve the (AC) that have don't exist yet.
  - Beyond the sprint grooming session, each developer must take time to assess assigned stories if there has to be adjustments in estimates or requirements. 
  - If there is, he/she has to tag the Lead developer on the story before the middle of the current sprint so adjustments can be made.

Sprint 1 [Aug 8-9, 2022]:
Sprint 2 [Aug 8-9, 2022]:


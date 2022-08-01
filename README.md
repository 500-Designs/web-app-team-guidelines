<div align="center">
  <h1>500 Designs Web App Team - Custom Scrum Guidelins</h1>
</div>

Since we don't have scrum master, as of writing.
Current Lead Developer will be the scrum master for now.

Here are our team guideliness:

The following still follows the Agile [Scrum methodology](https://www.atlassian.com/agile/scrum) for software development but have slight modifications to give adjustment period for the new team structure and syncing with managers.

- Before a sprint starts or any code is written for that sprint the following must be agreed upon and verified through sprint grooming (SG)
  - Requirements
  - Goals
  - Assignments
  - Deliverables
  - Backlogs
- We will break down sprints into epic, each epic is a feature or a major component of the to be delivered at the end of the sprint.
- Each epic will consist of user stories
- Each story must a have a well defined acceptance criteria
- Each story must have a story point estimate to be decided by potential devs that will work on it or all devs that are capable.
  - Stories must be estimated to the least time and effort to get close to just 1 story per workshift. If it won't fit then it will be broken down to smaller stories.
  - Story point estimataion must not be taken lightly, each developer will have a couple of days to assess and change estimates if needed.
- Velocity chart and burndown charts will not be used / observed.
- Sprint grooming and daily scrum is purely technical, a manager if he/she wants may sit-in to observe but not intervene.
- Daily scrum lasts only 15minutes tops.
- After all devs have gotten their in-progress / rework stories. After the scrum.
- They will post it to the "WebApp Team" with story ID and name.
- The status meeting with managers:
  - Separate from sprint grooming or daily scrums.
  - It is where we can present to managers or product owners a demo of a feature, or component after a sprint is completed.
- After a SG has been completed, a clear and concise documentation for the Sprint goals and deliverables will be presented to the managers and product owners before the Sprint starts.

### Design Force Portal specific notes:

- Automations to be setup by lead dev on later sprints:
  - Automated tests to test each acceptance criteria
  - CI pipeless for deployment for each story to be passed for QA/rework
- The first sprint as Sprint 0, since it won't cover the whole full week.
- And it will comprise mostly newly onboarded web app team, getting the hang of the process.

### Intial sprint schedule

Sprint 0 [Aug 1-5, 2022]:

- Lightweight tasks for will be assigned for each dev to work on the remaining week until Aug 5.
- We will have 2 Sprint Grooming session. This grooming session will be for Sprint 1, which will start Aug 8.
  - 1st session: Aug 2. We will create acceptance criteria for each story and all devs with have a change to give initial estimates.
    - After the grooming each dev, will assess and add more acceptance criteria (AC) as he/she sees fit to his assigned stories.
    - The assigned dev will write a short technical description, if there are dependecies or requirements to achieve the (AC) that have don't exist yet.
    - If initial estimates are not possible or unclear, a comment to tag the scrum master should be added so that on the next SG this will be adjusted and deliverables for the sprint will be adjusted acordingly.
  - 2nd Session. (To be determined). this session will circle back to all created stories and each assigned dev will be asked if his /her estimate is still possible or it needs to be adjustment. This will conclude the sprint.

Sprint 1 [Aug 8-9, 2022]:

- Potential goal:
  - Client Dashboard Landing page and onboarding flow
  - Java based API, authentication user tables setup
  - Automated testing tools setup, Jest & storybook

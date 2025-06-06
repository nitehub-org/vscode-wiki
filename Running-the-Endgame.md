Each iteration closes with an [endgame](https://github.com/Microsoft/vscode/wiki/Development-Process#end-game).

## Duties of the endgame champion

> Proactive communication is key to a smooth and successful endgame.

- Create the endgame plan and update the schedule (see template below and potentially last month's schedule)
- Discuss the endgame plan in Monday's planning call
  - Find an endgame buddy in the other lab
  - Remind people to update their testing availability and platform(s) in the call and release channel
- Communicate in the `release` Slack channel every day about the plan, progress, TODOs and any other important notifications.
  - Tidy up milestone (PRs, Issues, Feature Requests missing labels)
  - Availability of the insiders build
  - Testing to be done (Test Plan Items, Verifications)
  - Fixing Bugs / Candidates & Writing Documentation
  - Sanity testing and releasing.
- Track progress and update the endgame plan by checking off the checklist items.
- Coordinate with the buddy by communicating the progress and expected jobs to be done.
- Adjust schedule, particularly the publishing dates, based on defects found, fixes made, holidays, vacations, etc.
- Update the endgame process/template with the improvements/fixes that you learn in the current endgame.

## Recovery Release

We release one or more recovery builds with a handful of critical fixes and translation updates a few days after a release. The candidate fixes are reviewed by the development team and are assigned to a recovery milestone. We want to be restrictive about the included candidates. The mindset is "we will lose users if we do not include the fix". Here are some examples:
- data loss
- a regression that users complain loudly about in issues or Twitter
- a significant performance regression
- an issue that impacts many users as indicated by telemetry data
- an embarrassing UI glitch
- critical security fixes (see Patch Tuesday Release Endgame Template below)
- an issue that impacts extensions or is an API regression

## Create Endgame Plan

You can create the main / recovery / patch tuesday endgame plans from [Milestones View](https://tools.code.visualstudio.com/milestones). 


This will create the endgame plan for the selected milestone. All you have to do after is to update the release and endgame dates.

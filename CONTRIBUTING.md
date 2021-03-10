When contributing new code to an existing repository please keep this in mind:

Patch / Small feature:
 - Make sure development branch is up to date with master
 - Make a new branch from development
 - Write the code, commit and push to the new branch
 - Create an pull request back to development, and invite at least one other team member
 - Do a 5 min code review session where you explain the changes, and the intent.
 - Approve or request changes on the PR. If approved, merge into development.

Larger feature:
 - Start by making a design document describing what and how this new feature will solve
 - Follow Patch / Small feature

Releases:
 - Test development branch in staging, and make sure everything is working as intended
 - Create a PR from development to master, and invite other team members.
 - Do a code review / release prep
 - When everything is ok, do the merge and tag the master branch with a new "pre-release" tag
 - After successfully doing the deploy to production, and seeing everything going smoothly, change the release tag from "pre-release" to release.

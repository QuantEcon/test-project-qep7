# test-project-qep7

A sandbox for the QEP-6 and QEP-7 redesign of how QuantEcon uses GitHub issues. It is a QEP-3 `test-*` repository, public so that tests can see what an anonymous reader sees, and archived when the pilot ends.

**Everything here is disposable.** Issues are created, edited and closed to test the platform and the issue templates. Nothing in this repository is a real plan or a real status.

## What is tested here

- **The issue templates** in `.github/ISSUE_TEMPLATE/`: one per type (Task, Decision, Project, upkeep Project, Phase, Programme).
- **Platform behaviour** the design relies on:
  - whether an edit to an issue body notifies subscribers;
  - how issue-field writes behave when a value is already set;
  - what the sub-issue panel shows for each child;
  - what anonymous readers see of fields and of dependencies on private issues;
  - what a template does with an issue type the organisation does not have.

The work is coordinated from QuantEcon/project-qep7#1, a private tracker. Results are recorded there, not here.

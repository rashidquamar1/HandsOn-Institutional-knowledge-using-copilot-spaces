# Contributing to OctoAcme

This repository follows the OctoAcme project management model to keep work aligned, visible, and measurable across initiation, planning, execution, release, and retrospective cycles.

## 1. Project lifecycle and expected workflow

All work should follow this lifecycle:

1. Initiation
   - Confirm the problem, stakeholder need, and measurable outcome.
   - Capture the project one-pager, stakeholder list, timeline, and initial risks.
   - Decide whether the work is approved to move into planning.

2. Planning
   - Define scope, backlog priorities, milestones, owners, and dependencies.
   - Document acceptance criteria and Definition of Done (DoD).
   - Capture risks in the project risk register.

3. Execution
   - Break work into small, reviewable increments.
   - Track progress on the project board and in weekly delivery updates.
   - Escalate blockers and dependencies using the documented escalation path.

4. Release & Deployment
   - Validate functionality with tests and QA.
   - Prepare release notes and rollback/mitigation guidance.
   - Deploy in a controlled window with smoke tests and post-deploy verification.

5. Retrospective
   - Review what went well, what did not, and what should change next.
   - Capture lessons learned and next steps for the upcoming milestone.

## 2. Roles and responsibilities

Contributors are expected to operate in alignment with the OctoAcme roles used across the project docs.

- Product Manager / Product Lead
  - Defines the problem, priority, and success metrics.
  - Owns backlog prioritization and acceptance criteria.

- Project Manager
  - Coordinates scope, schedule, milestones, dependencies, and communication.
  - Maintains project visibility and escalation.

- Developers
  - Implement features and fixes according to acceptance criteria.
  - Write and maintain tests and supporting documentation.
  - Participate in review, design discussion, and risk identification.

- QA / Testing
  - Validate feature quality and acceptance criteria.
  - Help identify gaps, regressions, and release readiness issues.

## 3. Contribution expectations

### Before starting work
- Confirm the issue, feature request, or milestone is clearly scoped.
- Validate that the work aligns with the project roadmap and objectives.
- Identify dependencies, owner, and acceptance criteria before implementation begins.

### Issue and backlog hygiene
Every work item should include:
- title
- problem or user value
- acceptance criteria
- priority
- estimate or size
- owner
- dependencies or blockers
- related documentation or links

### Branching and pull request workflow
- Create a branch for the work item.
- Keep changes focused and reviewable.
- Link the pull request to the relevant issue or milestone.
- Include acceptance criteria in the PR description.
- Prefer small PRs when possible, with a goal of keeping scope narrow and easier to review.

### Review and quality gates
Before merge:
- automated tests must pass
- linting and validation checks must pass
- CI must be green
- the PR must be reviewed by at least one approver
- the work must align with acceptance criteria and DoD

## 4. Tracking, visibility, and communication

### Project board
Use a project board with columns such as:
- Backlog
- Ready
- In Progress
- In Review
- QA
- Done

### Status reporting
Teams should provide regular updates through:
- daily standups or equivalent team check-ins
- weekly delivery syncs
- milestone or demo reviews
- stakeholder updates when relevant

### Risk and dependency management
Each project should maintain a simple risk register with:
- ID
- description
- impact
- likelihood
- owner
- mitigation
- status

Risks and blockers should be reviewed weekly and escalated as needed.

### Escalation path
Escalate tasks in this order:
1. Team-level triage
2. Project Manager
3. Product Lead / dependent teams
4. Sponsor or executive escalation for business-impacting issues

## 5. Definition of Done

A work item is considered done only when:
- the acceptance criteria are met
- relevant tests and QA checks pass
- code review is complete
- the change is merged and linked to the issue
- release or rollout impact has been considered
- any residual risks or follow-up items are documented

## 6. Release and deployment responsibilities

Before shipping:
- confirm all acceptance criteria are met
- run smoke tests and critical validation paths
- confirm the release note and rollback plan are ready
- document known issues, if any
- verify deployment window and support readiness

If a release causes a material issue:
- notify the relevant responders
- assess whether rollback is required
- document the incident and schedule a retrospective

## 7. Continuous improvement

At the end of each milestone or iteration:
- capture what worked well
- document risks, blockers, or process issues
- identify concrete improvement actions for the next cycle
- update the backlog and roadmap accordingly

## 8. Contribution summary

The team’s success depends on:
- clear ownership
- visible planning
- regular communication
- quality-controlled execution
- disciplined release readiness
- learning from each iteration

Contributions are expected to reflect these principles and maintain the project’s transparency, quality, and customer value focus.

# OctoAcme Project Management Documentation

## Overview
OctoAcme runs projects with an iterative, outcomes-driven lifecycle: Initiation, Planning, Execution, Release, and Retrospective. Initiation focuses on validating the business need with a concise Project One-pager that defines the problem, measurable goals, and primary stakeholders. Planning turns approved initiatives into a prioritized backlog with clear acceptance criteria, estimates, and a Definition of Done. Execution is managed through a project board and pull request workflow that prioritizes small, testable increments. Releases follow a standardized checklist including CI/security checks, smoke tests, and a rollback plan. Retrospectives capture learnings and convert them into tracked action items.

Workflows emphasize clarity and repeatability. Teams use a project board with columns (Backlog 12 Ready 12 In Progress 12 In Review 12 QA 12 Done), keep PRs small and linked to issues and acceptance criteria, and require automated tests and linting in CI before requesting review. Risk and dependency management is tracked in a simple risk register and escalated via a defined ladder (team 12 PM 12 Product Lead 12 Sponsor) when needed. Checklists at initiation, planning, execution, and release stages help enforce branching/PR conventions, CI configuration, and weekly risk updates.

Communication is structured and regular: daily standups (15 minutes) for progress and blockers, weekly delivery syncs for status and flagged risks, demos at the end of sprints/milestones, and monthly stakeholder updates. PMs and Product Leads run a weekly alignment sync; templates are provided for weekly status updates and incident communications so messages remain consistent across stakeholders. Security incidents follow the security runbook and notify on-call security in parallel to the standard escalation path.

Quality assurance is integrated into the delivery pipeline. The baseline includes unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for acceptance where needed. Releases require passing CI and security scans, drafted release notes, a documented rollback/mitigation plan, and post-deploy verifications. Action items from retrospectives are tracked in the backlog so the team can measure the impact of continuous improvements.

## Quick start
Start here for a concise introduction and then open the detailed guides below.

### Core documents
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## How to use these docs
- New team members: read the Overview, Roles & Personas, then follow Quick Start links.
- Project leads: keep the Project One-pager and risk register updated in the project repo.
- Contributors: follow branching/PR conventions and make sure CI checks pass before requesting review.

## Acceptance criteria (from the request)
- Content aligns with existing process docs
- Update improves clarity or closes a documented gap
- Proposed content has been reviewed with stakeholders (if needed)

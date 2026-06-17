# OctoAcme Project Management Docs

This folder collects OctoAcme's project management process documents and provides a single, discoverable entry point for onboarding and ongoing execution. The docs describe a lightweight, iterative lifecycle (initiation → planning → execution → release → retrospective) that emphasizes measurable outcomes, clear ownership, and incremental delivery. Use these docs as the single source of truth for templates, cadence, and escalation paths.

Core workflows center on:
1. Initiating work with a one‑pager that defines the problem, objectives, success metrics, stakeholders, and risks.
2. Planning by breaking approved work into prioritized backlog items with acceptance criteria and a Definition of Done.
3. Executing via a project board and small, CI‑tested pull requests that include issue links and acceptance criteria.
4. Releasing with pre‑release checks, staging verification, smoke tests, and documented rollback plans.
5. Retrospecting to capture action items that feed back into the backlog for continuous improvement.

Roles and communication are explicit: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate plans, risks, and stakeholder updates; Developers implement and test; QA validates acceptance; and Stakeholders review and approve. Team cadence includes daily standups for blockers and progress, a weekly delivery sync for status and risks, and sprint demos. Reporting focuses on velocity, burndown, and the project-specific success metrics defined in each project one‑pager.

Quality is enforced through automated tests (unit, integration), end‑to‑end smoke tests for critical flows, security scans in CI, and manual QA when needed. PRs should be small, include issue links and acceptance criteria, and pass CI/lint before review. Releases are classified (patch/minor/major) and follow the documented deployment checklist and incident rollback playbook.

## Documents in this folder

- docs/octoacme-project-management-overview.md — Project Management Overview  
- docs/octoacme-project-initiation.md — Project Initiation Guide  
- docs/octoacme-project-planning.md — Project Planning  
- docs/octoacme-execution-and-tracking.md — Execution & Tracking  
- docs/octoacme-risks-and-communication.md — Risk Management & Communication  
- docs/octoacme-release-and-deployment.md — Release & Deployment Guide  
- docs/octoacme-retrospective-and-continuous-improvement.md — Retrospective & Continuous Improvement  
- docs/octoacme-roles-and-personas.md — Roles & Personas

## Examples & templates (quick extracts)

### Project one-pager (template)
- Project name:  
- Problem statement:  
- Objective / Goal (SMART):  
- Success metrics:  
- Primary stakeholders:  
- Suggested timeline / milestones:  
- Quick risks & dependencies:  
- Proposed team / roles:  

### Backlog item template
- Title:  
- Description:  
- Acceptance criteria:  
- Priority:  
- Estimate:  
- Owner:  
- Related docs/links:  

### Example PR description
- Linked issue: #<issue-number>  
- Summary of change:  
- Acceptance criteria:  
- Test plan:  
- Notes on rollout / migration (if any):  

### Example weekly status template
- Progress this week:  
- Next steps:  
- Risks & blockers:  
- Ask / decisions needed:  

## How to contribute
Propose changes using the "Add Content to Project Management Process Docs" issue template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml. When creating the issue, select the document to update (or "<new document>" for new files), provide a summary, rationale, and suggested content so reviewers can quickly accept or iterate.

## Next steps / TODO
- Add this README to docs/ (create new file)  
- Optionally include code snippets or CI examples (indicate which files you want included)  
- Track any follow-up items as issues using the existing template

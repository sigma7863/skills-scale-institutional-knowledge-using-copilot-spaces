# OctoAcme Project Management Docs

Welcome! This README provides a brief overview of the project management processes used at OctoAcme and links to detailed documentation.

## Project Management Processes Summary

OctoAcme's project management approach is built on customer-first principles and iterative delivery. We emphasize clear ownership, data-informed decisions, and psychological safety to ensure teams can deliver value effectively. Each cross-functional project has a defined Project Manager (PM) who coordinates delivery, schedules, risks, and communications, alongside a Product Manager (PdM) who defines outcomes and measures success.

Our workflow follows a structured lifecycle: from **Initiation** (problem definition, stakeholder alignment, and high-level timelines) through **Planning** (scope breakdown, resource allocation, milestone mapping, and risk identification) to **Execution & Tracking** (daily standups, iterative development, PR reviews, and quality assurance). Throughout execution, teams maintain a clear communication cadence with twice-weekly standups, weekly PM-PdM syncs, and monthly stakeholder updates. Quality assurance is integrated into every stage, with unit tests, integration tests, automated CI checks, and manual QA ensuring each increment meets acceptance criteria before release.

The release and deployment process follows a disciplined approach with smoke tests, rollback plans, deployment verification, and stakeholder announcements. Risk management is ongoing: teams maintain a risk register, assess impact and likelihood, implement mitigation plans, and monitor status weekly. Communication follows established templates for weekly status updates and incident responses, with clear escalation paths from team-level to PM to product leads and sponsors when needed.

After each project or major milestone, teams conduct retrospectives to capture learnings, identify action items, and drive continuous improvement. This complete process—supported by key artifacts like project charters, roadmaps, sprint backlogs, risk registers, and retrospective notes—ensures that projects deliver customer value predictably while enabling teams to learn and improve over time.

## Document Links

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risks and Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

## How to Use These Docs

This README is the single entry point for all OctoAcme project management documentation. To keep these docs up to date, update the project README when making process changes, add new documentation files to the `docs/` folder, and reference them in this file. 

For Copilot Spaces integration, note that the `.copilot` reference is already included in the Project Management Overview doc. To make process-specific docs available to Copilot Spaces, add them to the `.copilot/` directory so they can be used as context for AI-assisted workflows and guidance.

## Acceptance Criteria

- [x] Content aligns with existing process docs
- [x] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)

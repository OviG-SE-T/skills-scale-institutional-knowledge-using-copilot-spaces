# OctoAcme Project Management Docs

## Overview
This README provides a summary of OctoAcme's project management approach and links to detailed process documents.

OctoAcme uses an iterative, stakeholder-driven project management lifecycle that emphasizes:
- **Customer-first approach**: Prioritizing customer value and usability in all decisions
- **Iterative delivery**: Delivering small, testable increments with continuous feedback
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measuring impact and iterating based on evidence
- **Psychological safety**: Encouraging feedback and learning across all team members

## Key Workflows

OctoAcme's project lifecycle follows five main phases:

1. **Initiation**: Problem statement, stakeholder alignment, and high-level timeline
2. **Planning**: Scope definition, resource allocation, milestones, and dependencies
3. **Execution**: Build, test, review, and iterate with regular team syncs
4. **Release & Deployment**: Deploy, verify, and announce to stakeholders
5. **Retrospective & Continuous Improvement**: Capture learnings and action items

## Roles and Personas

OctoAcme projects involve clearly defined roles:

- **Project Manager (PM)**: Coordinates delivery, schedules, risk management, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design, and maintain testability
- **QA/Testing**: Validate quality against acceptance criteria
- **Stakeholders**: Provide inputs, feedback, and approvals

## Communication Strategies

Regular communication cadence ensures alignment and transparency:

- **Weekly sync** between PM and PdM
- **Twice-weekly standups** for delivery team (or as agreed)
- **Monthly stakeholder updates** with progress and risk summaries
- **Ad-hoc escalations** for critical issues
- **Demo/Review sessions** at the end of each sprint or milestone

## Quality Assurance Practices

OctoAcme maintains high quality standards through:

- **Unit tests** for new logic
- **Integration tests** where applicable
- **End-to-end smoke tests** for critical flows before release
- **Security scanning** in CI pipelines
- **Manual QA** for feature acceptance when needed
- **Code reviews** with at least one approval before merging
- **Automated testing and linting** in CI before review

## Process Documents

For detailed checklists, templates, and best practices, refer to these core process documents:

- [Project Management Overview](octoacme-project-management-overview.md) - Core principles, roles, and lifecycle overview
- [Project Initiation Guide](octoacme-project-initiation.md) - Steps to validate, authorize, and align on new projects
- [Project Planning](octoacme-project-planning.md) - Scope definition, estimation, and milestone planning
- [Execution & Tracking](octoacme-execution-and-tracking.md) - Day-to-day workflows, team rhythm, and progress tracking
- [Risk Management & Communication](octoacme-risks-and-communication.md) - Risk identification, stakeholder communication, and escalation paths
- [Release & Deployment Guide](octoacme-release-and-deployment.md) - Deployment processes and verification steps
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) - Learning from experiences and improving processes
- [Roles and Personas](octoacme-roles-and-personas.md) - Detailed role definitions and responsibilities

## Getting Started

New team members should:
1. Read the [Project Management Overview](octoacme-project-management-overview.md) for foundational understanding
2. Review [Roles and Personas](octoacme-roles-and-personas.md) to understand team structure
3. Familiarize themselves with relevant phase-specific guides based on current project stage
4. Keep project artifacts updated in the project repository
5. Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context

For questions or suggestions about these processes, please reach out to your Project Manager or Product Manager.

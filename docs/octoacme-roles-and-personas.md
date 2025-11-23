# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Quality Assurance (QA)

### Role Summary
QA Engineers ensure quality, reliability, and usability through testing and validation. They define test strategies, execute tests, and collaborate with developers and product managers to prevent defects.

### Responsibilities
- Design and execute test plans for new features and fixes
- Perform functional, regression, and exploratory testing
- Collaborate with developers to reproduce and document defects
- Validate fixes before releases
- Contribute to test automation efforts

### Goals
- Catch defects before production
- Ensure features meet acceptance criteria
- Improve test coverage and automation
- Reduce customer-reported issues

### Typical Communication
- Daily standups and sprint planning
- Bug reports and test case documentation
- Pre-release sign-offs and validation checklists

---

## Release Manager

### Role Summary
Release Managers coordinate scheduling, communications, and readiness activities for all releases. They ensure production launches are successful by orchestrating collaboration between PM, QA, Developers, and Technical Writers.

### Responsibilities
- Plan and coordinate release schedules and deployment windows
- Ensure all pre-release requirements are met (see [Release & Deployment Guide](octoacme-release-and-deployment.md))
- Communicate release status to stakeholders
- Coordinate go/no-go decisions with PM and QA leads
- Manage release notes and documentation updates
- Coordinate rollback procedures if needed

### Goals
- Execute smooth, predictable releases
- Minimize production incidents
- Ensure clear communication across all stakeholders
- Maintain accurate release documentation

### Typical Communication
- Weekly release planning meetings with PM, QA, and Dev leads
- Release readiness reviews and go/no-go decision meetings
- Release announcements and stakeholder updates
- Post-release reports and retrospectives

### Related Documents
- [Release & Deployment Guide](octoacme-release-and-deployment.md) for release checklists and procedures
- [Risks & Communication](octoacme-risks-and-communication.md) for stakeholder communication patterns

---

## Scrum Master

### Role Summary
Scrum Masters champion agile best practices, facilitate ceremonies, and remove impediments to delivery. They ensure team health, process alignment, and continuous improvement while serving as a bridge between the delivery team and project leadership.

### Responsibilities
- Facilitate agile ceremonies (standups, sprint planning, reviews, retrospectives)
- Remove impediments and blockers to team progress
- Coach team on agile principles and best practices
- Protect team from interruptions and scope creep
- Track team metrics (velocity, burndown) and identify improvement opportunities
- Foster psychological safety and team collaboration

### Goals
- Maximize team productivity and flow
- Ensure consistent agile practices across sprints
- Improve team health and morale
- Enable self-organization and continuous improvement

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-ones with team members to address concerns
- Weekly syncs with PM and project leadership
- Facilitated retrospectives with action item tracking

### Related Documents
- [Project Planning](octoacme-project-planning.md) for sprint planning and backlog management
- [Execution & Tracking](octoacme-execution-and-tracking.md) for team rhythm and workflows
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) for facilitation guidance

---

## UX Designer

### Role Summary
UX Designers infuse user perspective into requirements, designs, and deliverables. They ensure products are user-centered, usable, and accessible before release through research, design, and validation activities.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Review designs and validate user experience quality
- Define and advocate for accessibility standards
- Collaborate with PM to shape user-centered requirements
- Partner with Developers to ensure design fidelity

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support costs
- Ensure product-market fit through user validation
- Build design systems and maintain consistency

### Typical Communication
- Design reviews and critique sessions
- User research presentations and insights sharing
- Acceptance criteria collaboration with PM
- Design handoff meetings with developers

### Related Documents
- [Project Planning](octoacme-project-planning.md) for incorporating UX work into sprint planning
- [Project Initiation](octoacme-project-initiation.md) for early UX involvement in requirements

---

## Data Analyst

### Role Summary
Data Analysts monitor project metrics, gather evidence to support decisions, and create dashboards and reports. They engage with all delivery roles to provide insights, measure progress, and enable data-driven decision making.

### Responsibilities
- Define and track key project metrics and KPIs
- Create dashboards and visualizations for stakeholders
- Analyze trends and patterns to inform prioritization
- Support A/B testing and experiment design
- Provide data for retrospectives and improvement initiatives
- Collaborate with PM and Product Managers on success metrics

### Goals
- Enable evidence-based decision making
- Provide visibility into project health and progress
- Identify opportunities through data insights
- Measure and communicate impact of deliveries

### Typical Communication
- Weekly metric reviews with PM and leadership
- Dashboard updates and data insights presentations
- Retrospective data summaries
- Ad-hoc analysis requests and findings

### Related Documents
- [Execution & Tracking](octoacme-execution-and-tracking.md) for reporting and metrics guidance
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) for measuring improvement impact

---

## Technical Writer

### Role Summary
Technical Writers ensure documentation is comprehensive, consistent, accessible, and up to date. They partner with all roles to translate complex processes, features, and systems into clear guidance, checklists, and templates.

### Responsibilities
- Create and maintain user-facing and internal documentation
- Develop templates, checklists, and process documentation
- Review and edit documentation for clarity and accessibility
- Ensure documentation aligns with product changes
- Collaborate with all roles to gather technical information
- Organize and maintain documentation repositories

### Goals
- Improve documentation clarity and accessibility
- Reduce support burden through comprehensive docs
- Ensure documentation is current and discoverable
- Support onboarding and knowledge transfer

### Typical Communication
- Documentation reviews with subject matter experts
- Release coordination meetings with Release Manager
- Content planning sessions with PM and Product Managers
- Documentation feedback and improvement discussions

### Related Documents
- All process documents in the [docs folder](README.md) are maintained with Technical Writer collaboration
- [Release & Deployment Guide](octoacme-release-and-deployment.md) for release notes coordination

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.


# OctoAcme Project Management Docs

## Overview

These docs describe the core project management processes followed by OctoAcme to deliver customer value, manage risk, and enable continuous improvement. Our approach is structured, customer-centric, and designed to enable teams to work efficiently while maintaining transparency and alignment across stakeholders.

## OctoAcme Project Management Approach

### Core Principles
- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments to gather feedback and adapt
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

### Project Lifecycle

OctoAcme projects follow a five-phase lifecycle:

1. **Initiation**: Define the problem statement, identify stakeholders, establish high-level timeline, and decide go/no-go
2. **Planning**: Break work into shippable increments, identify dependencies, estimate scope, and create a release plan
3. **Execution**: Build, test, review, and iterate with daily standups and continuous tracking
4. **Release**: Deploy to production with verification, rollback plans, and stakeholder communication
5. **Close & Retrospective**: Capture learnings and convert them into actionable improvements

### Key Roles

- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Developers**: Implement features, collaborate on design, and maintain quality
- **QA/Testing**: Validates quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and strategic direction

### Communication & Cadence

- **Daily standups** (15 min): Progress, blockers, dependencies
- **Weekly PM + PdM sync**: Alignment and prioritization
- **Twice-weekly delivery team standups**: Execution updates
- **Weekly stakeholder updates**: Status, risks, decisions needed
- **Monthly stakeholder briefings**: High-level progress and roadmap alignment
- **Demos/Reviews**: At the end of each sprint or milestone
- **Retrospectives**: After each sprint, release, or milestone

## Process Documents

### [Project Management Overview](octoacme-project-management-overview.md)
A concise introduction to OctoAcme's project management approach for new team members. Covers core principles, roles, key artifacts, the project lifecycle, and communication cadence.

### [Project Initiation Guide](octoacme-project-initiation.md)
Guidance for validating and authorizing new work. Covers the initial steps to confirm business need, align stakeholders, define success criteria, and decide whether to proceed to planning. Includes the Project One-pager template.

**Key Activities:**
- Confirm business need and measurable outcomes
- Identify stakeholders and champions
- Define success criteria and initial timeline
- Create a lightweight Project One-pager
- Obtain sponsor alignment

### [Project Planning](octoacme-project-planning.md)
Guidance for turning an approved initiative into an actionable plan and backlog for delivery. Covers breaking work into shippable increments, identifying dependencies and risks, estimating scope, defining Definition of Done, and creating release plans.

**Key Activities:**
- Kickoff meeting with stakeholders and delivery team
- Create prioritized backlog with acceptance criteria
- Estimate scope (T-shirt sizing or story points)
- Identify dependencies and integration points
- Define release plan and milestone map

### [Execution & Tracking](octoacme-execution-and-tracking.md)
Guidance for managing day-to-day execution and tracking progress toward project milestones. Covers team rhythm, pull request workflows, quality and testing standards, reporting and metrics, and blocker escalation.

**Key Activities:**
- Daily standups and weekly delivery syncs
- Use project boards (GitHub Projects) with defined columns
- Small PRs with clear acceptance criteria and automated testing
- Unit, integration, and end-to-end testing
- Track velocity and monitor success metrics
- Escalate blockers following a three-level process

### [Risk Management & Communication](octoacme-risks-and-communication.md)
Guidance for identifying, managing, and communicating risks and dependencies. Covers maintaining a risk register, the risk lifecycle, stakeholder communication strategies, and escalation paths.

**Key Activities:**
- Maintain a risk register with ID, description, impact, likelihood, owner, and mitigation plan
- Review and update risks at weekly syncs
- Provide regular stakeholder updates
- Follow escalation paths: Team-level → PM → Product Lead → Sponsor
- Document incident communication and post-incident retrospectives

### [Release & Deployment Guide](octoacme-release-and-deployment.md)
Guidance for standardizing how OctoAcme releases features to production. Covers release types (patch, minor, major), pre-release requirements, deployment checklists, rollback procedures, and release notes templates.

**Key Activities:**
- Verify all acceptance criteria are met and passing CI/security scans
- Draft release notes and prepare rollback/mitigation plans
- Deploy to staging, run smoke tests, then deploy to production
- Conduct post-deploy verifications
- Announce release to stakeholders and support
- Execute rollback procedures if necessary

### [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
Guidance for capturing learnings and converting them into actionable improvements. Covers running retrospectives, tracking improvements, and building a continuous improvement culture.

**Key Activities:**
- Timebox retrospectives (45–75 minutes)
- Capture what went well, what could improve, and action items
- Prioritize 2–3 top action items to avoid overload
- Track improvements with clear owners and due dates
- Review outstanding actions in weekly PM sync
- Measure impact of improvements

### [Roles & Personas](octoacme-roles-and-personas.md)
Detailed definitions of typical roles and responsibilities used in OctoAcme projects. Includes Developers, Product Managers, and Project Managers with their responsibilities, goals, and typical communication patterns.

## Getting Started

**For new team members:**
1. Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our approach
2. Review the [Roles & Personas](octoacme-roles-and-personas.md) document to find your role and responsibilities
3. Explore process documents relevant to your current work phase

**For Project Managers:**
1. Follow the [Project Initiation Guide](octoacme-project-initiation.md) for new projects
2. Use [Project Planning](octoacme-project-planning.md) to create detailed plans
3. Refer to [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day management
4. Use [Risk Management & Communication](octoacme-risks-and-communication.md) to track and escalate issues
5. Follow [Release & Deployment Guide](octoacme-release-and-deployment.md) for production releases
6. Conduct [Retrospectives](octoacme-retrospective-and-continuous-improvement.md) after milestones to capture learnings

**For Product Managers:**
1. Collaborate with PM during [Project Initiation](octoacme-project-initiation.md) to define success metrics
2. Own the backlog and prioritization during [Project Planning](octoacme-project-planning.md)
3. Track success metrics during [Execution & Tracking](octoacme-execution-and-tracking.md)
4. Measure impact post-release using the [Release & Deployment Guide](octoacme-release-and-deployment.md)

## Questions or Updates?

If you have questions about these processes or want to suggest improvements, please:
1. Open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
2. Propose your changes for team review
3. Help us keep these docs accurate, relevant, and useful for everyone

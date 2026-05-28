# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Project Delivery Roles

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

### Key Interactions
- Works closely with **QA Analysts** on test coverage and quality standards
- Collaborates with **Product Managers** on acceptance criteria and priority
- Coordinates with **Project Managers** on schedules and dependencies
- Supports **Business Analysts** with technical feasibility input

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

### Key Interactions
- Works with **Business Analysts** to clarify requirements and user needs
- Collaborates with **Developers** and **QA Analysts** on feasibility and quality trade-offs
- Aligns with **Project Managers** on delivery timelines
- Engages with **Stakeholders** on priorities and outcomes

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

### Key Interactions
- Coordinates with all roles to ensure alignment and remove blockers
- Works with **Scrum Masters** on process optimization and team health
- Escalates risks and issues to **Stakeholders** as needed
- Collaborates with **Support Engineers** on hand-off planning

---

## Supporting & Specialized Roles

## QA Analysts

### Role Summary
QA Analysts design and execute test strategies to ensure product quality. They collaborate with developers and product teams to drive quality coverage, verify acceptance criteria, and report on product readiness for release.

### Responsibilities
- Design and execute comprehensive test plans (unit, integration, end-to-end)
- Create and maintain test cases and regression test suites
- Report quality metrics and product readiness status
- Collaborate with developers to identify and prevent defects
- Verify acceptance criteria are met before features move to production
- Perform manual QA for critical user flows and edge cases
- Support automation and CI/CD pipeline testing

### Goals
- Ensure high product quality and customer satisfaction
- Catch defects early and reduce production issues
- Maintain comprehensive test coverage and traceability
- Enable confident, frequent releases

### Typical Communication
- Quality status reports in weekly delivery syncs
- Test plans and coverage documentation
- Defect reports with clear reproduction steps
- Collaboration with developers on test strategy

### Key Interactions
- Partners with **Developers** on test-driven development and quality standards
- Works with **Product Managers** to validate acceptance criteria
- Supports **Project Managers** with go/no-go readiness assessments
- Coordinates with **Support Engineers** on critical issue validation

---

## Business Analysts

### Role Summary
Business Analysts gather requirements, translate business needs into actionable user stories, and act as a bridge between stakeholders and the delivery team. They ensure clarity and alignment on what needs to be built.

### Responsibilities
- Conduct requirements gathering and stakeholder interviews
- Translate business needs into clear, testable acceptance criteria
- Create and maintain user stories and requirement documentation
- Identify business impacts and dependencies
- Validate solutions against original business objectives
- Clarify ambiguities and resolve conflicting requirements

### Goals
- Ensure requirements are clear, complete, and achievable
- Reduce rework and misalignment between business and delivery
- Enable faster decision-making with well-documented tradeoffs
- Bridge communication gaps between technical and non-technical stakeholders

### Typical Communication
- Requirement documentation and user stories
- Stakeholder update meetings
- Design review collaboration
- Post-release validation reports

### Key Interactions
- Works with **Stakeholders** to understand business needs and priorities
- Collaborates with **Product Managers** on requirement clarification
- Partners with **Developers** to ensure technical feasibility
- Supports **QA Analysts** in defining acceptance criteria and test scenarios
- Advises **Project Managers** on scope and dependency implications

---

## Scrum Masters / Agile Coaches

### Role Summary
Scrum Masters and Agile Coaches facilitate team ceremonies, remove process blockers, and coach teams on agile best practices. They protect team focus and enable continuous improvement through process optimization.

### Responsibilities
- Facilitate sprint planning, daily standups, retrospectives, and reviews
- Remove process blockers and facilitate resolution of team impediments
- Coach team members on agile principles and practices
- Track team velocity and burndown metrics
- Protect team from scope creep and context switching
- Foster psychological safety and encourage collaboration
- Identify process improvements and drive adoption

### Goals
- Enable high-performing, self-organizing teams
- Reduce cycle time through process efficiency
- Increase team engagement and morale
- Continuous team and process improvement

### Typical Communication
- Facilitation of team ceremonies
- Team health assessments and coaching
- Process improvement action items
- Metrics dashboards and retrospective notes

### Key Interactions
- Works with all team members to optimize team dynamics and processes
- Collaborates with **Project Managers** on timeline and resource management
- Partners with **Developers** and **QA Analysts** on workflow optimization
- Supports **Product Managers** in maintaining backlog health
- Escalates impediments to **Project Managers** when team-level resolution is insufficient

---

## Stakeholders

### Role Summary
Stakeholders are business sponsors, organizational leaders, end-users, or customers who provide input, feedback, and approvals throughout project delivery. They have vested interest in project success and outcomes.

### Responsibilities
- Provide business context and success criteria
- Make prioritization and trade-off decisions
- Approve key project decisions and gate reviews
- Provide feedback on work in progress
- Communicate project status to their constituencies
- Identify business risks and dependencies

### Goals
- Ensure project delivers measurable business value
- Align project outcomes with organizational strategy
- Reduce business and stakeholder risk
- Maintain transparency and stakeholder confidence

### Typical Communication
- Project kickoff and initiation meetings
- Monthly stakeholder briefings
- Gate reviews and milestone approvals
- Escalation notifications for critical issues

### Key Interactions
- Works with **Product Managers** and **Business Analysts** on priorities and requirements
- Receives updates from **Project Managers** on status and risks
- Reviews outcomes with **QA Analysts** and delivery team
- Escalates decisions and provides governance oversight

---

## Support Engineers

### Role Summary
Support Engineers handle escalated issues, post-release questions, and ensure smooth hand-off from delivery to operations and customer support. They bridge the gap between development and production support.

### Responsibilities
- Participate in release planning and hand-off activities
- Support production deployments and initial issue triage
- Validate critical issues and escalate bugs back to dev team if needed
- Document production runbooks and troubleshooting guides
- Provide operational insights on scalability and performance
- Conduct post-release verification and health checks
- Coordinate with operations on monitoring and alerting

### Goals
- Ensure smooth release transitions with minimal production issues
- Reduce mean-time-to-resolution (MTTR) for production incidents
- Gather operational insights to inform future design decisions
- Enable support team to handle issues independently

### Typical Communication
- Release hand-off documentation and runbooks
- Deployment day coordination and verification
- Post-incident retrospectives and action items
- Operational metrics and monitoring reports

### Key Interactions
- Partners with **Developers** on production issue investigation and root cause analysis
- Works with **QA Analysts** on pre-release verification and smoke testing
- Coordinates with **Project Managers** on deployment scheduling and risk mitigation
- Supports **Stakeholders** with post-release validation and success metrics

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the **Key Interactions** section to understand how roles collaborate and depend on each other.
- When making project decisions, consider perspectives from all relevant personas to ensure balanced outcomes.

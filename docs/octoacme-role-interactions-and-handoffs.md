# OctoAcme Role Interaction & Handoff Checklist

This checklist helps teams ensure clear handoff and coordination between roles throughout the project lifecycle.

## Project Initiation Phase

### Stakeholder → Product Manager / Project Manager
- [ ] Business case and success criteria documented
- [ ] Budget and resource constraints communicated
- [ ] Key stakeholder constraints and dependencies identified
- [ ] Approval to proceed to planning phase obtained

### Product Manager → Business Analyst
- [ ] High-level problem statement shared
- [ ] Customer/user pain points communicated
- [ ] Success metrics and outcomes defined
- [ ] Assumptions and known constraints documented

---

## Planning Phase

### Business Analyst → Product Manager
- [ ] Requirements gathering completed
- [ ] User stories drafted with acceptance criteria
- [ ] Feasibility risks and dependencies identified
- [ ] Clarification questions resolved

### Product Manager → Scrum Master / Project Manager
- [ ] Prioritized backlog shared
- [ ] Milestone timeline and release plan agreed
- [ ] Team composition and capacity confirmed
- [ ] Risk register initialized

### Scrum Master / Project Manager → Developers & QA Analysts
- [ ] Sprint goals and scope communicated
- [ ] Acceptance criteria clarified
- [ ] Test strategy discussed
- [ ] Technical dependencies mapped

---

## Execution Phase

### Daily Coordination
- [ ] Developers, QA Analysts, and Scrum Master in daily standup
- [ ] Blockers identified and escalated
- [ ] Progress tracked against sprint goals
- [ ] Risks updated if new issues emerge

### Weekly Handoffs
- [ ] Product Manager reviews progress against acceptance criteria
- [ ] Project Manager communicates status to stakeholders
- [ ] Scrum Master captures process improvements
- [ ] Business Analyst clarifies any requirement ambiguities

### Development to QA Handoff (per story)
- [ ] Code complete and PR merged
- [ ] All acceptance criteria mapped to test cases
- [ ] Known limitations or edge cases documented
- [ ] QA has access to test environment
- [ ] Support engineer notified of features approaching release

---

## QA & Testing Phase

### QA Analyst → Development Team
- [ ] Defects logged with clear reproduction steps
- [ ] Blocker vs. non-blocker severity communicated
- [ ] Test coverage metrics shared
- [ ] Known issues documented for release notes

### QA Analyst → Product Manager
- [ ] Feature readiness assessment provided
- [ ] Quality metrics and go/no-go recommendation given
- [ ] Regression test results shared

---

## Release Phase

### Product Manager & Project Manager → Support Engineer
- [ ] Release notes and known issues documented
- [ ] Runbook and troubleshooting guide provided
- [ ] Deployment schedule and rollback plan shared
- [ ] Critical monitoring metrics and alerts configured
- [ ] Support escalation path clarified

### QA Analyst → Support Engineer
- [ ] Smoke test scenarios documented
- [ ] Critical flow validation results shared
- [ ] Known issues and workarounds communicated

### Developers → Support Engineer
- [ ] Technical architecture and key changes explained
- [ ] Operational considerations documented
- [ ] Performance and scalability implications noted
- [ ] Potential issues and mitigation strategies discussed

### Support Engineer → Stakeholders
- [ ] Deployment status and verification results shared
- [ ] Any production issues or rollbacks communicated
- [ ] Post-release health check results provided

---

## Post-Release & Retrospective

### Scrum Master / Project Manager → All Roles
- [ ] Retrospective scheduled and facilitated
- [ ] Action items captured and assigned
- [ ] Process improvements identified

### Support Engineer → Product Manager
- [ ] Initial user feedback and support ticket trends shared
- [ ] Performance metrics and operational insights provided
- [ ] Suggestions for future improvements documented

### Business Analyst → Stakeholders
- [ ] Business metrics and success indicators reported
- [ ] Customer feedback summary shared
- [ ] ROI and impact assessment provided

---

## Key Handoff Principles

1. **Clear Ownership**: Each handoff has clear owner and receiver
2. **Documentation**: All critical information is documented (not just verbal)
3. **Verification**: Receiver confirms receipt and understanding
4. **Escalation Path**: If issues arise, clear escalation path is known
5. **Feedback Loop**: Previous stakeholders are informed of outcomes
6. **Continuous Improvement**: Handoff process is evaluated in retrospectives

## When Handoffs Go Wrong

If a handoff is missed or unclear:
1. Identify the root cause (unclear responsibility, missing communication, capacity issue)
2. Document the impact (rework, delay, quality issue)
3. Add to retrospective action items to prevent recurrence
4. Notify relevant stakeholders of any downstream effects

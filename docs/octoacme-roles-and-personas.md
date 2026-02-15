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

## Engineering Leads

### Role Summary
Engineering Leads guide technical direction, mentor developers, and ensure engineering best practices are followed. They collaborate with Project Managers and Product Managers to balance technical excellence with delivery timelines.

### Responsibilities
- Define technical architecture and design standards
- Mentor and support developers through code reviews and pair programming
- Assess technical feasibility and effort estimates
- Identify and resolve technical blockers
- Drive engineering quality and operational excellence

### Goals
- Maintain high code quality and system reliability
- Foster team growth and technical skill development
- Balance technical debt with feature delivery
- Ensure scalable and maintainable solutions

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback and guidance
- Sprint planning technical input
- Engineering retrospectives

---

## QA / Quality Assurance

### Role Summary
QA professionals validate that features meet acceptance criteria and quality standards before release. They design test strategies, execute tests, and advocate for quality throughout the development lifecycle.

### Responsibilities
- Create and maintain test plans and test cases
- Execute manual and automated tests
- Report and track defects
- Verify acceptance criteria before sign-off
- Collaborate with developers on testability

### Goals
- Ensure features meet quality standards before release
- Minimize production defects
- Improve test coverage and automation
- Provide timely feedback to developers

### Typical Communication
- Test reports and defect summaries
- QA sign-off on features
- Sprint planning input on testability
- Quality metrics and trends

---

## Change Coordinator

### Role Summary
The Change Coordinator manages the change control process, ensuring that all changes to production systems are properly reviewed, documented, and communicated. They reduce risk by coordinating approvals and maintaining a clear audit trail of what changed, when, and why.

### Responsibilities
- Review and triage incoming change requests
- Coordinate change approval workflows (CAB meetings)
- Maintain the change log and audit trail
- Communicate upcoming changes to stakeholders
- Track change success rates and incidents caused by changes
- Escalate high-risk changes for additional review

### Goals
- Minimize production incidents from uncontrolled changes
- Ensure regulatory and compliance requirements are met
- Maintain clear visibility into upcoming changes
- Balance change velocity with risk management

### Key Interactions
- **Project Managers**: Coordinate change timing with project schedules
- **Engineering Leads**: Review technical change details and risk assessment
- **QA**: Ensure proper testing before production changes
- **Stakeholder Liaison**: Communicate change windows to business stakeholders

### Artifacts Owned/Maintained
- [Change Request Template](change-request-template.md)
- Change Log / Change Calendar
- Change Approval Board (CAB) meeting notes

---

## Quality Champion

### Role Summary
The Quality Champion drives quality culture across the team, advocates for quality practices, and ensures quality gates are enforced throughout the development lifecycle. They work to embed quality into every phase rather than treating it as a final checkpoint.

### Responsibilities
- Define and maintain quality standards and metrics
- Facilitate quality gate reviews before releases
- Champion testing best practices and automation
- Identify quality trends and improvement opportunities
- Support teams in adopting quality tools and processes
- Escalate quality risks that could impact releases

### Goals
- Shift quality left (earlier in the development process)
- Increase automated test coverage and reliability
- Reduce defect escape rate to production
- Foster a culture where everyone owns quality

### Key Interactions
- **QA**: Partner on test strategy and quality metrics
- **Engineering Leads**: Advocate for testability and quality in design
- **Project Managers**: Provide quality status for go/no-go decisions
- **Process Improvement Facilitator**: Identify quality process improvements

### Artifacts Owned/Maintained
- [Quality Gate Checklist](quality-gate-checklist.md)
- Quality metrics dashboard
- Testing standards and guidelines

---

## Stakeholder Liaison

### Role Summary
The Stakeholder Liaison serves as the primary bridge between the delivery team and business stakeholders. They ensure stakeholders are informed, their needs are understood, and their feedback is incorporated effectively without disrupting team flow.

### Responsibilities
- Maintain stakeholder communication plans
- Schedule and facilitate stakeholder demos and updates
- Gather and synthesize stakeholder feedback
- Manage stakeholder expectations on timelines and scope
- Escalate stakeholder concerns to Project Manager or Product Manager
- Ensure key decisions have stakeholder buy-in

### Goals
- Keep stakeholders informed and engaged
- Minimize surprise escalations
- Ensure stakeholder needs influence product direction
- Protect team focus time from ad-hoc stakeholder requests

### Key Interactions
- **Project Managers**: Align on status updates and risk communication
- **Product Managers**: Translate stakeholder feedback into product insights
- **Change Coordinator**: Communicate change windows to affected stakeholders
- **Developers**: Buffer team from distracting stakeholder requests

### Artifacts Owned/Maintained
- [Stakeholder Communication Plan](stakeholder-communication-plan.md)
- Stakeholder contact list and RACI
- Demo schedules and stakeholder feedback logs

---

## Process Improvement Facilitator

### Role Summary
The Process Improvement Facilitator leads the team in identifying, prioritizing, and implementing process improvements. They facilitate retrospectives, track action items, and ensure the team continuously learns and evolves its ways of working.

### Responsibilities
- Facilitate sprint and release retrospectives
- Track and follow up on improvement action items
- Identify process bottlenecks and inefficiencies
- Propose and pilot process experiments
- Measure impact of process changes
- Share learnings across teams

### Goals
- Foster a culture of continuous improvement
- Ensure retrospective actions are completed, not forgotten
- Reduce friction and waste in team processes
- Increase team satisfaction and productivity

### Key Interactions
- **Project Managers**: Coordinate process changes with project workflows
- **Quality Champion**: Partner on quality process improvements
- **All team members**: Gather input on process pain points and successes

### Artifacts Owned/Maintained
- [Retrospective Action Tracker](retrospective-action-tracker.md)
- Retrospective summaries and trends
- Process improvement experiment results

---

## Activity-to-Role Mapping (RACI)

This section shows who is Responsible, Accountable, Consulted, or Informed for common project activities.

| Activity | Project Manager | Product Manager | Developer | Engineering Lead | QA | Change Coordinator | Quality Champion | Stakeholder Liaison | Process Improvement Facilitator |
|----------|----------------|-----------------|-----------|------------------|----|--------------------|------------------|---------------------|--------------------------------|
| Define project scope | C | A | C | C | I | I | I | C | I |
| Create project plan | A | C | I | C | I | I | I | I | I |
| Prioritize backlog | C | A | I | C | I | I | I | C | I |
| Implement features | I | I | R | A | I | I | I | I | I |
| Code review | I | I | R | A | I | I | C | I | I |
| Write tests | I | I | R | A | C | I | C | I | I |
| Execute QA testing | I | I | C | C | R/A | I | C | I | I |
| Quality gate review | C | I | I | C | C | I | A | I | I |
| Submit change request | C | I | C | C | C | A | C | I | I |
| Approve production change | C | I | I | C | C | A | C | C | I |
| Communicate to stakeholders | C | C | I | I | I | I | I | A | I |
| Facilitate retrospective | C | I | C | C | C | I | C | I | A |
| Track improvement actions | C | I | C | C | C | I | C | I | A |
| Release to production | A | C | R | C | C | C | C | C | I |
| Post-deployment verification | C | I | R | C | R | C | C | I | I |

**Legend:**
- **R** (Responsible): Does the work
- **A** (Accountable): Ultimately answerable for completion
- **C** (Consulted): Provides input
- **I** (Informed): Kept up-to-date

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The RACI matrix helps clarify collaboration points and decision rights across the project lifecycle.


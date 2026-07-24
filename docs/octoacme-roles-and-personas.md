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

## Engineering Lead / Tech Lead

### Role Summary
Engineering Leads own technical direction, architecture decisions, and code quality standards. They align implementation strategy to product outcomes and delivery constraints.

### Responsibilities
- Define and document architecture and technical approach
- Set and enforce code quality and design review standards
- Mentor developers and unblock complex technical challenges
- Identify technical risks and drive mitigation plans
- Provide technical feasibility input and delivery estimates

### Goals
- Deliver maintainable, scalable, and secure solutions
- Reduce rework by making clear technical trade-offs early
- Improve engineering velocity through better technical alignment

### Typical Communication
- Architecture and design review discussions
- Technical trade-off conversations in planning and refinement
- PR reviews, implementation guidance, and risk escalations

### How this role interacts with existing roles
- **Developers:** provides mentoring, design guidance, and code review support
- **Product Managers:** aligns technical trade-offs with product goals and priorities
- **Project Managers:** informs feasibility, estimates, dependencies, and risk impacts
- **QA / Test Engineer:** collaborates on quality gates and testability for critical flows
- **Designer / UX Researcher:** aligns system design with UX constraints and implementation details
- **Release Manager:** confirms technical readiness and rollback considerations for releases

---

## QA / Test Engineer

### Role Summary
QA / Test Engineers own validation of acceptance criteria and quality gates across the delivery lifecycle. They ensure releases meet functional and reliability expectations.

### Responsibilities
- Validate features against acceptance criteria and Definition of Done
- Design and execute manual and automated test scenarios
- Triage defects, verify fixes, and track quality risks
- Drive pre-release smoke testing and regression confidence
- Collaborate on test coverage strategy for critical paths

### Goals
- Prevent regressions and production-impacting defects
- Improve confidence in release readiness
- Ensure consistent quality standards across teams

### Typical Communication
- Bug triage updates and QA status reports
- Test plans, test case feedback, and acceptance validation notes
- Pre-release smoke test results and go/no-go quality signals

### How this role interacts with existing roles
- **Developers:** partners on bug triage, fix validation, and test coverage improvements
- **Product Managers:** clarifies acceptance criteria and validates intended behavior
- **Project Managers:** surfaces quality risks and timelines that affect delivery plans
- **Release Manager:** provides pre-release smoke test outcomes and release quality sign-off input

---

## Designer / UX Researcher

### Role Summary
Designers / UX Researchers own user experience, usability, and design validation. They ensure solutions are intuitive and grounded in user needs.

### Responsibilities
- Frame user problems and define experience requirements
- Produce flows, wireframes, and interaction specifications
- Conduct user research and usability validation
- Support design hand-off and implementation fidelity reviews
- Incorporate feedback from support and stakeholders into design improvements

### Goals
- Deliver usable, accessible, and cohesive user experiences
- Reduce usability friction and support burden
- Validate designs before and after implementation

### Typical Communication
- Discovery and problem-framing workshops with product
- Design reviews and implementation walkthroughs with engineering
- Research findings and usability recommendations shared with project stakeholders

### How this role interacts with existing roles
- **Product Managers:** collaborates on problem framing, research insights, and feature intent
- **Developers:** supports design hand-off and reviews implementation fidelity
- **Project Managers:** aligns design milestones and dependencies with delivery timelines
- **Support / Customer Success:** incorporates customer pain points into UX improvements

---

## Release Manager

### Role Summary
Release Managers own release coordination, deployment scheduling, and rollback readiness according to the Release & Deployment guide.

### Responsibilities
- Coordinate release scope, timing, and deployment windows
- Verify pre-release requirements and readiness checklists
- Ensure rollback and incident communication plans are in place
- Lead release go/no-go coordination across teams
- Track post-deploy verification and release announcements

### Goals
- Deliver predictable, low-risk releases
- Minimize deployment-related incidents and recovery time
- Keep stakeholders informed throughout release execution

### Typical Communication
- Release readiness and go/no-go updates
- Deployment schedule and status communications
- Incident and rollback coordination notes

### How this role interacts with existing roles
- **Developers:** confirms readiness checks, deployment support, and rollback technical coverage
- **QA / Test Engineer:** incorporates smoke test results into release decisions
- **Project Managers:** aligns release timing with milestones and external dependencies
- **Product Managers:** confirms release scope and customer-facing change expectations
- **Support / Customer Success:** coordinates release communication and incident messaging

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders / Sponsors provide business direction, approvals, and escalation resolution for high-impact decisions.

### Responsibilities
- Set business priorities and success expectations
- Approve major scope, timeline, and investment decisions
- Resolve escalations with cross-team business impact
- Ensure delivery remains aligned to strategic outcomes
- Champion stakeholder alignment across the organization

### Goals
- Maximize business value and strategic alignment
- Reduce decision latency for high-impact issues
- Maintain confidence in delivery progress and outcomes

### Typical Communication
- Executive status reviews and milestone updates
- Escalation decisions and priority alignment discussions
- Approval checkpoints for major releases or scope changes

### How this role interacts with existing roles
- **Product Managers:** aligns priorities, outcomes, and roadmap decisions
- **Project Managers:** receives status updates and resolves escalations per defined paths
- **Engineering Lead / Tech Lead:** reviews major technical trade-offs tied to business outcomes
- **Support / Customer Success:** reviews customer-impacting incident trends and service risks

---

## Support / Customer Success

### Role Summary
Support / Customer Success represents the voice of the customer post-release, surfacing incidents, adoption blockers, and improvement opportunities.

### Responsibilities
- Capture and triage customer feedback and production issues
- Communicate impact and urgency of incidents to delivery teams
- Track recurring customer pain points and adoption risks
- Share release outcomes and known issues with customers
- Feed post-release insights into planning and retrospectives

### Goals
- Improve customer satisfaction and retention
- Shorten time to detect and communicate customer-impacting issues
- Strengthen feedback loops between customers and product teams

### Typical Communication
- Incident updates and customer impact summaries
- Feedback reports from support channels and success calls
- Post-release communication on changes, known issues, and follow-up actions

### How this role interacts with existing roles
- **Product Managers:** provides structured customer feedback for prioritization
- **Release Manager:** aligns incident communication and release messaging
- **Project Managers:** flags recurring support risks that affect plans and timelines
- **Designer / UX Researcher:** shares usability pain points and adoption friction

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

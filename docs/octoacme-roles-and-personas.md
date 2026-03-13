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

### Interactions with Other Roles
- **Product Manager**: receive feature specs and acceptance criteria; collaborate on feasibility and trade-offs.
- **Project Manager**: report progress, surface technical risks, and flag blockers.
- **QA / Test Lead**: partner on test coverage, reproduce defects, and resolve bugs.
- **DevOps Engineer**: coordinate on CI/CD pipelines, environment issues, and deployment readiness.
- **UX Designer**: receive design handoffs and provide feasibility feedback.

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

### Interactions with Other Roles
- **Project Manager**: align on timelines, scope changes, and risk decisions.
- **Developers**: provide acceptance criteria and feature specs; validate delivered work.
- **UX Designer**: collaborate on feature specs and usability goals.
- **QA / Test Lead**: define acceptance criteria and review test results.
- **Stakeholders**: gather requirements, present roadmaps, and collect feedback.

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

### Interactions with Other Roles
- **Product Manager**: align on scope, priorities, and delivery trade-offs.
- **Developers**: remove blockers, track progress, and escalate risks.
- **Release Manager**: coordinate release scheduling and deployment windows.
- **DevOps Engineer**: track infrastructure risks and capacity constraints.
- **QA / Test Lead**: monitor quality risks and ensure testing milestones are met.
- **Stakeholders**: provide status updates, manage escalations, and facilitate go/no-go decisions.

---

## Release Manager

### Role Summary
The Release Manager coordinates release timelines, deployment windows, and rollback plans to ensure smooth, predictable software releases.

### Responsibilities
- Plan and manage release schedules and deployment windows
- Coordinate release readiness checks with Project Manager, DevOps, and QA
- Own rollback plans and contingency procedures
- Communicate release status and outcomes to stakeholders
- Maintain the release calendar and change log

### Goals
- Deliver releases on schedule with minimal disruption
- Ensure all teams are aligned and prepared before each release
- Reduce release-related incidents and rollbacks

### Typical Communication
- Release readiness meetings and go/no-go checklists
- Release announcements and post-release summaries
- Coordination emails and tickets with DevOps, QA, and PM

### Interactions with Other Roles
- **Project Manager**: coordinate release scheduling and align on milestone dates.
- **DevOps Engineer**: oversee deployment execution and infrastructure readiness.
- **QA / Test Lead**: validate release readiness and review sign-off criteria.
- **Stakeholders**: communicate release announcements and obtain approvals.
- **Support Lead**: hand off post-release issue triage and monitor early feedback.

---

## DevOps Engineer

### Role Summary
DevOps Engineers ensure CI/CD pipeline stability, manage infrastructure as code, and maintain the reliability and scalability of deployment environments.

### Responsibilities
- Build, maintain, and improve CI/CD pipelines
- Manage infrastructure as code and environment configurations
- Support developers and QA with environment setup and troubleshooting
- Monitor system health, performance, and reliability
- Implement and enforce security and compliance controls in pipelines

### Goals
- Maximize pipeline reliability and deployment speed
- Reduce environment-related blockers for developers and QA
- Maintain secure, scalable, and observable infrastructure

### Typical Communication
- Infrastructure change notifications and runbooks
- On-call incident reports and post-mortems
- Pipeline status dashboards and alerts

### Interactions with Other Roles
- **Developers**: provide CI/CD support, environment setup, and deployment guidance.
- **QA / Test Lead**: provision and maintain test environments.
- **Release Manager**: execute deployments and provide infrastructure readiness sign-off.
- **Project Manager**: surface infrastructure risks and capacity constraints.

---

## UX Designer

### Role Summary
UX Designers conduct user research, create wireframes and prototypes, and ensure that product experiences are usable, accessible, and aligned with customer needs.

### Responsibilities
- Conduct user research and synthesize findings into design insights
- Create wireframes, prototypes, and high-fidelity design assets
- Collaborate with Product Manager on feature specs and usability goals
- Gather and incorporate user and stakeholder feedback through design iterations
- Align design milestones with project timelines

### Goals
- Deliver intuitive and accessible user experiences
- Reduce usability issues discovered late in development
- Ensure design decisions are grounded in user research and data

### Typical Communication
- Design reviews and prototype walkthroughs
- Usability research reports and design handoff documentation
- Collaborative sessions with Product Manager and Developers

### Interactions with Other Roles
- **Product Manager**: collaborate on feature specs and usability goals.
- **Developers**: provide design handoffs and discuss implementation feasibility.
- **Stakeholders**: present prototypes and solicit user feedback.
- **Project Manager**: align design deliverables with project milestones.

---

## QA / Test Lead

### Role Summary
The QA / Test Lead validates quality and acceptance criteria across all project phases, owning the test strategy, test plans, and defect triage to ensure releases meet defined standards.

### Responsibilities
- Define and maintain the test strategy and test plans
- Coordinate manual and automated testing efforts
- Triage defects and track resolution with developers
- Validate acceptance criteria defined by Product Manager
- Provide release readiness sign-off to the Release Manager

### Goals
- Prevent quality regressions from reaching production
- Improve test coverage and testing efficiency over time
- Ensure every release meets defined acceptance criteria

### Typical Communication
- Test plans, defect reports, and test results summaries
- Release readiness sign-off communications
- Defect triage meetings with developers

### Interactions with Other Roles
- **Developers**: collaborate on test coverage, bug reproduction, and fix validation.
- **Product Manager**: review and validate acceptance criteria.
- **Release Manager**: provide release readiness sign-off.
- **Project Manager**: surface quality risks and testing milestone status.
- **DevOps Engineer**: coordinate on test environment setup and CI pipeline test stages.

---

## Support Lead

### Role Summary
The Support Lead leads incident response and post-release issue triage, maintains support documentation, and coordinates feedback collection to drive continuous improvement.

### Responsibilities
- Lead incident response and escalation for production issues
- Triage and prioritize post-release customer-reported issues
- Maintain internal and external support documentation
- Coordinate with Product Manager, Developers, and QA to resolve customer issues
- Collect and synthesize customer feedback for the product team

### Goals
- Minimize customer impact from production incidents
- Reduce time-to-resolution for escalated issues
- Improve product quality by closing the feedback loop between support and development

### Typical Communication
- Incident reports and post-mortems
- Support metrics dashboards and trend summaries
- Escalation tickets and handoff communications

### Interactions with Other Roles
- **Release Manager**: coordinate on post-release issues and hotfix priorities.
- **Developers**: escalate bugs and provide reproduction steps for urgent fixes.
- **Product Manager**: channel customer feedback into roadmap and backlog decisions.
- **Project Manager**: report support metrics and flag risks stemming from open issues.

---

## Stakeholders

### Role Summary
Stakeholders provide strategic direction, inputs, and approvals that shape project scope and priorities. They review deliverables at key milestones and participate in go/no-go decisions.

### Responsibilities
- Provide business requirements, priorities, and strategic context
- Review project deliverables and give feedback at key milestones
- Participate in go/no-go decisions and priority-setting discussions
- Approve scope changes and major risk decisions
- Champion project outcomes within their business units

### Goals
- Ensure the project delivers measurable business value
- Maintain visibility into project progress and risks
- Make timely decisions to keep projects on track

### Typical Communication
- Monthly or milestone-based status briefings
- Review meetings for key deliverables and demos
- Escalation discussions and approval communications

### Interactions with Other Roles
- **Product Manager**: provide business priorities and requirements; review roadmap updates.
- **Project Manager**: receive status updates and participate in escalations.
- **Release Manager**: provide release approvals and receive release announcements.
- **UX Designer**: review prototypes and provide user feedback.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The full set of personas — Developers, Product Managers, Project Managers, Release Manager, DevOps Engineer, UX Designer, QA / Test Lead, Support Lead, and Stakeholders — covers the end-to-end project lifecycle and supports exercises across planning, execution, release, and support phases.
- The "Interactions with Other Roles" sections map cross-functional dependencies and communication patterns, making them useful for generating realistic scenario prompts.



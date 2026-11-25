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

## Release Manager

### Role Summary
Release Managers coordinate release readiness and ensure that production deployments are controlled, observable, and recoverable.

### Responsibilities
- Define release readiness and approval requirements
- Coordinate deployment windows and release sequencing
- Maintain rollback and mitigation plans
- Draft and publish release notes
- Coordinate stakeholder and support announcements

### Goals
- Deliver releases safely and predictably
- Reduce deployment-related risk and downtime
- Improve release visibility and operational readiness

### Typical Communication
- Release readiness reviews with Project and Product Managers
- Deployment plans and go/no-go updates with Developers and QA/Testing
- Post-deployment summaries for stakeholders and support teams

### Interactions with Existing Roles
- Works with **Project Managers** to align releases with milestones and communicate schedules.
- Works with **Product Managers** to confirm release scope and customer-facing messaging.
- Works with **Developers** to validate merged changes and rollback instructions.
- Works with **QA/Testing** to confirm acceptance and smoke-test results.

---

## Security and Compliance Lead

### Role Summary
Security and Compliance Leads define required controls and help the project identify, mitigate, and escalate security and regulatory risks.

### Responsibilities
- Define applicable security and compliance requirements
- Review threat models, control designs, and mitigation plans
- Coordinate security assessments and incident escalation
- Track unresolved security findings and exceptions
- Verify required evidence and approvals before release

### Goals
- Reduce security and compliance risk
- Embed security controls throughout delivery
- Maintain clear escalation and audit readiness

### Typical Communication
- Security reviews during planning and before release
- Risk updates with Project Managers and stakeholders
- Incident coordination through the Security on-call path

### Interactions with Existing Roles
- Works with **Developers** to define secure implementation patterns and address findings.
- Works with **Project Managers** to track compliance dependencies, risks, and approvals.
- Works with **QA/Testing** to define security and compliance validation scenarios.
- Works with **Product Managers** to evaluate trade-offs among scope, value, and risk.

---

## Support and Customer Operations Lead

### Role Summary
Support and Customer Operations Leads prepare operational teams and customers for new releases and communicate known issues and customer impact.

### Responsibilities
- Assess support readiness and operational impact
- Prepare support procedures and escalation paths
- Review known issues and customer-facing documentation
- Gather customer feedback and recurring support themes
- Coordinate incident and release communications

### Goals
- Improve customer readiness and support quality
- Reduce resolution time and avoidable escalations
- Feed customer evidence back into product decisions

### Typical Communication
- Support readiness reviews with the delivery team
- Customer-impact updates to Product and Project Managers
- Release briefings and escalation guidance for support teams

### Interactions with Existing Roles
- Works with **Product Managers** to represent customer needs and validate outcomes.
- Works with **Project Managers** to align communication plans and readiness milestones.
- Works with **Developers** to clarify known issues, fixes, and troubleshooting guidance.
- Works with **QA/Testing** to review acceptance scenarios and identify support edge cases.
- Works with **Stakeholders** to communicate operational impacts and decisions.

---

## Data and Observability Lead

### Role Summary
Data and Observability Leads define how project outcomes and operational health are measured, monitored, and reported.

### Responsibilities
- Define success metrics and reporting requirements
- Specify dashboards, alerts, logs, and traces
- Establish data quality and metric validation expectations
- Monitor adoption, reliability, usage, and delivery signals
- Communicate trends and findings to project decision-makers

### Goals
- Create reliable evidence for project decisions
- Improve visibility into technical and customer outcomes
- Detect delivery and operational risks early

### Typical Communication
- Metrics reviews with Product and Project Managers
- Instrumentation planning with Developers
- Validation and reporting reviews with QA/Testing

### Interactions with Existing Roles
- Works with **Product Managers** to define measurable outcomes and evaluate adoption or impact.
- Works with **Developers** to instrument features and operational signals.
- Works with **QA/Testing** to validate metrics, test data, and monitoring behavior.
- Works with **Project Managers** to provide delivery and risk signals for status reporting.

---

## Change and Enablement Lead

### Role Summary
Change and Enablement Leads plan stakeholder adoption, training, documentation, and rollout communication so teams and customers can use delivered capabilities effectively.

### Responsibilities
- Assess change impact and stakeholder adoption needs
- Plan training, documentation, and enablement materials
- Coordinate rollout and communication schedules
- Identify adoption risks and support interventions
- Measure enablement outcomes and gather feedback

### Goals
- Improve stakeholder adoption and readiness
- Reduce resistance and avoidable operational disruption
- Ensure rollout activities are complete and measurable

### Typical Communication
- Change-readiness planning with Project and Product Managers
- Training and rollout coordination with Support and Customer Operations
- Adoption updates for stakeholders

### Interactions with Existing Roles
- Works with **Product Managers** to translate value and feature changes into enablement activities.
- Works with **Project Managers** to incorporate adoption work and milestones into plans.
- Works with **Support and Customer Operations** to align documentation, training, and escalation readiness.
- Works with **Stakeholders** to communicate changes and gather adoption feedback.
- Works with **Developers** and **QA/Testing** to verify documentation and validate realistic customer scenarios.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

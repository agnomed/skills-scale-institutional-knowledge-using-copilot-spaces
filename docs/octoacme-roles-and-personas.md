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
- Work with the Product Manager to clarify outcomes and acceptance criteria.
- Coordinate estimates, dependencies, and delivery risk with the Project Manager.
- Implement guidance from the Engineering/Technical Lead and validate changes with QA.

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
- Align scope and outcomes with stakeholders and the Business/Requirements Analyst.
- Work with UX/Design on customer needs and solution usability.
- Make prioritization decisions with engineering and delivery input while the Project Manager tracks execution.

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
- Partner with the Scrum Master/Delivery Facilitator on team flow, impediments, and planning visibility.
- Coordinate release readiness with the Release Manager/Release Lead and operational readiness with SRE/Operations.
- Escalate delivery constraints or unresolved risks to the Product Manager and stakeholders.

---

## Release Manager / Release Lead

### Role Summary
The Release Manager / Release Lead owns release readiness and coordinates the deployment process, including scheduling, rollout, verification, and rollback planning.

### Responsibilities
- Confirm that acceptance criteria, CI checks, security scans, release notes, and smoke tests are complete
- Coordinate deployment windows and stakeholder communication
- Verify rollout and rollback plans before production changes
- Lead release execution and post-deployment verification

### Goals
- Deliver safe, observable releases
- Minimize deployment risk and recovery time
- Keep delivery, support, and stakeholder teams aligned

### Typical Communication
- Pre-release readiness reviews
- Deployment coordination and status updates
- Post-release verification and incident handoffs

### Interactions with Other Roles
- Coordinates implementation and technical readiness with Developers and the Engineering/Technical Lead.
- Reviews quality evidence with QA and operational readiness with SRE/Operations.
- Works with the Project Manager on timing and the Product Manager on release scope and communication.

---

## Scrum Master / Delivery Facilitator

### Role Summary
The Scrum Master / Delivery Facilitator helps the delivery team maintain an effective, predictable flow of work and removes or escalates impediments.

### Responsibilities
- Facilitate agreed ceremonies such as planning, standups, reviews, and retrospectives
- Identify and remove team-level impediments
- Promote focus, psychological safety, and continuous improvement
- Improve flow and working agreements with the delivery team

### Goals
- Improve team predictability and sustainable delivery
- Reduce preventable blockers and meeting waste
- Strengthen collaboration and learning

### Typical Communication
- Daily standups and delivery planning
- Retrospectives and action-item follow-up
- Impediment and capacity updates

### Interactions with Other Roles
- Partners with the Project Manager on delivery visibility and risk escalation without duplicating ownership of the project plan.
- Works with Developers and QA to improve flow and remove process barriers.
- Supports the Product Manager by keeping backlog refinement and feedback loops focused and effective.

---

## Engineering / Technical Lead

### Role Summary
The Engineering / Technical Lead provides technical direction and coordinates design decisions, architecture dependencies, and engineering quality practices.

### Responsibilities
- Establish technical approach and implementation guardrails
- Identify architecture and integration dependencies
- Coordinate design and code reviews
- Support Developers and QA on testability and operational readiness

### Goals
- Deliver maintainable, scalable solutions
- Reduce technical uncertainty and avoidable rework
- Improve engineering quality and shared technical understanding

### Typical Communication
- Technical design and architecture reviews
- Estimation and dependency discussions
- Code-review escalation and incident follow-up

### Interactions with Other Roles
- Clarifies technical trade-offs with the Product Manager and Project Manager.
- Guides Developers and incorporates QA findings into technical plans.
- Coordinates release constraints with the Release Lead and observability and resilience needs with SRE/Operations.

---

## UX / Design Lead

### Role Summary
The UX / Design Lead represents customer and usability needs by turning research and requirements into clear, accessible user experiences.

### Responsibilities
- Translate customer needs and requirements into designs and interaction patterns
- Validate designs and prototypes with users and stakeholders
- Define usability, accessibility, and visual acceptance expectations
- Collaborate on design review and implementation quality

### Goals
- Improve usability and accessibility
- Reduce friction between discovery and delivery
- Ensure the delivered experience reflects intended customer value

### Typical Communication
- Design critiques and research readouts
- Backlog and acceptance-criteria workshops
- Implementation reviews

### Interactions with Other Roles
- Partners with the Product Manager on outcomes and with stakeholders on needs and feedback.
- Works with the Business/Requirements Analyst to resolve requirement ambiguity.
- Provides designs and acceptance guidance to Developers and QA, and validates delivered behavior.

---

## Security Lead

### Role Summary
The Security Lead establishes security expectations, advises on risk decisions, and coordinates response for security findings or incidents.

### Responsibilities
- Define applicable security requirements and review high-risk changes
- Advise delivery teams on threat models and mitigations
- Coordinate security scanning, findings, exceptions, and incident escalation
- Promote secure implementation and operational practices

### Goals
- Reduce security risk without blocking necessary delivery
- Improve the team's ability to identify and remediate vulnerabilities
- Maintain clear security accountability and escalation paths

### Typical Communication
- Threat-model and security review sessions
- Security findings and remediation tracking
- Security incident communication

### Interactions with Other Roles
- Advises the Engineering/Technical Lead and Developers on secure design and implementation.
- Defines security acceptance evidence for QA and release readiness for the Release Lead.
- Raises material risks to the Project Manager and Product Manager and follows the security incident runbook with SRE/Operations.

---

## Business / Requirements Analyst

### Role Summary
The Business / Requirements Analyst clarifies stakeholder needs and traces outcomes to requirements, decisions, and testable deliverables.

### Responsibilities
- Gather and refine requirements and process needs
- Trace requirements to backlog items and acceptance criteria
- Resolve requirement ambiguity and document decisions
- Support planning and acceptance validation

### Goals
- Improve requirement clarity and traceability
- Reduce rework caused by conflicting or incomplete needs
- Keep stakeholder expectations aligned with delivered outcomes

### Typical Communication
- Requirements and discovery workshops
- Stakeholder interviews and decision logs
- Backlog refinement and acceptance reviews

### Interactions with Other Roles
- Works with stakeholders and the Product Manager to clarify priorities and measurable outcomes.
- Coordinates with UX/Design on requirements that affect user journeys.
- Provides traceable context to Developers and QA and surfaces unresolved decisions to the Project Manager.

---

## SRE / Operations Lead

### Role Summary
The SRE / Operations Lead defines operational readiness and is accountable for service reliability, monitoring, incident response, and support expectations.

### Responsibilities
- Define availability, monitoring, alerting, and support requirements
- Prepare operational runbooks and incident-response procedures
- Coordinate observability, capacity, and rollback readiness
- Lead or support operational incident triage and follow-up

### Goals
- Improve service reliability and recovery time
- Ensure production support is prepared before deployment
- Turn operational findings into measurable improvements

### Typical Communication
- Operational readiness reviews
- Monitoring and capacity planning
- Incident updates and retrospectives

### Interactions with Other Roles
- Coordinates with Developers and the Engineering/Technical Lead on implementation, observability, and incident root-cause follow-up.
- Works with QA on production-like validation and with the Release Lead on rollout, rollback, and verification.
- Communicates operational risk to the Project Manager and Product Manager and escalates security incidents with the Security Lead.

---

## Ownership and Handoff Guidelines

Use a concise RACI-style view when accountability is not obvious. One role should be clearly accountable for each key outcome, while Product, Project, technical, quality, security, and operational roles provide responsibility and informed review.

- Product outcomes and prioritization: accountable—Product Manager; informed—stakeholders, Project Manager, Delivery team
- Delivery plan and risk visibility: accountable—Project Manager; responsible—Scrum Master/Delivery Facilitator and Delivery team
- Technical direction: accountable—Engineering/Technical Lead; informed—Developers, Product Manager, Project Manager
- User experience: accountable—UX/Design Lead; responsible—Product Manager and Developers; verified—QA
- Requirements clarity: accountable—Business/Requirements Analyst; informed—stakeholders, Product Manager, Developers, QA
- Security requirements and findings: accountable—Security Lead; responsible—Engineering and QA; informed—Project Manager and Product Manager
- Release readiness and execution: accountable—Release Manager/Release Lead; informed—Developers, QA, SRE/Operations, Project Manager, Product Manager
- Operational readiness: accountable—SRE/Operations Lead; responsible—Engineering and Release Lead; informed—QA and Project Manager

Escalate unresolved delivery impediments through the Delivery team and Scrum Master/Delivery Facilitator to the Project Manager. Escalate material scope or prioritization decisions to the Product Manager. Escalate technical safety concerns to the Engineering/Technical Lead and security concerns to the Security Lead. Escalate release or operational risk to the Release Lead or SRE/Operations Lead and follow the project and incident escalation paths documented in the program process guides.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When roles are combined in a small team, document the combined role in project-specific plans and retain clear accountability for product, delivery, quality, security, and operations decisions.

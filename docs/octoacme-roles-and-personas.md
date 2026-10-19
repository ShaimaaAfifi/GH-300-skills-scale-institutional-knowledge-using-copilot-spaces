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

## Technical Leads

### Role Summary
Technical Leads guide implementation and keep technical decisions aligned with product goals, architecture, and quality requirements.

### Responsibilities and Decision Scope
- Align Developers on technical approach, interfaces, and engineering standards
- Review technical trade-offs and help QA plan testable solutions
- Make implementation decisions within agreed architecture; bring changes affecting scope, cost, or risk to the Product Manager and Project Manager

### Inputs and Deliverables
- Need product requirements and acceptance criteria, architecture constraints, and Developer estimates
- Own technical designs, decision records, implementation guidance, and technical risk mitigations

### Project Lifecycle and Collaboration
- Planning: clarify feasibility, dependencies, and estimates with the Product Manager and Project Manager
- Execution: support Developers, review designs and code, and coordinate integration and testability with QA
- Release: confirm technical readiness and help resolve deployment issues with Release Managers and Operations
- Retrospectives: identify technical improvements and assign follow-up work with the team

### Escalation
- Raise blockers and cross-team dependencies with the Project Manager; escalate product trade-offs to the Product Manager and significant architecture or security risks to the appropriate owner.

---

## UX/UI Designers

### Role Summary
UX/UI Designers shape usable, accessible experiences and provide design guidance that Developers can implement and QA can verify.

### Responsibilities and Decision Scope
- Research user needs and create user flows, prototypes, and interface specifications
- Apply design-system and accessibility guidance; resolve interaction details within agreed product goals
- Partner with the Product Manager on changes to user needs, scope, or priorities

### Inputs and Deliverables
- Need product goals, stakeholder and user feedback, technical constraints from Developers, and QA findings
- Own design files, interaction and accessibility notes, and design acceptance guidance

### Project Lifecycle and Collaboration
- Planning: clarify user outcomes and design effort with the Product Manager and Project Manager
- Execution: review implementations with Developers and help QA validate intended behavior and accessibility
- Release: check user-facing changes and coordinate any needed updates to help content with Support
- Retrospectives: share usability findings and propose design improvements

### Escalation
- Raise usability or accessibility gaps with the Product Manager and Project Manager; surface implementation constraints with the Technical Lead.

---

## Release Managers

### Role Summary
Release Managers coordinate release readiness, timing, communication, and rollback planning across delivery and operations.

### Responsibilities and Decision Scope
- Maintain the release checklist, schedule, release notes, and rollback or mitigation plan
- Coordinate go/no-go decisions against agreed readiness criteria; do not bypass QA, security, or deployment controls

### Inputs and Deliverables
- Need delivery status from the Project Manager, verification results from QA, readiness details from Developers and Technical Leads, and operational constraints from Support/Operations
- Own the release plan, readiness summary, deployment coordination, and release communications

### Project Lifecycle and Collaboration
- Planning: align milestones and release dependencies with the Project Manager and Product Manager
- Execution: track readiness and open risks with Developers and QA
- Release: coordinate deployment and verification with Operations, QA, and Developers; communicate status to stakeholders
- Retrospectives: capture release issues and follow-up actions with the team

### Escalation
- Escalate unmet readiness criteria or schedule risks to the Project Manager and relevant technical or QA owners; bring business-impacting go/no-go decisions to the Product Manager and stakeholders.

---

## Support/Operations Representatives

### Role Summary
Support/Operations Representatives bring customer support and production-operability needs into delivery and help teams respond to incidents.

### Responsibilities and Decision Scope
- Surface customer issues, operational constraints, monitoring needs, and incident learnings
- Advise on operational readiness and follow established on-call and incident procedures

### Inputs and Deliverables
- Need product and release plans from the Product Manager and Project Manager, implementation and runbook details from Developers, and test results from QA
- Own operational requirements, support guidance, runbook updates, and production feedback for the team

### Project Lifecycle and Collaboration
- Planning: identify support impact, service needs, and operational dependencies with the Project Manager and Technical Lead
- Execution: review supportability and observability with Developers; share customer trends with the Product Manager
- Release: validate operational readiness, monitoring, and support communications with the Release Manager and QA
- Retrospectives: provide incident and customer feedback and track operational improvements

### Escalation
- Raise incidents and service risks through on-call procedures and promptly inform the Project Manager and Technical Lead; escalate customer-impacting product decisions to the Product Manager.

---

## Security Champions

### Role Summary
Security Champions help the delivery team identify and address security requirements and risks throughout the project.

### Responsibilities and Decision Scope
- Promote secure design and development practices and coordinate security reviews with the appropriate security owner
- Advise on threat modeling and mitigations; security approval remains with the designated security authority where required

### Inputs and Deliverables
- Need product data and compliance requirements, designs from Technical Leads and Developers, QA test plans, and operational context
- Own security requirements, threat-model findings, mitigation tracking, and security review coordination

### Project Lifecycle and Collaboration
- Planning: identify security requirements and risks with the Product Manager, Project Manager, and Technical Lead
- Execution: advise Developers on mitigations and coordinate security testing with QA
- Release: confirm findings and required approvals are tracked with the Release Manager and security owner
- Retrospectives: share lessons from incidents or reviews and propose security improvements

### Escalation
- Escalate unresolved or high-impact risks to the security owner and Project Manager; involve the Product Manager when mitigation affects scope or release timing.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

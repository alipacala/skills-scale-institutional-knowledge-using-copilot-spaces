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

## UX / Product Designer

### Role Summary
UX / Product Designers shape end-to-end user experiences so delivered solutions are usable, accessible, and aligned to user needs and product intent.

### Responsibilities
- Produce user journeys, wireframes, interaction patterns, and design specifications
- Validate usability through research, prototypes, and feedback loops
- Define UX-related acceptance criteria and accessibility expectations
- Keep design artifacts aligned with business goals and technical constraints

### Goals and Accountability Boundaries
- Improve task success, usability, and accessibility outcomes
- Own design intent and user interaction quality, while product scope and sequencing remain with Product Managers

### Lifecycle Touchpoints
- Discovery and planning for problem framing, personas, and user flows
- Execution for design clarification, implementation support, and UX sign-off
- Release and retrospective for feedback synthesis and improvement backlog input

### Interactions with Existing Roles
- **Project Managers**: align design milestones and dependencies with delivery timelines
- **Product Managers**: co-define user outcomes, priorities, and acceptance criteria
- **Developers**: clarify interaction details and resolve feasibility trade-offs
- **QA / Testing**: provide usability and accessibility test scenarios
- **Stakeholders**: communicate design rationale and capture feedback

### Typical Communication
- Design reviews, critiques, and prototype walkthroughs
- User research summaries and usability findings
- Acceptance criteria clarifications during planning and execution

---

## Technical Lead / Architect

### Role Summary
Technical Leads / Architects guide solution architecture and engineering standards to ensure systems are scalable, secure, maintainable, and fit for purpose.

### Responsibilities
- Define architectural direction, key design decisions, and technical standards
- Surface and manage technical risks, constraints, and cross-team dependencies
- Review complex implementations and mentor engineers on design quality
- Partner on non-functional requirements, including reliability, performance, and security

### Goals and Accountability Boundaries
- Maintain architectural integrity and long-term maintainability
- Own technical decision quality and guardrails, while delivery scheduling remains with Project Managers

### Lifecycle Touchpoints
- Initiation and planning for architecture options, sizing, and risk assessment
- Execution for design reviews, technical unblock support, and change control
- Release for readiness validation and post-release learning

### Interactions with Existing Roles
- **Project Managers**: coordinate technical dependencies and risk mitigation plans
- **Product Managers**: align solution options with product outcomes and trade-offs
- **Developers**: provide implementation guidance and code/design review support
- **QA / Testing**: align on testability and non-functional validation strategy
- **Stakeholders**: explain technical implications for scope, timeline, and risk

### Typical Communication
- Architecture decision records and technical design docs
- Engineering syncs and implementation reviews
- Risk and dependency updates in delivery forums

---

## DevOps / SRE or Release Manager

### Role Summary
DevOps / SRE or Release Managers own deployment reliability and release coordination so changes can be delivered safely and predictably.

### Responsibilities
- Maintain CI/CD workflows, environments, and deployment runbooks
- Define release readiness checks, rollback plans, and operational checklists
- Partner on observability, incident preparedness, and change controls
- Coordinate release windows, communications, and post-release validation

### Goals and Accountability Boundaries
- Improve deployment success rate, recovery speed, and operational stability
- Own release readiness and operational safeguards, while feature acceptance remains with Product and QA

### Lifecycle Touchpoints
- Planning for environment, pipeline, and release dependency readiness
- Execution for build/deploy support, reliability checks, and change approvals
- Release and post-release monitoring, incident response, and lessons learned

### Interactions with Existing Roles
- **Project Managers**: align release milestones, go/no-go criteria, and escalation paths
- **Product Managers**: coordinate launch windows and customer-impact constraints
- **Developers**: support deployment automation, operational instrumentation, and runbook quality
- **QA / Testing**: align test environments, smoke tests, and release verification gates
- **Stakeholders**: communicate release status, risks, and incident updates

### Typical Communication
- Release plans, go/no-go meetings, and deployment status updates
- Operational dashboards and incident channels
- Post-release and post-incident reviews

---

## Security and Privacy Representative

### Role Summary
Security and Privacy Representatives ensure products and delivery practices meet security and data protection expectations throughout the lifecycle.

### Responsibilities
- Provide threat modeling and privacy impact guidance
- Define security/privacy requirements and required controls
- Review design and implementation against policy and risk posture
- Support incident response readiness and remediation tracking

### Goals and Accountability Boundaries
- Reduce security and privacy risk exposure while enabling timely delivery
- Own security/privacy review quality and control recommendations, while product prioritization remains with Product Managers

### Lifecycle Touchpoints
- Initiation and planning for control requirements and risk classification
- Execution for secure design/code review and verification support
- Release for security/privacy sign-off and incident preparedness checks

### Interactions with Existing Roles
- **Project Managers**: track security/privacy risks, dependencies, and approvals
- **Product Managers**: balance risk controls with customer value and delivery goals
- **Developers**: guide secure implementation patterns and remediation priorities
- **QA / Testing**: align on security and privacy validation scenarios
- **Stakeholders**: communicate risk posture, compliance implications, and exceptions

### Typical Communication
- Security/privacy review notes and risk assessments
- Control checklists and remediation plans
- Incident readiness and response playbooks

---

## Data / Analytics Partner

### Role Summary
Data / Analytics Partners define and validate measurement so teams can evaluate outcomes, make evidence-based decisions, and continuously improve.

### Responsibilities
- Define success metrics, instrumentation requirements, and reporting needs
- Validate data quality and consistency across events, dashboards, and reports
- Analyze experiment and feature performance to inform prioritization
- Support retrospective insights with measurable trends and root causes

### Goals and Accountability Boundaries
- Improve confidence in decision-making through reliable, actionable metrics
- Own measurement design and insight quality, while roadmap decisions remain with Product Managers and Stakeholders

### Lifecycle Touchpoints
- Discovery and planning for KPI definition and telemetry planning
- Execution for instrumentation validation and ongoing metric monitoring
- Release and retrospective for adoption/outcome analysis and recommendations

### Interactions with Existing Roles
- **Project Managers**: provide status metrics and risk indicators for delivery reporting
- **Product Managers**: align on outcome definitions, KPI targets, and experiment design
- **Developers**: specify telemetry implementation and data quality expectations
- **QA / Testing**: validate instrumentation behavior and analytics event correctness
- **Stakeholders**: communicate outcome trends and decision-ready insights

### Typical Communication
- KPI definitions, dashboard walkthroughs, and metric reviews
- Experiment readouts and impact analyses
- Retrospective insights and recommendations

---

## Customer Success / Support Representative

### Role Summary
Customer Success / Support Representatives represent customer-facing operational realities and feedback so launches are supportable and customer impact is managed.

### Responsibilities
- Provide customer context, common pain points, and support readiness requirements
- Contribute support workflows, knowledge base needs, and escalation paths
- Validate launch communication, training, and operational handoff readiness
- Feed customer feedback and incident trends back into planning

### Goals and Accountability Boundaries
- Improve customer adoption, issue resolution speed, and release readiness
- Own support readiness and feedback quality, while delivery execution remains with project and engineering teams

### Lifecycle Touchpoints
- Planning for support requirements, customer messaging, and readiness criteria
- Execution for acceptance scenario input and support process preparation
- Release and post-release for customer communication, issue triage, and feedback loops

### Interactions with Existing Roles
- **Project Managers**: align launch readiness tasks, escalation routes, and communication cadence
- **Product Managers**: share customer insights and prioritize high-impact support themes
- **Developers**: provide issue reproduction context and collaborate on defect triage
- **QA / Testing**: contribute real-world support scenarios for acceptance and regression coverage
- **Stakeholders**: communicate customer impact, readiness status, and post-launch trends

### Typical Communication
- Customer feedback summaries and support trend reports
- Launch readiness and training coordination
- Incident and escalation handoff updates

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

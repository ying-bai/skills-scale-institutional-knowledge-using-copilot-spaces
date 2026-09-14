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

## Supporting Cross-Functional Personas

These personas extend the core delivery roles above for larger or more regulated initiatives where ownership, escalation paths, and cross-team coordination need to be explicit.

### Stakeholder Liaison

#### Role Summary
The Stakeholder Liaison bridges the project team and business stakeholders. This role gathers requirements, shares status, manages expectations, and makes sure stakeholder feedback is reflected in planning and delivery decisions.

#### Responsibilities & Deliverables
- Consolidate stakeholder requirements, questions, and constraints
- Prepare status summaries, milestone updates, and decision requests
- Surface changes in stakeholder priorities to the Project Manager and Product Manager
- Maintain a clear record of stakeholder approvals, follow-ups, and open concerns

#### Key Interactions
- Partners with Product Managers to translate stakeholder needs into prioritized outcomes
- Works with Project Managers to align communications, timelines, and dependency updates
- Coordinates with Developers and the Quality Assurance Lead when stakeholder feedback affects scope or acceptance criteria

#### Decision Scope & Escalation
- Can clarify stakeholder expectations and confirm communication plans
- Can request prioritization review when requirements or expectations change materially
- Escalates unresolved expectation gaps, approval delays, or sponsor-level concerns through the Project Manager to the Product Lead or Sponsor

#### Skills & Competencies
- Strong written and verbal communication
- Stakeholder management and facilitation
- Requirements gathering and synthesis
- Conflict resolution and expectation setting

#### Example Scenarios
- Initiation: collects business goals and stakeholder success measures for the project charter
- Planning: helps the team validate milestone expectations before roadmap commitments are finalized
- Execution: communicates trade-offs when delivery dates shift and captures approval on revised scope

---

### Technical Architect

#### Role Summary
The Technical Architect defines the technical direction for the project and reviews major design decisions. This role ensures solutions remain scalable, maintainable, secure, and aligned with platform standards.

#### Responsibilities & Deliverables
- Establish technical direction, guardrails, and architectural principles
- Review design proposals, integration patterns, and major implementation trade-offs
- Identify technical risks, dependencies, and long-term maintainability concerns
- Produce or approve design notes, architecture decisions, and system constraints

#### Key Interactions
- Works closely with Developers on implementation approach, decomposition, and design reviews
- Partners with Project Managers to highlight technical dependencies and sequencing impacts
- Collaborates with the Quality Assurance Lead on non-functional quality expectations such as performance, resiliency, and observability

#### Decision Scope & Escalation
- Can approve or reject design approaches that violate architecture standards or introduce unacceptable technical risk
- Recommends mitigation plans when scale, security, or maintainability concerns are identified
- Escalates cross-team architectural conflicts or platform-impacting decisions to engineering leadership

#### Skills & Competencies
- System design and architecture review
- Scalability, reliability, and security fundamentals
- Technical mentoring and design facilitation
- Broad knowledge of the platform, integrations, and operational constraints

#### Example Scenarios
- Initiation: advises on feasibility and major technical constraints during solution shaping
- Planning: reviews proposed architecture before estimates are finalized
- Execution: resolves a design dispute between delivery teams and sets the preferred implementation pattern

---

### Quality Assurance Lead

#### Role Summary
The Quality Assurance Lead owns project quality standards, test planning, and verification strategy. This role works across product and engineering to ensure deliverables meet acceptance criteria and definition-of-done expectations.

#### Responsibilities & Deliverables
- Define test strategy, coverage expectations, and verification checkpoints
- Coordinate test planning across functional, regression, and release-readiness activities
- Track quality risks, defects, and acceptance gaps through resolution
- Maintain test evidence, sign-off criteria, and readiness recommendations for release

#### Key Interactions
- Partners with Developers to clarify testability, defect triage, and remediation priorities
- Works with Product Managers to confirm acceptance criteria are testable and complete
- Coordinates with the Release Manager on smoke tests, release verification, and go/no-go input

#### Decision Scope & Escalation
- Can block readiness sign-off when acceptance criteria, test coverage, or defect thresholds are not met
- Recommends release deferral when unresolved defects create unacceptable delivery risk
- Escalates systemic quality issues to the Project Manager, Product Manager, and engineering leadership as needed

#### Skills & Competencies
- Test strategy and planning
- Defect management and root-cause analysis
- Risk-based quality assessment
- Clear documentation of acceptance and verification results

#### Example Scenarios
- Planning: defines the verification approach for a high-risk feature before sprint commitments
- Execution: coordinates regression testing after a late design change
- Release: advises whether the release should proceed after smoke tests expose a critical defect

---

### Business Analyst

#### Role Summary
The Business Analyst analyzes business needs and translates them into actionable requirements. This role helps the team connect stakeholder intent, user stories, and solution validation back to measurable business objectives.

#### Responsibilities & Deliverables
- Elicit, document, and refine business requirements and process impacts
- Translate requirements into user stories, workflows, and acceptance-ready detail
- Validate proposed solutions against business rules and expected outcomes
- Maintain requirement traceability between stakeholder needs, backlog items, and delivered capabilities

#### Key Interactions
- Partners with the Stakeholder Liaison and Product Managers to refine business priorities
- Works with Developers and the Technical Architect to clarify workflows, constraints, and edge cases
- Supports the Quality Assurance Lead by ensuring acceptance criteria reflect business intent

#### Decision Scope & Escalation
- Can recommend requirement clarifications, scope splits, and acceptance updates
- Can reject ambiguous or incomplete requirements from being treated as delivery-ready
- Escalates requirement conflicts or business rule disputes to the Product Manager and Sponsor when alignment is needed

#### Skills & Competencies
- Business process analysis
- User story writing and acceptance criteria definition
- Facilitation, interviewing, and documentation
- Analytical thinking and validation against business outcomes

#### Example Scenarios
- Initiation: maps current-state pain points and desired business outcomes
- Planning: converts stakeholder goals into backlog-ready stories and acceptance criteria
- Execution: validates that a completed workflow matches the intended approval process before release

---

### Release Manager

#### Role Summary
The Release Manager coordinates release planning and deployment readiness. This role aligns delivery, quality, and operational stakeholders on deployment schedules, release notes, and compliance with release procedures.

#### Responsibilities & Deliverables
- Build and maintain the release plan, timeline, and deployment checklist
- Coordinate release windows, change approvals, and communication plans
- Publish release notes, rollout expectations, and rollback considerations
- Confirm release readiness inputs from development, QA, and operational stakeholders

#### Key Interactions
- Works with Project Managers on milestone timing and dependency alignment
- Coordinates with the Quality Assurance Lead on smoke tests, verification, and defect thresholds
- Partners with Developers and operational owners to confirm deployment sequencing and rollback readiness

#### Decision Scope & Escalation
- Can pause or reschedule a release when readiness criteria, approvals, or deployment safeguards are incomplete
- Can require missing release notes, rollback plans, or verification evidence before go-live
- Escalates release-blocking issues to the Project Manager, Product Manager, and operational leadership during go/no-go decisions

#### Skills & Competencies
- Release planning and change coordination
- Deployment process discipline
- Cross-functional communication under time constraints
- Risk assessment, incident awareness, and rollback planning

#### Example Scenarios
- Planning: coordinates the initial release calendar for a multi-team feature launch
- Execution: adjusts the deployment window when a dependent change is delayed
- Release: runs the go/no-go check, ensures release notes are published, and confirms post-deploy verification

---

### Risk and Compliance Officer

#### Role Summary
The Risk and Compliance Officer monitors risks tied to compliance, security, privacy, and regulatory obligations. This role helps the project team identify gaps early, document mitigations, and escalate issues before they become release or audit problems.

#### Responsibilities & Deliverables
- Identify compliance, security, privacy, and regulatory risks relevant to the project
- Maintain mitigation guidance, evidence requests, and compliance-related action items
- Review changes for adherence to required controls, approvals, and documentation
- Track and escalate exceptions, unresolved findings, or audit-sensitive issues

#### Key Interactions
- Partners with Project Managers to keep risk registers current and visible
- Works with the Technical Architect and Developers on control design, data handling, and remediation options
- Coordinates with the Release Manager when compliance evidence or approvals affect deployment readiness

#### Decision Scope & Escalation
- Can require mitigation plans, additional reviews, or documented exceptions for identified compliance gaps
- Can recommend that a release be blocked when regulatory, privacy, or security obligations are unmet
- Escalates serious compliance exposure or security incidents using the defined security and sponsor escalation paths

#### Skills & Competencies
- Risk management and control assessment
- Compliance, privacy, and security awareness
- Documentation and evidence management
- Judgment on escalation timing and regulatory impact

#### Example Scenarios
- Initiation: flags data-handling obligations for a project involving customer information
- Planning: adds compliance checkpoints and evidence needs to the delivery plan
- Release: prevents deployment until required approvals and security remediation steps are complete

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

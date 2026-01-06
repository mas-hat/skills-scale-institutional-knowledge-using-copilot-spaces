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

## Quality Assurance (QA) Lead

### Role Summary
QA Leads ensure product quality through comprehensive testing strategies, automation, and early defect detection. They advocate for testability and quality standards throughout the development lifecycle.

### Responsibilities
- Design and implement test strategies (unit, integration, E2E, performance)
- Build and maintain automated test suites and CI/CD quality gates
- Coordinate testing activities across development sprints
- Define acceptance criteria in collaboration with Product Managers
- Track quality metrics and defect trends
- Advocate for testability in design and architecture decisions

### Goals
- Catch defects early before reaching production
- Maintain high test coverage and reliability
- Reduce manual testing overhead through automation
- Ensure compliance with quality standards and regulations

### Typical Communication
- Collaborate with Developers on test strategy and implementation
- Work with Product Managers to clarify acceptance criteria
- Report quality metrics to Project Managers and stakeholders
- Daily standups and sprint planning sessions
- Test plan reviews and bug triage meetings

---

## UX/UI Designer

### Role Summary
UX/UI Designers create intuitive, accessible, and visually compelling user experiences. They bridge user needs with technical implementation through research, prototyping, and design systems.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Develop and maintain design systems and component libraries
- Ensure accessibility standards (WCAG) are met
- Collaborate on information architecture and user flows
- Validate designs with users and iterate based on feedback

### Goals
- Maximize usability and user satisfaction
- Reduce friction in user workflows
- Maintain consistent, accessible design patterns
- Balance aesthetic quality with technical feasibility

### Typical Communication
- Partner with Product Managers on user research and feature definition
- Work closely with Developers on design implementation and feasibility
- Present designs and research findings to Project Managers and stakeholders
- Regular design reviews and feedback sessions
- Handoff specifications and assets to development team

---

## Technical Writer

### Role Summary
Technical Writers create clear, accurate documentation that enables users and team members to understand and effectively use products and systems. They ensure knowledge is accessible and maintainable.

### Responsibilities
- Write and maintain user guides, API documentation, and tutorials
- Create internal documentation (runbooks, architecture docs, onboarding guides)
- Collaborate with Developers to document features and APIs
- Establish documentation standards and style guides
- Review and edit technical content for clarity and accuracy
- Manage documentation publishing and version control

### Goals
- Reduce support burden through self-service documentation
- Enable faster onboarding for new team members
- Ensure documentation stays current with product changes
- Make complex technical concepts accessible to target audiences

### Typical Communication
- Work with Developers to gather technical details and review drafts
- Coordinate with Product Managers on feature priorities and user-facing content
- Align with Project Managers on documentation milestones and deliverables
- Participate in sprint reviews to identify documentation needs
- Gather feedback from users and support teams

---

## Release Coordinator

### Role Summary
Release Coordinators orchestrate the deployment process, ensuring releases are planned, tested, and delivered smoothly with minimal risk. They manage release schedules, dependencies, and communication.

### Responsibilities
- Plan and schedule releases across multiple teams and components
- Coordinate release activities (code freeze, testing windows, deployment)
- Maintain release documentation and runbooks
- Track release readiness (PRs merged, tests passing, approvals obtained)
- Manage communication of release schedules and status
- Facilitate go/no-go decisions and rollback procedures

### Goals
- Deliver releases on schedule with zero downtime
- Minimize deployment-related incidents
- Maintain clear visibility into release status and blockers
- Continuously improve release processes and automation

### Typical Communication
- Coordinate with Project Managers on release timelines and risks
- Work with Developers on merge schedules and deployment procedures
- Align with QA Leads on testing completion and quality gates
- Report release status to stakeholders and leadership
- Host release planning and retrospective meetings

---

## Security Champion

### Role Summary
Security Champions embed security best practices throughout the development lifecycle. They identify vulnerabilities, promote secure coding, and ensure compliance with security policies.

### Responsibilities
- Conduct security reviews of code, designs, and architectures
- Implement and monitor security scanning tools (SAST, DAST, dependency checks)
- Triage and prioritize security findings and vulnerabilities
- Provide security guidance and training to development teams
- Ensure compliance with security policies and industry standards
- Coordinate incident response for security issues

### Goals
- Minimize security vulnerabilities in production
- Shift security left by catching issues early in development
- Build security awareness across the engineering organization
- Maintain compliance with security frameworks (SOC2, ISO, etc.)

### Typical Communication
- Review code and designs with Developers for security concerns
- Work with Product Managers to balance security requirements with features
- Report security metrics and risks to Project Managers and leadership
- Collaborate with QA Leads on security testing strategies
- Facilitate threat modeling and security design reviews

---

## How These Additions Address Gaps

The five new roles close critical gaps in the OctoAcme project management model:

**Clarity in Handoffs**: The QA Lead, UX/UI Designer, and Technical Writer roles formalize quality gates and deliverables that were previously implicit. This reduces ambiguity about when features are "ready" and ensures documentation and testing aren't afterthoughts.

**Reduced Single-Role Overload**: Previously, Developers were implicitly responsible for testing, security, documentation, and design implementation. By explicitly defining specialized roles, we acknowledge that these disciplines require dedicated focus and expertise, preventing burnout and improving outcomes.

**Release Reliability**: The Release Coordinator role separates deployment orchestration from project management, allowing Project Managers to focus on planning while ensuring releases get the specialized attention they need for success.

**Security by Design**: The Security Champion role ensures security is proactively addressed throughout development rather than being a last-minute gate, reducing the risk of costly late-stage security issues.

**Improved Onboarding**: New team members can now reference specific role definitions to understand responsibilities, communication patterns, and how roles interact. The addition of a role mapping table (see [Role Interaction Matrix](./octoacme-role-interaction-matrix.md)) provides a visual reference for understanding collaboration patterns.

**Accountability**: Each role has clear goals and responsibilities, making it easier to assign work, measure performance, and identify process improvements.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For a visual overview of how these roles interact, see the [Role Interaction Matrix](./octoacme-role-interaction-matrix.md).


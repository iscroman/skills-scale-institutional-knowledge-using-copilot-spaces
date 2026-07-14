# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Interaction with Other Roles
- **With Product Managers**: Discuss acceptance criteria, estimate work, identify trade-offs
- **With Project Managers**: Track progress, flag blockers, commit to sprints
- **With QA/Testing Lead**: Define test strategy, review acceptance criteria, validate fixes
- **With Technical Lead**: Get design guidance, participate in architecture reviews

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Interaction with Other Roles
- **With Project Managers**: Weekly syncs on status, risks, and resource constraints
- **With Developers**: Discuss requirements, review estimates, refine acceptance criteria
- **With Stakeholders/Sponsors**: Present roadmap, discuss prioritization, request approvals
- **With Design/UX Lead**: Review user research, validate design direction

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Interaction with Other Roles
- **With Product Managers**: Weekly alignment on scope, prioritization, and risks
- **With Developers**: Track sprint progress, identify blockers, manage commitments
- **With Stakeholders/Sponsors**: Provide status, escalate risks, request decisions
- **With QA/Testing Lead**: Coordinate test schedules, track quality metrics
- **With Release/DevOps Lead**: Plan release timelines and coordinate deployments

---

### QA / Testing Lead

#### Role Summary
QA/Testing Leads define quality standards, design test strategies, and validate that solutions meet acceptance criteria and quality gates before release.

#### Responsibilities
- Develop test plan and quality acceptance criteria aligned with business needs
- Coordinate manual and automated testing efforts
- Identify, track, and triage defects
- Validate solutions meet the Definition of Done before handoff
- Define quality metrics and reporting dashboards
- Collaborate on release readiness assessments

#### Goals
- Deliver high-quality software with minimal production defects
- Reduce cycle time for testing without compromising quality standards
- Provide visibility into test coverage and quality risks

#### Typical Communication
- Planning sessions to define acceptance criteria and test strategy
- Daily standups during active development and testing phases
- QA sign-off or gating before releases and production deployments
- Defect and quality metric reports

#### Interaction with Other Roles
- **With Developers**: Review acceptance criteria, coordinate test strategy, triage defects
- **With Product Managers**: Validate acceptance criteria align with user expectations
- **With Project Managers**: Report on test progress and quality status
- **With Technical Lead**: Coordinate testing of complex technical components
- **With Release/DevOps Lead**: Coordinate smoke tests and post-deployment verification

---

## Extended Roles

### Stakeholder / Executive Sponsor

#### Role Summary
Executive Sponsors provide business-level oversight, secure resources, and make strategic decisions. They ensure projects align with organizational goals and remove high-level blockers.

#### Responsibilities
- Approve project charter and major scope changes
- Allocate budget and resources to projects
- Remove organizational barriers and escalated blockers
- Provide executive visibility and status updates to leadership
- Make trade-off decisions when projects compete for resources
- Validate business outcomes and ROI

#### Goals
- Ensure projects deliver measurable business value
- Maintain organizational alignment and consistent prioritization
- Minimize high-level escalations and resource conflicts

#### Typical Communication
- Monthly or milestone-based executive briefings
- Exception-based escalations from Project Manager
- Approval workflows for major scope changes or resource requests
- Executive steering committee meetings (as needed)

#### Interaction with Other Roles
- **With Project Managers**: Receive escalations, provide approvals and resource allocation
- **With Product Managers**: Discuss roadmap, strategic direction, and business outcomes
- **With Technical Lead**: Understand technical feasibility and architectural implications (as needed)

---

### Technical Lead / Architect

#### Role Summary
Technical Leads ensure solutions are technically sound, scalable, and maintainable. They guide design decisions and manage technical risks.

#### Responsibilities
- Review and approve technical design and architecture
- Identify technical risks and propose mitigations
- Guide design reviews and establish code quality standards
- Mentor developers on technical best practices and patterns
- Ensure solutions align with platform standards and avoid duplicating existing functionality
- Evaluate technical trade-offs (performance, scalability, maintainability, cost)

#### Goals
- Deliver technically sound, maintainable, and scalable solutions
- Reduce technical debt and future maintenance burden
- Build team capability and shared technical knowledge

#### Typical Communication
- Design reviews and architecture discussions during planning
- Code review guidance and feedback
- Technical risk assessments and mitigation planning
- Documentation of architectural decisions

#### Interaction with Other Roles
- **With Developers**: Conduct design reviews, provide architectural guidance, review code
- **With Project Managers**: Assess technical feasibility, estimate technical complexity, flag risks
- **With QA/Testing Lead**: Coordinate testing strategy for complex technical components
- **With Stakeholders/Sponsors**: Explain technical trade-offs and feasibility (as needed)

---

### Design / UX Lead

#### Role Summary
Design/UX Leads ensure solutions are user-centered, accessible, and aligned with brand standards. They drive design quality and user experience throughout the project.

#### Responsibilities
- Conduct user research and define user needs and personas
- Create wireframes, prototypes, and design specifications
- Conduct usability testing and gather user feedback
- Ensure accessibility compliance (WCAG standards) and design system consistency
- Partner with developers on design implementation and quality assurance
- Validate design against success metrics and user feedback

#### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce user friction, support burden, and learning curve
- Build consistency and coherence across the product

#### Typical Communication
- Design review sessions with stakeholders and developers
- Usability testing results and user feedback summaries
- Design specifications and handoff documentation to developers
- Design system updates and pattern documentation

#### Interaction with Other Roles
- **With Product Managers**: Conduct user research, validate design direction, review acceptance criteria for UX
- **With Developers**: Review implementation fidelity, troubleshoot design challenges, iterate on details
- **With QA/Testing Lead**: Ensure usability acceptance criteria are included in test plans
- **With Stakeholders**: Present design rationale and user feedback

---

### Release / DevOps Lead

#### Role Summary
Release/DevOps Leads manage deployment pipelines, infrastructure, and release coordination. They ensure reliable, safe deployments and operational excellence.

#### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Plan and execute production deployments with minimal downtime
- Manage infrastructure, platform reliability, and monitoring
- Define release procedures, approval gates, and rollback strategies
- Monitor deployment quality, incident response, and post-deployment verification
- Coordinate with QA and Product teams on release readiness

#### Goals
- Enable frequent, reliable, and safe deployments to production
- Minimize deployment risk, downtime, and incident severity
- Maintain high system availability, performance, and observability

#### Typical Communication
- Release planning and go/no-go coordination
- Deployment execution and real-time monitoring
- Post-deployment verification and incident response
- Infrastructure and platform status updates

#### Interaction with Other Roles
- **With Project Managers**: Coordinate release timelines and deployment windows
- **With QA/Testing Lead**: Run smoke tests, post-deploy verification, and incident triage
- **With Developers**: Provide feedback on deployment issues, coordinate hotfixes
- **With Technical Lead**: Ensure deployment strategy aligns with architecture

---

## How These Personas Are Used

- Use these persona definitions to frame scenarios and sample interactions in OctoAcme exercises and real projects.
- Each persona can be used as a "persona prompt" for Copilot Spaces to shape role-specific guidance.
- When gaps emerge in a project, refer to this doc to identify missing roles or responsibilities.
- Adapt role definitions to your team's structure—these personas are templates, not prescriptive.

---

**Last Updated**: 2024
**Maintained By**: OctoAcme Project Management Community

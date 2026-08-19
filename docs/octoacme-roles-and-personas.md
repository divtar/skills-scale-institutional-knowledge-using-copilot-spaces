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
- **With QA/Testing Lead**: Collaborate on test planning and ensure code is testable; receive feedback on quality issues
- **With Technical Architect/Tech Lead**: Receive technical direction and design guidance; participate in architecture reviews
- **With Project Manager**: Provide estimates and status updates; escalate blockers and dependencies
- **With Product Manager**: Clarify acceptance criteria and requirements; propose implementation trade-offs

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
- **With Project Manager**: Align on scope, timeline, and milestones; review progress against success metrics
- **With Developers**: Define acceptance criteria; validate implementation against requirements
- **With QA/Testing Lead**: Approve test strategy and acceptance validation approach
- **With Stakeholder/Sponsor**: Communicate business value and strategic alignment
- **With Technical Architect/Tech Lead**: Discuss technical feasibility and trade-offs

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
- **With Product Manager**: Ensure roadmap alignment and prioritization; track delivery of features
- **With Developers**: Monitor progress; manage dependencies and blockers
- **With QA/Testing Lead**: Coordinate testing timelines; track quality metrics
- **With Technical Architect/Tech Lead**: Identify and mitigate technical risks
- **With Stakeholder/Sponsor**: Provide regular status updates and escalate risks
- **With Scrum Master/Agile Coach**: Collaborate on process improvement and team health

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads define and execute the quality strategy for a project. They work closely with developers and product teams to ensure features meet acceptance criteria and quality standards before release.

### Responsibilities
- Design test plans and define testing strategy (unit, integration, end-to-end)
- Build and maintain test automation frameworks
- Lead manual testing and acceptance validation
- Report quality metrics and test coverage
- Identify quality risks and propose mitigation strategies
- Collaborate with developers on testability during design phase

### Goals
- Ensure features meet acceptance criteria and quality standards
- Reduce defects escaping to production
- Maintain high test coverage for critical flows

### Typical Communication
- Sprint planning and daily standups
- Test plans and quality reports
- Bug tracking and risk escalations

### Interactions with Other Roles
- **With Developers**: Provide test requirements; review code for testability; collaborate on test automation
- **With Product Manager**: Validate acceptance criteria; confirm feature readiness for release
- **With Project Manager**: Report quality status and testing progress; flag quality risks
- **With Technical Architect/Tech Lead**: Align on testing strategy for complex technical components
- **With Stakeholder/Sponsor**: Provide quality assurance sign-off for releases

---

## Technical Architect/Tech Lead

### Role Summary
Technical Architects provide technical direction, ensure scalability and maintainability, and manage technical risks and dependencies. They mentor developers and make key technology decisions.

### Responsibilities
- Define technical direction and architecture patterns
- Review design proposals for scalability and maintainability
- Mentor developers and conduct technical reviews
- Identify and manage technical risks and dependencies
- Ensure adherence to coding standards and best practices
- Make technology stack and framework decisions

### Goals
- Ensure systems are scalable, maintainable, and secure
- Reduce technical debt while delivering features
- Foster a culture of technical excellence

### Typical Communication
- Design review meetings and architecture discussions
- Code review feedback and technical guidance
- Technical risk escalations

### Interactions with Other Roles
- **With Developers**: Provide technical guidance; review designs and code; mentor on best practices
- **With QA/Testing Lead**: Discuss testability and architecture for quality assurance
- **With Project Manager**: Identify and escalate technical risks and dependencies
- **With Product Manager**: Advise on technical feasibility and propose implementation trade-offs
- **With Security/Compliance Officer**: Ensure security and compliance requirements are built into architecture

---

## Stakeholder/Sponsor

### Role Summary
Sponsors provide business context, strategic guidance, and governance oversight. They approve scope changes, allocate resources, and ensure alignment with organizational strategy.

### Responsibilities
- Define business objectives and success metrics
- Approve project scope, timeline, and resource allocation
- Provide strategic guidance and escalation path
- Review and approve major decisions and trade-offs
- Communicate project status to executive leadership
- Remove organizational blockers

### Goals
- Ensure project delivers business value
- Maintain strategic alignment
- Enable efficient decision-making and resource allocation

### Typical Communication
- Monthly stakeholder updates and milestone reviews
- Executive briefings and decision approval
- Escalation point for strategic issues

### Interactions with Other Roles
- **With Project Manager**: Receive status updates; approve scope and timeline changes; escalate strategic issues
- **With Product Manager**: Align on business value and strategic priorities; approve major feature decisions
- **With Scrum Master/Agile Coach**: Understand team health and process improvements
- **With Technical Architect/Tech Lead**: Understand technical trade-offs and risk mitigation strategies

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove team blockers, and coach the team on agile principles. They focus on team health, process improvement, and sustainable delivery.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Remove impediments and blockers that prevent team progress
- Coach team members on agile principles and practices
- Monitor team velocity and identify process improvements
- Foster psychological safety and continuous learning culture
- Escalate organizational blockers to Project Manager or Sponsor

### Goals
- Enable consistent, sustainable delivery
- Improve team collaboration and communication
- Reduce friction and process waste
- Increase team engagement and job satisfaction

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective notes and action items
- One-on-one coaching and mentoring
- Process improvement recommendations

### Interactions with Other Roles
- **With Project Manager**: Escalate blockers; coordinate process improvements
- **With Developers**: Coach on technical practices; remove impediments
- **With Product Manager**: Ensure backlog clarity; manage scope creep
- **With all team members**: Foster psychological safety and continuous learning
- **With Stakeholder/Sponsor**: Communicate team health and process metrics

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officers ensure that projects meet security standards, regulatory requirements, and organizational policies. They embed security and compliance considerations into the development process.

### Responsibilities
- Define security and compliance requirements for projects
- Review architecture and design for security vulnerabilities
- Conduct security assessments and penetration testing
- Ensure adherence to regulatory requirements and organizational policies
- Provide security training and awareness for the team
- Manage security incident response and remediation

### Goals
- Prevent security breaches and compliance violations
- Build security into the development process from the start
- Maintain regulatory compliance and reduce organizational risk
- Promote a security-conscious culture

### Typical Communication
- Security requirements and threat models
- Architecture and design reviews
- Security assessment reports
- Compliance audit results and remediation plans

### Interactions with Other Roles
- **With Technical Architect/Tech Lead**: Define secure architecture patterns; review technology decisions
- **With Developers**: Provide security guidance; review code for vulnerabilities
- **With Project Manager**: Escalate security risks; manage compliance timelines
- **With QA/Testing Lead**: Coordinate security testing and vulnerability assessment
- **With Stakeholder/Sponsor**: Report on compliance status and security posture

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The "Interactions with Other Roles" sections clarify how roles collaborate and depend on each other for project success.

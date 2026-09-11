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

## Technical Lead / Architect

### Role Summary
Technical Leads guide architectural and design decisions, own the technical roadmap alignment, and ensure solutions are feasible within technical constraints and team capabilities. They balance product vision with technical reality.

### Responsibilities
- Define and communicate technical architecture and design patterns
- Review complex technical designs and architectural proposals
- Identify technical risks, dependencies, and constraints early
- Mentor developers and support their growth
- Collaborate with Product Managers on feasibility and tradeoffs
- Guide technology selections and tool evaluations
- Ensure adherence to coding standards and technical quality gates

### Goals
- Deliver scalable, maintainable systems that support business growth
- Reduce technical debt and future rework
- Build team technical capability and reduce single points of failure
- Make informed tradeoff decisions between speed and quality

### Typical Communication
- Technical design reviews and architecture discussions
- Sprint planning to assess feasibility
- Weekly sync with PM and Project Manager on technical constraints
- Technical documentation and ADR (Architecture Decision Records)

### Interactions with Other Roles
- **With Product Manager**: Discuss feasibility, estimate impact of scope changes on technical approach
- **With Project Manager**: Advise on schedule risk related to technical complexity
- **With Developers**: Mentor, review designs, support problem-solving
- **With QA Lead**: Define technical test strategy and automation approach

---

## QA Lead / Quality Advocate

### Role Summary
QA Leads own the testing strategy and quality assurance activities, working cross-functionally to ensure products meet acceptance criteria and quality standards before release.

### Responsibilities
- Define and coordinate the overall testing strategy (unit, integration, end-to-end, manual)
- Establish quality acceptance criteria and Definition of Done validation processes
- Coordinate QA efforts across the team and manage test coverage
- Identify and track defects; prioritize based on severity and impact
- Collaborate with developers on test automation and tooling
- Conduct manual QA and acceptance testing for critical features
- Monitor quality metrics and report on test results and risk

### Goals
- Ensure features meet acceptance criteria and quality standards
- Reduce defects in production and minimize rework
- Improve test coverage and automation
- Provide confidence to stakeholders about release readiness

### Typical Communication
- Test plan reviews and quality metrics in weekly syncs
- Defect logs and quality dashboards
- Acceptance criteria clarification during sprint planning
- Post-release quality reports and incident analysis

### Interactions with Other Roles
- **With Developers**: Clarify test requirements, collaborate on automation approach, review test coverage
- **With Product Manager**: Validate acceptance criteria, prioritize defect fixes, support feature sign-off
- **With Project Manager**: Report quality status, flag schedule risks related to quality issues
- **With Technical Lead**: Align on test strategy and automation tooling aligned with technical approach

---

## Stakeholder / Sponsor

### Role Summary
Sponsors champion the project at an executive or leadership level, providing resources, removing organizational blockers, and ensuring alignment with business objectives and customer interests.

### Responsibilities
- Champion the project's business value and strategic alignment
- Provide resources (budget, headcount, infrastructure) to support delivery
- Remove organizational and cross-team blockers
- Review and approve major scope or timeline changes
- Communicate project status to broader leadership and customers
- Ensure project aligns with business strategy and customer needs
- Make final decisions on go/no-go and resource allocation

### Goals
- Deliver customer and business value aligned with strategy
- Remove barriers to team success
- Maintain executive visibility and stakeholder confidence
- Support timely, informed decision-making

### Typical Communication
- Monthly stakeholder updates and reviews
- Escalation reviews for major risks or decisions
- Executive briefings and customer communications
- Strategic alignment discussions with leadership

### Interactions with Other Roles
- **With Project Manager**: Review status, resolve escalations, approve major changes
- **With Product Manager**: Discuss strategic alignment, customer feedback, and business impact
- **With Team**: Remove blockers and provide resources; celebrate successes
- **With Other Stakeholders**: Coordinate across teams and organizational boundaries

---

## Scrum Master / Delivery Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, coach the team on process adherence, remove impediments, and foster a culture of continuous improvement and psychological safety.

### Responsibilities
- Plan and facilitate agile ceremonies (standups, planning, retrospectives, reviews)
- Coach the team on agile principles and ceremonies
- Identify and help remove impediments and blockers
- Track and communicate sprint metrics and team health
- Foster psychological safety and encourage feedback
- Support team retrospectives and drive process improvements
- Escalate systemic blockers to Project Manager and leadership

### Goals
- Enable the team to deliver effectively and sustainably
- Improve team velocity and predictability over time
- Build a psychologically safe team culture
- Reduce process friction and impediments

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective facilitation and action item tracking
- Metrics and health updates in weekly syncs
- Coaching conversations and one-on-ones with team members

### Interactions with Other Roles
- **With Project Manager**: Escalate blockers and risks, provide team health insights
- **With Developers**: Coach on agile practices, remove impediments
- **With All Roles**: Facilitate ceremonies and maintain process consistency
- **With Team**: Build trust and psychological safety through consistent, supportive facilitation

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers ensure projects meet security, privacy, and regulatory requirements. They own risk assessments, guide security best practices, and coordinate compliance reviews before release.

### Responsibilities
- Identify and assess security and compliance risks early in planning
- Review architectural and design decisions for security implications
- Coordinate security testing and vulnerability assessments
- Guide secure coding practices and security reviews
- Ensure compliance with regulatory and organizational policies
- Coordinate security incident response and post-incident reviews
- Maintain security and compliance documentation and audit trails
- Support secure deployment and post-release monitoring

### Goals
- Prevent security breaches and compliance violations
- Build security and compliance into the development process
- Reduce regulatory and legal risk to the organization
- Maintain stakeholder confidence through transparent security practices

### Typical Communication
- Security and compliance reviews during planning and design phases
- Security testing results and vulnerability reports
- Compliance checklists and risk assessments
- Incident response coordination and post-incident reviews

### Interactions with Other Roles
- **With Technical Lead / Architect**: Review technical design for security implications
- **With Developers**: Guide secure coding practices, review code for vulnerabilities
- **With Product Manager**: Discuss security/compliance requirements and tradeoffs
- **With Project Manager**: Flag security/compliance risks and schedule impact
- **With QA Lead**: Coordinate security testing and vulnerability assessment

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

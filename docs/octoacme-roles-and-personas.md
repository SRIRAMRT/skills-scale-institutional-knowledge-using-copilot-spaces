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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality assurance strategy and ensure that deliverables meet acceptance criteria and quality standards. They collaborate with developers and product managers to define test strategies, validate features, and identify defects.

### Responsibilities
- Define and maintain QA strategy and test plans
- Execute manual and automated testing
- Validate acceptance criteria before release
- Report quality metrics and testing progress
- Identify and prioritize bugs and regressions
- Recommend process improvements based on defect patterns

### Goals
- Ensure high-quality deliverables that meet customer expectations
- Reduce defects reaching production
- Provide early feedback on quality risks

### Interactions with Other Roles
- **Developers**: Collaborate on test coverage, automation frameworks, and defect resolution
- **Product Managers**: Align on acceptance criteria and quality expectations
- **Project Managers**: Report quality status and blockers; participate in release readiness assessments
- **Technical Architect**: Advise on test infrastructure and automation strategies

### Typical Communication
- Sprint planning and retrospectives
- Test case reviews and defect reports
- Quality metrics in weekly status updates
- Release readiness sign-offs

---

## Technical Architect

### Role Summary
Technical Architects design system solutions, define technical standards, and assess technical feasibility and risks. They collaborate with developers, product managers, and other architects to ensure scalability, performance, and maintainability.

### Responsibilities
- Design technical solutions to meet requirements
- Define and enforce technical standards and best practices
- Review technical designs and code for architectural alignment
- Assess technical risks and propose mitigation strategies
- Lead technical proof-of-concepts and evaluations
- Advise on infrastructure, integration, and scalability decisions

### Goals
- Deliver scalable, maintainable technical solutions
- Minimize technical debt and rework
- Reduce integration and performance risks

### Interactions with Other Roles
- **Developers**: Review designs and provide architectural guidance; mentor on best practices
- **Product Managers**: Advise on technical feasibility and trade-offs during prioritization
- **Project Managers**: Identify technical risks and dependencies for planning
- **QA/Testing Lead**: Define testability requirements and non-functional test strategies

### Typical Communication
- Technical design reviews and architecture discussions
- Design documents and architecture decision records (ADRs)
- Technical risk assessments in planning
- Code review feedback on architectural concerns

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business requirements and technical solutions. They gather, document, and validate stakeholder needs, ensuring that delivered solutions align with business objectives.

### Responsibilities
- Gather and document business requirements from stakeholders
- Analyze requirements for clarity, completeness, and feasibility
- Create requirement specifications and user stories
- Facilitate communication between business stakeholders and technical teams
- Validate solutions against business requirements
- Identify and document process improvements

### Goals
- Ensure clear understanding of business needs across teams
- Minimize scope creep and rework due to requirement gaps
- Enable data-driven decisions through business process analysis

### Interactions with Other Roles
- **Product Managers**: Partner on requirement prioritization and acceptance criteria
- **Developers**: Clarify requirements and support implementation questions
- **Project Managers**: Provide detailed requirement documentation for planning
- **QA/Testing Lead**: Define business-focused test scenarios and acceptance criteria

### Typical Communication
- Requirements gathering workshops and interviews
- Written requirement specifications and user story documentation
- Walkthrough sessions with technical and business teams
- Validation and sign-off on completed work

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile processes, remove blockers, and coach teams on agile practices and continuous improvement. They protect team focus and enable self-organization while maintaining alignment with project goals.

### Responsibilities
- Facilitate sprint ceremonies (planning, standups, reviews, retrospectives)
- Remove blockers and escalate impediments
- Coach team on agile practices and methodologies
- Track velocity and sprint metrics
- Foster psychological safety and continuous improvement culture
- Facilitate communication and collaboration within and across teams

### Goals
- Maximize team velocity and predictability
- Build a high-performing, self-organizing team
- Continuously improve processes and team collaboration

### Interactions with Other Roles
- **Project Managers**: Collaborate on scheduling and risk management
- **Developers**: Support team dynamics and remove technical/process blockers
- **Product Managers**: Facilitate backlog refinement and prioritization discussions
- **All roles**: Coach on agile values and principles

### Typical Communication
- Sprint ceremony facilitation
- One-on-ones with team members for coaching
- Metrics reports and retrospective insights
- Cross-team coordination and impediment escalation

---

## Release Manager

### Role Summary
Release Managers own the deployment process and production readiness. They coordinate release planning, manage deployment schedules, and ensure smooth transitions from staging to production.

### Responsibilities
- Plan and schedule releases in coordination with stakeholders
- Manage release documentation and version control
- Coordinate deployment activities and manage deployment windows
- Conduct pre-release verification and smoke testing
- Manage rollback procedures and incident response during deployments
- Communicate release status and post-deployment verification results

### Goals
- Deliver releases on schedule with minimal risk and downtime
- Ensure clear visibility into deployment status and health
- Enable rapid rollback and incident resolution if issues arise

### Interactions with Other Roles
- **Developers**: Ensure code is deployment-ready and participate in deployment activities
- **QA/Testing Lead**: Coordinate smoke testing and release verification
- **Project Managers**: Align on release schedule and dependencies
- **Technical Architect**: Advise on deployment architecture and infrastructure readiness

### Typical Communication
- Release planning and kickoff meetings
- Deployment status updates and incident communications
- Release notes and deployment runbooks
- Post-deployment verification reports

---

## Security / Compliance Officer

### Role Summary
Security/Compliance Officers ensure that projects meet security standards, regulatory requirements, and compliance policies. They assess security risks, provide guidance on secure coding practices, and validate compliance before release.

### Responsibilities
- Define security and compliance requirements for projects
- Conduct security reviews and threat assessments
- Audit code and infrastructure for security vulnerabilities
- Ensure compliance with regulatory requirements (e.g., GDPR, HIPAA, SOC 2)
- Recommend security best practices and mitigation strategies
- Validate security controls before production release

### Goals
- Minimize security vulnerabilities and compliance violations
- Ensure customer data protection and privacy
- Build security into the development lifecycle (shift-left)

### Interactions with Other Roles
- **Developers**: Provide security training and review code for vulnerabilities
- **Technical Architect**: Advise on secure architecture design and infrastructure security
- **QA/Testing Lead**: Define security and penetration testing requirements
- **Project Managers**: Flag compliance risks and support security escalations
- **Release Manager**: Validate security controls and compliance before production release

### Typical Communication
- Security reviews and threat assessment reports
- Code and infrastructure security audits
- Security incident response and investigation
- Compliance certification and audit documentation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Personas interact across functional areas to ensure comprehensive project delivery covering quality, technical design, business alignment, process efficiency, deployment readiness, and security compliance.

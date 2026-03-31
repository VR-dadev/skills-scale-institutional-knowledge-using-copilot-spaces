
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

## UX Designer

### Role Summary
UX Designers ensure user experience is prioritized in feature design and delivery. They collaborate closely with Product Managers and Developers to translate product vision into intuitive, accessible, and user-centered workflows.

### Responsibilities
- Create wireframes, prototypes, and design systems to guide development
- Conduct and support usability testing and user research
- Clarify UI/UX requirements with developers during implementation
- Gather and incorporate user feedback to improve designs
- Champion accessibility and design consistency across products
- Participate in design reviews and provide design guidance

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support burden
- Build design consistency and reusable patterns

### Typical Communication
- Design kickoff and specification meetings with Product and Engineering
- Design review sessions during planning and execution phases
- User feedback and usability test results
- Design system documentation and component libraries

### Key Interactions
- **Product Manager**: Collaborates on feature specs, user insights, and success metrics
- **Developers**: Partners during implementation to clarify interactive requirements and edge cases
- **QA/Testing**: Aligns on acceptance criteria for user-facing features
- **Stakeholders**: Gathers feedback and validates design direction against business goals

---

## Business Analyst

### Role Summary
Business Analysts bridge business requirements and technical execution. They capture stakeholder needs, clarify requirements, and help define solutions that deliver business value while remaining technically feasible.

### Responsibilities
- Gather and document business requirements and workflows
- Translate business needs into actionable, prioritized user stories
- Support acceptance criteria definition and validation
- Create test scenarios and support QA case creation
- Identify and document process improvements
- Facilitate discussions between business stakeholders and technical teams

### Goals
- Ensure requirements are clear, complete, and testable
- Minimize rework due to unclear specifications
- Bridge communication gaps between business and technical teams

### Typical Communication
- Requirements gathering and documentation sessions
- Backlog refinement and story mapping sessions
- User story and acceptance criteria workshops
- Test case review and validation

### Key Interactions
- **Stakeholders**: Gathers business requirements and validates solutions
- **Product Manager**: Works to prioritize and refine backlog items
- **Project Manager**: Helps identify dependencies and scope impacts
- **Development Team**: Clarifies requirements and supports implementation
- **QA/Testing**: Collaborates on test scenarios and acceptance criteria

---

## DevOps Engineer

### Role Summary
DevOps Engineers own infrastructure, automation, and deployment processes to enable teams to deliver code quickly and reliably. They work across development and operations to build resilient systems and streamline release processes.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines and automation
- Monitor infrastructure health, performance, and security posture
- Troubleshoot deployment issues and coordinate rollbacks when needed
- Advise on release strategies, deployment windows, and rollback plans
- Manage infrastructure as code and automate provisioning
- Lead incident response coordination for infrastructure-related issues

### Goals
- Enable fast, safe, reliable deployments
- Maintain high system availability and performance
- Reduce manual operational overhead through automation

### Typical Communication
- Release planning and deployment coordination
- Infrastructure architecture and design reviews
- Post-incident retrospectives and runbooks
- Monitoring dashboards and alerting guidelines

### Key Interactions
- **Developers**: Partners on build pipeline configuration, deployment standards, and environment setup
- **Project Manager**: Coordinates release schedules and deployment windows
- **QA/Testing**: Ensures staging environment matches production for accurate testing
- **Security Lead**: Collaborates on infrastructure security, compliance, and vulnerability scanning
- **Product Manager**: Discusses deployment strategy and release cadence

---

## Security Lead

### Role Summary
Security Leads champion application and infrastructure security best practices throughout the project lifecycle. They work across teams to identify risks, conduct reviews, and enable secure delivery without slowing down development.

### Responsibilities
- Conduct threat modeling and security architecture reviews
- Review code and deployments for security vulnerabilities
- Establish security standards, checklists, and scanning practices
- Lead incident response coordination for security issues
- Advise teams on secure coding, authentication, and data handling
- Ensure compliance with regulatory and organizational security policies

### Goals
- Prevent security vulnerabilities from reaching production
- Build security awareness and ownership across the team
- Balance security rigor with development velocity

### Typical Communication
- Security reviews and threat modeling sessions
- Vulnerability disclosure and triage coordination
- Security incident response and post-mortems
- Security training and guidance documentation

### Key Interactions
- **Developers**: Reviews code for vulnerabilities, provides secure coding guidance
- **Project Manager**: Advises on security risks and mitigation timelines
- **DevOps Engineer**: Collaborates on infrastructure security and compliance controls
- **QA/Testing**: Coordinates security testing and penetration test scenarios
- **Product Manager**: Discusses security implications of features and data handling

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test planning, and validation. They work with the team to define quality standards, create test plans, and ensure features meet acceptance criteria before release.

### Responsibilities
- Define QA strategy, test plans, and quality standards for the project
- Create and maintain test cases, test scenarios, and test documentation
- Perform manual testing for features and edge cases
- Configure and maintain automated testing infrastructure
- Triage and track defects, working with developers on resolution
- Validate fixes and regression test before release

### Goals
- Ensure features meet acceptance criteria and quality standards
- Find and prevent defects before they reach production
- Build repeatable, scalable quality processes

### Typical Communication
- Test planning and review meetings
- Defect triage and resolution discussions
- Release validation sign-off and testing reports
- Test automation discussions with developers

### Key Interactions
- **Developers**: Reviews acceptance criteria, reports defects, coordinates fixes
- **Product Manager**: Clarifies feature requirements and edge cases
- **Business Analyst**: Collaborates on test scenarios and acceptance criteria
- **Project Manager**: Provides test status and risk assessment
- **DevOps Engineer**: Coordinates testing in staging and production-like environments

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When planning projects, ensure all relevant personas are represented in team discussions and decision-making.
- Use the interaction notes to clarify communication patterns and reduce dependencies during execution.

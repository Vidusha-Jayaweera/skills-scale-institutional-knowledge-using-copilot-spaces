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

## QA Engineers

### Role Summary
QA Engineers ensure product quality through testing, validation, and quality assurance activities. They collaborate with developers and product teams to verify features meet acceptance criteria and maintain high quality standards.

### Responsibilities
- Design and execute test plans and test cases
- Perform manual and automated testing
- Report and track defects through resolution
- Validate acceptance criteria and user stories
- Participate in requirement reviews and sprint planning
- Maintain test automation frameworks

### Goals
- Ensure high product quality and reliability
- Catch defects early in the development cycle
- Improve test coverage and automation
- Reduce production incidents

### Typical Communication
- Daily standups and sprint ceremonies
- Bug reports and test results
- Test plan reviews with developers and product managers
- Quality metrics and release readiness reports

### How they interact with other roles
- **Developers**: Collaborate on acceptance criteria, review test results, and validate fixes
- **Product Managers**: Clarify requirements and acceptance criteria, report quality metrics
- **Project Managers**: Report on testing progress, blockers, and release readiness
- **DevOps Engineers**: Integrate automated tests into CI/CD pipelines
- **Stakeholders**: Provide quality reports and risk assessments

---

## UX Designer

### Role Summary
UX Designers create user-centered designs that balance user needs with business goals. They conduct research, create wireframes and prototypes, and ensure the product delivers an intuitive and effective user experience.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Design user flows and information architecture
- Collaborate with developers on implementation details
- Maintain design systems and style guides
- Validate designs through user feedback and metrics

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and increase satisfaction
- Ensure design consistency across products
- Validate designs with real user data

### Typical Communication
- Design reviews and critique sessions
- User research findings and recommendations
- Design handoff documentation for developers
- Usability test reports and insights

### How they interact with other roles
- **Product Managers**: Collaborate on feature requirements, user needs, and business goals
- **Developers**: Hand off designs, answer implementation questions, review UI implementation
- **Project Managers**: Provide design estimates, report on design progress and dependencies
- **Business Analysts**: Use requirements to inform design decisions
- **Stakeholders**: Present design concepts and gather feedback

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain the infrastructure, tooling, and automation that enable reliable, efficient software delivery. They bridge development and operations to ensure smooth deployment and production operations.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure as code and cloud resources
- Monitor system health, performance, and availability
- Implement security and compliance controls
- Automate deployment and operational tasks
- Respond to incidents and support production systems

### Goals
- Maximize system reliability and uptime
- Reduce deployment time and friction
- Automate repetitive operational tasks
- Ensure security and compliance

### Typical Communication
- Deployment notifications and release coordination
- Incident reports and post-mortems
- Infrastructure and tooling documentation
- System health and performance metrics

### How they interact with other roles
- **Developers**: Provide deployment pipelines, troubleshoot build issues, support production debugging
- **QA Engineers**: Integrate automated tests into CI/CD, provide test environments
- **Project Managers**: Report on infrastructure readiness, deployment status, and risks
- **Product Managers**: Provide production metrics and system capabilities
- **Stakeholders**: Report on system availability and security posture

---

## Technical Writer

### Role Summary
Technical Writers create clear, accurate documentation that helps users, developers, and stakeholders understand and use the product effectively. They translate complex technical concepts into accessible content.

### Responsibilities
- Write and maintain user documentation, API docs, and guides
- Create tutorials, how-to articles, and troubleshooting content
- Review and edit technical content for clarity and accuracy
- Maintain documentation style guides and standards
- Collaborate with developers and product teams on documentation needs
- Gather feedback to improve documentation quality

### Goals
- Produce clear, accurate, and helpful documentation
- Reduce support burden through self-service content
- Ensure documentation stays current with product changes
- Improve user onboarding and success

### Typical Communication
- Documentation reviews with SMEs and developers
- Style guide updates and writing standards
- Content plans aligned with product releases
- User feedback and documentation metrics

### How they interact with other roles
- **Developers**: Gather technical details, review code examples, document APIs
- **Product Managers**: Align documentation with feature priorities and user needs
- **Project Managers**: Provide documentation estimates, track documentation deliverables
- **UX Designers**: Ensure documentation aligns with user experience
- **Stakeholders**: Report on documentation coverage and user satisfaction

---

## Business Analyst

### Role Summary
Business Analysts bridge business stakeholders and delivery teams by eliciting, analyzing, and documenting requirements. They ensure solutions align with business needs and help teams understand the "why" behind features.

### Responsibilities
- Gather and document business requirements
- Analyze business processes and identify improvement opportunities
- Create functional specifications and user stories
- Facilitate requirements workshops and walkthroughs
- Validate solutions against business needs
- Support user acceptance testing

### Goals
- Ensure solutions deliver business value
- Reduce rework through clear, complete requirements
- Improve communication between business and technical teams
- Identify opportunities for process improvement

### Typical Communication
- Requirements documents and user stories
- Process flow diagrams and business rules
- Stakeholder interviews and workshops
- Requirements traceability and acceptance criteria

### How they interact with other roles
- **Product Managers**: Translate product vision into detailed requirements
- **Developers**: Clarify requirements, answer questions, review implementations
- **QA Engineers**: Define test scenarios based on business requirements
- **Project Managers**: Provide requirements status, identify scope changes
- **UX Designers**: Collaborate on user needs and workflows
- **Stakeholders**: Elicit needs, validate solutions, facilitate UAT

---

## Role Handoffs & Collaboration

Successful project delivery depends on clear handoffs and collaboration between roles. This section outlines typical handoff points and accountability:

### Typical Project Flow
1. **Business Analyst → Product Manager**: BA gathers initial requirements and business needs; PdM prioritizes and defines product vision
2. **Product Manager → UX Designer**: PdM shares feature requirements and success criteria; UX Designer creates user flows and designs
3. **UX Designer → Developers**: Designer provides mockups, prototypes, and specifications; Developers implement features
4. **Developers → QA Engineers**: Developers deliver completed features with unit tests; QA validates against acceptance criteria
5. **QA Engineers → DevOps Engineer**: QA confirms test results and release readiness; DevOps deploys to production
6. **DevOps Engineer → Technical Writer**: DevOps confirms deployment; Technical Writer updates documentation for new features
7. **Technical Writer → Stakeholders**: Documentation published; Product ready for customer communication and training

### RACI Model for Key Deliverables

| Deliverable | Product Manager | Business Analyst | UX Designer | Developer | QA Engineer | DevOps Engineer | Technical Writer | Project Manager |
|-------------|----------------|-----------------|-------------|-----------|-------------|----------------|-----------------|----------------|
| Requirements | A | R | C | C | C | I | I | I |
| Design | A | C | R | C | I | I | I | I |
| Implementation | C | I | C | R | C | I | I | I |
| Testing | C | I | I | C | R | C | I | I |
| Deployment | I | I | I | I | C | R | I | C |
| Documentation | C | C | C | C | I | I | R | I |
| Release | A | I | I | C | C | R | C | R |

**Legend**: R = Responsible (does the work), A = Accountable (owns the outcome), C = Consulted (provides input), I = Informed (kept updated)

### Handoff Best Practices
- **Make handoffs explicit**: Use clear signals (e.g., status changes, notifications, handoff meetings)
- **Document dependencies**: Track what each role needs from others in the project plan
- **Define "done"**: Each handoff should have clear acceptance criteria
- **Communicate blockers early**: Escalate delays that impact downstream roles
- **Use the persona assignment checklist**: Ensure all roles are assigned and understand their responsibilities at project start

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.


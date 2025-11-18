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

## QA / Testing

### Role Summary
QA engineers validate that features meet acceptance criteria and quality standards. They design test strategies, identify defects, and ensure production-readiness.

### Responsibilities
- Design and execute test plans and test cases
- Identify and document defects and edge cases
- Validate fixes and regression testing
- Collaborate on automation and CI/CD integration
- Provide feedback on testability during design

### Goals
- Prevent defects from reaching production
- Maintain consistent test coverage
- Reduce time to identify and resolve issues

### Typical Communication
- Test reports and defect tracking
- Collaboration in sprint planning and reviews
- Feedback on acceptance criteria clarity

---

## UX Designer

### Role Summary
UX Designers focus on the user experience by conducting research, creating wireframes and prototypes, and ensuring usability aligns with user needs and business goals.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Collaborate with Product Managers to validate design decisions
- Deliver design specifications and assets to Developers
- Iterate based on user feedback and analytics

### Interaction
- Collaborates with Product Managers to refine requirements and validate usability
- Works closely with Developers to handoff designs and clarify implementation details
- Coordinates with QA to ensure the user experience meets specifications
- Gathers input from Stakeholders on design direction and brand alignment

### Goals
- Deliver intuitive, accessible user experiences
- Reduce friction and improve user satisfaction
- Align design with business objectives and user needs

### Typical Communication
- Design review sessions and critique meetings
- Handoff documentation with annotations and specs
- User research findings and usability test results

---

## Technical Lead (Tech Lead)

### Role Summary
Technical Leads guide architectural decisions, mentor developers, and ensure technical quality across the codebase. They balance immediate delivery needs with long-term maintainability and scalability.

### Responsibilities
- Guide architectural decisions and technical strategy
- Review complex code contributions and design docs
- Mentor developers on best practices and problem-solving
- Anticipate technical risks and propose mitigations
- Validate technical feasibility during planning

### Interaction
- Partners with Developers for implementation guidance and code reviews
- Advises Project Managers and Product Managers on technical trade-offs and timelines
- Works with QA to define test automation strategy and code quality standards
- Collaborates with DevOps/Infrastructure Engineers on deployment and scalability
- Communicates technical constraints and opportunities to Stakeholders

### Goals
- Maintain high code quality and system reliability
- Enable team productivity through clear technical direction
- Balance technical debt with feature delivery
- Foster continuous learning and technical growth

### Typical Communication
- Architecture review meetings and technical design docs
- Code review feedback and mentoring sessions
- Technical feasibility assessments during sprint planning

---

## Customer Support Lead

### Role Summary
Customer Support Leads coordinate feedback from support channels, surface bugs and feature requests, and ensure customers receive timely assistance. They bridge the gap between users and product teams.

### Responsibilities
- Coordinate customer feedback from support tickets and channels
- Surface bugs, feature requests, and adoption issues
- Assist in pre-release and post-release communication
- Convey customer sentiment and pain points to product teams
- Maintain support documentation and knowledge bases

### Interaction
- Regularly updates Project Managers and Product Managers on recurring issues and customer priorities
- Helps QA reproduce customer-reported bugs and validate fixes
- Informs Developers about high-impact requests and workarounds
- Communicates release updates and feature changes to support teams and customers
- Collaborates with Stakeholders on customer satisfaction metrics

### Goals
- Ensure timely and accurate customer support
- Reduce customer friction and escalations
- Improve product based on real-world feedback
- Maintain high customer satisfaction scores

### Typical Communication
- Support ticket reports and trend analysis
- Customer feedback summaries and feature requests
- Release notes and support readiness briefings

---

## DevOps/Infrastructure Engineer

### Role Summary
DevOps/Infrastructure Engineers maintain deployment pipelines, provision environments, ensure system observability, and own incident response. They enable reliable, scalable, and efficient software delivery.

### Responsibilities
- Maintain and improve CI/CD pipelines
- Provision and manage development, staging, and production environments
- Ensure monitoring, logging, and observability are in place
- Own incident response playbooks and on-call rotations
- Collaborate on performance optimization and scalability

### Interaction
- Ensures Developers can deploy and test efficiently with reliable tooling
- Collaborates with QA on test environment provisioning and automation infrastructure
- Communicates operational risks and release readiness to Project Managers and Product Managers
- Partners with Technical Leads on architectural decisions affecting infrastructure
- Coordinates with Customer Support Leads during incidents and post-mortems

### Goals
- Minimize deployment friction and lead time
- Maintain system uptime and reliability
- Enable rapid incident detection and recovery
- Support scalability and performance goals

### Typical Communication
- Deployment status updates and pipeline health reports
- Incident reports and post-mortem findings
- Infrastructure capacity planning and cost optimization proposals

---

## Cross-role Interaction Guidance

Effective project delivery requires clear handoffs and escalation paths across roles:

### Handoffs
- **Product Manager → UX Designer**: Share problem statements, user stories, and success metrics to inform design decisions
- **UX Designer → Developers**: Deliver design specifications, assets, and prototypes with clear annotations
- **Developers → QA**: Provide context on implementation details, test data setup, and edge cases
- **QA → DevOps/Infrastructure Engineer**: Communicate test environment requirements and validation needs
- **DevOps/Infrastructure Engineer → Project Manager**: Report deployment status, risks, and operational readiness

### Escalation Lines
- **Technical Risks**: Developers/QA → Technical Lead → Product Manager/Project Manager
- **Design Conflicts**: Developers/UX Designer → Product Manager (for product direction) or Technical Lead (for technical constraints)
- **Customer Impact**: Customer Support Lead → Product Manager/Project Manager → Stakeholders (for urgent issues)
- **Operational Incidents**: DevOps/Infrastructure Engineer → Technical Lead → Project Manager → Stakeholders (based on severity)
- **Resource/Timeline Concerns**: Any role → Project Manager → Product Manager/Stakeholders

### Coordination Best Practices
- Schedule regular cross-functional sync meetings (e.g., weekly alignment between PM, PdM, Tech Lead, and Design)
- Use shared project boards and documentation to maintain visibility
- Establish clear RACI (Responsible, Accountable, Consulted, Informed) for major decisions
- Document handoff checklists for onboarding and releases (see `docs/checklists/`)

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.


# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Delivery Roles

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

#### Interactions
- Collaborates with **QA Lead** on test strategy and acceptance criteria
- Works with **DevOps Engineer** on deployment and infrastructure concerns
- Partners with **UX/UI Designer** on implementation details and usability
- Receives requirements from **Business Analyst** and **Product Manager**

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

#### Interactions
- Aligns with **Business Analyst** on detailed requirements
- Works with **UX/UI Designer** to validate user experience
- Partners with **Project Manager** on timelines and release planning
- Communicates with **Technical Writer** on user-facing documentation needs

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

#### Interactions
- Coordinates with **Scrum Master / Agile Coach** on process execution
- Partners with **Product Manager** on prioritization and timeline alignment
- Works with **DevOps Engineer** on deployment scheduling
- Escalates blockers to **Scrum Master** and sponsors as needed

---

## Extended Delivery & Operations Roles

### UX/UI Designer

#### Role Summary
UX/UI Designers create intuitive, accessible user interfaces and experiences. They collaborate with Product Managers and Developers to ensure user needs are met and interfaces are both functional and delightful.

#### Responsibilities
- Conduct user research and translate findings into design requirements
- Create wireframes, prototypes, and high-fidelity designs
- Define interaction patterns and design systems
- Collaborate on accessibility and usability standards
- Validate designs through user testing and iterate based on feedback

#### Goals
- Deliver user-centered, accessible interfaces
- Reduce friction in user workflows
- Establish consistent design language across products
- Improve user satisfaction and adoption

#### Typical Communication
- Design reviews with stakeholders and developers
- User research findings and usability test reports
- Design system documentation and component specs
- Collaboration tools (Figma, design reviews, feedback sessions)

#### Interactions
- Partners with **Product Manager** on feature prioritization and user needs
- Works closely with **Developers** on implementation feasibility and design-to-code handoff
- Collaborates with **QA Lead** on acceptance criteria for UX/UI
- Provides assets and guidance to **Technical Writer** for user documentation

---

### Technical Writer

#### Role Summary
Technical Writers create clear, concise documentation for users and internal stakeholders. They work with Developers, Product Managers, and UX/UI Designers to ensure documentation is accurate, complete, and accessible.

#### Responsibilities
- Author user guides, API documentation, and release notes
- Maintain internal knowledge bases and runbooks
- Review technical content for clarity and accuracy
- Collaborate on accessibility and localization needs
- Update documentation as features evolve

#### Goals
- Reduce support burden through comprehensive self-service documentation
- Improve user onboarding and adoption
- Maintain accurate, up-to-date reference materials
- Enable consistent communication with users

#### Typical Communication
- Documentation reviews with engineers and product managers
- Release notes and changelog updates
- Knowledge base and wiki maintenance
- User feedback incorporation

#### Interactions
- Receives feature requirements from **Product Manager** and **Developers**
- Works with **UX/UI Designer** to document user workflows
- Partners with **QA Lead** on testing procedures and acceptance criteria documentation
- Collaborates with **Project Manager** on release timing and announcements

---

### QA Lead

#### Role Summary
QA Leads oversee quality assurance strategy, coordinate testing efforts, and ensure acceptance criteria are met before release. They partner with Developers and Product Managers to define testability and quality standards.

#### Responsibilities
- Define test strategy and acceptance criteria in partnership with Product Manager and Developers
- Coordinate manual and automated testing efforts
- Identify and triage defects
- Plan for regression testing and end-to-end smoke tests
- Ensure compliance with security and accessibility standards

#### Goals
- Prevent defects from reaching production
- Establish confidence in quality before release
- Build reusable test assets and automation
- Improve overall product reliability

#### Typical Communication
- Test plans and quality metrics
- Defect reports and root cause analysis
- Acceptance criteria clarification sessions
- QA dashboards and test coverage reports

#### Interactions
- Collaborates with **Product Manager** on defining acceptance criteria
- Works with **Developers** on test coverage and testability concerns
- Partners with **DevOps Engineer** on test environment setup and CI/CD integration
- Validates **UX/UI Designer** mockups against usability standards

---

### DevOps Engineer

#### Role Summary
DevOps Engineers ensure reliable infrastructure, automate deployment pipelines, and maintain system observability. They enable the team to deploy safely and scale efficiently.

#### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure, monitoring, and alerting
- Automate testing and deployment processes
- Manage configuration and secrets safely
- Support incident response and post-mortems

#### Goals
- Reduce time-to-market through fast, reliable deployments
- Maintain high system uptime and reliability
- Enable self-service deployments for teams
- Provide observability and incident response capability

#### Typical Communication
- Infrastructure architecture and deployment runbooks
- Incident reports and post-mortems
- Monitoring dashboards and alerting thresholds
- On-call schedules and escalation procedures

#### Interactions
- Supports **Developers** with deployment tooling and infrastructure
- Works with **Project Manager** on release scheduling
- Partners with **QA Lead** on test environment setup
- Collaborates with **Scrum Master / Agile Coach** on sprint ceremonies around deployments

---

### Business Analyst

#### Role Summary
Business Analysts bridge the gap between business needs and technical solutions. They capture detailed requirements, identify edge cases, and ensure alignment between stakeholder expectations and implementation.

#### Responsibilities
- Gather and document business requirements
- Identify and document edge cases and error scenarios
- Validate requirements for completeness and testability
- Facilitate alignment between business and technical stakeholders
- Support impact analysis on proposed changes

#### Goals
- Reduce misalignment and rework through clear requirements
- Improve delivery accuracy and user satisfaction
- Enable faster decision-making through clear tradeoff analysis
- Support scaling by making tacit knowledge explicit

#### Typical Communication
- Requirements documents and user story templates
- Impact analysis and tradeoff discussions
- Stakeholder feedback sessions
- Process documentation and runbooks

#### Interactions
- Works closely with **Product Manager** on requirement prioritization
- Collaborates with **Developers** on feasibility and technical constraints
- Partners with **QA Lead** on test case development and acceptance criteria
- Supports **Technical Writer** with detailed feature workflows
- Assists **Project Manager** with risk identification

---

### Scrum Master / Agile Coach

#### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach teams on agile best practices. They help teams optimize their delivery process and maintain psychological safety.

#### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Identify and escalate impediments blocking team progress
- Coach team on agile principles and continuous improvement
- Maintain team health metrics and retrospective outcomes
- Support organizational adoption of agile practices

#### Goals
- Maximize team velocity and predictability
- Foster psychological safety and continuous improvement
- Reduce time spent in ceremonies while increasing their value
- Scale agile practices across teams

#### Typical Communication
- Sprint planning agendas and burn-down charts
- Retrospective notes and action item tracking
- Impediment escalations and resolution updates
- Team metrics and health reports

#### Interactions
- Facilitates ceremonies involving all roles (**Developers**, **Product Manager**, **Project Manager**, etc.)
- Escalates blockers to **Project Manager** or **Sponsor** as needed
- Coaches **Project Manager** on agile process optimization
- Supports **Business Analyst** and **Product Manager** on backlog refinement ceremonies

---

## Strategic & Specialized Roles

### Release Manager

#### Role Summary
Release Managers own the release coordination process and oversee the deployment of software to production environments. They work with DevOps Engineers, Developers, and Project Managers to ensure smooth, well-communicated releases and rollback capabilities.

#### Responsibilities
- Plan and schedule production release windows
- Coordinate deployment execution with DevOps Engineer and team
- Manage release communications to stakeholders and support teams
- Document and maintain rollback/mitigation plans
- Track release status and handle deployment issues
- Conduct post-release verification and announce completion
- Maintain release documentation and version history

#### Goals
- Minimize deployment risk and production incidents
- Ensure transparent, timely communication during releases
- Enable rapid response to issues with clear rollback procedures
- Establish confidence in the release process across stakeholders

#### Typical Communication
- Release schedules and deployment windows
- Release notes and change summaries
- Pre-deployment and post-deployment checklists
- Incident alerts and status updates during deployment
- Release retrospectives and improvement recommendations

#### Interactions
- Works closely with **DevOps Engineer** on deployment execution and infrastructure readiness
- Coordinates with **Project Manager** on release timing and milestone alignment
- Communicates with **QA Lead** on final acceptance and smoke testing completion
- Informs **Developers** and **Technical Writer** of release status and final deployment time
- Updates **Product Manager** on release readiness and tracks stakeholder communications

---

### Data Analyst

#### Role Summary
Data Analysts define and measure success metrics for projects and products. They collaborate with Product Managers and Developers to design experiments, collect meaningful data, and provide insights that drive decision-making and continuous improvement.

#### Responsibilities
- Define and track key performance indicators (KPIs) and success metrics
- Design experiments and A/B tests for feature validation
- Analyze data trends and identify patterns affecting project outcomes
- Create dashboards and reports for stakeholder visibility
- Provide data-driven insights to support prioritization decisions
- Validate hypotheses through quantitative and qualitative analysis
- Support post-release analysis and impact measurement

#### Goals
- Ensure projects are measured against agreed success metrics
- Enable rapid, data-driven iteration and decision-making
- Reduce decision-making bias through evidence and analysis
- Drive continuous improvement through actionable insights

#### Typical Communication
- Metric definitions and success criteria documentation
- Data dashboards and regular analytics reports
- Experiment design and results analysis
- Stakeholder briefings with key findings and recommendations
- Retrospective analysis and lessons learned reports

#### Interactions
- Partners with **Product Manager** on defining success metrics and experiment design
- Collaborates with **Developers** on instrumentation and data collection implementation
- Works with **QA Lead** on test data and quality measurement
- Supports **Project Manager** with progress reporting and risk identification
- Informs **Business Analyst** of data patterns affecting requirements

---

### Solution Architect

#### Role Summary
Solution Architects align technical implementation with overall architecture vision and organizational standards. They oversee integration design, manage complexity, and ensure solutions are scalable, maintainable, and aligned with long-term strategic goals.

#### Responsibilities
- Define overall solution architecture and design approach
- Ensure alignment with organizational architecture standards and principles
- Review design decisions for scalability, performance, and maintainability
- Identify and manage technical risks and dependencies
- Support integration planning and cross-system compatibility
- Mentor developers on architectural best practices
- Conduct design reviews and provide architecture guidance

#### Goals
- Deliver scalable, maintainable solutions aligned with strategy
- Reduce technical debt and improve system reliability
- Enable faster time-to-market through reusable components and patterns
- Support organizational growth through architecture foresight

#### Typical Communication
- Architecture design documents and decision records
- Technology stack recommendations and evaluations
- Integration and dependency diagrams
- Design review sessions with development teams
- Architecture governance and standards documentation

#### Interactions
- Collaborates with **Developers** on design feasibility and implementation guidance
- Works with **DevOps Engineer** on infrastructure requirements and deployment architecture
- Partners with **Project Manager** on timeline implications of architectural decisions
- Advises **Product Manager** on technical feasibility and trade-offs
- Supports **Business Analyst** on understanding technical constraints and capabilities

---

### Change Manager

#### Role Summary
Change Managers coordinate and support the organizational and process changes required to implement new solutions. They work across teams to manage stakeholder adoption, minimize disruption, and ensure successful change integration.

#### Responsibilities
- Develop and execute change management strategy and communication plans
- Identify stakeholders affected by changes and tailor communication approaches
- Create change impact assessments and mitigation strategies
- Conduct training and readiness activities for affected teams
- Monitor adoption and address change resistance
- Capture feedback and iterate on change approach as needed
- Support transition from pilot/staging to full production

#### Goals
- Maximize stakeholder adoption and minimize change resistance
- Reduce disruption and productivity impact during transitions
- Ensure sustained behavior change and process adoption
- Build organizational capability for managing future changes

#### Typical Communication
- Change impact assessments and stakeholder analysis
- Communication plans and messaging templates
- Training materials and readiness assessments
- Adoption metrics and feedback reports
- Post-implementation review and lessons learned

#### Interactions
- Partners with **Project Manager** on change timeline and integration planning
- Collaborates with **Product Manager** on user adoption strategy
- Works with **UX/UI Designer** on user experience of changes
- Supports **Technical Writer** with training documentation and user guides
- Coordinates with all teams on change communication and readiness

---

### Customer Success / Support Lead

#### Role Summary
Customer Success / Support Leads represent customer needs and feedback in the product development cycle. They manage customer relationships, triage support issues, and feed insights back into the product and process improvement roadmap.

#### Responsibilities
- Manage customer support team and triage incoming support requests
- Identify support trends, common issues, and product gaps
- Escalate critical customer issues to product and engineering teams
- Collaborate on customer-facing documentation and help resources
- Track customer satisfaction metrics and NPS (Net Promoter Score)
- Represent customer voice in product planning and prioritization
- Support onboarding and training for new customers

#### Goals
- Maximize customer satisfaction and retention
- Reduce support burden through proactive issue prevention
- Feed customer insights into product roadmap decisions
- Maintain strong customer relationships and advocacy

#### Typical Communication
- Support metrics and issue trend reports
- Customer feedback and satisfaction surveys
- Issue escalation and resolution tracking
- Feature requests and product improvement recommendations
- Customer success stories and reference case studies

#### Interactions
- Provides feedback to **Product Manager** on customer needs and pain points
- Collaborates with **Developers** on root cause analysis of support issues
- Works with **QA Lead** on quality concerns identified through support tickets
- Partners with **Technical Writer** on documentation clarity and helpfulness
- Supports **Change Manager** on user adoption and training needs
- Communicates with **Project Manager** on customer-impacting timelines

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the **Interactions** sections to understand cross-functional handoffs and dependencies.
- When planning cross-functional projects, ensure representation from personas relevant to your scope.

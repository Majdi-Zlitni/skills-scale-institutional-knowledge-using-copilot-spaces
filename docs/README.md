# OctoAcme Project Management Documentation

## Project Management Overview

OctoAcme follows an iterative, customer-centric project management lifecycle structured into five distinct phases: Initiation, Planning, Execution, Release, and Retrospective. The process begins with a lightweight 'Project One-pager' to validate business needs and success metrics. Governance is maintained through clear decision gates, ensuring that projects only move from planning to execution once stakeholders agree on priorities and resource availability is confirmed.

Success is driven by clear ownership and collaboration between four primary roles: Product Managers (PdM), Project Managers (PM), Developers, and QA. The PdM defines the 'what' and 'why' through prioritized backlogs, while the PM focuses on the 'how' and 'when' by managing schedules, risks, and stakeholder communication. Developers and QA specialists collaborate throughout the execution phase to implement features and validate them against strict acceptance criteria, fostering a culture of transparency and psychological safety.

The execution phase is governed by a consistent team rhythm, including daily or twice-weekly standups and weekly delivery syncs. OctoAcme utilizes GitHub Projects for visual tracking, moving work through a standardized pipeline from backlog to completion. Communication is structured via a dedicated Risk Register and a tiered escalation path (Team -> PM -> Product Lead -> Sponsor), ensuring that blockers are resolved quickly. Stakeholders are kept informed through monthly updates and a 'single source of truth' document located within the project repository.

Quality is integrated into the workflow through a 'shift-left' approach, requiring automated unit and integration tests, security scanning, and linting within the CI pipeline before any code is merged. Every pull request is kept small and must pass at least one peer review. For deployments, OctoAcme employs standardized checklists for major, minor, and patch releases, incorporating staging smoke tests and post-deployment verification to minimize production risks. Continuous improvement is then realized through mandatory retrospectives where teams convert learnings into actionable backlog items.

## Documentation Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

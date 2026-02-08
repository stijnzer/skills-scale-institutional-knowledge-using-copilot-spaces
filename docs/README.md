# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Docs! This guide serves as your entry point to understanding how OctoAcme manages projects, from initiation through delivery and continuous improvement.

## Overview

OctoAcme's project management approach fosters **transparency, accountability, and efficient delivery** across cross-functional teams. Our practices ensure that every project delivers measurable value while maintaining high quality standards and team engagement.

### Key Principles

Projects at OctoAcme start with a **one-pager** that validates the problem, defines success metrics, aligns stakeholders, and outlines the timeline and risks. Detailed planning breaks work into prioritized increments, defines the Definition of Done, manages dependencies, and estimates scope with methods like story points.

**Persona roles** are clearly defined: Project Managers coordinate delivery and risk; Product Managers define outcomes and priorities; Developers build and test features; QA ensures acceptance and quality; Stakeholders provide input and approvals. Team cadence includes standups, delivery syncs, sprint demos, regular stakeholder updates, and paths for escalation.

**Execution** uses project boards and a pull request workflow with automated tests and code reviews enforced via CI. Risks and dependencies are logged and tracked. Releases require passing tests, release notes, stakeholder announcements, and rollback plans. After each release or milestone, **retrospectives** capture lessons for continuous improvement—ensuring reliability and growth of OctoAcme's project practices.

## Documentation Index

### Getting Started

New to OctoAcme project management? Start here:

1. **[Project Management Overview](octoacme-project-management-overview.md)** - Introduction to OctoAcme's approach, principles, core roles, key artifacts, and lifecycle
2. **[Roles and Personas](octoacme-roles-and-personas.md)** - Detailed responsibilities and communication patterns for Developers, Product Managers, Project Managers, QA, and Stakeholders

### Project Lifecycle

Follow these guides through the complete project lifecycle:

3. **[Project Initiation](octoacme-project-initiation.md)** - Creating the project charter/one-pager, defining problem statements, stakeholders, and initial timelines
4. **[Project Planning](octoacme-project-planning.md)** - Breaking down work, prioritization, Definition of Done, dependency management, and estimation
5. **[Execution and Tracking](octoacme-execution-and-tracking.md)** - Using project boards, pull request workflows, CI/CD, and monitoring progress
6. **[Risks and Communication](octoacme-risks-and-communication.md)** - Managing risks, dependencies, team cadence (standups, syncs, demos), and stakeholder updates
7. **[Release and Deployment](octoacme-release-and-deployment.md)** - Release criteria, testing requirements, release notes, announcements, and rollback plans
8. **[Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** - Capturing learnings, action items, and evolving practices

## How These Documents Interconnect

```
Project Management Overview (Start here)
        ↓
Roles and Personas (Who does what?)
        ↓
┌───────────────────────────────────────┐
│     PROJECT LIFECYCLE FLOW            │
├───────────────────────────────────────┤
│ 1. Project Initiation                 │
│    ↓                                  │
│ 2. Project Planning                   │
│    ↓                                  │
│ 3. Execution and Tracking ←──┐       │
│    ↓                          │       │
│ 4. Risks and Communication ──┘       │
│    ↓                                  │
│ 5. Release and Deployment             │
│    ↓                                  │
│ 6. Retrospective & Improvement        │
│    ↓                                  │
│    └──→ (feeds back to Planning)     │
└───────────────────────────────────────┘
```

### Quick Reference by Role

- **New Team Members**: Start with [Overview](octoacme-project-management-overview.md) → [Roles](octoacme-roles-and-personas.md) → Your role-specific sections
- **Project Managers**: Focus on [Initiation](octoacme-project-initiation.md), [Planning](octoacme-project-planning.md), [Risks & Communication](octoacme-risks-and-communication.md), and [Retrospectives](octoacme-retrospective-and-continuous-improvement.md)
- **Product Managers**: Review [Overview](octoacme-project-management-overview.md), [Initiation](octoacme-project-initiation.md), [Planning](octoacme-project-planning.md), and [Roles](octoacme-roles-and-personas.md)
- **Developers**: See [Execution](octoacme-execution-and-tracking.md), [Release](octoacme-release-and-deployment.md), and [Roles](octoacme-roles-and-personas.md)
- **QA/Testing**: Review [Execution](octoacme-execution-and-tracking.md), [Release](octoacme-release-and-deployment.md)
- **Stakeholders**: Start with [Overview](octoacme-project-management-overview.md) and [Risks & Communication](octoacme-risks-and-communication.md)

## Using These Docs with Copilot Spaces

To make these process docs available as context in Copilot Spaces:
- Copy relevant docs to your project's `.copilot/` directory
- Reference them in your Copilot Space configuration
- Copilot will use them to provide role-specific guidance and process recommendations

## Contributing

These process docs evolve based on team learnings and retrospective action items. If you have suggestions for improvements, please coordinate with your Project Manager or submit feedback through your team's established channels.

---

**Last Updated**: February 2026  
**Maintained by**: OctoAcme Project Management Office

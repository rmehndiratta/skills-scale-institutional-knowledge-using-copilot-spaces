# OctoAcme Project Management Docs

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management grounded in clear ownership and iterative delivery. The organization defines five core phases—**Initiation, Planning, Execution, Release, and Retrospective**—each with specific deliverables and decision gates. At the center are three primary roles: the **Project Manager** (who coordinates delivery, schedules, and risks), the **Product Manager** (who defines outcomes and prioritizes the backlog), and the **Delivery Team** (developers and QA who implement and validate work). This role clarity ensures accountability and enables efficient cross-functional collaboration.

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

1. **Initiation** - Problem statement, stakeholders, high-level timeline
2. **Planning** - Scope, resources, milestones, dependencies
3. **Execution** - Build, test, review, iterate
4. **Release** - Deploy, verify, announce
5. **Close & Retrospective** - Capture learnings and next steps

## OctoAcme Process Summary

### Execution & Team Rhythm

Execution at OctoAcme is shaped by a predictable team rhythm and standardized workflows. The organization conducts daily standups (15 minutes), weekly delivery syncs, and sprint-based planning to maintain alignment and surface blockers early. Work flows through a project board with clear stages—Backlog, Ready, In Progress, In Review, QA, Done—and pull requests are kept lean (≤400 lines when possible) with automated testing and linting required before human review. Quality is embedded throughout: unit and integration tests are written alongside features, end-to-end smoke tests validate critical flows before release, and security scanning runs in CI. This "shift-left" mindset reduces late-stage rework and ensures that code meets acceptance criteria incrementally.

### Risk Management & Communication

Communication and risk management are formalized to prevent surprises and keep stakeholders informed. OctoAcme maintains a **Risk Register** with structured tracking (ID, Description, Impact, Likelihood, Owner, Mitigation, Status) and a three-level escalation path: team-level triage in daily standups, PM escalation to the Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues. Weekly status templates ensure consistent reporting of progress, next steps, and blockers to stakeholders. For release, a pre-release checklist confirms all acceptance criteria are met, CI passes, security scans clear, and rollback plans are documented—preparing teams to deploy with confidence.

### Continuous Improvement

OctoAcme treats project completion and learning as integral to continuous improvement. After each sprint, release, or milestone, the team runs a structured retrospective (45–75 minutes) to capture what went well, what could improve, and to generate 2–3 prioritized action items with clear owners and due dates. These actions feed back into the project backlog or are tracked in issues, and their impact is measured and celebrated. This cycle of structured delivery, transparent communication, and blameless learning reinforces a culture of psychological safety, ownership, and iterative excellence.

## Process Documentation

### Getting Started

- [Project Management Overview](octoacme-project-management-overview.md) - Start here for core roles, principles, and the project lifecycle
- [Roles and Personas](octoacme-roles-and-personas.md) - Understand key project roles and responsibilities

### Phase Guides

- [Project Initiation Guide](octoacme-project-initiation.md) - Validate business need and authorize work
- [Project Planning](octoacme-project-planning.md) - Turn approved initiatives into actionable plans
- [Execution & Tracking](octoacme-execution-and-tracking.md) - Day-to-day management and progress tracking
- [Release & Deployment Guide](octoacme-release-and-deployment.md) - Standardize releases and reduce risk

### Supporting Processes

- [Risk Management & Communication](octoacme-risks-and-communication.md) - Identify, manage, and communicate risks
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) - Capture learnings and drive improvements

## Quick Navigation

Use this README to find the process guidance you need. For detailed checklists, templates, and workflows, see the linked documents.

---

**Purpose of this knowledge base:**
- Centralize scattered project management knowledge in Copilot Spaces
- Convert tacit team insights into searchable, versioned artifacts
- Give all team members equal access to processes, decisions, and rationale
- Enable consistent, repeatable project execution
- Accelerate onboarding and reduce single-person dependency risk

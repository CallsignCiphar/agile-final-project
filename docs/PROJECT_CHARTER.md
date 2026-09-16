# Project Charter: TaskFlow

## Purpose

TaskFlow is the deliverable for this Agile final project. The goal is twofold: ship a working task and project management web app, and demonstrate a full Scrum cycle (backlog, sprint planning, execution, review, retrospective) in doing so.

## Problem statement

Small teams and individuals tracking multiple projects often rely on disconnected tools (spreadsheets, sticky notes, chat threads) that don't scale past a handful of tasks. TaskFlow provides a single, simple place to organize projects and tasks without the setup overhead of enterprise PM tools.

## Objectives

1. Deliver a working web application covering account creation, project creation, task management, and a Kanban board view.
2. Run the build as two, two-week sprints following Scrum ceremonies (planning, daily check-ins, review, retrospective).
3. Maintain full traceability from backlog item to GitHub Issue to committed code.
4. Produce documentation (charter, backlog, sprint plans, Definition of Done) suitable for grading and for reuse as a portfolio artifact.

## Scope

**In scope**
- User authentication (sign up, log in, log out)
- Project CRUD (create, read, update, delete)
- Task CRUD within a project, including status, assignee, and due date
- Kanban board view with drag-and-drop status changes
- Basic dashboard (task counts, overdue tasks)

**Out of scope (for this project)**
- Multi-tenant team billing or subscription tiers
- Real-time collaborative editing
- Mobile native apps
- Third-party integrations (Slack, email digests, calendar sync)

## Stakeholders

| Role | Owner |
|---|---|
| Product Owner | Sadiq (solo) |
| Scrum Master | Sadiq (solo) |
| Development team | Sadiq (solo) |
| Instructor / grader | Course instructor |

## Timeline

| Milestone | Target |
|---|---|
| Project kickoff, charter, and backlog | Week 1 |
| Sprint 1 (core CRUD: auth, projects, tasks) | Weeks 2-3 |
| Sprint 1 review and retrospective | End of Week 3 |
| Sprint 2 (board view, dashboard, polish) | Weeks 4-5 |
| Sprint 2 review, retrospective, final submission | End of Week 5 |

## Success criteria

- All Sprint 1 and Sprint 2 committed stories are delivered and demoed.
- Product backlog, sprint plans, and Definition of Done are kept current in `docs/`.
- GitHub Issues and Project board reflect real progress (not backfilled at the end).
- A short retrospective is written after each sprint with at least one concrete process change carried into the next sprint.

## Assumptions and constraints

- Single developer, roughly 10-12 focused hours per week available.
- No budget for paid infrastructure; hosting choices favor free tiers.
- Course deadline is fixed; scope will flex (via backlog reprioritization) before the deadline moves.

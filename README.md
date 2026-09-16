# TaskFlow

TaskFlow is a lightweight task and project management web app, built as an Agile final project to demonstrate Scrum practices end to end: product backlog, sprint planning, iterative delivery, and retrospectives.

## Problem statement

Small teams often bounce between sticky notes, spreadsheets, and chat threads to track work. TaskFlow gives a team a single place to create projects, break work into tasks, assign owners, and track status on a simple board, without the overhead of a heavyweight PM tool.

## Core features

- User accounts with sign up and login
- Create and manage projects
- Create tasks within a project (title, description, status, assignee, due date)
- Kanban-style board view (To Do / In Progress / Done)
- Task comments and activity history
- Basic dashboard showing task counts and overdue items

## Tech stack

| Layer | Choice |
|---|---|
| Frontend | React |
| Backend | Node.js, Express |
| Database | MongoDB |
| Auth | JWT-based session auth |
| Hosting | TBD (Render / Vercel) |

## Project structure

```
agile-final-project/
  docs/
    PROJECT_CHARTER.md      Problem, objectives, scope, success criteria
    PRODUCT_BACKLOG.md      Prioritized epics and user stories
    SPRINT_1_PLAN.md        Sprint 1 goal and sprint backlog
    DEFINITION_OF_DONE.md   Checklist a story must meet to be marked done
  client/                   React frontend (added during Sprint 1)
  server/                   Express backend and API (added during Sprint 1)
  CONTRIBUTING.md           Branching, commit, and PR conventions
```

## Agile process

This project is run as two, two-week sprints under a simplified Scrum process (solo developer acting as Product Owner, Scrum Master, and Dev Team):

1. **Backlog** – all planned work lives in [docs/PRODUCT_BACKLOG.md](docs/PRODUCT_BACKLOG.md) and as GitHub Issues, prioritized with MoSCoW.
2. **Sprint planning** – at the start of each sprint, stories are pulled from the backlog into a sprint plan (see [docs/SPRINT_1_PLAN.md](docs/SPRINT_1_PLAN.md)) based on capacity.
3. **Execution** – work is tracked on the GitHub Project board (Backlog / To Do / In Progress / In Review / Done).
4. **Review and retro** – each sprint closes with a short review of what was delivered and a retrospective, logged in the relevant sprint doc.

See [docs/PROJECT_CHARTER.md](docs/PROJECT_CHARTER.md) for the full project scope and success criteria.

## Getting started

```
# clone the repo
git clone https://github.com/CallsignCiphar/agile-final-project.git
cd agile-final-project

# backend
cd server && npm install && npm run dev

# frontend (separate terminal)
cd client && npm install && npm start
```

Setup instructions will be filled in as `client/` and `server/` are scaffolded in Sprint 1.

## Status

Project kickoff. Sprint 1 in planning, see the [Project board](../../projects) for live status.

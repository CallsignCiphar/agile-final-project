# Product Catalog Service — Agile Final Project

This repository is the final project for the Coursera / IBM Skills Network course **"Introduction to Agile Development and Scrum"**. It demonstrates the Agile and Scrum workflow taught in the course — backlog creation and prioritization, issue templates, sprint planning, Gherkin acceptance criteria, and a Kanban board — applied to a hypothetical **Product Catalog Service**.

The grading focus for this assignment is the Agile/Scrum *process artifacts*, not a working application, so this repo contains no application code. Everything here is the planning, tracking, and process documentation the course asks for.

## Scenario

Stakeholders need a **Product Catalog Service**: a backend service that lets a store manage the products it sells online. The stakeholders submitted the following requirements:

1. Ability to create products in the catalog
2. Ability to retrieve products from the catalog
3. Ability to update products in the catalog
4. Ability to delete products from the catalog
5. Ability to "Like" products in the catalog
6. Ability to "Dislike" products in the catalog
7. Ability to list all products in the catalog
8. Ability to query a subset of products in the catalog
9. Cloud hosting for the service
10. Automated deployment (CI/CD) to the cloud

## Agile artifacts in this repo

| Course task | Where it lives |
|---|---|
| Workspace / board | [GitHub Project: Product Catalog Service](../../projects) |
| Issue templates | [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE) |
| Issues from stakeholder requests | [Issues](../../issues) |
| Prioritized backlog / icebox | [`docs/PRODUCT_BACKLOG.md`](docs/PRODUCT_BACKLOG.md) |
| "As a... I need... so that..." stories | Each issue, using the [user story template](.github/ISSUE_TEMPLATE/user_story.md) |
| Sprint | [`docs/SPRINT_1_PLAN.md`](docs/SPRINT_1_PLAN.md) and the [Sprint 1 milestone](../../milestones) |
| Gherkin acceptance criteria | On each Sprint 1 issue |
| Assigned & moved issues | [Project board](../../projects) — Icebox → Product Backlog → Sprint Backlog → In Progress → Done |

## Board columns

The GitHub Project uses a Kanban board with these columns:

- **Icebox** — deprioritized ideas, not scheduled yet
- **Product Backlog** — prioritized, ready to be pulled into a sprint
- **Sprint Backlog** — committed to the current sprint
- **In Progress** — actively being worked on this sprint
- **Done** — completed

## Labels

- `user-story` — a stakeholder requirement tracked as a GitHub Issue

## Author

Maintained by [CallsignCiphar](https://github.com/CallsignCiphar) as a solo submission for the IBM/Coursera Agile & Scrum final project.

# Sprint 1 Plan — Product Catalog Service

## Sprint goal

Deliver the top 5 Product Catalog Service stakeholder requirements — Create, Retrieve, Update, Delete, and List all products — each with Gherkin acceptance criteria, assigned and moved across the board to demonstrate the Scrum workflow.

## Sprint backlog (top 5, pulled from the Product Backlog)

| # | Story | Acceptance criteria (Gherkin) |
|---|---|---|
| 1 | As a store manager, I need to create products in the catalog, so that new items can be sold. | **Given** valid product details, **When** I submit a create request, **Then** the product is added to the catalog and returned with a unique ID. |
| 2 | As a store manager, I need to retrieve a product from the catalog, so that I can view its details. | **Given** a product exists in the catalog, **When** I request it by ID, **Then** its full details are returned. |
| 3 | As a store manager, I need to update a product in the catalog, so that its information stays accurate. | **Given** a product exists in the catalog, **When** I submit updated details, **Then** the catalog reflects the new information. |
| 4 | As a store manager, I need to delete a product from the catalog, so that discontinued items are removed. | **Given** a product exists in the catalog, **When** I delete it by ID, **Then** it no longer appears in the catalog. |
| 5 | As a shopper, I need to list all products in the catalog, so that I can browse everything available. | **Given** the catalog contains products, **When** I request the full list, **Then** all products are returned. |

Full Gherkin acceptance criteria live on each story's GitHub Issue.

## Board movement

Per the assignment's "assign and move issues" step, Sprint 1 issues are:

- Assigned to [CallsignCiphar](https://github.com/CallsignCiphar)
- Moved from **Product Backlog** → **Sprint Backlog** when pulled into the sprint
- Moved to **In Progress** / **Done** on the board to demonstrate real movement through the workflow

## Deferred to a later sprint

Query a subset of products and cloud hosting remain in the **Product Backlog** (not iced, but not in Sprint 1) since they build on the core CRUD/list operations delivered in this sprint.

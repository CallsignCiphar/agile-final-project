# Product Backlog — Product Catalog Service

All 10 stakeholder requirements, triaged into the **Product Backlog** (prioritized, ready to be pulled into a sprint) and the **Icebox** (deprioritized, not scheduled). Each item is tracked as a GitHub Issue using the `user-story` label and the "As a... I need... so that..." template.

## Product Backlog (prioritized)

| Priority | Stakeholder requirement | Story |
|---|---|---|
| 1 | Create products in the catalog | As a store manager, I need to create products in the catalog, so that new items can be sold. |
| 2 | Retrieve products from the catalog | As a store manager, I need to retrieve a product from the catalog, so that I can view its details. |
| 3 | Update products in the catalog | As a store manager, I need to update a product in the catalog, so that its information stays accurate. |
| 4 | Delete products from the catalog | As a store manager, I need to delete a product from the catalog, so that discontinued items are removed. |
| 5 | List all products in the catalog | As a shopper, I need to list all products in the catalog, so that I can browse everything available. |
| 6 | Query a subset of products in the catalog | As a shopper, I need to query a subset of products in the catalog, so that I can find products matching specific criteria. |
| 7 | Cloud hosting for the service | As a product owner, I need the service hosted in the cloud, so that it is reliably available to customers. |

Items 1–5 are pulled into **Sprint 1** — see [`SPRINT_1_PLAN.md`](SPRINT_1_PLAN.md).

## Icebox (deprioritized for now)

| Requirement | Story | Reason iced |
|---|---|---|
| "Like" products in the catalog | As a shopper, I need to like a product, so that I can indicate products I'm interested in. | Nice-to-have engagement feature, not core CRUD |
| "Dislike" products in the catalog | As a shopper, I need to dislike a product, so that I can indicate products I'm not interested in. | Nice-to-have engagement feature, not core CRUD |
| Automated deployment to the cloud | As a product owner, I need automated deployment to the cloud, so that new releases ship without manual steps. | Depends on cloud hosting being in place first |

## Prioritization rationale

Core CRUD and read operations (create, retrieve, update, delete, list) come first because every other capability depends on them existing. Query/filtering and cloud hosting follow as they extend the core service. Like/Dislike are social/engagement features layered on top of a working catalog, and automated deployment is an optimization of the hosting story — both are valuable but not required to demonstrate the core service, so they sit in the Icebox.

# Product Backlog: TaskFlow

Prioritized with MoSCoW (Must / Should / Could / Won't). Story points use a Fibonacci-like scale (1, 2, 3, 5, 8). Each story below is also tracked as a GitHub Issue for execution.

## Epic 1: Authentication

| # | User story | Priority | Points | Sprint |
|---|---|---|---|---|
| 1 | As a new user, I want to sign up with email and password so that I can create an account. | Must | 3 | 1 |
| 2 | As a returning user, I want to log in and log out so that my sessions are secure. | Must | 2 | 1 |

## Epic 2: Project management

| # | User story | Priority | Points | Sprint |
|---|---|---|---|---|
| 3 | As a user, I want to create a project with a name and description so that I can group related tasks. | Must | 3 | 1 |
| 4 | As a user, I want to view a list of my projects so that I can navigate between them. | Must | 2 | 1 |
| 5 | As a user, I want to edit or delete a project so that I can keep my workspace accurate. | Should | 2 | 2 |

## Epic 3: Task management

| # | User story | Priority | Points | Sprint |
|---|---|---|---|---|
| 6 | As a user, I want to create a task within a project with a title, description, and due date so that I can track work items. | Must | 5 | 1 |
| 7 | As a user, I want to edit or delete a task so that I can correct mistakes or remove stale work. | Must | 3 | 1 |
| 8 | As a user, I want to assign a task an owner so that responsibility is clear. | Should | 2 | 2 |

## Epic 4: Kanban board

| # | User story | Priority | Points | Sprint |
|---|---|---|---|---|
| 9 | As a user, I want to see my project's tasks on a To Do / In Progress / Done board so that I can see status at a glance. | Must | 5 | 2 |
| 10 | As a user, I want to drag a task card between columns so that updating status is fast. | Should | 5 | 2 |

## Epic 5: Dashboard

| # | User story | Priority | Points | Sprint |
|---|---|---|---|---|
| 11 | As a user, I want a dashboard showing task counts by status and overdue tasks so that I know what needs attention. | Should | 3 | 2 |

## Epic 6: Comments and activity (stretch)

| # | User story | Priority | Points | Sprint |
|---|---|---|---|---|
| 12 | As a user, I want to leave comments on a task so that I can log context or decisions. | Could | 3 | Backlog (unscheduled) |
| 13 | As a user, I want to see an activity history on a task so that I can see what changed and when. | Won't (this project) | 3 | Backlog (unscheduled) |

## Backlog grooming notes

- Epics 1-3 form the walking skeleton for Sprint 1: without auth, projects, and tasks, there is nothing to put on a board.
- Epic 4 (board) and Epic 5 (dashboard) are the visible payoff and are scheduled for Sprint 2 once the data model is stable.
- Epic 6 is explicitly descoped for this project (see Project Charter, out of scope) but kept in the backlog for future iterations.
- Re-groomed at the end of each sprint; priority and sprint assignment above reflect the latest grooming pass.

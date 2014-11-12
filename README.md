# developer cheat sheet

Customer here means the person/people who provide requirements. Depending on the scenario the customer is also the end user.

Ticket and issue are used synonymously.

## Requirements

Identify the main stakeholder who has the power to decide. This becomes important in prioritisation discussions.

Collect all requirements, the customer has. Even if they’re little and trivial.

Prioritise the most fundamental and important requirements. What requirement provides the highest benefit for the customer?

Prioritise requirements together with the customer.

Requirements must be technically possible.

If a requirement is difficult or expensive in terms of time, then decide if it is worth to implement it. Is the benefit for the customer higher than the cost of implementation?

If time/money is limited, agree on a set of requirements which are implemented. When the customer delivers a new requirement which was not agreed, they must drop one from the implementation list for it.

Requirements should be written down in tickets(Redmine, Jira, …)/issues(GitHub).

## Implementation

### General

If a new task/bug/feature comes up, create a ticket for it.

### Git/GitHub/Version control

Implement features/bugfixes in small steps.
=> Commit often, commit early
=> Before you commit something, software must compile and all tests must pass.

Every feature has its own branch.

Implement only one feature per branch.

Small features
=> When you develop in small features, it is easier to integrate changes back into the main branch.

Somebody else should review your work on the feature branch.
=> Create a Pull Request on GitHub.

#### Pull Requests (PR)

Create a Pull Request, when:
- you’re finished with implementation
- you want feedback for the changes you did so far

If a PR is not finished, mark it as `Work in Progress (WIP)`.

Only merge Pull Requests, where source code compiles and all tests pass.

Do not merge your own Pull Requests.

Decide who needs to approve your PR.

At least one other team member should review your work.

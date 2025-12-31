---
sidebar_label: Construction Process
description: Follow these steps during construction.
---

# Construction Process

<!-- **Construction is executed using Scrum:** -->
<!-- 
![Scrum](../../assets/scrum.webp) -->


### 1. Transform [SWDD](../4-design/software-design-document.md) into work items

    - Traceability Martix: Requirement - Design Element - Work Item - Code - Test
    - Work item: ID, SWDD Reference, Description, Acceptance Criteria, Tests, Dependencies, Risk (low, med, high)
    - Establish dependency relationships (UML use case diagrams)
    - Risk factors: Technical novelty, complexity, integrations, performance, security

    - Sync work items with features
        - Feature flags are used for branching
        - Inspectable work items reflect feature abstraction
        - Inspection closes out work item and moves code into trunk

| Work Item ID | Work Item Title | Work Item Description | SWDD ID | SWDD Description | Test ID | Acceptance Criteria | Dependencies | Risk |
| - | - | - | - | - | - | - | - | - |
|   |   |   |   |   |   |   |   |   |

### 2. Create construction plan

- Plan the order in which work items will be completed. Consider dependencies and abstractions

### 3. Create construction schedule

### 4. Assign work items to indiviuals

- Promotes responsibility
- Consider personnel requirements (vacations, etc.)

### 5. Complete work items

    - Conduct sprints
    - Each work item will have associate tests
    - Work items measure progress of requirement fulfillment.
    - Create feature branches corresponding to inspectable work items

### 6. As work items are completed, conduct [Continuous Itegration Process](./ci-process.md)
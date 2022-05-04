---
name: New milestone
about: Use this template to create and track a milestone
title: "Milestone [PROJECT NAME] [DEADLINE]"
labels: milestone
---
## Milestone Scope

The milestone scope is about the full scope of a budget that was agreed to with a customer. So when the below scope is completed, the customer should be happy to pay and the product iteration should be done. This issue serves as an overview of overall progress and to discuss and adapt scope if required.

The milestone scope is closely related but not identical to the breakdown: The breakdown's goal is to inform a fulfilment crowd of people about how the full project scope will be implemented, the milestone's goal is to fix an agreement with non-technical customers about deliverable that we should implement.

The goal of this issue is to inform technical and non-technical people about the high-level progress of the milestone. So if someone from key account management looks at this, they should get an idea of the overall progress without asking anyone (e.g.: the PM) for help. When the project-team (PM, TL, devs, devops) looks at this, they should get an idea of the overall progress and also of some details.

This issue must be written for the kick-off of a project and should be heavily based on the solution + breakdown steps of our usual offers pipeline. The "solution" is the top-level that can be discussed and agreed to with the customer. The "breakdown" is the detailed tasks that resolve the top-level "solution" items. Put differently: The solution is customer facing, the breakdown is SIDESTREAM facing. All solution + breakdown items should be represented here from the beginning, so that team and non-team members have an overview of the overall project progress.

In the below scope:
- first-level checkboxes represent the "solution", they must not become issues but rather be checked once sub-tasks were resolved and the PM deems them to be done
- non-first-level checkboxes are the breakdown, they will mostly become issues at some point during execution that will then be picked up in interval plannings and by team members
- non-first-level bullets may be used to group the breakdown further, but must not be used on the first level

To create the milestone:
- [ ] fill out the "Scope" section below
    - remove the example scope that currently fills the section
    - use the "solution" and "breakdown" for the content
    - in the beginning all or most of the list will be plain checkboxes and bullets
- [ ] let TL, KAM, ... review where applicable
- [ ] set the "Deadline" field in the project milestones view
- [ ] close the milestone once:
    - [ ] all scope was completed
    - [ ] major changes dictate it (scope changes, side-agreements with customer, ...)

### Scope

Example scope, please overwrite:
- [ ] Deploy the application to the customer infrastructure (this must not be an issue)
    - [ ] create file for CI/CD (must be an issue)
    - [ ] setup S3 for storage (must be an issue)
    - [ ] create helm chart for deployment (must be an issue)
    - [ ] test deployment of helm chart to our own cluster (must be an issue)
    - [ ] deploy the helm chart to the customer cluster (must be an issue)
- [ ] Frontend
    - implement the base layout
        - [ ] add the sidebar component
        - [ ] add the sidebar container
        - [ ] glue in the sidebar container to the app
    - implement the operators view
        - [ ] ...
- [ ] Backend
    - ...
- [ ] ...
